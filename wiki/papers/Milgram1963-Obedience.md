---
title: "Behavioral Study of Obedience"
authors: [Stanley Milgram]
year: 1963
venue: "The Journal of Abnormal and Social Psychology"
doi: "10.1037/h0040525"
url: "https://doi.org/10.1037/h0040525"
pdf_path: "raw/papers/Milgram1963-Obedience.md"
tags:
  - type/paper
  - domain/social-psychology
  - status/ingested
preregistered: false
open_data: false
sample_type: "Community sample (New Haven, CT, non-college adults)"
sample_size: "N = 40"
theories: ["[[Obedience-to-Authority]]", "[[Agentic-State]]"]
paradigms: ["[[Milgram-Obedience-Paradigm]]"]
scales: ["[[14-Point-Pain-Rating-Scale]]"]
---

# [[Milgram1963-Obedience]]

## 📌 一句話核心結論 (Takeaway)
> 在具備合法性威信（Legitimate Authority）的實驗情境下，即便沒有任何實體懲罰威脅，高達 65%（26/40）的成年被試者仍會違背自身道德良知，遵從指令對無辜受害者施加標註為致命危險的 450 Volts 電擊。

---

## 🎯 研究動機與核心假設 (Hypotheses)
- **核心問題**: 面對權威者的破壞性指令（Destructive Command），一般個體在多大程度上會選擇服從（Obedience）而非違抗（Defiance）？二戰納粹大屠殺等殘暴罪行究竟是源於施暴者的特定人格缺陷（Dispositional / Authoritarian Personality），還是強大情境壓力（Situational Pressure）下的普遍心理機制？
- **主要理論假設**: 
  - $H_1$: 當實驗者具備體制認可的權威合法性時，多數個體會抑制「不傷害他人」的道德直覺，遵從權威者的逐步升級指令。
  - $H_2$: 違抗權威會伴隨極為劇烈的內在衝突與自主神經系統張力（Extreme Nervous Tension）。

---

## 🔬 研究設計與方法 (Research Design)
- **自變量 (Independent Variables, IV)**: 
  - 實驗情境中的權威指令與標準化催促語（Standardized Prods，共 4 級遞進催促）。
  - 受害者（Learner）的反饋狀態（於 300V 與 315V 進行捶牆抗議，之後陷入完全沈默）。
- **因變量 (Dependent Variables, DV)**: 
  - **最大電擊電壓值 (Maximum Shock Administered)**：離散指標 $0 \le k \le 30$（對應 0V 至 450V）。
  - **中斷點 (Break-off Point)**：被試者正式拒絕執行實驗者命令時的電壓階段。
  - **完全服從率 (Full Obedience Rate)**：堅持施加電擊至最高檔位 450V 的被試比例。
- **中介變量 / 調節變量 (Mediator / Moderator)**:
  - 心理抗拒與權威義務感（Perceived Obligation to Authority vs. Empathy for Victim）。
- **實驗範式 / 演算法**: [[Milgram-Obedience-Paradigm]]（電擊產生器典範，含 30 個電壓檔位與 4 級階梯式催促）。
- **樣本特徵**: 
  - 樣本數 $N = 40$（均為男性，年齡 20-50 歲，居住於康乃狄克州 New Haven 地區）。
  - 職業構成多元化：勞工（37.5%）、商業白領/銷售（40.0%）、專業人士（22.5%）；教育程度涵蓋未完成小學者至博士學位者。
  - 被試費：\$4.50（僅為到場參與之報酬，明確告知即便中途退出亦無須退還）。
  - 樣本限制：全男性、非跨文化樣本（典型早期 WEIRD 樣本），但避免了僅使用大學心理系學生的偏差。

---

## 📐 數學公式、統計模型與演算法 (Mathematical & Statistical Modeling)
本研究將服從行為嚴格量化為離散等級變量。電擊產生器共有 $K = 30$ 個開關，第 $k$ 級開關之電壓定義為等差數列：
$$
V_k = 15 \times k \quad (\text{for } k \in \{1, 2, \dots, 30\})
$$
其中 $V_1 = 15\text{V}$（Slight Shock），最高等級 $V_{30} = 450\text{V}$（標示為 XXX）。

定義第 $i$ 位被試者之中斷決策指標為其最終施加之最大檔位 $k_i \in \{0, 1, \dots, 30\}$。定義完全服從指標函數（Obedience Indicator Function）：
$$
\mathbb{I}_{\text{obedient}}(i) = 
\begin{cases} 
1, & \text{if } k_i = 30 \ (V_i = 450\text{V}) \\ 
0, & \text{if } k_i < 30 
\end{cases}
$$
樣本完全服從率 $P_{\text{obedient}}$ 與樣本中斷率 $P_{\text{defiant}}$ 計算如下：
$$
P_{\text{obedient}} = \frac{1}{N} \sum_{i=1}^N \mathbb{I}_{\text{obedient}}(i) = \frac{26}{40} = 65.0\%
$$
$$
P_{\text{defiant}} = 1 - P_{\text{obedient}} = \frac{14}{40} = 35.0\%
$$

---

## 📊 實證結果與效應量 (Key Findings & Evidence)

### 1. 預測值與實際服從率的巨大落差 (Prediction vs. Reality Gap)
- **專家與公眾預測**: 14 位 Yale 大學心理學高年級學生預測僅有 $0\% \sim 3\%$（均值 $\mu = 1.2\%$）的被試會施加 450V 電擊；同事專家普遍認為極少人會超過「Very Strong Shock」（240V）。
- **實際行為分佈**:
  - **100%（40/40）** 的被試均突破了 300V（Learner 首次捶牆抗議點）。
  - **65%（26/40）** 的被試完全服從並施加了最高檔位 450V。

### 2. 中斷點分佈表 (Distribution of Break-off Points, Table 2)
| 電壓檔位區間 (Verbal Designation) | 電壓值 (Volts) | 該檔位中斷人數 (Defiant Ss) | 累積中斷人數 | 累積留存率 |
| :--- | :--- | :---: | :---: | :---: |
| Slight Shock | 15 - 60V | 0 | 0 | 100% |
| Moderate Shock | 75 - 120V | 0 | 0 | 100% |
| Strong Shock | 135 - 180V | 0 | 0 | 100% |
| Very Strong Shock | 195 - 240V | 0 | 0 | 100% |
| Intense Shock | 255 - 285V | 0 | 0 | 100% |
| **Intense Shock (Critique Point)** | **300V** | **5** | 5 | 87.5% |
| Extreme Intensity Shock | 315V | 4 | 9 | 77.5% |
| Extreme Intensity Shock | 330V | 2 | 11 | 72.5% |
| Extreme Intensity Shock | 345V | 1 | 12 | 70.0% |
| Extreme Intensity Shock | 360V | 1 | 13 | 67.5% |
| Danger: Severe Shock | 375V | 1 | 14 | 65.0% |
| Danger: Severe Shock | 390 - 420V | 0 | 14 | 65.0% |
| **XXX (Maximum Level)** | **450V** | **26 (完成)** | **14** | **65.0% (完全服從)** |

### 3. 極度緊張與病理反應 (Extreme Tension & Disturbance)
- 被試並非冷血施暴，而是承受巨大的自主神經系統張力：觀察到大量出汗、發抖、口吃、咬唇、呻吟、指甲深陷手掌肉中。
- **神經質笑聲 (Nervous Laughter)**：40 人中有 14 人（35%）出現無法克制的神經質狂笑；其中 3 人出現全身痙攣性抽搐發作（Convulsive Seizure），其中一名 46 歲百科全書推銷員甚至嚴重抽搐致使實驗必須暫停。
- **操弄檢驗**: 在事後訪談中，被試對受害者所承受痛苦的評分（使用 [[14-Point-Pain-Rating-Scale]]）：
  $$
  \text{Mean} = 13.42, \quad \text{Mode} = 14 \quad (\text{"Extremely painful"})
  $$
  證實被試高度確信電擊的真實性與痛苦度。

---

## ⚖️ 局限性與爭議點 (Limitations & Boundary Conditions)
- **研究倫理風暴 (Ethical Controversy)**：
  - 引發了心理學史上最大倫理爭端之一（Baumrind 1964 批判），對被試造成嚴重的暫時性精神創傷（Severe Emotional Distress），促成後續 Institutional Review Board (IRB) 的嚴格審查標準確立。
- **需求特徵與實驗真實性懷疑 (Demand Characteristics)**：
  - 後續學者（如 Orne & Holland 1968）質疑部分被試是否看穿了騙局，懷疑電擊並非真實（Pact of Ignorance）。
- **外部效度與情境特定性**:
  - 實驗在 Yale University 豪華實驗室進行，頂尖學術機構的名望賦予了極高合法性。在非學術背景（如橋港市商業辦公室 Bridgeport condition）中服從率有所下降（48%）。
- **性別與文化限制**:
  - 本篇第一批實驗全為男性，後續研究（Milgram 1974）顯示女性服從率與男性相仿（65%），但報告的衝突痛苦更高。

---

## 🔗 知識網絡關聯 (Relations)
- **奠基於 (Builds Upon)**: 
  - [[Adorno1950-AuthoritarianPersonality]]: 探討威權人格，但 Milgram 指出服從更多是情境產物而非單純人格特質。
  - [[Frank1944-PersonalPressure]]: 早期實驗性個人抗拒研究。
- **衍生核心概念**: 
  - [[Obedience-to-Authority]]: 確立為社會心理學核心主題。
  - [[Agentic-State]]: 個體將自我視為執行他人意圖的工具，進而卸除道德責任。
- **衍生實驗範式**: 
  - [[Milgram-Obedience-Paradigm]]: 電擊產生器與分級催促指令研究法。
- **採用之測量工具**: 
  - [[14-Point-Pain-Rating-Scale]]: 評估被試對受害人受創程度的主觀認知。
