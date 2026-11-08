# Claude Skills 完整指南

> 更新日期：2026-11-08
>
> 每週日 22:00（台灣時間）自動更新

## 分類指引

| 類別 | 資料夾 | Skill 數量 |
|------|-------|----------|
| SEO 相關 | [seo/](./seo/) | 34 個 |
| 工程 | [engineering/](./engineering/) | 10 個 |
| 業務 | [sales/](./sales/) | 36 個 |
| 財務 | [finance/](./finance/) | 8 個 |
| 人資 | [human-resources/](./human-resources/) | 9 個 |
| 設計 | [design/](./design/) | 7 個 |
| 行銷 | [marketing/](./marketing/) | 8 個 |
| 資料 | [data/](./data/) | 10 個 |
| 營運 | [operations/](./operations/) | 9 個 |
| 法務 | [legal/](./legal/) | 9 個 |
| 產品管理 | [product-management/](./product-management/) | 9 個 |
| 生物研究 | [bio-research/](./bio-research/) | 6 個 |
| 小型企業 | [small-business/](./small-business/) | 44 個 |
| 客戶支援 | [customer-support/](./customer-support/) | 5 個 |
| Anthropic | [anthropic-skills/](./anthropic-skills/) | 40 個 |
| 通用 | [general/](./general/) | 37 個 |

---

## 完整 Skill 清單

| Skill 指令 | 所在類別 | 來源 | 功能簡述 |
|-----------|---------|------|---------|
| [`/seo`](./seo/seo/) | SEO 相關 | 自訂 | Comprehensive SEO analysis for any website or business type. |
| [`/seo-agentic`](./seo/seo-agentic/) | SEO 相關 | 自訂 | Audit and fix agent readiness: the Lighthouse Agentic Brows… |
| [`/seo-ahrefs`](./seo/seo-ahrefs/) | SEO 相關 | 自訂 | Ahrefs API analyst (extension). |
| [`/seo-audit`](./seo/seo-audit/) | SEO 相關 | 自訂 | Run a full-site SEO audit and return a scored, prioritized … |
| [`/seo-backlinks`](./seo/seo-backlinks/) | SEO 相關 | 自訂 | Analyze a site's backlink profile, anchors, toxic signals, … |
| [`/seo-bing`](./seo/seo-bing/) | SEO 相關 | 自訂 | Bing Webmaster Tools + IndexNow extension. |
| [`/seo-cluster`](./seo/seo-cluster/) | SEO 相關 | 自訂 | Cluster keywords by SERP overlap and design hub-and-spoke c… |
| [`/seo-competitor-pages`](./seo/seo-competitor-pages/) | SEO 相關 | 自訂 | Generate SEO-optimized competitor comparison and alternativ… |
| [`/seo-content`](./seo/seo-content/) | SEO 相關 | 自訂 | Evaluate page content for usefulness, E-E-A-T, readability,… |
| [`/seo-content-brief`](./seo/seo-content-brief/) | SEO 相關 | 自訂 | Generate competitive SEO content briefs with per-section wo… |
| [`/seo-dataforseo`](./seo/seo-dataforseo/) | SEO 相關 | 自訂 | Live SEO data via DataForSEO MCP server: SERP analysis, key… |
| [`/seo-drift`](./seo/seo-drift/) | SEO 相關 | 自訂 | SEO drift monitoring: capture baselines of SEO-critical ele… |
| [`/seo-ecommerce`](./seo/seo-ecommerce/) | SEO 相關 | 自訂 | Analyze ecommerce SEO across product pages, product schema,… |
| [`/seo-firecrawl`](./seo/seo-firecrawl/) | SEO 相關 | 自訂 | Full-site crawling, scraping, and site mapping via Firecraw… |
| [`/seo-flow`](./seo/seo-flow/) | SEO 相關 | 自訂 | FLOW framework integration: evidence-led SEO using the Find… |
| [`/seo-geo`](./seo/seo-geo/) | SEO 相關 | 自訂 | Audit and improve content for AI Overviews and answer engin… |
| [`/seo-google`](./seo/seo-google/) | SEO 相關 | 自訂 | Google SEO APIs: Search Console (Search Analytics, URL Insp… |
| [`/seo-hreflang`](./seo/seo-hreflang/) | SEO 相關 | 自訂 | Hreflang and international SEO audit, validation, and gener… |
| [`/seo-image-gen`](./seo/seo-image-gen/) | SEO 相關 | 自訂 | AI image generation for SEO assets: OG/social preview image… |
| [`/seo-images`](./seo/seo-images/) | SEO 相關 | 自訂 | Image optimization analysis for SEO and performance. |
| [`/seo-local`](./seo/seo-local/) | SEO 相關 | 自訂 | Audit local SEO, including Google Business Profile, NAP con… |
| [`/seo-maps`](./seo/seo-maps/) | SEO 相關 | 自訂 | Maps intelligence for local SEO: geo-grid rank tracking, GB… |
| [`/seo-matomo`](./seo/seo-matomo/) | SEO 相關 | 自訂 | Matomo Reporting API extension. |
| [`/seo-page`](./seo/seo-page/) | SEO 相關 | 自訂 | Analyze one supplied URL across on-page, content, technical… |
| [`/seo-plan`](./seo/seo-plan/) | SEO 相關 | 自訂 | Strategic SEO planning for new or existing websites. |
| [`/seo-profound`](./seo/seo-profound/) | SEO 相關 | 自訂 | Profound LLM citation tracker (extension). |
| [`/seo-programmatic`](./seo/seo-programmatic/) | SEO 相關 | 自訂 | Programmatic SEO planning and analysis for pages generated … |
| [`/seo-report`](./seo/seo-report/) | SEO 相關 | 自訂 | Run a full SEO audit on a URL, generate Chinese + English H… |
| [`/seo-schema`](./seo/seo-schema/) | SEO 相關 | 自訂 | Detect, validate, or generate Schema.org JSON-LD for a supp… |
| [`/seo-seranking`](./seo/seo-seranking/) | SEO 相關 | 自訂 | SE Ranking AI visibility analyst (extension). |
| [`/seo-sitemap`](./seo/seo-sitemap/) | SEO 相關 | 自訂 | Analyze existing XML sitemaps or generate new ones with ind… |
| [`/seo-sxo`](./seo/seo-sxo/) | SEO 相關 | 自訂 | Diagnose search-experience and intent mismatches using SERP… |
| [`/seo-technical`](./seo/seo-technical/) | SEO 相關 | 自訂 | Audit technical SEO across crawlability, indexability, secu… |
| [`/seo-unlighthouse`](./seo/seo-unlighthouse/) | SEO 相關 | 自訂 | Multi-page Lighthouse audit via the MIT-licensed Unlighthou… |
| [`/engineering:architecture`](./engineering/) | 工程 | 平台內建 | 建立或評估架構決策記錄（ADR） |
| [`/engineering:code-review`](./engineering/) | 工程 | 平台內建 | 審查程式碼變更的安全、效能與正確性 |
| [`/engineering:debug`](./engineering/) | 工程 | 平台內建 | 結構化除錯：重現、隔離、診斷、修復 |
| [`/engineering:deploy-checklist`](./engineering/) | 工程 | 平台內建 | 部署前驗證檢查清單 |
| [`/engineering:documentation`](./engineering/) | 工程 | 平台內建 | 撰寫與維護技術文件 |
| [`/engineering:incident-response`](./engineering/) | 工程 | 平台內建 | 事故應變：分級、溝通、事後檢討 |
| [`/engineering:standup`](./engineering/) | 工程 | 平台內建 | 從近期活動產生 standup 更新 |
| [`/engineering:system-design`](./engineering/) | 工程 | 平台內建 | 設計系統、服務與架構 |
| [`/engineering:tech-debt`](./engineering/) | 工程 | 平台內建 | 識別、分類並排序技術債 |
| [`/engineering:testing-strategy`](./engineering/) | 工程 | 平台內建 | 設計測試策略與測試計畫 |
| [`/sales:account-context`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:account-plan`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:account-research`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:account-tiering`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:call-prep`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:call-summary`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:close-plan`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:competitive-intelligence`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:create-an-asset`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:crm-hygiene-check`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:customer-health`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:customer-voice`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:daily-briefing`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:deal-advance-gap`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:deal-review`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:deal-signals`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:deal-slip-scenario`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:draft-outreach`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:end-of-day`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:expansion-whitespace`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:forecast`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:handle-objection`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:inbox-sweep`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:lead-triage`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:log-activity`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:pipeline-review`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:renewal-radar`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:rep-context`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:route-lead`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:schedule-meeting`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:setup`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:stakeholder-map`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:team-pipeline`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:update-opportunity`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:weekly-wrap`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/sales:win-loss-review`](./sales/) | 業務 | 平台內建 | （官方未提供說明） |
| [`/finance:audit-support`](./finance/) | 財務 | 平台內建 | （官方未提供說明） |
| [`/finance:close-management`](./finance/) | 財務 | 平台內建 | （官方未提供說明） |
| [`/finance:financial-statements`](./finance/) | 財務 | 平台內建 | （官方未提供說明） |
| [`/finance:journal-entry`](./finance/) | 財務 | 平台內建 | （官方未提供說明） |
| [`/finance:journal-entry-prep`](./finance/) | 財務 | 平台內建 | （官方未提供說明） |
| [`/finance:reconciliation`](./finance/) | 財務 | 平台內建 | （官方未提供說明） |
| [`/finance:sox-testing`](./finance/) | 財務 | 平台內建 | （官方未提供說明） |
| [`/finance:variance-analysis`](./finance/) | 財務 | 平台內建 | （官方未提供說明） |
| [`/human-resources:comp-analysis`](./human-resources/) | 人資 | 平台內建 | 薪酬分析：基準、級距、股權 |
| [`/human-resources:draft-offer`](./human-resources/) | 人資 | 平台內建 | 草擬 offer letter |
| [`/human-resources:interview-prep`](./human-resources/) | 人資 | 平台內建 | 建立結構化面試計畫與評分表 |
| [`/human-resources:onboarding`](./human-resources/) | 人資 | 平台內建 | 產生新人報到清單與第一週計畫 |
| [`/human-resources:org-planning`](./human-resources/) | 人資 | 平台內建 | 人力規劃與組織設計 |
| [`/human-resources:people-report`](./human-resources/) | 人資 | 平台內建 | 產生人數、離職率等報告 |
| [`/human-resources:performance-review`](./human-resources/) | 人資 | 平台內建 | 結構化績效考核 |
| [`/human-resources:policy-lookup`](./human-resources/) | 人資 | 平台內建 | 查詢並說明公司政策 |
| [`/human-resources:recruiting-pipeline`](./human-resources/) | 人資 | 平台內建 | 追蹤招募流程 |
| [`/design:accessibility-review`](./design/) | 設計 | 平台內建 | WCAG 2.1 AA 無障礙稽核 |
| [`/design:design-critique`](./design/) | 設計 | 平台內建 | 取得結構化設計回饋 |
| [`/design:design-handoff`](./design/) | 設計 | 平台內建 | 產生開發交付規格 |
| [`/design:design-system`](./design/) | 設計 | 平台內建 | 稽核、記錄或擴充設計系統 |
| [`/design:research-synthesis`](./design/) | 設計 | 平台內建 | 將使用者研究整合為主題與建議 |
| [`/design:user-research`](./design/) | 設計 | 平台內建 | 規劃、執行與整合使用者研究 |
| [`/design:ux-copy`](./design/) | 設計 | 平台內建 | 撰寫或審閱 UX 文案 |
| [`/marketing:brand-review`](./marketing/) | 行銷 | 平台內建 | （官方未提供說明） |
| [`/marketing:campaign-plan`](./marketing/) | 行銷 | 平台內建 | （官方未提供說明） |
| [`/marketing:competitive-brief`](./marketing/) | 行銷 | 平台內建 | （官方未提供說明） |
| [`/marketing:content-creation`](./marketing/) | 行銷 | 平台內建 | （官方未提供說明） |
| [`/marketing:draft-content`](./marketing/) | 行銷 | 平台內建 | （官方未提供說明） |
| [`/marketing:email-sequence`](./marketing/) | 行銷 | 平台內建 | （官方未提供說明） |
| [`/marketing:performance-report`](./marketing/) | 行銷 | 平台內建 | （官方未提供說明） |
| [`/marketing:seo-audit`](./marketing/) | 行銷 | 平台內建 | （官方未提供說明） |
| [`/data:analyze`](./data/) | 資料 | 平台內建 | （官方未提供說明） |
| [`/data:build-dashboard`](./data/) | 資料 | 平台內建 | （官方未提供說明） |
| [`/data:create-viz`](./data/) | 資料 | 平台內建 | （官方未提供說明） |
| [`/data:data-context-extractor`](./data/) | 資料 | 平台內建 | （官方未提供說明） |
| [`/data:data-visualization`](./data/) | 資料 | 平台內建 | （官方未提供說明） |
| [`/data:explore-data`](./data/) | 資料 | 平台內建 | （官方未提供說明） |
| [`/data:sql-queries`](./data/) | 資料 | 平台內建 | （官方未提供說明） |
| [`/data:statistical-analysis`](./data/) | 資料 | 平台內建 | （官方未提供說明） |
| [`/data:validate-data`](./data/) | 資料 | 平台內建 | （官方未提供說明） |
| [`/data:write-query`](./data/) | 資料 | 平台內建 | （官方未提供說明） |
| [`/operations:capacity-plan`](./operations/) | 營運 | 平台內建 | 資源產能規劃 |
| [`/operations:change-request`](./operations/) | 營運 | 平台內建 | 建立變更請求與影響分析 |
| [`/operations:compliance-tracking`](./operations/) | 營運 | 平台內建 | 追蹤合規要求與稽核準備 |
| [`/operations:process-doc`](./operations/) | 營運 | 平台內建 | 記錄業務流程（流程圖、RACI、SOP） |
| [`/operations:process-optimization`](./operations/) | 營運 | 平台內建 | 分析並改善業務流程 |
| [`/operations:risk-assessment`](./operations/) | 營運 | 平台內建 | 識別、評估並緩解營運風險 |
| [`/operations:runbook`](./operations/) | 營運 | 平台內建 | 建立或更新營運 runbook |
| [`/operations:status-report`](./operations/) | 營運 | 平台內建 | 產生含 KPI 與風險的狀態報告 |
| [`/operations:vendor-review`](./operations/) | 營運 | 平台內建 | 評估供應商 |
| [`/legal:brief`](./legal/) | 法務 | 平台內建 | （官方未提供說明） |
| [`/legal:compliance-check`](./legal/) | 法務 | 平台內建 | （官方未提供說明） |
| [`/legal:legal-response`](./legal/) | 法務 | 平台內建 | （官方未提供說明） |
| [`/legal:legal-risk-assessment`](./legal/) | 法務 | 平台內建 | （官方未提供說明） |
| [`/legal:meeting-briefing`](./legal/) | 法務 | 平台內建 | （官方未提供說明） |
| [`/legal:review-contract`](./legal/) | 法務 | 平台內建 | （官方未提供說明） |
| [`/legal:signature-request`](./legal/) | 法務 | 平台內建 | （官方未提供說明） |
| [`/legal:triage-nda`](./legal/) | 法務 | 平台內建 | （官方未提供說明） |
| [`/legal:vendor-check`](./legal/) | 法務 | 平台內建 | （官方未提供說明） |
| [`/product-management:brainstorm`](./product-management/) | 產品管理 | 平台內建 | 與產品想法進行腦力激盪 |
| [`/product-management:competitive-brief`](./product-management/) | 產品管理 | 平台內建 | （官方未提供說明） |
| [`/product-management:metrics-review`](./product-management/) | 產品管理 | 平台內建 | （官方未提供說明） |
| [`/product-management:product-brainstorming`](./product-management/) | 產品管理 | 平台內建 | （官方未提供說明） |
| [`/product-management:roadmap-update`](./product-management/) | 產品管理 | 平台內建 | （官方未提供說明） |
| [`/product-management:sprint-planning`](./product-management/) | 產品管理 | 平台內建 | （官方未提供說明） |
| [`/product-management:stakeholder-update`](./product-management/) | 產品管理 | 平台內建 | （官方未提供說明） |
| [`/product-management:synthesize-research`](./product-management/) | 產品管理 | 平台內建 | （官方未提供說明） |
| [`/product-management:write-spec`](./product-management/) | 產品管理 | 平台內建 | （官方未提供說明） |
| [`/bio-research:instrument-data-to-allotrope`](./bio-research/) | 生物研究 | 平台內建 | （官方未提供說明） |
| [`/bio-research:nextflow-development`](./bio-research/) | 生物研究 | 平台內建 | （官方未提供說明） |
| [`/bio-research:scientific-problem-selection`](./bio-research/) | 生物研究 | 平台內建 | （官方未提供說明） |
| [`/bio-research:scvi-tools`](./bio-research/) | 生物研究 | 平台內建 | （官方未提供說明） |
| [`/bio-research:single-cell-rna-qc`](./bio-research/) | 生物研究 | 平台內建 | （官方未提供說明） |
| [`/bio-research:start`](./bio-research/) | 生物研究 | 平台內建 | （官方未提供說明） |
| [`/small-business:ad-manager`](./small-business/) | 小型企業 | 平台內建 | 廣告成效分析與優化建議 |
| [`/small-business:ap-processor`](./small-business/) | 小型企業 | 平台內建 | 處理應付帳款帳單與付款批次 |
| [`/small-business:brand-style`](./small-business/) | 小型企業 | 平台內建 | 設定品牌樣式與輸出偏好 |
| [`/small-business:build-agent`](./small-business/) | 小型企業 | 平台內建 | 把重複性任務轉成可重用 skill |
| [`/small-business:build-connector`](./small-business/) | 小型企業 | 平台內建 | 透過 Zapier 連接未支援的工具 |
| [`/small-business:business-pulse`](./small-business/) | 小型企業 | 平台內建 | 一頁式跨部門業務快照 |
| [`/small-business:call-list`](./small-business/) | 小型企業 | 平台內建 | 建立今日電話清單 |
| [`/small-business:canva-creator`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:cash-flow-snapshot`](./small-business/) | 小型企業 | 平台內建 | 30/60/90 天現金流預測 |
| [`/small-business:close-month`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:content-strategy`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:contract-review`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:crm-autopilot`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:grant-rfp-writer`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:grow-pipeline`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:growth-pulse`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:hiring-screener`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:inbox-manager`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:inventory-planner`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:invoice-chase`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:job-post-builder`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:lead-finder`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:lead-triage`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:marketing-monday`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:monday-brief`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:month-end-prep`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:outreach-composer`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:pay-the-bills`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:payroll-prep`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:plan-payroll`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:proposal-builder`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:reactivate`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:report-builder`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:report-pack`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:restock`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:review-reputation`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:seo-ai-visibility`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:smb-onboard`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:smb-router`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:social-content-engine`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:speed-to-lead`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:tax-prep`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:tax-season-organizer`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/small-business:ticket-deflector`](./small-business/) | 小型企業 | 平台內建 | （官方未提供說明） |
| [`/customer-support:customer-escalation`](./customer-support/) | 客戶支援 | 平台內建 | （官方未提供說明） |
| [`/customer-support:customer-research`](./customer-support/) | 客戶支援 | 平台內建 | （官方未提供說明） |
| [`/customer-support:draft-response`](./customer-support/) | 客戶支援 | 平台內建 | （官方未提供說明） |
| [`/customer-support:kb-article`](./customer-support/) | 客戶支援 | 平台內建 | （官方未提供說明） |
| [`/customer-support:ticket-triage`](./customer-support/) | 客戶支援 | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:ai-weekly-digest`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:algorithmic-art`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:brand-guidelines`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:built-in-browser`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:canvas-design`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:chrome-browser`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:cier-pest-writer`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:cier-policy-article-writer`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:computer-use`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:copywriter`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:daily-news-digest`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:deep-research`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:doc-coauthoring`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:docs`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:docx`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:dual-review-organizer`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:en-to-zh-translator`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:fable-mode-thinking`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:google-workspace`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:humanize-zh-draft`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:import-memory`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:internal-comms`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:learn`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:mcp-builder`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:meeting-minutes-translator`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:morning`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:official-letter-writer`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:pdf`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:pmi-questionnaire-review`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:policy-calc-writer`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:policy-style-writer`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:pptx`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:sdgs-netzero-analyzer`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:si-platform-health-check`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:skill-creator`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:slack-gif-creator`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:theme-factory`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:web-artifacts-builder`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:weekly-news-digest`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:xlsx`](./anthropic-skills/) | Anthropic | 平台內建 | （官方未提供說明） |
| [`/cier-meeting-minutes`](./general/cier-meeting-minutes/) | 通用 | 自訂 | 中經院國際研討會會議記錄產生器（依逐字稿產出會議記錄） |
| [`/diagram-design`](./general/diagram-design/) | 通用 | 自訂 | Create branded architecture, architecture delta, IT current… |
| [`/news-collector`](./general/news-collector/) | 通用 | 自訂 | 台商新聞自動蒐集與彙整——使用者提供 Excel 檔案或公司清單，自動搜尋每家公司近兩年財經新聞，詢問輸出目錄，為每家… |
| [`/pdf-to-markdown`](./general/pdf-to-markdown/) | 通用 | 自訂 | Convert entire PDF documents to clean, structured Markdown … |
| [`/session-start-hook`](./general/) | 通用 | 平台內建 | 建立 SessionStart hook |
| [`/pdf-viewer:annotate`](./general/) | 通用 | 平台內建 | 協作標註 PDF |
| [`/pdf-viewer:fill-form`](./general/) | 通用 | 平台內建 | 互動填寫 PDF 表單 |
| [`/pdf-viewer:open`](./general/) | 通用 | 平台內建 | 開啟 PDF 檢視器 |
| [`/pdf-viewer:sign`](./general/) | 通用 | 平台內建 | 在 PDF 放置簽名 |
| [`/pdf-viewer:view-pdf`](./general/) | 通用 | 平台內建 | 互動式 PDF 檢視器 |
| [`/productivity:memory-management`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/productivity:start`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/productivity:task-management`](./general/) | 通用 | 平台內建 | 以 TASKS.md 管理任務 |
| [`/productivity:update`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/enterprise-search:digest`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/enterprise-search:knowledge-synthesis`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/enterprise-search:search`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/enterprise-search:search-strategy`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/enterprise-search:source-management`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/cowork-plugin-management:cowork-plugin-customizer`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/cowork-plugin-management:create-cowork-plugin`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/dataviz`](./general/) | 通用 | 平台內建 | 建立圖表與資料視覺化的設計指引 |
| [`/artifact-design`](./general/) | 通用 | 平台內建 | Artifact 設計指引 |
| [`/artifact-diagramming`](./general/) | 通用 | 平台內建 | Artifact 圖表繪製指引 |
| [`/artifact-capabilities`](./general/) | 通用 | 平台內建 | Artifact 執行期能力 |
| [`/update-config`](./general/) | 通用 | 平台內建 | 設定 Claude Code settings.json |
| [`/keybindings-help`](./general/) | 通用 | 平台內建 | 自訂鍵盤快速鍵 |
| [`/code-review`](./general/) | 通用 | 平台內建 | 審查 diff 或 PR 的正確性問題 |
| [`/simplify`](./general/) | 通用 | 平台內建 | 審查並簡化變更的程式碼 |
| [`/fewer-permission-prompts`](./general/) | 通用 | 平台內建 | 新增允許清單以減少權限提示 |
| [`/loop`](./general/) | 通用 | 平台內建 | 依間隔重複執行 prompt |
| [`/claude-api`](./general/) | 通用 | 平台內建 | Claude API / SDK 參考 |
| [`/workflow-authoring`](./general/) | 通用 | 平台內建 | Workflow 腳本撰寫參考 |
| [`/run`](./general/) | 通用 | 平台內建 | 啟動並驅動專案 app |
| [`/plugin-authoring`](./general/) | 通用 | 平台內建 | 製作 mod（介面或行為變更） |
| [`/init`](./general/) | 通用 | 平台內建 | （官方未提供說明） |
| [`/security-review`](./general/) | 通用 | 平台內建 | （官方未提供說明） |

## 使用方式

在 Claude Code 輸入 `/skill-name` 即可呼叫。
