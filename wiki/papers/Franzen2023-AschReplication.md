---
title: "The power of social influence: A replication and extension of the Asch experiment"
authors: [Axel Franzen, Sebastian Mader]
year: 2023
venue: "PLOS ONE"
doi: "10.1371/journal.pone.0294325"
url: "https://doi.org/10.1371/journal.pone.0294325"
pdf_path: "raw/papers/Franzen2023-AschReplication.md"
tags:
  - type/paper
  - domain/social-psychology
  - status/ingested
preregistered: false
open_data: true
sample_type: "University students (University of Bern, Switzerland)"
sample_size: "N = 210 (Valid N = 202)"
theories: ["[[Conformity]]", "[[Obedience-to-Authority]]"]
paradigms: ["[[Asch-Line-Judgment-Paradigm]]"]
scales: ["[[BFI-10]]", "[[Rosenberg-Self-Esteem-Scale]]"]
---

# [[Franzen2023-AschReplication]]

## 📌 一句話核心結論 (Takeaway)
> 本研究成功在當代歐洲樣本中高度重現了 Asch (1955) 的經典從眾效應（錯誤率達 33%）；雖然金錢激勵（Monetary Incentives）能將錯誤率顯著壓低 8 個百分點至 25%，但無法消除群體壓力；且該從眾效應可直接泛化至政治態度（引發高達 38 個百分點的意見轉變），而在人格特質中僅「經驗開放性（Openness）」能顯著抵抗從眾。

---

## 🎯 研究動機與核心假設 (Hypotheses)
- **核心問題**:
  1. 經典 Asch 從眾效應是否具有跨時代與跨文化普遍性？在受過現代高等教育的瑞士大學生中是否依然穩固？
  2. 心理學實驗缺乏物質代價，若引入經濟學的**金錢激勵（Monetary Incentives）**，個體是否會因「追求正確答案有實質報酬」而擺脫群體壓力？
  3. 群體壓力能否從客觀客觀感知任務（線段長度）跨越並泛化至高度主觀的**政治立場與態度（Political Opinions）**？
  4. 哪些人格特質（Big Five、自尊、智力、社會認同需求）能預測個體對從眾壓力的抵抗力？
- **主要理論假設**: 
  - $H_1$ (Replication): 在標準線段判斷任務中將觀察到顯著的群體從眾率（預期錯誤率約 30% 左右）。
  - $H_2$ (Incentive Effect): 對正確回答給予金錢獎勵將顯著降低錯誤從眾率。
  - $H_3$ (Political Generalization): 群體多數意見將顯著影響個體的政治態度表達。
  - $H_4 - H_7$ (Individual Differences): 社會認同需求正向預測從眾（$H_4$），智力（$H_5$）、自尊（$H_6$）與開放性（$H_7$）負向預測從眾。

---

## 🔬 研究設計與方法 (Research Design)
- **自變量 (Independent Variables, IV)**: 
  - **群體錯誤多數反饋**: 5 名同謀（Confederates）一致公開給予錯誤答案（Critical Trials）。
  - **物質激勵操弄 (Incentive Condition)**: 
    - 無激勵組（Non-incentivized）：基本出席費 20 瑞士法郎（CHF）。
    - 激勵組（Incentivized）：20 CHF 出席費 + 每答對一題線段任務額外獲得 1 CHF（最高可獲 30 CHF）。
  - **政治立場群體多數操弄**: 同謀一致回答 "Yes" 或 "No"（隨機反轉順序）。
- **因變量 (Dependent Variables, DV)**: 
  - **線段任務錯誤率 (Error Rate / Conforming Answers)**：在 6 次關鍵試次中的錯誤次數（$0 \le Y \le 6$）。
  - **政治問題贊同率 (Proportion of 'Yes' Answers)**：5 題政治主張的同意比例。
- **實驗範式 / 演算法**: [[Asch-Line-Judgment-Paradigm]] 擴展版（含金錢激勵組與政治意見評估）。
- **樣本特徵**: 
  - 招募自瑞士伯恩大學（University of Bern）學生，總計 $N = 210$（女性佔 61%，平均年齡 22.6 歲）。
  - 嚴格數據清洗：排除 4 名注意力檢驗未通過者、3 名察覺同謀或猜中 Asch 實驗者、1 名性別填寫 Other 者，最終有效樣本 $N = 202$（男性 78 人，女性 124 人）。
  - 事先統計檢定力分析（Power Analysis）：設定 $\alpha = 0.05$, Power $= 0.8$，檢驗 5 個百分點差異需每組約 100 人。

---

## 📐 數學公式、統計模型與演算法 (Mathematical & Statistical Modeling)

### 1. 線段任務錯誤次數多元迴歸模型 (OLS & Count Models)
將 6 次關鍵試次中被試跟隨同謀給出錯誤答案的次數 $Y_i \in \{0, 1, \dots, 6\}$ 作為因變量，建立普通最小平方法（OLS）模型：
$$
Y_i = \beta_0 + \beta_1 \text{Incentive}_i + \beta_2 \text{Female}_i + \sum_{k=1}^5 \gamma_k \text{BigFive}_{ki} + \beta_3 \text{IQ}_i + \beta_4 \text{SelfEsteem}_i + \beta_5 \text{Approval}_i + \epsilon_i
$$
*(研究亦採用 Poisson Regression 與 Negative Binomial Regression 進行穩健性檢驗，係數方向與顯著性完全一致)*。

### 2. 政治態度轉變差異量化
針對第 $j$ 個政治題目，定義同謀回答 "Yes" 組與同謀回答 "No" 組之被試贊同率差值：
$$
\Delta P_j = P(\text{Subject Yes} \mid \text{Group Yes}) - P(\text{Subject Yes} \mid \text{Group No})
$$

---

## 📊 實證結果與效應量 (Key Findings & Evidence)

### 1. Asch 經典效應的高精度重現 ($H_1$)
- 在**無金錢激勵組**中，被試在 6 次關鍵試次的平均錯誤率為 **33.0%**（平均錯誤數 1.97 題）。
- 與 Asch (1955) 原始研究之 36.8% 相比，無顯著差異（兩獨立樣本雙尾 T 檢定：$t(16) = 0.59, p = 0.57$），證實跨越近 70 年後從眾壓力依然極為穩固。

### 2. 金錢激勵對從眾的抑制作用 ($H_2$)
- 在**金錢激勵組**中，平均錯誤率顯著下降至 **25.0%**（平均錯誤數降至 1.47 題）。
- 激勵使錯誤數平均減少 0.5 題（雙尾 T 檢定：$t(208) = 2.24, p = 0.03$，整體錯誤率降低 8 個百分點）。
- **關鍵洞察**：物質誘因確實顯著提高了回答精確度，但**即便有金錢獎勵，依然有高達 25% 的錯誤從眾率**，否定了「從眾純粹是因實驗無成本所致的假象」的質疑。

### 3. 政治意見上的強大從眾轉移 ($H_3$)
當同謀一致表達特定政治立場時，被試意見產生劇烈偏移（5 道題目之雙尾檢定均達 $p < 0.001$）：
| 政治議題 (Political Issue) | 同謀回答 "No" 時被試贊同率 | 同謀回答 "Yes" 時被試贊同率 | 差值 ($\Delta P$) | 統計顯著性 |
| :--- | :---: | :---: | :---: | :---: |
| 1. 瑞士聯邦政府擴權 | 3% | 27% | **+23.4%** | $p < .001$ |
| 2. 瑞士工會組織擴權 | 29% | 72% | **+42.7%** | $p < .001$ |
| 3. 雇主協會擴權 | 6% | 44% | **+37.7%** | $p < .001$ |
| 4. 給予公民更多自由權利 | 33% | 81% | **+47.6%** | $p < .001$ |
| 5. 給予瑞士企業更多自由 | 8% | 46% | **+38.0%** | $p < .001$ |
- 政治意見平均轉變幅度高達 **38.0 個百分點**，證實群體規範壓力在高度主觀的民主政治議題上同樣極具穿透力。

### 4. 個體差異與人格特質預測力 ($H_4 - H_7$)
- **Big Five**: 僅**經驗開放性（Openness）**顯著負向預測從眾次數（$\beta = -0.30, p < 0.05$）；外向性、宜人性、嚴謹性與神經質均未達顯著標準。
- **性別與社會認同交互作用**: 
  - 女性整體呈現稍微偏高的從眾傾向（$p < 0.10$）。
  - 對女性樣本而言，社會認同需求（MLAM 量表）顯著正向預測從眾次數（$\chi^2(1) = 4.23, p = 0.04$），但對男性無效。
  - 對男性樣本而言，智力（HMT 矩陣測驗）每多答對一題，從眾錯誤減少 0.27 題（但在性別交互檢定中未達顯著差異）。
  - 自尊（Rosenberg Scale）與從眾無統計顯著關聯。

---

## ⚖️ 局限性與爭議點 (Limitations & Boundary Conditions)
- **激勵額度上限**: 每題正確僅獎勵 1 CHF（總額最高 30 CHF），屬於小額激勵。若提高激勵金額至更高數量級，是否能進一步壓縮甚至消除從眾效應，尚待檢驗。
- **陌生人群體 vs. 熟人團體**: 實驗中的同謀為完全陌生的同學；真實政治與社會生活中的從眾多發生於熟人圈、政黨或同溫層內部，壓力可能遠高於陌生人實驗情境。
- **政治題目的中立性**: 本研究挑選的政治問題相對溫和抽象；若遭遇涉及強烈道德邊界或深層身分認同（Identity-relevant）的極端議題，個體從眾韌性可能有所不同。
- **量表簡化偏差**: 採用 BFI-10 短量表可能引入測量誤差（Measurement Error），降低偵測其餘人格維度微弱效應的統計檢定力。

---

## 🔗 知識網絡關聯 (Relations)
- **奠基於 (Builds Upon)**: 
  - [[Asch-Line-Judgment-Paradigm]]: 繼承經典視覺線段長度判斷範式。
  - [[Milgram1963-Obedience]]: 共同構成社會影響力（Social Influence）兩大支柱（Milgram 探討垂直權威服從，Asch/Franzen 探討水平同儕從眾）。
- **衍生核心概念**: 
  - [[Conformity]]: 拓展了從眾的邊界條件（激勵抗性、政治態度泛化）。
- **採用之測量工具**: 
  - [[BFI-10]]: 測量五大人格特質。
  - [[Rosenberg-Self-Esteem-Scale]]: 評估自我評價與自尊強度。
