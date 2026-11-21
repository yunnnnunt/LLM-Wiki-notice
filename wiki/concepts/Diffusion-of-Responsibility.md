---
title: "Diffusion of Responsibility"
aliases: [責任分散, 責任稀釋, 責任擴散]
tags:
  - type/concept
  - domain/social-psychology
---

# [[Diffusion-of-Responsibility]]

## 📖 定義與核心機制
**責任分散 (Diffusion of Responsibility)** 指的是當一項任務、義務或道德行為存在多名潛在承擔者時，個體所感受到的個人義務感（Personal Obligation）與未履行責任時的道德自責（Psychological Blame）隨群體規模的擴大而被稀釋的現象。

### 核心微觀心理過程：
1. **義務感遞減**: 單獨在場時，救助義務為 $100\%$ 聚焦於個人；群體人數為 $n$ 時，主觀感知責任被拆解為 $\approx \frac{1}{n}$。
2. **潛在責難分散**: 若發生悲劇，面臨的道德斥責由全體在場者共同分攤，單一受試者所承受的代價微乎其微。
3. **行動冗餘假定 (Assumed Redundancy)**: 在無法窺探他人即時行動的情況下，個體傾向自我合理化地推斷「其他某人必定已經在採取行動或報警了」。

---

## 🌲 數學與機率模型 (Probability Formulation)
在一個由 $n$ 位互不通訊的潛在旁觀者構成的情境中，若單獨一人在時限 $t$ 內採取行動的機率為 $P(t)$，則至少有一人採取行動的整體機率 $P_{\ge 1}(t)$ 滿足：
$$
P_{\ge 1}(t) = 1 - \left[1 - P(t)\right]^n
$$
實證上，由於 $P(t)$ 隨 $n$ 的增加而急劇衰減（即 $P(t, n) \ll P(t, 1)$），導致群體累積救助機率在危機爆發初期（如前 45 秒）反而顯著低於單人情況（[[Darley1968-BystanderIntervention]]）。

---

## 🧪 實證證據矩陣 (Empirical Evidence Matrix)
| 論文 | 樣本與情境 | 驗證之假設/效應 | 效應量 / 統計強度 | 支持/反對 |
| :--- | :--- | :--- | :--- | :---: |
| [[Darley1968-BystanderIntervention]] | $N = 70$, 閉門耳機情境 | 排除視線干擾下的純粹責任分散 | 2 人組速度分數 $0.87$ vs. 6 人組 $0.51$ ($p<.01$) | 奠基證明 |

---

## 🔗 理論交織與拓展 (Theoretical Intersections)
- **與 [[Agentic-State]] 的對比**:
  - 在 [[Milgram1963-Obedience]] 中，責任是**縱向向上轉嫁**給合法權威者（Vertical Shifting）；
  - 在責任分散中，責任是**橫向平行分攤**給同儕旁觀者（Horizontal Dilution）。
- **社會惰化 (Social Loafing)**：群體共同執行物理/認知任務時，個人努力程度因無法單獨評估而下降，與責任分散共享相同的心理機制。
- **網路旁觀者行為 (Cyberbystander Behavior)**：在社群媒體霸凌或網路求助中，由於在線旁觀者規模極其龐大且具匿名性，責任分散效應更加劇烈。
