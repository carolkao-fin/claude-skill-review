# /cier-meeting-minutes

> 更新日期：2026-11-08
> 來源：自訂 skill

## 功能說明

# 中經院國際研討會會議記錄產生器

**觸發時機**：使用者要求「產生會議記錄」「整理研討會記錄」「根據逐字稿產出會議記錄」，且來源檔位於 `C:\Users\carol\Desktop\AI\研討會\` 目錄下。

**不要觸發**：一般文字摘要、非 DOCX 輸入、或非研討會場次的會議記錄。

---

## 一、前置確認（執行前必問）

若使用者未明確提供以下資訊，**逐一確認**，不要假設：

1. **場次編號與名稱**：例如「場次一：全球貿易與供應鏈」
2. **逐字稿/會議記錄來源檔**：`傳檔結果\` 下哪個 DOCX
3. **輸出目錄**：預設 `C:\Users\carol\Desktop\AI\研討會\國語\轉檔結果(會議記錄格式)\`
4. **是否需要 speak-human-tw 潤稿**（預設：是）

---

## 二、固定來源路徑

| 角色 | 路徑 |
|------|------|
| 格式模板 | `C:\Users\carol\Desktop\AI\研討會\★ 1141121-國際研討會會議記錄.docx` |
| 議程檔 | `C:\Users\carol\Desktop\AI\研討會\議程.docx` |
| 逐字稿來源 | `C:\Users\carol\Desktop\AI\研討會\國語\傳檔結果\場次{N}_{名稱}_{日期}_會議紀錄_ch.docx` |
| 輸出目錄 | `C:\Users\carol\Desktop\AI\研討會\國語\轉檔結果(會議記錄格式)\` |

---

## 三、讀取來源檔的方法

**所有 DOCX 讀取一律用 Python**，不用 PowerShell COM 物件（COM 物件在無 Word 視窗情況下容易崩潰）。

```python
# 方法 A：python-docx（有安裝時優先）
from docx import Document
doc = Document(path)
text = "\n".join(p.text for p in doc.paragraphs if p.text.strip())

# 方法 B：zipfile + XML（備用）
import zipfile, re
with zipfile.ZipFile(path) as z:
    xml = z.open('word/document.xml').read().decode('utf-8')
xml = re.sub(r'</w:p>', '\n', xml)
text = re.sub(r'<[^>]+>', '', xml)
```

**中文輸出到終端時**，先設定編碼以防亂碼：
```python
import sys; sys.stdout.reconfigure(encoding='utf-8')
```

**寫 Python 腳本時**，先將腳本存到 scratchpad 目錄，再用 `python -I` 執行，不要直接 inline 執行含中文的 python -c 命令。

---

## 四、來源檔結構說明

### 逐字稿 DOCX（`場次{N}_..._ch.docx`）內部結構：
```
一、會議摘要
二、關鍵議題
三、行動事項
四、備註
五、逐字稿（Transcript）
```
**摘要內容來自「五、逐字稿」段落**，不用「一、會議摘要」（那是自動生成的簡略版）。

### 議程 DOCX 提供：
- 場次主持人
- 每位引言人的姓名（中英文）、機構頭銜、報告題目（中英文）
- 評論人姓名與機構

### 格式模板 DOCX（★ 1141121）提供：
- 文件階層結構（不取內容）
- 字型、縮排、標題格式的參考

---

## 五、輸出文件格式（嚴格照此結構）

```
[標題行1] 全球供應鏈與AI競爭國際研討會   （置中，粗體，16pt）
[標題行2] 會 議 紀 錄                     （置中，粗體，14pt）
[標題行3] 中華民國{年}年{月}月{日}日（星期{X}）（置中，12pt）

場次{N}：{中文場次名}（{English Session Name}）  （粗體，13pt）

一、引言人報告重點摘要                           （粗體，13pt）

(一) {機構職稱全稱}  {中文姓名}({English Name})  （粗體，12pt，左縮排 0.3cm）
主題：「{中文題目}」({English Title})              （12pt，左縮排 0.3cm）

{N}.{小節名稱}                                   （粗體，12pt，左縮排 0.3cm）
{散文段落，從逐字稿彙整，詳見第六節}              （12pt，左縮排 0.3cm）

（重複 (一)(二)(三)…）

二、評論人-{機構職稱}  {中文姓名}({English Name})（粗體，13pt）

{N}.{評論主題}                                   （粗體，12pt，左縮排 0.3cm）
{散文段落}                                       （12pt，左縮排 0.3cm）

三、討論與交流                                   （粗體，13pt）

{提問標籤}：{問題內容}                           （加粗標籤 + 一般問題文字）
{回應者姓名}({English Name})：{回答散文}          （加粗姓名 + 一般回答文字）
```

---

## 六、散文摘要撰寫規則

### 核心原則：先保事實，再整理脈絡，不代發言者下結論

1. **從逐字稿萃取**，不用「一、會議摘要」的現成文字
2. **每個小節**寫一至兩個完整段落，涵蓋該講者在此主題的核心論點與具體例子
3. **保留具體數字與事實**：關稅次數、比例、年份、國家名稱
4. **不加評論性收尾**（如「這是重要的政策轉向」「顯示了X的根本改變」）
5. **不加解說導引句**（如「就短期政策走向而言，」「整體而言，」）
6. **發言者稱謂**：第一次出現用「{姓名}教授/研究員/副執行長指出，」，後文用「他/她」或直接用姓名
7. **允許在段落開頭帶出講者立場**，例如「比曼教授以資料說明，」「杜懋之認為，」

### Q&A 標籤規則（重要）

| 提問者身分 | 標籤格式 |
|-----------|---------|
| 評論人（如楊書菲）向講者提問 | `評論人提問（向{姓名}）：` |
| 主持人向講者追問 | `主持人提問（向{姓名}）：` |
| **現場觀眾**提問 | `現場提問：` |

**只有來自會場聽眾的問題才用「現場提問：」**，評論人與主持人的提問一律用各自標籤。若逐字稿無法明確判斷提問者身分，預設為主持人提問，並在備註欄標記「提問者待確認」。

---

## 七、python-docx 產生文件的核心程式模板

```python
from docx import Document
from docx.shared import Pt, Cm
from docx.enum.text import WD_ALIGN_PARAGRAPH
from docx.oxml.ns import qn
from docx.oxml import OxmlElement

doc = Document()

# 版面設定
section = doc.sections[0]
section.page_height = Cm(29.7); section.page_width = Cm(21.0)
section.left_margin = Cm(3.0); section.right_margin = Cm(3.0)
section.top_margin = Cm(2.5); section.bottom_margin = Cm(2.5)

def set_font(run, bold=False, size=12, zh='標楷體', en='Times New Roman'):
    run.bold = bold; run.font.size = Pt(size); run.font.name = en
    rPr = run._element.find(qn('w:rPr'))
    if rPr is None:
        rPr = OxmlElement('w:rPr'); run._element.insert(0, rPr)
    rFonts = rPr.find(qn('w:rFonts'))
    if rFonts is None:
        rFonts = OxmlElement('w:rFonts'); rPr.insert(0, rFonts)
    rFonts.set(qn('w:eastAsia'), zh)

def p(text, bold=False, size=12, indent=0.0, align=None, sb=0, sa=0):
    para = doc.add_paragraph()
    para.paragraph_format.left_indent = Cm(indent)
    para.paragraph_format.space_before = Pt(sb)
    para.paragraph_format.space_after = Pt(sa)
    if align: para.alignment = align
    run = para.add_run(text)
    set_font(run, bold=bold, size=size)
    return para

def pm(parts, indent=0.0, sb=0, sa=0):
    """Mixed bold/plain paragraph. parts: [(text, bold, size), ...]"""
    para = doc.add_paragraph()
    para.paragraph_format.left_indent = Cm(indent)
    para.paragraph_format.space_before = Pt(sb)
    para.paragraph_format.space_after = Pt(sa)
    for (text, bold, size) in parts:
        run = para.add_run(text)
        set_font(run, bold=bold, size=size)
    return para
```

**Q&A 段落**（加粗標籤 + 一般文字）一律用 `pm()`：
```python
pm([("評論人提問（向邁克爾・比曼）：", True, 12),
    ("如果美國貿易政策…", False, 12)], sb=4, sa=1)

pm([("邁克爾・比曼(Michael Beeman)：", True, 12),
    ("成為不可或缺…", False, 12)], indent=0.3, sb=1, sa=4)
```

---

## 八、輸出檔名規則

```
場次{N}_{場次英文名縮寫}_{日期}_會議記錄.docx
```

範例：`場次一_全球貿易與供應鏈_20261020_會議記錄.docx`

---

## 九、完整執行步驟

```
1. 確認輸入（場次、來源檔、輸出目錄）
2. 用 Python 讀取議程 → 取得講者清單、頭銜、題目
3. 用 Python 讀取逐字稿 → 定位「五、逐字稿」段落後的所有內容
4. 分析逐字稿：
   a. 按講者識別各段發言
   b. 識別評論人發言與其向講者的提問
   c. 識別主持人提問
   d. 識別現場觀眾提問（明確標示「現場」或「觀眾」）
5. 撰寫各引言人的散文摘要（每位 3-5 個小節，每節 1-2 段）
6. 撰寫評論人的散文摘要（2-4 個小節）
7. 整理討論與交流（用正確的提問標籤）
8. 用 python-docx 產生 DOCX，存至輸出目錄
9. 詢問是否執行 /speak-human-tw 潤稿
```

---

## 十、常見錯誤與對策

| 錯誤 | 原因 | 對策 |
|------|------|------|
| COM 物件錯誤 (HRESULT 0x800706BE) | Word 程序未正常啟動 | 改用 python-docx 或 zipfile |
| UnicodeEncodeError cp950 | 直接 print 中文到終端 | `sys.stdout.reconfigure(encoding='utf-8')` 或寫檔再讀 |
| rPr is None (AttributeError) | python-docx 新 run 未初始化 rPr | 用 `OxmlElement` 手動建立 rPr/rFonts 節點 |
| 路徑含中文，python -c 亂碼 | PowerShell 編碼問題 | 腳本存到 scratchpad，用 `python -I` 執行 |
| 逐字稿找不到段落 | 路徑在子目錄 `傳檔結果\` | 確認完整路徑，不要用根目錄 |

---

## 十一、speak-human-tw 整合

產生文件後，詢問使用者：

> 文件已產生，是否需要執行 /speak-human-tw 去除 AI 寫作痕跡？

若確認，執行以下清單（正式辦公文書情境，力度中）：
- 刪解說導引句（「就…而言，」「整體而言，」）
- 刪評論性收尾（「顯示了…根本性轉變」「已告確立」）
- 刪評述殘留（「以樂觀的論調」「艱難的提問」）
- 刪通用結論句（「是目前最務實的應對之道」）
- 保留所有數字、人名、機構名、英文題目不動

## 使用方式

在 Claude Code 輸入：
/cier-meeting-minutes
