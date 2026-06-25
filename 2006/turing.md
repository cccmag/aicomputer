# 2006 年圖靈獎：Frances Allen

## 編譯器最佳化的先驅

Frances E. Allen 是 2006 年 ACM 圖靈獎得主，授獎理由為「對於編譯器最佳化理論與實務的開創性貢獻，為現代編譯器化和自動平行執行的基礎」。她是圖靈獎 1966 年設立以來第一位女性得主。

Allen 於 1932 年出生於紐約州 Peru 的一個農場家庭。她於 1954 年在 Albany 師範大學（今 SUNY Albany）獲得數學學士學位，1957 年在密西根大學獲得數學碩士學位。她原本計畫成為一名中學數學教師，但在 1957 年加入了 IBM 研究實驗室——一個被她視為「臨時」工作的決定，最終卻成為她終生的職業。

## IBM 的編譯器黃金時代

Allen 加入 IBM 時，她被分配到 IBM Stretch（7030）超級電腦的編譯器專案——FSQ（FORTRAN Stretch QUADRUPLE）專案，這是一個將 FORTRAN 程式碼轉換為 Stretch 機器語言的編譯器。她的任務是開發子程式碼生成和程式碼最佳化的功能。

在 1960 年代和 1970 年代，IBM Research 的編譯器團隊是世界上最重要的編譯器研究群體之一。Allen 和她的同事（包括 John Cocke——1987 年圖靈獎得主）共同開發了許多現代編譯器的基礎技術：

- **控制流程分析（Control Flow Analysis）**：將程式轉換為控制流程圖（CFG），作為編譯器分析的基礎
- **資料流程分析（Data Flow Analysis）**：追蹤變數在程式中的定義和使用
- **常數傳播（Constant Propagation）**：在編譯時期計算常數運算式的值
- **公共子運算式消除（Common Subexpression Elimination）**：避免重複計算相同的運算式
- **基本區塊和延伸基本區塊**（Basic Blocks and Extended Basic Blocks）
- **運算元疊起（Code Motion）**：將不變的運算式移出迴圈

## 平行編譯的先驅

1980 年代，Allen 將她的注意力轉向平行運算的編譯器支援——這是她在 1990 年代初期領導的 IBM XL FORTRAN 編譯器專案的核心方向。她的團隊開發了自動向量化和自動平行化的編譯器技術，讓科學計算程式可以自動利用 IBM 的向量處理器和多處理器系統。

Allen 的編譯器研究對 IBM 的 POWER 架構（1990 年推出的 RISC 處理器系列）產生了直接影響——John Cocke 的 RISC 概念和 Allen 的最佳化技術共同賦予了 POWER 處理器出色的效能。

## 經典論文與影響

Allen 在編譯器領域最著名的論文之一是 1970 年與 Cocke 合寫的「A Catalog of Optimizing Transformations」——一份系統性的編譯器最佳化技術目錄。另一篇是 1976 年的「Control Flow Analysis」——這篇論文將控制流程圖（CFG）的分析理論化，成為後續編譯器課程的標準教材。

Allen 的貢獻不僅僅在學術上——她的編譯器最佳化技術直接影響了 IBM 的 FORTRAN 和 PL/I 編譯器，以及後來的 GNU Compiler Collection（GCC）和 LLVM。她的工作讓「編譯器不僅僅是翻譯器，更是程式碼的智慧最佳化器」這個概念變成現實。

## 延伸閱讀

- [Frances Allen - ACM Turing Award](https://amturing.acm.org/award_winners/allen_1012327.cfm)
- [Frances Allen - Wikipedia](https://en.wikipedia.org/wiki/Frances_E._Allen)
- [Control Flow Analysis - Frances Allen, 1970](https://dl.acm.org/doi/10.1145/800001.811668)
- [Programming Languages and Compilers at IBM Research](https://www.ibm.com/ibm/history/ibm100/us/en/icons/compprog/)
