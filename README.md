# Claude Skills 完整指南

> 更新日期：2026-11-08
>
> 每週日 22:00（台灣時間）自動更新

---

## Skill 分類總覽

| 分類 | Skills |
|------|--------|
| SEO | [`/seo`](./seo/seo/) [`/seo-agentic`](./seo/seo-agentic/) [`/seo-ahrefs`](./seo/seo-ahrefs/) [`/seo-audit`](./seo/seo-audit/) [`/seo-backlinks`](./seo/seo-backlinks/) [`/seo-bing`](./seo/seo-bing/) [`/seo-cluster`](./seo/seo-cluster/) [`/seo-competitor-pages`](./seo/seo-competitor-pages/) [`/seo-content`](./seo/seo-content/) [`/seo-content-brief`](./seo/seo-content-brief/) [`/seo-dataforseo`](./seo/seo-dataforseo/) [`/seo-drift`](./seo/seo-drift/) [`/seo-ecommerce`](./seo/seo-ecommerce/) [`/seo-firecrawl`](./seo/seo-firecrawl/) [`/seo-flow`](./seo/seo-flow/) [`/seo-geo`](./seo/seo-geo/) [`/seo-google`](./seo/seo-google/) [`/seo-hreflang`](./seo/seo-hreflang/) [`/seo-image-gen`](./seo/seo-image-gen/) [`/seo-images`](./seo/seo-images/) [`/seo-local`](./seo/seo-local/) [`/seo-maps`](./seo/seo-maps/) [`/seo-matomo`](./seo/seo-matomo/) [`/seo-page`](./seo/seo-page/) [`/seo-plan`](./seo/seo-plan/) [`/seo-profound`](./seo/seo-profound/) [`/seo-programmatic`](./seo/seo-programmatic/) [`/seo-report`](./seo/seo-report/) [`/seo-schema`](./seo/seo-schema/) [`/seo-seranking`](./seo/seo-seranking/) [`/seo-sitemap`](./seo/seo-sitemap/) [`/seo-sxo`](./seo/seo-sxo/) [`/seo-technical`](./seo/seo-technical/) [`/seo-unlighthouse`](./seo/seo-unlighthouse/) |
| 工程 | [`/engineering:architecture`](./engineering/) [`/engineering:code-review`](./engineering/) [`/engineering:debug`](./engineering/) [`/engineering:deploy-checklist`](./engineering/) [`/engineering:documentation`](./engineering/) [`/engineering:incident-response`](./engineering/) [`/engineering:standup`](./engineering/) [`/engineering:system-design`](./engineering/) [`/engineering:tech-debt`](./engineering/) [`/engineering:testing-strategy`](./engineering/) |
| 業務 | [`/sales:account-context`](./sales/) [`/sales:account-plan`](./sales/) [`/sales:account-research`](./sales/) [`/sales:account-tiering`](./sales/) [`/sales:call-prep`](./sales/) [`/sales:call-summary`](./sales/) [`/sales:close-plan`](./sales/) [`/sales:competitive-intelligence`](./sales/) [`/sales:create-an-asset`](./sales/) [`/sales:crm-hygiene-check`](./sales/) [`/sales:customer-health`](./sales/) [`/sales:customer-voice`](./sales/) [`/sales:daily-briefing`](./sales/) [`/sales:deal-advance-gap`](./sales/) [`/sales:deal-review`](./sales/) [`/sales:deal-signals`](./sales/) [`/sales:deal-slip-scenario`](./sales/) [`/sales:draft-outreach`](./sales/) [`/sales:end-of-day`](./sales/) [`/sales:expansion-whitespace`](./sales/) [`/sales:forecast`](./sales/) [`/sales:handle-objection`](./sales/) [`/sales:inbox-sweep`](./sales/) [`/sales:lead-triage`](./sales/) [`/sales:log-activity`](./sales/) [`/sales:pipeline-review`](./sales/) [`/sales:renewal-radar`](./sales/) [`/sales:rep-context`](./sales/) [`/sales:route-lead`](./sales/) [`/sales:schedule-meeting`](./sales/) [`/sales:setup`](./sales/) [`/sales:stakeholder-map`](./sales/) [`/sales:team-pipeline`](./sales/) [`/sales:update-opportunity`](./sales/) [`/sales:weekly-wrap`](./sales/) [`/sales:win-loss-review`](./sales/) |
| 財務 | [`/finance:audit-support`](./finance/) [`/finance:close-management`](./finance/) [`/finance:financial-statements`](./finance/) [`/finance:journal-entry`](./finance/) [`/finance:journal-entry-prep`](./finance/) [`/finance:reconciliation`](./finance/) [`/finance:sox-testing`](./finance/) [`/finance:variance-analysis`](./finance/) |
| 人資 | [`/human-resources:comp-analysis`](./human-resources/) [`/human-resources:draft-offer`](./human-resources/) [`/human-resources:interview-prep`](./human-resources/) [`/human-resources:onboarding`](./human-resources/) [`/human-resources:org-planning`](./human-resources/) [`/human-resources:people-report`](./human-resources/) [`/human-resources:performance-review`](./human-resources/) [`/human-resources:policy-lookup`](./human-resources/) [`/human-resources:recruiting-pipeline`](./human-resources/) |
| 設計 | [`/design:accessibility-review`](./design/) [`/design:design-critique`](./design/) [`/design:design-handoff`](./design/) [`/design:design-system`](./design/) [`/design:research-synthesis`](./design/) [`/design:user-research`](./design/) [`/design:ux-copy`](./design/) |
| 行銷 | [`/marketing:brand-review`](./marketing/) [`/marketing:campaign-plan`](./marketing/) [`/marketing:competitive-brief`](./marketing/) [`/marketing:content-creation`](./marketing/) [`/marketing:draft-content`](./marketing/) [`/marketing:email-sequence`](./marketing/) [`/marketing:performance-report`](./marketing/) [`/marketing:seo-audit`](./marketing/) |
| 資料 | [`/data:analyze`](./data/) [`/data:build-dashboard`](./data/) [`/data:create-viz`](./data/) [`/data:data-context-extractor`](./data/) [`/data:data-visualization`](./data/) [`/data:explore-data`](./data/) [`/data:sql-queries`](./data/) [`/data:statistical-analysis`](./data/) [`/data:validate-data`](./data/) [`/data:write-query`](./data/) |
| 營運 | [`/operations:capacity-plan`](./operations/) [`/operations:change-request`](./operations/) [`/operations:compliance-tracking`](./operations/) [`/operations:process-doc`](./operations/) [`/operations:process-optimization`](./operations/) [`/operations:risk-assessment`](./operations/) [`/operations:runbook`](./operations/) [`/operations:status-report`](./operations/) [`/operations:vendor-review`](./operations/) |
| 法務 | [`/legal:brief`](./legal/) [`/legal:compliance-check`](./legal/) [`/legal:legal-response`](./legal/) [`/legal:legal-risk-assessment`](./legal/) [`/legal:meeting-briefing`](./legal/) [`/legal:review-contract`](./legal/) [`/legal:signature-request`](./legal/) [`/legal:triage-nda`](./legal/) [`/legal:vendor-check`](./legal/) |
| 產品管理 | [`/product-management:brainstorm`](./product-management/) [`/product-management:competitive-brief`](./product-management/) [`/product-management:metrics-review`](./product-management/) [`/product-management:product-brainstorming`](./product-management/) [`/product-management:roadmap-update`](./product-management/) [`/product-management:sprint-planning`](./product-management/) [`/product-management:stakeholder-update`](./product-management/) [`/product-management:synthesize-research`](./product-management/) [`/product-management:write-spec`](./product-management/) |
| 生物研究 | [`/bio-research:instrument-data-to-allotrope`](./bio-research/) [`/bio-research:nextflow-development`](./bio-research/) [`/bio-research:scientific-problem-selection`](./bio-research/) [`/bio-research:scvi-tools`](./bio-research/) [`/bio-research:single-cell-rna-qc`](./bio-research/) [`/bio-research:start`](./bio-research/) |
| 小型企業 | [`/small-business:ad-manager`](./small-business/) [`/small-business:ap-processor`](./small-business/) [`/small-business:brand-style`](./small-business/) [`/small-business:build-agent`](./small-business/) [`/small-business:build-connector`](./small-business/) [`/small-business:business-pulse`](./small-business/) [`/small-business:call-list`](./small-business/) [`/small-business:canva-creator`](./small-business/) [`/small-business:cash-flow-snapshot`](./small-business/) [`/small-business:close-month`](./small-business/) [`/small-business:content-strategy`](./small-business/) [`/small-business:contract-review`](./small-business/) [`/small-business:crm-autopilot`](./small-business/) [`/small-business:grant-rfp-writer`](./small-business/) [`/small-business:grow-pipeline`](./small-business/) [`/small-business:growth-pulse`](./small-business/) [`/small-business:hiring-screener`](./small-business/) [`/small-business:inbox-manager`](./small-business/) [`/small-business:inventory-planner`](./small-business/) [`/small-business:invoice-chase`](./small-business/) [`/small-business:job-post-builder`](./small-business/) [`/small-business:lead-finder`](./small-business/) [`/small-business:lead-triage`](./small-business/) [`/small-business:marketing-monday`](./small-business/) [`/small-business:monday-brief`](./small-business/) [`/small-business:month-end-prep`](./small-business/) [`/small-business:outreach-composer`](./small-business/) [`/small-business:pay-the-bills`](./small-business/) [`/small-business:payroll-prep`](./small-business/) [`/small-business:plan-payroll`](./small-business/) [`/small-business:proposal-builder`](./small-business/) [`/small-business:reactivate`](./small-business/) [`/small-business:report-builder`](./small-business/) [`/small-business:report-pack`](./small-business/) [`/small-business:restock`](./small-business/) [`/small-business:review-reputation`](./small-business/) [`/small-business:seo-ai-visibility`](./small-business/) [`/small-business:smb-onboard`](./small-business/) [`/small-business:smb-router`](./small-business/) [`/small-business:social-content-engine`](./small-business/) [`/small-business:speed-to-lead`](./small-business/) [`/small-business:tax-prep`](./small-business/) [`/small-business:tax-season-organizer`](./small-business/) [`/small-business:ticket-deflector`](./small-business/) |
| 客戶支援 | [`/customer-support:customer-escalation`](./customer-support/) [`/customer-support:customer-research`](./customer-support/) [`/customer-support:draft-response`](./customer-support/) [`/customer-support:kb-article`](./customer-support/) [`/customer-support:ticket-triage`](./customer-support/) |
| Anthropic 官方 | [`/anthropic-skills:ai-weekly-digest`](./anthropic-skills/) [`/anthropic-skills:algorithmic-art`](./anthropic-skills/) [`/anthropic-skills:brand-guidelines`](./anthropic-skills/) [`/anthropic-skills:built-in-browser`](./anthropic-skills/) [`/anthropic-skills:canvas-design`](./anthropic-skills/) [`/anthropic-skills:chrome-browser`](./anthropic-skills/) [`/anthropic-skills:cier-pest-writer`](./anthropic-skills/) [`/anthropic-skills:cier-policy-article-writer`](./anthropic-skills/) [`/anthropic-skills:computer-use`](./anthropic-skills/) [`/anthropic-skills:copywriter`](./anthropic-skills/) [`/anthropic-skills:daily-news-digest`](./anthropic-skills/) [`/anthropic-skills:deep-research`](./anthropic-skills/) [`/anthropic-skills:doc-coauthoring`](./anthropic-skills/) [`/anthropic-skills:docs`](./anthropic-skills/) [`/anthropic-skills:docx`](./anthropic-skills/) [`/anthropic-skills:dual-review-organizer`](./anthropic-skills/) [`/anthropic-skills:en-to-zh-translator`](./anthropic-skills/) [`/anthropic-skills:fable-mode-thinking`](./anthropic-skills/) [`/anthropic-skills:google-workspace`](./anthropic-skills/) [`/anthropic-skills:humanize-zh-draft`](./anthropic-skills/) [`/anthropic-skills:import-memory`](./anthropic-skills/) [`/anthropic-skills:internal-comms`](./anthropic-skills/) [`/anthropic-skills:learn`](./anthropic-skills/) [`/anthropic-skills:mcp-builder`](./anthropic-skills/) [`/anthropic-skills:meeting-minutes-translator`](./anthropic-skills/) [`/anthropic-skills:morning`](./anthropic-skills/) [`/anthropic-skills:official-letter-writer`](./anthropic-skills/) [`/anthropic-skills:pdf`](./anthropic-skills/) [`/anthropic-skills:pmi-questionnaire-review`](./anthropic-skills/) [`/anthropic-skills:policy-calc-writer`](./anthropic-skills/) [`/anthropic-skills:policy-style-writer`](./anthropic-skills/) [`/anthropic-skills:pptx`](./anthropic-skills/) [`/anthropic-skills:sdgs-netzero-analyzer`](./anthropic-skills/) [`/anthropic-skills:si-platform-health-check`](./anthropic-skills/) [`/anthropic-skills:skill-creator`](./anthropic-skills/) [`/anthropic-skills:slack-gif-creator`](./anthropic-skills/) [`/anthropic-skills:theme-factory`](./anthropic-skills/) [`/anthropic-skills:web-artifacts-builder`](./anthropic-skills/) [`/anthropic-skills:weekly-news-digest`](./anthropic-skills/) [`/anthropic-skills:xlsx`](./anthropic-skills/) |
| 通用 | [`/cier-meeting-minutes`](./general/cier-meeting-minutes/) [`/diagram-design`](./general/diagram-design/) [`/news-collector`](./general/news-collector/) [`/pdf-to-markdown`](./general/pdf-to-markdown/) [`/session-start-hook`](./general/) [`/pdf-viewer:annotate`](./general/) [`/pdf-viewer:fill-form`](./general/) [`/pdf-viewer:open`](./general/) [`/pdf-viewer:sign`](./general/) [`/pdf-viewer:view-pdf`](./general/) [`/productivity:memory-management`](./general/) [`/productivity:start`](./general/) [`/productivity:task-management`](./general/) [`/productivity:update`](./general/) [`/enterprise-search:digest`](./general/) [`/enterprise-search:knowledge-synthesis`](./general/) [`/enterprise-search:search`](./general/) [`/enterprise-search:search-strategy`](./general/) [`/enterprise-search:source-management`](./general/) [`/cowork-plugin-management:cowork-plugin-customizer`](./general/) [`/cowork-plugin-management:create-cowork-plugin`](./general/) [`/dataviz`](./general/) [`/artifact-design`](./general/) [`/artifact-diagramming`](./general/) [`/artifact-capabilities`](./general/) [`/update-config`](./general/) [`/keybindings-help`](./general/) [`/code-review`](./general/) [`/simplify`](./general/) [`/fewer-permission-prompts`](./general/) [`/loop`](./general/) [`/claude-api`](./general/) [`/workflow-authoring`](./general/) [`/run`](./general/) [`/plugin-authoring`](./general/) [`/init`](./general/) [`/security-review`](./general/) |

---

## 完整 Skill 清單

| Skill 指令 | 所在資料夾 | 來源 | 功能簡述 |
|-----------|-----------|------|---------|
| [`/seo`](./seo/seo/) | `seo/seo/` | 自訂 | Comprehensive SEO analysis for any website or business type. |
| [`/seo-agentic`](./seo/seo-agentic/) | `seo/seo-agentic/` | 自訂 | Audit and fix agent readiness: the Lighthouse Agentic Brows… |
| [`/seo-ahrefs`](./seo/seo-ahrefs/) | `seo/seo-ahrefs/` | 自訂 | Ahrefs API analyst (extension). |
| [`/seo-audit`](./seo/seo-audit/) | `seo/seo-audit/` | 自訂 | Run a full-site SEO audit and return a scored, prioritized … |
| [`/seo-backlinks`](./seo/seo-backlinks/) | `seo/seo-backlinks/` | 自訂 | Analyze a site's backlink profile, anchors, toxic signals, … |
| [`/seo-bing`](./seo/seo-bing/) | `seo/seo-bing/` | 自訂 | Bing Webmaster Tools + IndexNow extension. |
| [`/seo-cluster`](./seo/seo-cluster/) | `seo/seo-cluster/` | 自訂 | Cluster keywords by SERP overlap and design hub-and-spoke c… |
| [`/seo-competitor-pages`](./seo/seo-competitor-pages/) | `seo/seo-competitor-pages/` | 自訂 | Generate SEO-optimized competitor comparison and alternativ… |
| [`/seo-content`](./seo/seo-content/) | `seo/seo-content/` | 自訂 | Evaluate page content for usefulness, E-E-A-T, readability,… |
| [`/seo-content-brief`](./seo/seo-content-brief/) | `seo/seo-content-brief/` | 自訂 | Generate competitive SEO content briefs with per-section wo… |
| [`/seo-dataforseo`](./seo/seo-dataforseo/) | `seo/seo-dataforseo/` | 自訂 | Live SEO data via DataForSEO MCP server: SERP analysis, key… |
| [`/seo-drift`](./seo/seo-drift/) | `seo/seo-drift/` | 自訂 | SEO drift monitoring: capture baselines of SEO-critical ele… |
| [`/seo-ecommerce`](./seo/seo-ecommerce/) | `seo/seo-ecommerce/` | 自訂 | Analyze ecommerce SEO across product pages, product schema,… |
| [`/seo-firecrawl`](./seo/seo-firecrawl/) | `seo/seo-firecrawl/` | 自訂 | Full-site crawling, scraping, and site mapping via Firecraw… |
| [`/seo-flow`](./seo/seo-flow/) | `seo/seo-flow/` | 自訂 | FLOW framework integration: evidence-led SEO using the Find… |
| [`/seo-geo`](./seo/seo-geo/) | `seo/seo-geo/` | 自訂 | Audit and improve content for AI Overviews and answer engin… |
| [`/seo-google`](./seo/seo-google/) | `seo/seo-google/` | 自訂 | Google SEO APIs: Search Console (Search Analytics, URL Insp… |
| [`/seo-hreflang`](./seo/seo-hreflang/) | `seo/seo-hreflang/` | 自訂 | Hreflang and international SEO audit, validation, and gener… |
| [`/seo-image-gen`](./seo/seo-image-gen/) | `seo/seo-image-gen/` | 自訂 | AI image generation for SEO assets: OG/social preview image… |
| [`/seo-images`](./seo/seo-images/) | `seo/seo-images/` | 自訂 | Image optimization analysis for SEO and performance. |
| [`/seo-local`](./seo/seo-local/) | `seo/seo-local/` | 自訂 | Audit local SEO, including Google Business Profile, NAP con… |
| [`/seo-maps`](./seo/seo-maps/) | `seo/seo-maps/` | 自訂 | Maps intelligence for local SEO: geo-grid rank tracking, GB… |
| [`/seo-matomo`](./seo/seo-matomo/) | `seo/seo-matomo/` | 自訂 | Matomo Reporting API extension. |
| [`/seo-page`](./seo/seo-page/) | `seo/seo-page/` | 自訂 | Analyze one supplied URL across on-page, content, technical… |
| [`/seo-plan`](./seo/seo-plan/) | `seo/seo-plan/` | 自訂 | Strategic SEO planning for new or existing websites. |
| [`/seo-profound`](./seo/seo-profound/) | `seo/seo-profound/` | 自訂 | Profound LLM citation tracker (extension). |
| [`/seo-programmatic`](./seo/seo-programmatic/) | `seo/seo-programmatic/` | 自訂 | Programmatic SEO planning and analysis for pages generated … |
| [`/seo-report`](./seo/seo-report/) | `seo/seo-report/` | 自訂 | Run a full SEO audit on a URL, generate Chinese + English H… |
| [`/seo-schema`](./seo/seo-schema/) | `seo/seo-schema/` | 自訂 | Detect, validate, or generate Schema.org JSON-LD for a supp… |
| [`/seo-seranking`](./seo/seo-seranking/) | `seo/seo-seranking/` | 自訂 | SE Ranking AI visibility analyst (extension). |
| [`/seo-sitemap`](./seo/seo-sitemap/) | `seo/seo-sitemap/` | 自訂 | Analyze existing XML sitemaps or generate new ones with ind… |
| [`/seo-sxo`](./seo/seo-sxo/) | `seo/seo-sxo/` | 自訂 | Diagnose search-experience and intent mismatches using SERP… |
| [`/seo-technical`](./seo/seo-technical/) | `seo/seo-technical/` | 自訂 | Audit technical SEO across crawlability, indexability, secu… |
| [`/seo-unlighthouse`](./seo/seo-unlighthouse/) | `seo/seo-unlighthouse/` | 自訂 | Multi-page Lighthouse audit via the MIT-licensed Unlighthou… |
| [`/engineering:architecture`](./engineering/) | `engineering/architecture/` | 平台內建 | 建立或評估架構決策記錄（ADR） |
| [`/engineering:code-review`](./engineering/) | `engineering/code-review/` | 平台內建 | 審查程式碼變更的安全、效能與正確性 |
| [`/engineering:debug`](./engineering/) | `engineering/debug/` | 平台內建 | 結構化除錯：重現、隔離、診斷、修復 |
| [`/engineering:deploy-checklist`](./engineering/) | `engineering/deploy-checklist/` | 平台內建 | 部署前驗證檢查清單 |
| [`/engineering:documentation`](./engineering/) | `engineering/documentation/` | 平台內建 | 撰寫與維護技術文件 |
| [`/engineering:incident-response`](./engineering/) | `engineering/incident-response/` | 平台內建 | 事故應變：分級、溝通、事後檢討 |
| [`/engineering:standup`](./engineering/) | `engineering/standup/` | 平台內建 | 從近期活動產生 standup 更新 |
| [`/engineering:system-design`](./engineering/) | `engineering/system-design/` | 平台內建 | 設計系統、服務與架構 |
| [`/engineering:tech-debt`](./engineering/) | `engineering/tech-debt/` | 平台內建 | 識別、分類並排序技術債 |
| [`/engineering:testing-strategy`](./engineering/) | `engineering/testing-strategy/` | 平台內建 | 設計測試策略與測試計畫 |
| [`/sales:account-context`](./sales/) | `sales/account-context/` | 平台內建 | （官方未提供說明） |
| [`/sales:account-plan`](./sales/) | `sales/account-plan/` | 平台內建 | （官方未提供說明） |
| [`/sales:account-research`](./sales/) | `sales/account-research/` | 平台內建 | （官方未提供說明） |
| [`/sales:account-tiering`](./sales/) | `sales/account-tiering/` | 平台內建 | （官方未提供說明） |
| [`/sales:call-prep`](./sales/) | `sales/call-prep/` | 平台內建 | （官方未提供說明） |
| [`/sales:call-summary`](./sales/) | `sales/call-summary/` | 平台內建 | （官方未提供說明） |
| [`/sales:close-plan`](./sales/) | `sales/close-plan/` | 平台內建 | （官方未提供說明） |
| [`/sales:competitive-intelligence`](./sales/) | `sales/competitive-intelligence/` | 平台內建 | （官方未提供說明） |
| [`/sales:create-an-asset`](./sales/) | `sales/create-an-asset/` | 平台內建 | （官方未提供說明） |
| [`/sales:crm-hygiene-check`](./sales/) | `sales/crm-hygiene-check/` | 平台內建 | （官方未提供說明） |
| [`/sales:customer-health`](./sales/) | `sales/customer-health/` | 平台內建 | （官方未提供說明） |
| [`/sales:customer-voice`](./sales/) | `sales/customer-voice/` | 平台內建 | （官方未提供說明） |
| [`/sales:daily-briefing`](./sales/) | `sales/daily-briefing/` | 平台內建 | （官方未提供說明） |
| [`/sales:deal-advance-gap`](./sales/) | `sales/deal-advance-gap/` | 平台內建 | （官方未提供說明） |
| [`/sales:deal-review`](./sales/) | `sales/deal-review/` | 平台內建 | （官方未提供說明） |
| [`/sales:deal-signals`](./sales/) | `sales/deal-signals/` | 平台內建 | （官方未提供說明） |
| [`/sales:deal-slip-scenario`](./sales/) | `sales/deal-slip-scenario/` | 平台內建 | （官方未提供說明） |
| [`/sales:draft-outreach`](./sales/) | `sales/draft-outreach/` | 平台內建 | （官方未提供說明） |
| [`/sales:end-of-day`](./sales/) | `sales/end-of-day/` | 平台內建 | （官方未提供說明） |
| [`/sales:expansion-whitespace`](./sales/) | `sales/expansion-whitespace/` | 平台內建 | （官方未提供說明） |
| [`/sales:forecast`](./sales/) | `sales/forecast/` | 平台內建 | （官方未提供說明） |
| [`/sales:handle-objection`](./sales/) | `sales/handle-objection/` | 平台內建 | （官方未提供說明） |
| [`/sales:inbox-sweep`](./sales/) | `sales/inbox-sweep/` | 平台內建 | （官方未提供說明） |
| [`/sales:lead-triage`](./sales/) | `sales/lead-triage/` | 平台內建 | （官方未提供說明） |
| [`/sales:log-activity`](./sales/) | `sales/log-activity/` | 平台內建 | （官方未提供說明） |
| [`/sales:pipeline-review`](./sales/) | `sales/pipeline-review/` | 平台內建 | （官方未提供說明） |
| [`/sales:renewal-radar`](./sales/) | `sales/renewal-radar/` | 平台內建 | （官方未提供說明） |
| [`/sales:rep-context`](./sales/) | `sales/rep-context/` | 平台內建 | （官方未提供說明） |
| [`/sales:route-lead`](./sales/) | `sales/route-lead/` | 平台內建 | （官方未提供說明） |
| [`/sales:schedule-meeting`](./sales/) | `sales/schedule-meeting/` | 平台內建 | （官方未提供說明） |
| [`/sales:setup`](./sales/) | `sales/setup/` | 平台內建 | （官方未提供說明） |
| [`/sales:stakeholder-map`](./sales/) | `sales/stakeholder-map/` | 平台內建 | （官方未提供說明） |
| [`/sales:team-pipeline`](./sales/) | `sales/team-pipeline/` | 平台內建 | （官方未提供說明） |
| [`/sales:update-opportunity`](./sales/) | `sales/update-opportunity/` | 平台內建 | （官方未提供說明） |
| [`/sales:weekly-wrap`](./sales/) | `sales/weekly-wrap/` | 平台內建 | （官方未提供說明） |
| [`/sales:win-loss-review`](./sales/) | `sales/win-loss-review/` | 平台內建 | （官方未提供說明） |
| [`/finance:audit-support`](./finance/) | `finance/audit-support/` | 平台內建 | （官方未提供說明） |
| [`/finance:close-management`](./finance/) | `finance/close-management/` | 平台內建 | （官方未提供說明） |
| [`/finance:financial-statements`](./finance/) | `finance/financial-statements/` | 平台內建 | （官方未提供說明） |
| [`/finance:journal-entry`](./finance/) | `finance/journal-entry/` | 平台內建 | （官方未提供說明） |
| [`/finance:journal-entry-prep`](./finance/) | `finance/journal-entry-prep/` | 平台內建 | （官方未提供說明） |
| [`/finance:reconciliation`](./finance/) | `finance/reconciliation/` | 平台內建 | （官方未提供說明） |
| [`/finance:sox-testing`](./finance/) | `finance/sox-testing/` | 平台內建 | （官方未提供說明） |
| [`/finance:variance-analysis`](./finance/) | `finance/variance-analysis/` | 平台內建 | （官方未提供說明） |
| [`/human-resources:comp-analysis`](./human-resources/) | `human-resources/comp-analysis/` | 平台內建 | 薪酬分析：基準、級距、股權 |
| [`/human-resources:draft-offer`](./human-resources/) | `human-resources/draft-offer/` | 平台內建 | 草擬 offer letter |
| [`/human-resources:interview-prep`](./human-resources/) | `human-resources/interview-prep/` | 平台內建 | 建立結構化面試計畫與評分表 |
| [`/human-resources:onboarding`](./human-resources/) | `human-resources/onboarding/` | 平台內建 | 產生新人報到清單與第一週計畫 |
| [`/human-resources:org-planning`](./human-resources/) | `human-resources/org-planning/` | 平台內建 | 人力規劃與組織設計 |
| [`/human-resources:people-report`](./human-resources/) | `human-resources/people-report/` | 平台內建 | 產生人數、離職率等報告 |
| [`/human-resources:performance-review`](./human-resources/) | `human-resources/performance-review/` | 平台內建 | 結構化績效考核 |
| [`/human-resources:policy-lookup`](./human-resources/) | `human-resources/policy-lookup/` | 平台內建 | 查詢並說明公司政策 |
| [`/human-resources:recruiting-pipeline`](./human-resources/) | `human-resources/recruiting-pipeline/` | 平台內建 | 追蹤招募流程 |
| [`/design:accessibility-review`](./design/) | `design/accessibility-review/` | 平台內建 | WCAG 2.1 AA 無障礙稽核 |
| [`/design:design-critique`](./design/) | `design/design-critique/` | 平台內建 | 取得結構化設計回饋 |
| [`/design:design-handoff`](./design/) | `design/design-handoff/` | 平台內建 | 產生開發交付規格 |
| [`/design:design-system`](./design/) | `design/design-system/` | 平台內建 | 稽核、記錄或擴充設計系統 |
| [`/design:research-synthesis`](./design/) | `design/research-synthesis/` | 平台內建 | 將使用者研究整合為主題與建議 |
| [`/design:user-research`](./design/) | `design/user-research/` | 平台內建 | 規劃、執行與整合使用者研究 |
| [`/design:ux-copy`](./design/) | `design/ux-copy/` | 平台內建 | 撰寫或審閱 UX 文案 |
| [`/marketing:brand-review`](./marketing/) | `marketing/brand-review/` | 平台內建 | （官方未提供說明） |
| [`/marketing:campaign-plan`](./marketing/) | `marketing/campaign-plan/` | 平台內建 | （官方未提供說明） |
| [`/marketing:competitive-brief`](./marketing/) | `marketing/competitive-brief/` | 平台內建 | （官方未提供說明） |
| [`/marketing:content-creation`](./marketing/) | `marketing/content-creation/` | 平台內建 | （官方未提供說明） |
| [`/marketing:draft-content`](./marketing/) | `marketing/draft-content/` | 平台內建 | （官方未提供說明） |
| [`/marketing:email-sequence`](./marketing/) | `marketing/email-sequence/` | 平台內建 | （官方未提供說明） |
| [`/marketing:performance-report`](./marketing/) | `marketing/performance-report/` | 平台內建 | （官方未提供說明） |
| [`/marketing:seo-audit`](./marketing/) | `marketing/seo-audit/` | 平台內建 | （官方未提供說明） |
| [`/data:analyze`](./data/) | `data/analyze/` | 平台內建 | （官方未提供說明） |
| [`/data:build-dashboard`](./data/) | `data/build-dashboard/` | 平台內建 | （官方未提供說明） |
| [`/data:create-viz`](./data/) | `data/create-viz/` | 平台內建 | （官方未提供說明） |
| [`/data:data-context-extractor`](./data/) | `data/data-context-extractor/` | 平台內建 | （官方未提供說明） |
| [`/data:data-visualization`](./data/) | `data/data-visualization/` | 平台內建 | （官方未提供說明） |
| [`/data:explore-data`](./data/) | `data/explore-data/` | 平台內建 | （官方未提供說明） |
| [`/data:sql-queries`](./data/) | `data/sql-queries/` | 平台內建 | （官方未提供說明） |
| [`/data:statistical-analysis`](./data/) | `data/statistical-analysis/` | 平台內建 | （官方未提供說明） |
| [`/data:validate-data`](./data/) | `data/validate-data/` | 平台內建 | （官方未提供說明） |
| [`/data:write-query`](./data/) | `data/write-query/` | 平台內建 | （官方未提供說明） |
| [`/operations:capacity-plan`](./operations/) | `operations/capacity-plan/` | 平台內建 | 資源產能規劃 |
| [`/operations:change-request`](./operations/) | `operations/change-request/` | 平台內建 | 建立變更請求與影響分析 |
| [`/operations:compliance-tracking`](./operations/) | `operations/compliance-tracking/` | 平台內建 | 追蹤合規要求與稽核準備 |
| [`/operations:process-doc`](./operations/) | `operations/process-doc/` | 平台內建 | 記錄業務流程（流程圖、RACI、SOP） |
| [`/operations:process-optimization`](./operations/) | `operations/process-optimization/` | 平台內建 | 分析並改善業務流程 |
| [`/operations:risk-assessment`](./operations/) | `operations/risk-assessment/` | 平台內建 | 識別、評估並緩解營運風險 |
| [`/operations:runbook`](./operations/) | `operations/runbook/` | 平台內建 | 建立或更新營運 runbook |
| [`/operations:status-report`](./operations/) | `operations/status-report/` | 平台內建 | 產生含 KPI 與風險的狀態報告 |
| [`/operations:vendor-review`](./operations/) | `operations/vendor-review/` | 平台內建 | 評估供應商 |
| [`/legal:brief`](./legal/) | `legal/brief/` | 平台內建 | （官方未提供說明） |
| [`/legal:compliance-check`](./legal/) | `legal/compliance-check/` | 平台內建 | （官方未提供說明） |
| [`/legal:legal-response`](./legal/) | `legal/legal-response/` | 平台內建 | （官方未提供說明） |
| [`/legal:legal-risk-assessment`](./legal/) | `legal/legal-risk-assessment/` | 平台內建 | （官方未提供說明） |
| [`/legal:meeting-briefing`](./legal/) | `legal/meeting-briefing/` | 平台內建 | （官方未提供說明） |
| [`/legal:review-contract`](./legal/) | `legal/review-contract/` | 平台內建 | （官方未提供說明） |
| [`/legal:signature-request`](./legal/) | `legal/signature-request/` | 平台內建 | （官方未提供說明） |
| [`/legal:triage-nda`](./legal/) | `legal/triage-nda/` | 平台內建 | （官方未提供說明） |
| [`/legal:vendor-check`](./legal/) | `legal/vendor-check/` | 平台內建 | （官方未提供說明） |
| [`/product-management:brainstorm`](./product-management/) | `product-management/brainstorm/` | 平台內建 | 與產品想法進行腦力激盪 |
| [`/product-management:competitive-brief`](./product-management/) | `product-management/competitive-brief/` | 平台內建 | （官方未提供說明） |
| [`/product-management:metrics-review`](./product-management/) | `product-management/metrics-review/` | 平台內建 | （官方未提供說明） |
| [`/product-management:product-brainstorming`](./product-management/) | `product-management/product-brainstorming/` | 平台內建 | （官方未提供說明） |
| [`/product-management:roadmap-update`](./product-management/) | `product-management/roadmap-update/` | 平台內建 | （官方未提供說明） |
| [`/product-management:sprint-planning`](./product-management/) | `product-management/sprint-planning/` | 平台內建 | （官方未提供說明） |
| [`/product-management:stakeholder-update`](./product-management/) | `product-management/stakeholder-update/` | 平台內建 | （官方未提供說明） |
| [`/product-management:synthesize-research`](./product-management/) | `product-management/synthesize-research/` | 平台內建 | （官方未提供說明） |
| [`/product-management:write-spec`](./product-management/) | `product-management/write-spec/` | 平台內建 | （官方未提供說明） |
| [`/bio-research:instrument-data-to-allotrope`](./bio-research/) | `bio-research/instrument-data-to-allotrope/` | 平台內建 | （官方未提供說明） |
| [`/bio-research:nextflow-development`](./bio-research/) | `bio-research/nextflow-development/` | 平台內建 | （官方未提供說明） |
| [`/bio-research:scientific-problem-selection`](./bio-research/) | `bio-research/scientific-problem-selection/` | 平台內建 | （官方未提供說明） |
| [`/bio-research:scvi-tools`](./bio-research/) | `bio-research/scvi-tools/` | 平台內建 | （官方未提供說明） |
| [`/bio-research:single-cell-rna-qc`](./bio-research/) | `bio-research/single-cell-rna-qc/` | 平台內建 | （官方未提供說明） |
| [`/bio-research:start`](./bio-research/) | `bio-research/start/` | 平台內建 | （官方未提供說明） |
| [`/small-business:ad-manager`](./small-business/) | `small-business/ad-manager/` | 平台內建 | 廣告成效分析與優化建議 |
| [`/small-business:ap-processor`](./small-business/) | `small-business/ap-processor/` | 平台內建 | 處理應付帳款帳單與付款批次 |
| [`/small-business:brand-style`](./small-business/) | `small-business/brand-style/` | 平台內建 | 設定品牌樣式與輸出偏好 |
| [`/small-business:build-agent`](./small-business/) | `small-business/build-agent/` | 平台內建 | 把重複性任務轉成可重用 skill |
| [`/small-business:build-connector`](./small-business/) | `small-business/build-connector/` | 平台內建 | 透過 Zapier 連接未支援的工具 |
| [`/small-business:business-pulse`](./small-business/) | `small-business/business-pulse/` | 平台內建 | 一頁式跨部門業務快照 |
| [`/small-business:call-list`](./small-business/) | `small-business/call-list/` | 平台內建 | 建立今日電話清單 |
| [`/small-business:canva-creator`](./small-business/) | `small-business/canva-creator/` | 平台內建 | （官方未提供說明） |
| [`/small-business:cash-flow-snapshot`](./small-business/) | `small-business/cash-flow-snapshot/` | 平台內建 | 30/60/90 天現金流預測 |
| [`/small-business:close-month`](./small-business/) | `small-business/close-month/` | 平台內建 | （官方未提供說明） |
| [`/small-business:content-strategy`](./small-business/) | `small-business/content-strategy/` | 平台內建 | （官方未提供說明） |
| [`/small-business:contract-review`](./small-business/) | `small-business/contract-review/` | 平台內建 | （官方未提供說明） |
| [`/small-business:crm-autopilot`](./small-business/) | `small-business/crm-autopilot/` | 平台內建 | （官方未提供說明） |
| [`/small-business:grant-rfp-writer`](./small-business/) | `small-business/grant-rfp-writer/` | 平台內建 | （官方未提供說明） |
| [`/small-business:grow-pipeline`](./small-business/) | `small-business/grow-pipeline/` | 平台內建 | （官方未提供說明） |
| [`/small-business:growth-pulse`](./small-business/) | `small-business/growth-pulse/` | 平台內建 | （官方未提供說明） |
| [`/small-business:hiring-screener`](./small-business/) | `small-business/hiring-screener/` | 平台內建 | （官方未提供說明） |
| [`/small-business:inbox-manager`](./small-business/) | `small-business/inbox-manager/` | 平台內建 | （官方未提供說明） |
| [`/small-business:inventory-planner`](./small-business/) | `small-business/inventory-planner/` | 平台內建 | （官方未提供說明） |
| [`/small-business:invoice-chase`](./small-business/) | `small-business/invoice-chase/` | 平台內建 | （官方未提供說明） |
| [`/small-business:job-post-builder`](./small-business/) | `small-business/job-post-builder/` | 平台內建 | （官方未提供說明） |
| [`/small-business:lead-finder`](./small-business/) | `small-business/lead-finder/` | 平台內建 | （官方未提供說明） |
| [`/small-business:lead-triage`](./small-business/) | `small-business/lead-triage/` | 平台內建 | （官方未提供說明） |
| [`/small-business:marketing-monday`](./small-business/) | `small-business/marketing-monday/` | 平台內建 | （官方未提供說明） |
| [`/small-business:monday-brief`](./small-business/) | `small-business/monday-brief/` | 平台內建 | （官方未提供說明） |
| [`/small-business:month-end-prep`](./small-business/) | `small-business/month-end-prep/` | 平台內建 | （官方未提供說明） |
| [`/small-business:outreach-composer`](./small-business/) | `small-business/outreach-composer/` | 平台內建 | （官方未提供說明） |
| [`/small-business:pay-the-bills`](./small-business/) | `small-business/pay-the-bills/` | 平台內建 | （官方未提供說明） |
| [`/small-business:payroll-prep`](./small-business/) | `small-business/payroll-prep/` | 平台內建 | （官方未提供說明） |
| [`/small-business:plan-payroll`](./small-business/) | `small-business/plan-payroll/` | 平台內建 | （官方未提供說明） |
| [`/small-business:proposal-builder`](./small-business/) | `small-business/proposal-builder/` | 平台內建 | （官方未提供說明） |
| [`/small-business:reactivate`](./small-business/) | `small-business/reactivate/` | 平台內建 | （官方未提供說明） |
| [`/small-business:report-builder`](./small-business/) | `small-business/report-builder/` | 平台內建 | （官方未提供說明） |
| [`/small-business:report-pack`](./small-business/) | `small-business/report-pack/` | 平台內建 | （官方未提供說明） |
| [`/small-business:restock`](./small-business/) | `small-business/restock/` | 平台內建 | （官方未提供說明） |
| [`/small-business:review-reputation`](./small-business/) | `small-business/review-reputation/` | 平台內建 | （官方未提供說明） |
| [`/small-business:seo-ai-visibility`](./small-business/) | `small-business/seo-ai-visibility/` | 平台內建 | （官方未提供說明） |
| [`/small-business:smb-onboard`](./small-business/) | `small-business/smb-onboard/` | 平台內建 | （官方未提供說明） |
| [`/small-business:smb-router`](./small-business/) | `small-business/smb-router/` | 平台內建 | （官方未提供說明） |
| [`/small-business:social-content-engine`](./small-business/) | `small-business/social-content-engine/` | 平台內建 | （官方未提供說明） |
| [`/small-business:speed-to-lead`](./small-business/) | `small-business/speed-to-lead/` | 平台內建 | （官方未提供說明） |
| [`/small-business:tax-prep`](./small-business/) | `small-business/tax-prep/` | 平台內建 | （官方未提供說明） |
| [`/small-business:tax-season-organizer`](./small-business/) | `small-business/tax-season-organizer/` | 平台內建 | （官方未提供說明） |
| [`/small-business:ticket-deflector`](./small-business/) | `small-business/ticket-deflector/` | 平台內建 | （官方未提供說明） |
| [`/customer-support:customer-escalation`](./customer-support/) | `customer-support/customer-escalation/` | 平台內建 | （官方未提供說明） |
| [`/customer-support:customer-research`](./customer-support/) | `customer-support/customer-research/` | 平台內建 | （官方未提供說明） |
| [`/customer-support:draft-response`](./customer-support/) | `customer-support/draft-response/` | 平台內建 | （官方未提供說明） |
| [`/customer-support:kb-article`](./customer-support/) | `customer-support/kb-article/` | 平台內建 | （官方未提供說明） |
| [`/customer-support:ticket-triage`](./customer-support/) | `customer-support/ticket-triage/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:ai-weekly-digest`](./anthropic-skills/) | `anthropic-skills/ai-weekly-digest/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:algorithmic-art`](./anthropic-skills/) | `anthropic-skills/algorithmic-art/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:brand-guidelines`](./anthropic-skills/) | `anthropic-skills/brand-guidelines/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:built-in-browser`](./anthropic-skills/) | `anthropic-skills/built-in-browser/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:canvas-design`](./anthropic-skills/) | `anthropic-skills/canvas-design/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:chrome-browser`](./anthropic-skills/) | `anthropic-skills/chrome-browser/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:cier-pest-writer`](./anthropic-skills/) | `anthropic-skills/cier-pest-writer/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:cier-policy-article-writer`](./anthropic-skills/) | `anthropic-skills/cier-policy-article-writer/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:computer-use`](./anthropic-skills/) | `anthropic-skills/computer-use/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:copywriter`](./anthropic-skills/) | `anthropic-skills/copywriter/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:daily-news-digest`](./anthropic-skills/) | `anthropic-skills/daily-news-digest/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:deep-research`](./anthropic-skills/) | `anthropic-skills/deep-research/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:doc-coauthoring`](./anthropic-skills/) | `anthropic-skills/doc-coauthoring/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:docs`](./anthropic-skills/) | `anthropic-skills/docs/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:docx`](./anthropic-skills/) | `anthropic-skills/docx/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:dual-review-organizer`](./anthropic-skills/) | `anthropic-skills/dual-review-organizer/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:en-to-zh-translator`](./anthropic-skills/) | `anthropic-skills/en-to-zh-translator/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:fable-mode-thinking`](./anthropic-skills/) | `anthropic-skills/fable-mode-thinking/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:google-workspace`](./anthropic-skills/) | `anthropic-skills/google-workspace/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:humanize-zh-draft`](./anthropic-skills/) | `anthropic-skills/humanize-zh-draft/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:import-memory`](./anthropic-skills/) | `anthropic-skills/import-memory/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:internal-comms`](./anthropic-skills/) | `anthropic-skills/internal-comms/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:learn`](./anthropic-skills/) | `anthropic-skills/learn/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:mcp-builder`](./anthropic-skills/) | `anthropic-skills/mcp-builder/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:meeting-minutes-translator`](./anthropic-skills/) | `anthropic-skills/meeting-minutes-translator/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:morning`](./anthropic-skills/) | `anthropic-skills/morning/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:official-letter-writer`](./anthropic-skills/) | `anthropic-skills/official-letter-writer/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:pdf`](./anthropic-skills/) | `anthropic-skills/pdf/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:pmi-questionnaire-review`](./anthropic-skills/) | `anthropic-skills/pmi-questionnaire-review/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:policy-calc-writer`](./anthropic-skills/) | `anthropic-skills/policy-calc-writer/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:policy-style-writer`](./anthropic-skills/) | `anthropic-skills/policy-style-writer/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:pptx`](./anthropic-skills/) | `anthropic-skills/pptx/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:sdgs-netzero-analyzer`](./anthropic-skills/) | `anthropic-skills/sdgs-netzero-analyzer/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:si-platform-health-check`](./anthropic-skills/) | `anthropic-skills/si-platform-health-check/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:skill-creator`](./anthropic-skills/) | `anthropic-skills/skill-creator/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:slack-gif-creator`](./anthropic-skills/) | `anthropic-skills/slack-gif-creator/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:theme-factory`](./anthropic-skills/) | `anthropic-skills/theme-factory/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:web-artifacts-builder`](./anthropic-skills/) | `anthropic-skills/web-artifacts-builder/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:weekly-news-digest`](./anthropic-skills/) | `anthropic-skills/weekly-news-digest/` | 平台內建 | （官方未提供說明） |
| [`/anthropic-skills:xlsx`](./anthropic-skills/) | `anthropic-skills/xlsx/` | 平台內建 | （官方未提供說明） |
| [`/cier-meeting-minutes`](./general/cier-meeting-minutes/) | `general/cier-meeting-minutes/` | 自訂 | 中經院國際研討會會議記錄產生器（依逐字稿產出會議記錄） |
| [`/diagram-design`](./general/diagram-design/) | `general/diagram-design/` | 自訂 | Create branded architecture, architecture delta, IT current… |
| [`/news-collector`](./general/news-collector/) | `general/news-collector/` | 自訂 | 台商新聞自動蒐集與彙整——使用者提供 Excel 檔案或公司清單，自動搜尋每家公司近兩年財經新聞，詢問輸出目錄，為每家… |
| [`/pdf-to-markdown`](./general/pdf-to-markdown/) | `general/pdf-to-markdown/` | 自訂 | Convert entire PDF documents to clean, structured Markdown … |
| [`/session-start-hook`](./general/) | `general/session-start-hook/` | 平台內建 | 建立 SessionStart hook |
| [`/pdf-viewer:annotate`](./general/) | `general/annotate/` | 平台內建 | 協作標註 PDF |
| [`/pdf-viewer:fill-form`](./general/) | `general/fill-form/` | 平台內建 | 互動填寫 PDF 表單 |
| [`/pdf-viewer:open`](./general/) | `general/open/` | 平台內建 | 開啟 PDF 檢視器 |
| [`/pdf-viewer:sign`](./general/) | `general/sign/` | 平台內建 | 在 PDF 放置簽名 |
| [`/pdf-viewer:view-pdf`](./general/) | `general/view-pdf/` | 平台內建 | 互動式 PDF 檢視器 |
| [`/productivity:memory-management`](./general/) | `general/memory-management/` | 平台內建 | （官方未提供說明） |
| [`/productivity:start`](./general/) | `general/start/` | 平台內建 | （官方未提供說明） |
| [`/productivity:task-management`](./general/) | `general/task-management/` | 平台內建 | 以 TASKS.md 管理任務 |
| [`/productivity:update`](./general/) | `general/update/` | 平台內建 | （官方未提供說明） |
| [`/enterprise-search:digest`](./general/) | `general/digest/` | 平台內建 | （官方未提供說明） |
| [`/enterprise-search:knowledge-synthesis`](./general/) | `general/knowledge-synthesis/` | 平台內建 | （官方未提供說明） |
| [`/enterprise-search:search`](./general/) | `general/search/` | 平台內建 | （官方未提供說明） |
| [`/enterprise-search:search-strategy`](./general/) | `general/search-strategy/` | 平台內建 | （官方未提供說明） |
| [`/enterprise-search:source-management`](./general/) | `general/source-management/` | 平台內建 | （官方未提供說明） |
| [`/cowork-plugin-management:cowork-plugin-customizer`](./general/) | `general/cowork-plugin-customizer/` | 平台內建 | （官方未提供說明） |
| [`/cowork-plugin-management:create-cowork-plugin`](./general/) | `general/create-cowork-plugin/` | 平台內建 | （官方未提供說明） |
| [`/dataviz`](./general/) | `general/dataviz/` | 平台內建 | 建立圖表與資料視覺化的設計指引 |
| [`/artifact-design`](./general/) | `general/artifact-design/` | 平台內建 | Artifact 設計指引 |
| [`/artifact-diagramming`](./general/) | `general/artifact-diagramming/` | 平台內建 | Artifact 圖表繪製指引 |
| [`/artifact-capabilities`](./general/) | `general/artifact-capabilities/` | 平台內建 | Artifact 執行期能力 |
| [`/update-config`](./general/) | `general/update-config/` | 平台內建 | 設定 Claude Code settings.json |
| [`/keybindings-help`](./general/) | `general/keybindings-help/` | 平台內建 | 自訂鍵盤快速鍵 |
| [`/code-review`](./general/) | `general/code-review/` | 平台內建 | 審查 diff 或 PR 的正確性問題 |
| [`/simplify`](./general/) | `general/simplify/` | 平台內建 | 審查並簡化變更的程式碼 |
| [`/fewer-permission-prompts`](./general/) | `general/fewer-permission-prompts/` | 平台內建 | 新增允許清單以減少權限提示 |
| [`/loop`](./general/) | `general/loop/` | 平台內建 | 依間隔重複執行 prompt |
| [`/claude-api`](./general/) | `general/claude-api/` | 平台內建 | Claude API / SDK 參考 |
| [`/workflow-authoring`](./general/) | `general/workflow-authoring/` | 平台內建 | Workflow 腳本撰寫參考 |
| [`/run`](./general/) | `general/run/` | 平台內建 | 啟動並驅動專案 app |
| [`/plugin-authoring`](./general/) | `general/plugin-authoring/` | 平台內建 | 製作 mod（介面或行為變更） |
| [`/init`](./general/) | `general/init/` | 平台內建 | （官方未提供說明） |
| [`/security-review`](./general/) | `general/security-review/` | 平台內建 | （官方未提供說明） |

## 使用方式

在 Claude Code 輸入 `/skill-name` 即可呼叫對應 skill。
