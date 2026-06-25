# 1976 年圖靈獎：Michael Rabin 與 Dana Scott

## 非決定性自動機的共同發現者

1976 年的 ACM 圖靈獎由 Michael O. Rabin 和 Dana S. Scott 共同獲得，表彰他們在計算理論基礎上的開創性貢獻。兩人獲獎的原因中，最著名的是他們在 1959 年合作發表的論文「Finite Automata and Their Decision Problems」。

## 非決定性自動機

Rabin 和 Scott 在該論文中首次引入了**非決定性有限自動機**（Nondeterministic Finite Automaton, NFA）的概念。在 NFA 中，機器可以在同一個狀態面對同一個輸入字元時選擇多個不同的下一個狀態。這種看似「會猜答案」的機器，其實等價於決定性有限自動機（DFA）——只是狀態數量可能呈指數級差異。

Rabin 和 Scott 證明了 NFA 與 DFA 的等價性，並提出了將 NFA 轉換為 DFA 的構作方法，即所謂的「powerset construction」（或 subset construction）。這是形式語言理論中最基本的定理之一。

## Rabin 的貢獻

Michael Rabin 除了在自動機理論的貢獻外，還在計算複雜度理論、隨機演算法和密碼學領域有深遠影響。他提出了 Rabin-Karp 字串匹配演算法（與 Richard Karp 合作），以及依賴大數分解困難性的 Rabin 密碼系統。他的「Rabin 隨機素數測試」至今仍廣泛應用於現代密碼系統中。

## Scott 的貢獻

Dana Scott 在獲獎後轉向程式語言語意學，與 Christopher Strachey 共同創立了**指稱語意學**（Denotational Semantics）。他發展了 Scott domain 理論，為程式語言的數學語意提供了嚴格的數學基礎。他後來也貢獻於模態邏輯和哲學邏輯。

## 圖靈獎演講

Rabin 的演講主題為「Complexity of Computations」，討論了計算複雜度理論的現狀與未來。Scott 的演講則聚焦於程式語言的邏輯基礎。兩位得主的研究路線雖然不同，但都根植於對計算本質的深刻理解。

## 延伸閱讀

- [Michael Rabin - ACM Turing Award](https://amturing.acm.org/award_winners/rabin_6090973.cfm)
- [Dana Scott - ACM Turing Award](https://amturing.acm.org/award_winners/scott_1193622.cfm)
