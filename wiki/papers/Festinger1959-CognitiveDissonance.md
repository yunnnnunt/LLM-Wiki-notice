---
title: "Cognitive Consequences of Forced Compliance"
authors: [Leon Festinger, James M. Carlsmith]
year: 1959
venue: "The Journal of Abnormal and Social Psychology"
doi: "10.1037/h0041593"
url: "https://doi.org/10.1037/h0041593"
pdf_path: "raw/papers/Festinger1959-CognitiveDissonance.md"
tags:
  - type/paper
  - domain/social-psychology
  - status/ingested
preregistered: false
open_data: false
sample_type: "Male college students (Stanford University introductory psychology)"
sample_size: "N = 71 (Valid N = 60: 20 Control, 20 One Dollar, 20 Twenty Dollars)"
theories: ["[[Cognitive-Dissonance]]", "[[Self-Persuasion]]", "[[Obedience-to-Authority]]"]
paradigms: ["[[Induced-Compliance-Paradigm]]"]
scales: []
---

# [[Festinger1959-CognitiveDissonance]]

## 📌 一句話核心結論 (Takeaway)
> 當個體被迫做出與內心信念相悖的外在行為時，若外在酬賞極微薄（僅得 \$1，不足以合理化行為），個體會產生強烈的**認知失調（Cognitive Dissonance）**，並透過「自我說服（Self-Persuasion）」主動反轉內在態度（真正相信枯燥的任務極為有趣，評分由 $-0.45$ 飆升至 $+1.35$）；反之，獲得豐厚酬賞者（\$20）因外部理由充足，內在態度毫不改變（$-0.05$）。

---

## 🎯 研究動機與核心假設 (Hypotheses)
- **核心爭議**:
  - 行為主義（Behaviorism / Reinforcement Theory）與傳統經濟激勵假說主張：酬賞越大，制約強化的效果越好，態度轉變應越大（Kelman, 1953）。
  - Janis & King (1954; 1956) 主張說服源於「心理預演與即興發揮（Mental Rehearsal）」。
  - Festinger (1957) 則提出逆向預測：誘發順從的外在壓力越小（只要剛好跨過行為門檻），個體越無法用外在藉口自我辯護，內在認知失調越大，引發的私下態度改變越大。
- **主要理論假設**: 
  - $H_1$: 用於誘發外在違心言行的酬賞或壓力越大（超越誘發行為所需的最低門檻），後續的真實私人意見改變反而越小。
  - $H_2$: 僅在與失調內容直接相關的構念上（任務趣味性）會出現態度改變，非相關構念（任務學習程度）不產生變異。

---

## 🔬 研究設計與方法 (Research Design)
- **自變量 (Independent Variables, IV)**: 
  - **誘發順從的酬賞金額（Amount of Reward）**：
    1. **控制組 (Control, $n=20$)**：完成枯燥任務後直接受訪，不要求對外說謊。
    2. **\$1 組 (One Dollar Condition, $n=20$)**：由主試者誠懇懇求，支付 \$1（簽署收據）並聘請其向等候的下一位女受試者說謊，宣稱任務極為有趣。
    3. **\$20 組 (Twenty Dollars Condition, $n=20$)**：相同說謊要求，但支付高達 \$20 豐厚報酬（在 1959 年相當於高額誘因）。
- **因變量 (Dependent Variables, DV)**: 
  - 獨立訪談員（盲法評估，完全不知被試組別）在 4 道題目上的評分（11 點等距量尺）。
- **實驗範式**: [[Induced-Compliance-Paradigm]]（誘發順從範式 / 1 小時單手裝線軸與旋轉木栓任務）。
- **樣本特徵與排除標準**:
  - 史丹佛大學大一心理學男性學生 71 名。
  - 嚴格數據剔除（共 11 人被排除，留存 $N = 60$ 分析）：
    1. 5 人（\$1 組 3 人，\$20 組 2 人）在訪談中識破實驗，懷疑付錢是為了測試說謊；
    2. 2 人（均為 \$1 組）向女同謀坦白自己收錢說謊，實際很無聊；
    3. 3 人（\$1 組 1 人，\$20 組 2 人）拒絕收錢並拒絕受聘說謊；
    4. 1 人（\$1 組）向女同謀要電話企圖事後解釋真相。

---

## 📐 數學公式、統計模型與演算法 (Mathematical & Statistical Modeling)
Festinger 在文中將失調總量量化為失調認知與和諧認知的函數比例：
$$
\text{Total Magnitude of Dissonance} = f\left(\frac{D}{D + C}\right)
$$
其中：
- $D$（Sum of Dissonances）：與違心言論相衝突的認知總和（即「我知道這個任務極度無聊且機械化」）。
- $C$（Sum of Consonances）：支持該違心言論的理由總和（即「我獲得的外部報酬或懲罰威脅」）。

### 邊界極值推導：
1. 當外部報酬僅**「勉強足以（Just Barely Sufficient）」**誘發順從時（\$1 條件），$C \to \epsilon$，失調比例接近最大值：
   $$
   \lim_{C \to \text{min}} \frac{D}{D + C} \approx 1 \implies \text{Maximal Dissonance} \implies \text{最大內在態度轉變}
   $$
2. 當外部報酬極大時（\$20 條件），$C$ 遠大於 $D$，失調比例趨近於零：
   $$
   \frac{D}{D + C} \approx 0 \implies \text{Minimal Dissonance} \implies \text{無需改變內在態度}
   $$

---

## 📊 實證結果與效應量 (Key Findings & Evidence)

### 1. 訪談問題平均評分表 (Table 1 核心實證數據)
| 訪談評估問題 (Interview Questions) | 量表區間 | 控制組 (Control, $n=20$) | \$1 組 ($n=20$) | \$20 組 ($n=20$) | 統計檢定 (雙尾 T 檢定) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Q1. 任務是否有趣、享受？ (How enjoyable tasks were)** | **-5 到 +5** | **-0.45** | **+1.35** | **-0.05** | \$1 vs. 控制組: $t = 2.48, p = .02$<br>\$1 vs. \$20: $t = 2.22, p = .03$ |
| Q2. 從實驗中學到多少？ (How much they learned) | 0 到 10 | 3.08 | 2.80 | 3.15 | 無顯著差異 (最高 $t = 0.48, \text{n.s.}$) |
| Q3. 實驗的科學重要性 (Scientific importance) | 0 到 10 | 5.60 | 6.45 | 5.18 | \$1 vs. \$20: $t = 1.79, p = .08$ |
| Q4. 未來再次參與意願 (Participate in similar exp.) | -5 到 +5 | -0.62 | +1.20 | -0.25 | \$1 vs. 控制組: $t = 1.78, p = .08$ |

### 2. 徹底推翻 Janis & King 的「即興排練替代假說」
- 為了排除「\$1 組被試是否因為更努力即興發揮說服女同學，才說服了自己」的疑慮，研究者對所有說謊過程錄音進行隱蔽雙盲評分（信度 $r = .61 \sim .88$，Table 2）。
- 結果顯示：**\$20 組被試在說謊內容說服力（5.50 vs. 4.79）與投入時間（8.19 vs. 6.74）上均略高於 \$1 組**。這決定性地證實：\$1 組的態度反轉**絕非即興表演技巧所致，而是純粹源於認知失調的心理張力化解**！

---

## ⚖️ 局限性與爭議點 (Limitations & Boundary Conditions)
- **自我知覺理論（Self-Perception Theory）的挑戰**：
  - Daryl Bem (1967) 提出激進替代解釋：個體根本不需要經歷「心理痛苦與張力」，而是像局外觀察者一樣進行歸因推理——「既然我為了區區 \$1 做了這件事，那我想我可能真的覺得它挺有趣的」。
- **自由選擇與個人責任（Perceived Choice & Responsibility）**：
  - 後續研究（Cooper & Fazio, 1984）指出，認知失調的觸發必須具備「自由選擇感（Perceived Free Will）」與「可預見的負面後果（Foreseeable Aversive Consequences）」。如果個體感到自己是被完全脅迫的，失調便不會發生。

---

## 🔗 知識網絡關聯 (Relations)
- **與 [[Milgram1963-Obedience]] 的深層共振**: 
  - 米爾格倫的 15V 等差遞增正是利用了失調理論的「漸進承諾（Foot-in-the-Door）」：每施加一次微小電擊，被試為了降低內在矛盾，不得不修改認知合理化上一級行為，進而陷入難以自拔的深淵。
- **與 [[Franzen2023-AschReplication]] 的交叉對照**: 
  - Franzen 發現金錢激勵（1 CHF）無法消除從眾；而 Festinger 證實微薄金錢激勵反而會加速內在態度的自我合理化同化。
- **衍生核心概念**: 
  - [[Cognitive-Dissonance]]: 社會心理學史上被引用最多的核心概念之一。
- **衍生實驗範式**: 
  - [[Induced-Compliance-Paradigm]]: 測量態度轉變的經典實驗典範。
