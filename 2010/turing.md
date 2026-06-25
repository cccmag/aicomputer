# 2010 年圖靈獎：Leslie Valiant

## 計算學習理論的奠基者

2010 年的 ACM 圖靈獎頒給了 Leslie G. Valiant——一位英國計算機科學家，自 1982 年起任教於哈佛大學。頒獎理由是「對計算理論的變革性貢獻，特別是 Probably Approximately Correct（PAC）學習理論的創立、以及對計算複雜性、密碼學和並行計算的廣泛貢獻」。

## PAC 學習模型

Valiant 在 1984 年發表了開創性的論文「A Theory of the Learnable」——這篇論文定義了 PAC 學習（Probably Approximately Correct）模型，為計算學習理論奠定了數學基礎。

PAC 模型的核心概念很簡單：一個學習演算法只需要以高機率輸出一個「近似正確」的假設。具體來說：

**Probably（大概）**：演算法有至少 (1-δ) 的機率成功——其中 δ 是使用者可以設定的容錯參數。

**Approximately Correct（近似正確）**：演算法輸出的假設的錯誤率不超過 ε——其中 ε 是使用者可以設定的精確度參數。

**高效性**：演算法需要的樣本數和執行時間是 1/ε 和 1/δ 的多項式函數。

PAC 模型的優雅之處在於它同時捕捉了學習的三個關鍵維度：正確性、信心和效率。任何在 PAC 模型下可學習的類別都被認為是「本質上可學習的」。

## 對機器學習的深遠影響

Valiant 的 PAC 理論為機器學習提供了嚴謹的數學基礎。它讓研究人員可以：

- 計算特定問題需要多少訓練樣本
- 證明某些問題在本質上是不可學習的（即使在 PAC 意義下）
- 比較不同學習演算法的樣本效率

PAC 理論也與統計學習理論（Vapnik-Chervonenkis 維度）和歸納推理緊密相關。Valiant 的工作影響了語音辨識、自然語言處理、電腦視覺和生物資訊學等領域的機器學習應用。

## 其他貢獻

Valiant 在計算理論的其他領域也有重要貢獻：

**計數複雜性**：他定義了 #P 複雜性類別——計算一個 NP 問題的解的數量——並證明了許多計數問題是 #P-complete 的。

**並行計算**：他提出了 Valiant 的平行計算模型——展示了一些問題可以在平行電腦上獲得顯著的加速。

**分散式計算**：他的工作影響了分散式系統的理論基礎。

## 延伸閱讀

- [Leslie Valiant - ACM Turing Award](https://amturing.acm.org/award_winners/valiant_1393370.cfm)
- [Leslie Valiant - Wikipedia](https://zh.wikipedia.org/wiki/%E8%8E%B1%E6%96%AF%E8%8E%B1%C2%B7%E5%8D%8E%E5%AE%9A)
- [PAC 學習理論](https://en.wikipedia.org/wiki/Probably_approximately_correct_learning)
