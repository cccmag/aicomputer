# C++ 語言的誕生：從 C with Classes 開始

## Stroustrup 的語言設計

1982 年，在 AT&T 貝爾實驗室工作的 Bjarne Stroustrup 開始開發一個他稱為「C with Classes」的程式語言。Stroustrup 面臨一個實際問題：他需要撰寫模擬分散式系統的軟體，但現有語言都不適合。

他選擇以 C 語言為基礎，加入了 Simula 67 的類別（class）概念——這讓程式設計師可以在保有 C 語言的效能和可移植性的同時，使用物件導向程式設計。Stroustrup 的設計原則：不強迫使用物件導向、與 C 完全相容、零開銷抽象（不因使用抽象機制而付出效能代價）。

## 從 C with Classes 到 C++

1982 年的原型版本包括了類別、繼承、內聯函數（inline）、預設函數參數。但沒有虛擬函數、運算子重載、多重繼承——這些功能在後續幾年中逐步加入。

1983 年，這個語言被正式命名為 C++——Rick Mascitti 提出的名字，++ 是 C 語言的遞增運算子，暗示它是 C 的改良版本。C++ 的第一個商業編譯器（Cfront——將 C++ 編譯為 C 程式碼的翻譯器）在 1985 年發表。C++ 在 1990 年代成為系統軟體、遊戲、金融應用和大型軟體專案的主流語言。

## 延伸閱讀

- [C++ - Wikipedia](https://en.wikipedia.org/wiki/C%2B%2B)
- [Bjarne Stroustrup - Wikipedia](https://en.wikipedia.org/wiki/Bjarne_Stroustrup)
- [C++ 歷史 - Stroustrup 個人網站](https://www.stroustrup.com/hopl2.pdf)
