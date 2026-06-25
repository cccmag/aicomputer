# BCPL：通往 C 語言的橋樑

## 從 CPL 的複雜中誕生

1966 年，劍橋大學數學實驗室的博士生 Martin Richards 在他的博士論文中勾勒出了一門新語言的雛形——BCPL（Basic Combined Programming Language）。

BCPL 是對其前身 CPL（Combined Programming Language）的直接回應。CPL 由劍橋大學和倫敦大學聯合設計，始於 1962 年，但這門語言變得日益龐大複雜，以至於編譯器難以實作。Richards 的策略很明確：「移除那些使編譯困難的特性」——他保留了 CPL 的基本語法和結構，但捨棄了繁瑣的型別系統和多樣的定義結構。

## 單一資料型別的激進簡化

BCPL 最激進的設計決定是：它只有一種資料型別——「二進位位元模式」（binary bit pattern）。這個單一型別可以代表字元、整數、浮點數、指標，甚至是函數的進入點。這種「無型別」（typeless）設計使得 BCPL 極其簡單且高效。

這種設計理念後來深刻影響了 C 語言的發明者 Dennis Ritchie。

## 編譯器寫作的利器

BCPL 從一開始就被設計為編譯器寫作工具。Richards 在 1967 年春天訪問 MIT 的 Project MAC 時，首次在 IBM 7094 上使用 AED-0 語言實作了 BCPL 編譯器。BCPL 編譯器非常輕量且容易移植到新機器上——這種可移植性在當時是相當罕見的特性。

BCPL 引入了一項至今仍在使用的語法慣例：以大括號 `{}` 來界定程式碼區塊。

## 傳承與影響

BCPL 的影響力遠遠超出了它自身的普及程度：

- **B 語言**：Ken Thompson 在開發 UNIX 時，將 BCPL 簡化為 B 語言（以 BCPL 的第一個字母命名）
- **C 語言**：Dennis Ritchie 在 B 語言的基礎上加入型別系統，創造了 C 語言
- **Go 語言**：Google 的 Go 語言也受到 BCPL 的影響

這條傳承路線：CPL → BCPL → B → C → Go，展現了一門語言如何透過不斷簡化和重塑，最終影響了整個軟體產業的發展。

BCPL 至今仍在使用，尤其是在一些大學和工業界中作為演算法實驗和編譯器研究的小型工具。

## 延伸閱讀

- [BCPL - Wikipedia](https://en.wikipedia.org/wiki/BCPL)
- [Martin Richards 的 BCPL 首頁](https://www.cl.cam.ac.uk/~mr10/BCPL.html)
- [How BCPL evolved from CPL](https://www.cl.cam.ac.uk/~mr10/cpl2bcpl.pdf)
