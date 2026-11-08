# /seo-report

> 更新日期：2026-11-08
> 來源：自訂 skill

## 功能說明

# SEO Report — Full Audit + GitHub Auto-Save

**Invocation:** `/seo-report <url>`

Runs a complete SEO audit and saves all deliverables to
`C:\Users\carol\Desktop\AI\claude-seo` (the local clone of
`https://github.com/carolkao-fin/claude-seo`).

---

## Step 1 — Run the Audit

Invoke `/seo audit <url>` and collect the full report output.
Follow all instructions in the `seo` skill, including the
synthesis methodology (PERCEIVE → ANALYZE → VALIDATE → ACT)
and the 10-section structure:

1. 技術 SEO
2. 頁面優化 (On-Page SEO)
3. 內容品質 (Content Quality)
4. 結構化資料 (Schema)
5. AI 搜尋整備度 (GEO)
6. 多語系 / Hreflang
7. 值得保留的優勢 (Strengths)
8. 優先行動計畫 (Action Plan)
9. 增加流量的具體策略 (Traffic Strategies)

Compute the weighted SEO Health Score (0–100):

| 分類 | 權重 |
|------|------|
| Technical SEO | 22% |
| Content Quality | 23% |
| On-Page SEO | 20% |
| Schema | 10% |
| Performance (CWV) | 10% |
| AI Search | 10% |
| Images | 5% |

---

## Step 2 — Prepare Output Folder

```powershell
$date   = Get-Date -Format "yyyyMMdd"
$folder = "C:\Users\carol\Desktop\AI\claude-seo\audits\seo_$date"
New-Item -ItemType Directory -Force $folder | Out-Null
```

---

## Step 3 — Generate Chinese HTML Report

Build a full interactive HTML file (all Chinese) and save to
`$folder\seo-audit-report-zh.html`.

The HTML **must** follow this structure exactly:

### Layout
- Sticky top header: site title + SEO score badge
- Two-column layout: sticky left sidebar nav + scrollable main content
- Stacks to single column on mobile (≤768px)
- Dark / light theme via CSS tokens

### Sidebar Navigation (all Chinese)
Nav items: 總覽、技術 SEO、頁面優化、內容品質、結構化資料、AI 搜尋、
多語系、優勢、行動計畫、流量策略

Highlight the active section on scroll via IntersectionObserver.

### Section: 總覽 (Overview)
- SVG score ring (score / 100, colored by severity)
- Score label: 嚴重風險 / 需要改善 / 尚可 / 良好
- One-line summary (Chinese)
- Category score bars (7 categories)
- 4 count tiles: 嚴重 / 高 / 中 / 低
- Site profile accordion (URL, operator, type, language)

### Sections 2–8
Each section card has:
- Section icon + title + score badge
- One or more `<div class="finding">` accordions
- Each finding: priority badge (嚴重/高/中/低) + title + body

### Section: 行動計畫
Numbered action table with columns: # / 行動 / 難度 / 影響

### Section: 流量策略
Specific traffic growth strategies matching the audit findings.

### Priority badge colours
- 嚴重: `#DC2626` background `#FEF2F2`
- 高: `#EA580C` / `#FFF7ED`
- 中: `#B45309` / `#FFFBEB`
- 低: `#1D4ED8` / `#EFF6FF`

### Footer
"報告由 Claude Code 生成 · <url> · <YYYY 年 MM 月 DD 日>"

---

## Step 4 — Generate English HTML Report

Build the same layout in English and save to
`$folder\seo-audit-report-en.html`.

All section titles, finding titles, body text, nav labels,
priority badges, action plan items, and footer in English.
Priority badge text: Critical / High / Medium / Low.

---

## Step 5 — Generate Word Documents

### Chinese Word doc
Use the `docx` skill (Node.js `require('C:/Users/carol/.claude/skills/seo/node_modules/docx')`).
Save to `$folder\SEO報告_<SiteName>.docx`.

Chapters:
1. 執行摘要
2. 技術 SEO（分數 X/100）
3. 頁面優化（分數 X/100）
4. 內容品質（分數 X/100）
5. 結構化資料（分數 X/100）
6. AI 搜尋整備度（分數 X/100）
7. 多語系 / Hreflang（分數 X/100）
8. 值得保留的優勢
9. 優先行動計畫
10. 增加流量的具體策略

Font: Noto Sans TC (or Arial fallback).

### English Word doc
Same structure in English.
Save to `$folder\SEO_Report_<SiteName>_EN.docx`.
Font: Arial.

---

## Step 6 — Write index.md

Create `$folder\index.md` with clickable Artifact links:

```markdown
# SEO 稽核報告 — <site_name>

**網站：** <url>  
**日期：** YYYY-MM-DD  
**分數：** <score>/100

## 互動報告

| 版本 | 連結 |
|------|------|
| 🇹🇼 中文版 | [開啟報告](<zh artifact url>) |
| 🇬🇧 英文版 | [Open Report](<en artifact url>) |

## 發現摘要

| 嚴重 | 高 | 中 | 低 |
|------|----|----|-----|
| <critical> | <high> | <medium> | <low> |
```

After publishing both HTML files as Artifacts (Steps 3 & 4), insert their
`claude.ai/artifact/…` URLs into the table above.

---

## Step 7 — Write audit-info.json

```json
{
  "date": "YYYY-MM-DD",
  "url": "<audited url>",
  "site_name": "<site name>",
  "score": <number>,
  "critical": <count>,
  "high": <count>,
  "medium": <count>,
  "low": <count>,
  "files": [
    "seo-audit-report-zh.html",
    "seo-audit-report-en.html",
    "SEO報告_<SiteName>.docx",
    "SEO_Report_<SiteName>_EN.docx"
  ]
}
```

Save to `$folder\audit-info.json`.

---

## Step 8 — Update README.md

Append a new row to the audit table in
`C:\Users\carol\Desktop\AI\claude-seo\README.md`:

```
| seo_YYYYMMDD | <url> <site_name> | <score>/100 | <critical> | <high> | <medium> | <low> |
```

---

## Step 9 — Git Commit and Push

```powershell
cd "C:\Users\carol\Desktop\AI\claude-seo"
git add audits/seo_YYYYMMDD/ README.md
git commit -m "SEO audit: <site_name> (<url>) — score <score>/100 [<YYYY-MM-DD>]

Co-Authored-By: Claude Sonnet 4.6 <noreply@anthropic.com>"
git push origin main
```

After pushing, report the GitHub URL:
`https://github.com/carolkao-fin/claude-seo/tree/main/audits/seo_YYYYMMDD/`

---

## Deliverables Summary

After completing all steps, report:

```
✅ 稽核完成

網站：<site_name>
URL：<url>
分數：<score>/100

檔案已儲存至 GitHub：
https://github.com/carolkao-fin/claude-seo/tree/main/audits/seo_YYYYMMDD/

  📄 seo-audit-report-zh.html  中文互動報告
  📄 seo-audit-report-en.html  英文互動報告
  📝 SEO報告_<SiteName>.docx   中文 Word
  📝 SEO_Report_<SiteName>_EN.docx  英文 Word
```

## 使用方式

在 Claude Code 輸入：
/seo-report
