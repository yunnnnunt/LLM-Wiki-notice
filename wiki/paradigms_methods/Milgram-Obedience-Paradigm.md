---
title: "Milgram Obedience Paradigm"
aliases: [米爾格倫服從範式, 電擊產生器範式, Shock Generator Paradigm]
tags:
  - type/paradigm
  - domain/social-psychology
---

# [[Milgram-Obedience-Paradigm]]

## 🔬 範式概述與核心邏輯
**米爾格倫服從範式 (Milgram Obedience Paradigm)** 是一種用於在實驗室標準化測量破壞性權威服從程度的經典社會心理學實驗典範。該範式透過雙人配對學習實驗的欺瞞封面故事（Cover Story），在合法性權威的監督下，觀察受試者將電擊懲罰升級至危險檔位的行為臨界點。

---

## ⚙️ 實驗裝置與標準化流程 (Standard Protocol)

### 1. 角色分配與偽裝設置 (Rigged Drawing & Deception)
- 兩位參與者（一名真實被試，一名實驗助手/同謀 Confederate）。
- 抽籤過程經作弊設定（兩張紙條均寫有「Teacher」），使真實被試必定擔任施罰者「教師」，同謀擔任受罰者「學習者（Mr. Wallace）」。
- 學習者被帶至隔壁房間，固定在帶有電極的椅子上，塗上導電膏；告知被試「電擊雖然極度疼痛，但不會造成永久組織損傷」。

### 2. 電擊產生器規格 (Shock Generator Specifications)
- 橫向排列 30 個撥動開關，電壓範圍為 $15\text{V} \sim 450\text{V}$，階梯增量 $\Delta V = 15\text{V}$。
- 開關分為 8 個文字等級標籤（每組 4 個開關）：
  1. Slight Shock (15-60V)
  2. Moderate Shock (75-120V)
  3. Strong Shock (135-180V)
  4. Very Strong Shock (195-240V)
  5. Intense Shock (255-300V)
  6. Extreme Intensity Shock (315-360V)
  7. Danger: Severe Shock (375-420V)
  8. XXX (435-450V)
- **真實驗證 (Sample Shock)**：被試親自接受第 3 檔（45V 電池供電）真實微電擊，以建立對裝置真實性的堅定信念。

### 3. 學習任務與錯誤反饋排程
- 配對聯想詞學習任務（Paired-Associate Learning Task）。
- 學習者預先排定答題節奏（約 3 題錯誤對應 1 題正確）。
- 每當學習者答錯，被試必須先報出即將施加的電壓數值，隨後撥下開關，並於每次錯誤時調升一檔。

### 4. 標準化催促語序列 (Standardized Prods)
若被試猶豫或拒絕施加電擊，身著實驗袍的實驗者依序使用以下 4 級指令；唯有在被試違抗 Prod 4 時才終止實驗：
- **Prod 1**: *"Please continue."* 或 *"Please go on."*
- **Prod 2**: *"The experiment requires that you continue."*
- **Prod 3**: *"It is absolutely essential that you continue."*
- **Prod 4**: *"You have no other choice, you must go on."*

---

## 📐 依變量操作化定義 (Dependent Variables)
- **Break-off Point ($k_i$)**：被試終止實驗時的最後電擊開關序號 ($k \in [0, 30]$)。
- **Obedience Score ($V_i$)**：對應電壓數值 $V_i = 15 \times k_i$。
- **Defiant vs. Obedient 判定**：
  $$
  \text{Status} = 
  \begin{cases} 
  \text{Obedient}, & \text{if } k_i = 30 \ (450\text{V}) \\ 
  \text{Defiant}, & \text{if } k_i < 30 
  \end{cases}
  $$

---

## 📚 採用此範式的知識庫文獻
- [[Milgram1963-Obedience]]: 基準實驗（Baseline Remote-Feedback Condition），取得 65% 完全服從率。
