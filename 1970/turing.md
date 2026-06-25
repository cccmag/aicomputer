# 1970 年圖靈獎：James H. Wilkinson

## 數值分析的奠基者

1970 年 ACM 圖靈獎授予 James Hardy Wilkinson（1919–1998），表彰他在數值分析領域的開創性貢獻，特別是在線性代數計算方面的成就。

Wilkinson 於 1919 年出生在英格蘭肯特郡。他曾在劍橋大學三一學院學習數學，1946 年加入了 Alan Turing 在倫敦的國家物理實驗室（NPL）的團隊，參與了 Pilot ACE 計算機的開發。

## 往後誤差分析

Wilkinson 最著名的貢獻是**往後誤差分析**（backward error analysis）。傳統的誤差分析試圖追蹤每次計算的誤差累積——這在大型計算中往往不可行。Wilkinson 提出了相反的思路：將數值方法計算出的結果視為**略經擾動的原始問題的精確解**。

例如，當求解線性系統 Ax = b 時，計算機給出的解 x̂ 實際上可能是 (A+ΔA)x̂ = b 的精確解。Wilkinson 的方法專注於確定 ΔA 的大小，並證明如果 ΔA 足夠小，x̂ 就是可接受的近似解。

## Wilkinson 多項式

Wilkinson 多項式 W(x) = (x-1)(x-2)...(x-20) 是他用來展示多項式求根問題的數值不穩定性的經典例子。這個多項式在 x=1,...,20 有明顯的根，但對係數的微小擾動極度敏感——將 x¹⁹ 的係數改變 2⁻²³，根的變化就可以大到不可接受。這個例子如今仍然是數值分析課程的標準教材。

## ALGOL 與線性代數

Wilkinson 也參與了 ALGOL 語言的設計，並與 Friedrich L. Bauer、Heinz Rutishauser 等人共同開發了「ALGOL 的數值分析程式庫」（Handbook for Automatic Computation, Volume II: Linear Algebra）。這套程式庫為科學計算建立了標準化的方法。

## 圖靈獎演講

Wilkinson 在 1970 年的圖靈獎演講「Some Comments from a Numerical Analyst」中，討論了數值分析與計算機科學的關係，強調了理論分析對於可靠計算的重要性。

## 延伸閱讀

- [James H. Wilkinson - ACM Turing Award](https://amturing.acm.org/award_winners/wilkinson_0673475.cfm)
- [James H. Wilkinson - Wikipedia](https://en.wikipedia.org/wiki/James_H._Wilkinson)
