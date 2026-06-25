# 結構化程式設計的理論深化

## 從 goto 爭論到結構化方法

1968 年，Edsger Dijkstra 在《Communications of the ACM》上發表了著名的信件「Go To Statement Considered Harmful」，點燃了程式設計領域最具影響力的辯論。到了 1974 年，這場辯論已經從情緒化的爭論轉變為系統性的理論建構。

這一年，Dijkstra、C.A.R. Hoare、Ole-Johan Dahl 的主要著作開始形成結構化程式設計的理論基礎。結構化程式設計的核心主張是：任何程式都可以用三種控制結構（序列、選擇、重複）來表達，而不需要使用 goto 語句。

## 對軟體工程的影響

結構化程式設計不僅僅是語法問題，它反映了更深層的軟體工程思維：

- **逐步求精（Stepwise Refinement）**：Niklaus Wirth 在 1971 年提出的方法，主張從高層抽象逐步分解到具體實作。
- **模組化（Modularity）**：將程式分解為獨立的、可替換的模組。
- **正確性證明（Correctness Proofs）**：Dijkstra 和 Hoare 發展的公理語意學，允許對程式進行數學證明。

1974 年，這些想法開始從學術界滲透到實務界。越來越多的程式設計師開始接受結構化方法，即使 Fortran 和 COBOL 這類語言原本並不支援結構化結構，也出現了預處理器和轉換工具來模擬這些功能。

## Knuth 的平衡觀點

1974 年圖靈獎得主 Donald Knuth 在同年發表了「Structured Programming with go to Statements」論文，提出了更平衡的觀點。他認為結構化程式設計的目標是「寫出容易理解的正確程式」，而非教條式地禁止 goto——在某些情況下（如錯誤處理、狀態機），goto 可能反而是最清晰的方式。

這篇論文展現了 Knuth 典型的風格：深入分析、大量例子、電腦排版的美學講究（它是最早使用 TeX 排版的論文之一）。

## 延伸閱讀

- [結構化程式設計 - Wikipedia](https://zh.wikipedia.org/wiki/%E7%BB%93%E6%9E%84%E5%8C%96%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1)
- [Dijkstra 的 goto 信件 - ACM](https://dl.acm.org/doi/10.1145/362929.362947)
- [Knuth 論結構化程式設計 - Google 搜尋](https://www.google.com/search?q=Knuth+Structured+Programming+with+go+to+Statements+1974)
