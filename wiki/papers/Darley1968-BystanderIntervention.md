---
title: "Bystander Intervention in Emergencies: Diffusion of Responsibility"
authors: [John M. Darley, Bibb Latané]
year: 1968
venue: "Journal of Personality and Social Psychology"
doi: "10.1037/h0025589"
url: "https://doi.org/10.1037/h0025589"
pdf_path: "raw/papers/Darley1968-BystanderIntervention.md"
tags:
  - type/paper
  - domain/social-psychology
  - status/ingested
preregistered: false
open_data: false
sample_type: "University students (New York University, psychology pool)"
sample_size: "N = 72 (Valid N = 70: 59 females, 13 males)"
theories: ["[[Bystander-Effect]]", "[[Diffusion-of-Responsibility]]", "[[Conformity]]"]
paradigms: ["[[Intercom-Emergency-Seizure-Paradigm]]"]
scales: []
---

# [[Darley1968-BystanderIntervention]]

## 📌 一句話核心結論 (Takeaway)
> 當突發急難發生時，旁觀者人數的增加會顯著抑制個體的助人意願並大幅延遲通報速度（單獨在場時 85% 立即通報，4 名他人在場時暴跌至 31%）；這種不作為並非源於大眾所詬病的「冷漠（Apathy）」或人格缺陷，而是源於群體情境下個體心理對責任的嚴重稀釋——**責任分散 (Diffusion of Responsibility)**。

---

## 🎯 研究動機與核心假設 (Hypotheses)
- **核心歷史契機**: 1964 年紐約 Kitty Genovese 兇殺案。據《紐約時報》報導，至少 38 名鄰里目擊者在窗前目睹慘劇長達半小時卻無一人施救或報警。大眾輿論與學界普遍歸咎於「都市冷漠（Urban Apathy）」、「道德淪喪（Moral Decay）」與「異化（Alienation）」。
- **研究核心問題**: 旁觀者的不作為究竟是源於人格缺陷，還是特定社會情境結構的產物？
- **主要理論假設**: 
  - $H_1$ (Diffusion of Responsibility): 在無人可直接溝通的急難情境中，個體感知的其他旁觀者數量越多，其承擔救助義務的個人責任感越低，實施助人行為的機率越小、反應速度越慢。
  - $H_2$ (Personality Invariance): 傳統人格特質變量（如疏離感、馬基雅維利主義、威權人格、社會責任感）無法有效預測急難情境中的助人速度。

---

## 🔬 研究設計與方法 (Research Design)
- **自變量 (Independent Variables, IV)**: 
  - **感知群體規模 (Perceived Group Size)**：透過預錄錄音帶操控被試所感知的總討論人數：
    1. **2 人組**：被試 + 癲癇發作者（受害者）。
    2. **3 人組**：被試 + 受害者 + 1 名虛擬旁觀者（操控性別：女性、男性、或具急診經驗之醫學生）。
    3. **6 人組**：被試 + 受害者 + 4 名虛擬旁觀者。
  - **旁觀者性別與專業特徵**（在 3 人組中進行跨組變異）。
  - **被試自身性別**（男 vs. 女）。
- **因變量 (Dependent Variables, DV)**: 
  - **通報反應時間 (Response Time in Seconds)**：從受害者癲癇發作開始，至被試走出獨立隔間向走廊助理報告的經過秒數（上限截斷為 6 分鐘 / 360 秒）。
  - **發作期間通報率 (% Responding by End of Fit)**：在受害者麥克風被切斷前（125 秒內）採取行動的比例。
  - **總求助比例 (Overall % Helping)**：在 6 分鐘內最終是否通報求助。
- **實驗範式 / 演算法**: [[Intercom-Emergency-Seizure-Paradigm]]（隔間內線對講機急難範式，嚴格阻斷被試間的雙向即時溝通，徹底隔離純粹的責任分散效應）。
- **樣本特徵**: 
  - 紐約大學（NYU）心理學導論課程學生，共 72 名（59 名女性，13 名男性）；2 人因懷疑裝置為偽造而被剔除，有效樣本為 $N = 70$。

---

## 📐 數學公式、統計模型與演算法 (Mathematical & Statistical Modeling)

### 1. 反應速度分數變換 (Speed Score Transformation)
為降低極端長反應時間（特別是 360 秒截斷值）對方差分析的扭曲，將原始反應秒數 $T_i$ 轉換為倒數速度分數（Speed Score）：
$$
\text{Speed Score}_i = \frac{100}{T_i}
$$
其中反應越迅速，數值越高；未採取行動者數值趨近於 $0$。

### 2. 受害者獲得至少一人救助之群體累積機率模型 (Probability of Group Intervention)
若群體由 $n$ 名彼此獨立、無法溝通的旁觀者組成，且每位個體在時間 $t$ 內單獨提供救助的機率為 $P(t)$，則受害者在時間 $t$ 內獲得**至少一名旁觀者**救助的整體機率 $P_{\ge 1}(t)$ 計算為：
$$
P_{\ge 1}(t) = 1 - \left[1 - P(t)\right]^n
$$
*實證計算顯示*：在發作最初的 45 秒內，單獨一人在場時受害者獲得救助的機率約為 **$50\%$**；而在 5 名旁觀者在場條件下，受害者獲得救助的機率反而趨近於 **$0\%$**。這證實了個體層面的責任分散抑制效應，徹底壓過了人數增加帶來的潛在救助冗餘優勢。

---

## 📊 實證結果與效應量 (Key Findings & Evidence)

### 1. 群體規模對救助意願與速度的壓制 (Table 1 核心數據)
| 感知群體規模 (Perceived Group Size) | 樣本數 $N$ | 發作切斷前通報率 (125s 內) | 最終總求助率 (360s 內) | 平均反應時間 (秒) | 速度分數 (Speed Score) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **2 人組 (被試 + 受害者)** | 13 | **85%** | **100%** | **52 秒** | **0.87** |
| **3 人組 (被試 + 受害者 + 1 人)** | 26 | **62%** | **85%** | **93 秒** | **0.72** |
| **6 人組 (被試 + 受害者 + 4 人)** | 13 | **31%** | **62%** | **166 秒** | **0.51** |

- **統計顯著性**:
  - 救助意願比例差異：卡方檢定 $\chi^2(2) = 7.91, p < .02$。
  - 速度分數差異：單因子變異數分析 $F(2, 49) = 8.09, p < .01$。
  - Duncan 多重範圍檢定顯示，2 人組與 3 人組均顯著快於 6 人組（$p < .05$）。

### 2. 旁觀者特質與被試性別的無效性 (Group Composition & Gender)
- **他人性別與專業身分**: 在 3 人組中，無論另一名旁觀者是女性（通報率 62%）、男性（通報率 62%）還是聲稱在 Bellevue 醫院急診室工作的男醫學生（通報率 100%, $N=5$），反應速度與通報比例均未呈現統計顯著差異。
- **被試自身性別**: 男性被試通報率（69%）與女性被試（62%）無顯著差異，反應秒數亦然（110s vs. 92-94s），否定了「男性在急難中必然表現出更高行動力」的刻板假定。

### 3. 個體特質與人格量表的微弱相關
- 測量了馬基雅維利主義（Machiavellianism）、疏離感/失範量表（Anomie）、威權人格（Authoritarianism）、社會期望（Crowne-Marlowe）、社會責任感量表（Social Responsibility Scale）等 16 項指標。
- **結論**: **無一項人格測量指標能顯著預測求助速度**；唯一達統計顯著的微弱關聯是「成長社區規模」（$r = -.26, p < .05$，即來自較大城市的被試反應稍微偏慢）。

### 4. 未行動被試的心理衝突：並非「冷漠」，而是「雙重趨避衝突」
- 錄音與觀察證實，未採取行動的被試呈現極度焦慮與自主神經激活（雙手顫抖、手心冒汗、頻頻詢問「他還好嗎？」）。
- 其心理處於典型的**趨避-趨避衝突 (Avoidance-Avoidance Conflict)**：一方面面臨未提供救助的內疚感與道德羞恥，另一方面害怕過度反應出醜（Making a fool of oneself）、破壞實驗規則或違反匿名協議。

---

## ⚖️ 局限性與爭議點 (Limitations & Boundary Conditions)
- **歷史案例的事實修正 (The Kitty Genovese Myth)**：
  - 後續歷史與法醫檔案考證（Manning, Levine, & Collins, 2007）揭露《紐約時報》當初的報導存在嚴重誇大：實際並非 38 人全程袖手旁觀，部分目擊者曾報警或呼喊喝退兇手。雖然 Genovese 案件的真實細節被媒體扭曲，但 Darley & Latané 在實驗室所發現的「責任分散效應」在科學上是極為穩固且可重複的。
- **物理隔離 vs. 面對面互動**:
  - 本實驗採用獨立隔間與耳機，被試之間無法眼神交流或口頭交談。這嚴格**分離出了責任分散（Diffusion of Responsibility）**，但排除了另外兩項旁觀者效應機制：**多元無知（Pluralistic Ignorance）**與**評價顧慮（Evaluation Apprehension）**。
- **直接介入 vs. 間接通報**:
  - 本研究測量的是向實驗助理「報告（Reportorial Intervention）」，非直接衝入現場實施心肺復甦等高體能、高風險的「直接介入（Direct Intervention）」。

---

## 🔗 知識網絡關聯 (Relations)
- **奠基於 (Builds Upon)**: 
  - [[Milgram1963-Obedience]]: Milgram & Hollander (1964) 針對 Genovese 案撰寫評論，啟發了情境論取代特質論的研究取向。
  - 挑戰了社會學中的「冷漠與都市失範假說 (Apathy & Anomie Hypothesis)」。
- **衍生核心概念**: 
  - [[Bystander-Effect]]: 旁觀者人數抑制救助行為的總效應。
  - [[Diffusion-of-Responsibility]]: 旁觀者效應的三大子機制之首。
- **衍生實驗範式**: 
  - [[Intercom-Emergency-Seizure-Paradigm]]: 透過錄音隔間標準化模擬突發危機的實驗範式。
