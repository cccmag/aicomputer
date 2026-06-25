# PL/M 語言：為微處理器而生的高階語言

## 語言的起源

1974 年，Gary Kildall 在為 Intel 開發 CP/M 時，需要一種能夠在微處理器上高效運作的高階語言。當時的微處理器資源極度有限——只有幾 KB 的記憶體、沒有磁碟、沒有作業系統。組合語言雖然效率高，但開發速度太慢。

Kildall 的解決方案是 PL/M（Programming Language for Microcomputers）。這是一種結構化的高階語言，語法上受到 ALGOL 和 PL/I 的影響，但針對微處理器的限制進行了大幅簡化。

## 語言特色

PL/M 的設計以實用為導向。它支援區塊結構、程序呼叫、陣列、指標等現代語言概念，但省略了浮點數運算、動態記憶體分配等對小型系統來說過於奢侈的功能。

PL/M 編譯器可以生成高效的 8080 機器碼，其效率通常只比手工編寫的組合語言差 20-30%。這在當時是一個了不起的成就——它讓開發者可以用高階語言為微處理器寫程式，同時保持接近組合語言的效能。

## 對後續語言的影響

PL/M 雖然沒有像 C 語言那樣廣泛流行，但它證明了幾個重要的原則：

- 微處理器上的高階語言編譯是可行的
- 結構化程式設計可以在一台只有幾 KB 記憶體的機器上實現
- 作業系統可以用高階語言來撰寫

這些經驗直接影響了後來的 C 語言和編譯器設計。CP/M 完全用 PL/M 寫成，是世界上第一個以高階語言實現的主流作業系統。

## 延伸閱讀

- [PL/M - Wikipedia](https://en.wikipedia.org/wiki/PL/M)
- [Gary Kildall 生平 - Wikipedia](https://en.wikipedia.org/wiki/Gary_Kildall)
- [早期微處理器程式語言 - Google 搜尋](https://www.google.com/search?q=PL/M+programming+language+Intel+1974)
