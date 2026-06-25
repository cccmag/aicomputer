# C 語言的誕生：貝爾實驗室的革命

## 從 B 到 C

1972 年，在紐澤西州 Murray Hill 的貝爾實驗室，Dennis Ritchie 正在創造一個將主導系統軟體開發半個世紀的程式語言——C。

故事的起點是 Ken Thompson 在 1969 年開發的 B 語言，它源自 BCPL（Martin Richards，1966 年）。Thompson 用 B 語言在 PDP-7 上為 Unix 寫了一些工具，但 B 語言有嚴重的限制：它沒有型別系統，所有的運算都是面向機器字的，這在 PDP-11 上造成了效率問題。

## 設計目標

Ritchie 設計 C 時有幾個明確目標：

**作為系統程式語言**：C 必須能夠取代組合語言來撰寫 Unix 核心。這意味著它必須提供對記憶體的底層存取、指標算術、以及與機器指令高度對應的語法結構。

**簡潔而高效**：Ritchie 相信程式語言的設計應該讓程式設計師清楚地看到程式碼與機器行為之間的對應關係。C 的語法簡潔到只有少數幾個關鍵字，但其表達力極強。

**可移植性**：雖然 C 是為 PDP-11 設計的，但它提供了將系統軟體從特定硬體中抽象出來的能力——這正是 Unix 需要被移植到不同機器上的關鍵。

## C 的核心創新

C 引入了幾個在當時具有革命性的語言特性：

**資料型別系統**：int、char、float、double 等基本型別，以及陣列、結構體（struct）、聯合體（union）和指標（pointer）等複合型別。這套型別系統讓編譯器能夠檢查型別一致性和進行適當的型別轉換。

**指標與陣列的統一**：C 中指標與陣列的操作可以互相轉換，這為系統程式設計提供了極大的靈活性。`a[i]` 實際上被視為 `*(a + i)` 的語法糖。

**前處理器**：`#include`、`#define` 等前處理指令讓程式碼可以模組化地組織。

## 與 Unix 的共生關係

C 語言與 Unix 作業系統的發展密不可分。Ritchie 和 Thompson 在 1972 年開始用 C 重寫 Unix（即 Unix 第二版），這使得 Unix 成為第一個用高階語言實作的作業系統——也是第一個可以跨平台移植的作業系統。在此之前，所有的作業系統都只能用組合語言撰寫，綁死在特定的硬體架構上。

## 延伸閱讀

- [C 語言發展史 - Dennis Ritchie](https://www.bell-labs.com/usr/dmr/www/chist.html)
- [C 語言 - Wikipedia](https://en.wikipedia.org/wiki/C_(programming_language))
- [C 語言歷史 - Google 搜尋](https://www.google.com/search?q=C+language+1972+Dennis+Ritchie+Bell+Labs)
