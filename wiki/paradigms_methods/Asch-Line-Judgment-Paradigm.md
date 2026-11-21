---
title: "Asch Line Judgment Paradigm"
aliases: [阿希線段判斷範式, Asch Paradigm, Line-Matching Task]
tags:
  - type/paradigm
  - domain/social-psychology
---

# [[Asch-Line-Judgment-Paradigm]]

## 🔬 範式概述與核心邏輯
**阿希線段判斷範式 (Asch Line Judgment Paradigm)** 是社會心理學測量規範性群體從眾壓力（Normative Conformity）的最經典實驗典範。受試者與數名同謀（Confederates）一同坐在實驗室中，面對一條標準參考線（Reference line）與三條候選比較線（Comparison lines 1, 2, 3），依序公開口頭報出長度與參考線相符的編號。

---

## ⚙️ 實驗設計與標準化設置 (Standard Protocol)

### 1. 物理座次安排 (Seating Arrangement)
- 典型的設置包含 5 至 8 名參與者，其中僅有 1 名是真實受試者（Naive Subject），其餘皆為實驗同謀。
- 真實受試者必定被安排在倒數第二個座位（如 6 人組中的第 5 位），使其在發表判斷前必須先聆聽前面所有同謀的一致發言。

### 2. 試次分類 (Trials Structure)
- **非關鍵試次 (Uncritical / Neutral Trials)**：同謀給予客觀正確的回答，建立情境常態感並降低懷疑。
- **關鍵試次 (Critical Trials)**：同謀一致、公開地給出明顯錯誤的判斷。
  - 任務難度可透過線段長度差異調整（Easy Trials vs. Hard Trials）。

### 3. 當代擴展變體 (Modern Extensions)
- **金錢激勵引入 (Incentivized Condition)**：如 [[Franzen2023-AschReplication]] 每答對一題給予實質獎勵（1 CHF），檢驗經濟理性對社會壓力的抵消作用。
- **無同謀偏光鏡技術 (fMORI Technique)**：Mori & Arai (2010) 利用偏光眼鏡讓受試者看見客觀不同的投影畫面，免去聘用大量演員同謀的需求。
- **主觀態度擴展 (Attitude/Opinion Variant)**：將客觀線段替換為政治主張、社會議題投票，檢驗意見形成中的從眾傳染。

---

## 📐 指標操作化 (Operational Metrics)
- **試次錯誤率 (Trial-level Error Rate)**：
  $$
  \text{Error Rate} = \frac{\text{關鍵試次中跟隨同謀錯誤次數}}{\text{關鍵試次總數}}
  $$
- **個體錯誤次數 (Count of Conforming Answers)**：通常作為泊松迴歸（Poisson Regression）或 OLS 迴歸之因變量。
- **完全獨立者比例 (Never Conformed %)** vs. **至少從眾一次比例 (Conformed At Least Once %)**。

---

## 📚 採用此範式的知識庫文獻
- Asch (1951, 1955, 1956): 原創經典系列研究。
- [[Franzen2023-AschReplication]]: 現代瑞士大學生重現與激勵/政治擴展實驗（$N=202$）。
