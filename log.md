# Wiki Maintenance Log

本文件為純追加（Append-Only）的操作流水帳，記錄所有文獻 Ingest、Query 沉澱及 Lint 維護事件。

---

## [2026-11-22] init | 初始化社會心理學 LLM Wiki 知識庫架構與 AGENTS.md
## [2026-11-22] ingest | [[Milgram1963-Obedience]] - Behavioral Study of Obedience
- 建立論文精讀筆記: `wiki/papers/Milgram1963-Obedience.md`
- 保存原始文本: `raw/papers/Milgram1963-Obedience.md`
- 建立/更新概念頁面: `[[Obedience-to-Authority]]`, `[[Agentic-State]]`
- 建立範式頁面: `[[Milgram-Obedience-Paradigm]]`
- 建立量表頁面: `[[14-Point-Pain-Rating-Scale]]`
- 更新總目錄: `index.md`

## [2026-11-22] ingest | [[Franzen2023-AschReplication]] - The power of social influence: A replication and extension of the Asch experiment
- 建立論文精讀筆記: `wiki/papers/Franzen2023-AschReplication.md`
- 保存原始文本: `raw/papers/Franzen2023-AschReplication.md`
- 建立/更新概念頁面: `[[Conformity]]`, 更新 `[[Obedience-to-Authority]]`（建立水平從眾與垂直服從交叉對比）
- 建立範式頁面: `[[Asch-Line-Judgment-Paradigm]]`
- 建立量表頁面: `[[BFI-10]]`, `[[Rosenberg-Self-Esteem-Scale]]`
- 更新總目錄: `index.md`

## [2026-11-22] ingest | [[Darley1968-BystanderIntervention]] - Bystander Intervention in Emergencies: Diffusion of Responsibility
- 建立論文精讀筆記: `wiki/papers/Darley1968-BystanderIntervention.md`
- 保存原始文本: `raw/papers/Darley1968-BystanderIntervention.md`
- 建立/更新概念頁面: `[[Bystander-Effect]]`, `[[Diffusion-of-Responsibility]]`（串聯情境論對特質論之取代）
- 建立範式頁面: `[[Intercom-Emergency-Seizure-Paradigm]]`
- 更新總目錄: `index.md`

## [2026-11-22] query | 社會心理學在實際生活上的運用問題
- 建立橫向專題綜述: `wiki/syntheses/Social-Psychology-Real-World-Applications.md`
- 產出全螢幕簡報投影片: `presentations/Social-Psychology-Real-World-Applications.html`
- 綜合橫向比對: [[Milgram1963-Obedience]], [[Franzen2023-AschReplication]], [[Darley1968-BystanderIntervention]]
- 更新總目錄: `index.md`

## [2026-11-22] update | 擴展簡報投影片至 12 頁（藍白典雅風 + SVG 向量圖解）
- 更新投影片: `presentations/Social-Psychology-Real-World-Applications.html`
- 風格調整: 深海藍 (#0f2b5c) 配象牙白典雅學術風，精緻襯線標題與卡片微陰影
- 原生 SVG 繪製: Lewin 場論模型、Milgram 30 開關面板與催促階梯、Asch 線段與激勵柱狀圖、旁觀者衰減曲線圖
- 深度學術批判型 12 頁架構落實，每頁右下角固定獨立頁碼標記（01/12 至 12/12）

## [2026-11-22] complete | 全域圖譜導航模式 12 頁學術簡報正式交付
- 檔案路徑: `presentations/Social-Psychology-Real-World-Applications.html`
- 架構實現: 左側動態全域圖譜雷達 (Global Graph Radar) + 右側深度學術內容與專屬局部 SVG 圖解
- 拓撲鏈路: 「理論 ➔ 機制/批判 ➔ 現實危機 ➔ 制度防線」12 節點全貫通，無孤島節點
- 典雅藍白風: 深海藍 (#0f2b5c) + 象牙白 + 經典襯線標題 + 右下角固定獨立頁碼標記（01/12 至 12/12）

## [2026-11-22] ingest | [[Haney1973-StanfordPrison]] - A Study of Prisoners and Guards in a Simulated Prison
- 建立論文精讀筆記: `wiki/papers/Haney1973-StanfordPrison.md`
- 保存原始文本: `raw/papers/Haney1973-StanfordPrison.md`
- 建立概念與範式頁面: `[[Deindividuation]]`, `[[Stanford-Prison-Paradigm]]`
- 更新總目錄: `index.md`

## [2026-11-22] ingest | [[Festinger1959-CognitiveDissonance]] - Cognitive Consequences of Forced Compliance
- 建立論文精讀筆記: `wiki/papers/Festinger1959-CognitiveDissonance.md`
- 保存原始文本: `raw/papers/Festinger1959-CognitiveDissonance.md`
- 建立概念與範式頁面: `[[Cognitive-Dissonance]]`, `[[Induced-Compliance-Paradigm]]`
- 更新總目錄: `index.md`

## [2026-11-22] ingest-deep-verify | [[Festinger1959-CognitiveDissonance]] - 深度精準提取完成
- 來源: 使用者上傳之 13 頁原始論文 PDF 全文
- 提取要點: 71 名被試與 11 名特定原因剔除明細、Table 1 四大訪談題評分全數據、Table 2 錄音評判數據、失調公式 $f(D/(D+C))$
- 徹底反駁 Janis & King 心理預演替代解釋，理論鏈接至 Milgram 遞進承諾機制

## [2026-11-22] ingest | [[Baumeister1995-NeedToBelong]] - The Need to Belong: Desire for Interpersonal Attachments as a Fundamental Human Motivation
- 建立論文精讀筆記: `wiki/papers/Baumeister1995-NeedToBelong.md`
- 保存原始文本: `raw/papers/Baumeister1995-NeedToBelong.md`
- 建立核心動機概念: `[[Need-to-Belong]]`
- 理論深度穿針引線: 將從眾盲從、服從殘虐與旁觀冷漠的底層動力連結至「排斥恐懼（Ostracism）」
- 更新總目錄: `index.md`

## [2026-11-22] complete | 16 頁全域圖譜互動式簡報 (DAG Workflow) 正式交付
- 檔案路徑: `presentations/Social-Psychology-Real-World-Applications.html`
- 完整涵蓋 6 篇已 Ingest 論文（Milgram 1963, Franzen 2023, Darley 1968, Festinger 1959, Baumeister 1995, Haney 1973）
- 16 節點 DAG 嚴密閉環拓撲（Meta ➔ Theories ➔ Critiques ➔ Real Crises ➔ Interventions ➔ Epilogue）
- 左側 Global Graph Navigation Radar 動態即時高亮當前節點與拓撲邊，右側 16 組高精度原生 SVG 向量圖解
- 右下角固定獨立頁碼標記（`01 / 16` 至 `16 / 16`）
- 同步更新橫向專題綜述: `wiki/syntheses/Social-Psychology-Real-World-Applications.md`
- 產出完整課程作業繳交報告文檔，涵蓋主題介紹、Wiki 成果、簡報連結、Loop/Graph 設計與反思答辯
