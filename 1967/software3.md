# Dijkstra 的 THE 作業系統：階層式結構的典範

## 第一個階層式作業系統

1967 年，Eindhoven 理工學院的 Edsger Dijkstra 發表了 THE 多程式系統（THE multiprogramming system）的設計論文。THE 不是一個廣泛使用的產品，但它對作業系統設計的理論貢獻極為深遠。

THE 系統的核心理念是**階層式結構**（hierarchical structuring）：將作業系統的所有活動劃分為多個循序程序（sequential processes），並將這些程序放置在不同的抽象層級中。每一層都建構在下一層的抽象之上，隱藏了下層的實作細節。

## 層級設計

THE 的六個層級：

- **第 0 層**：處理器分配和中斷處理
- **第 1 層**：記憶體管理（頁面排程）
- **第 2 層**：操作員控制台
- **第 3 層**：輸入/輸出緩衝
- **第 4 層**：使用者程式
- **第 5 層**：系統操作員

這種設計不僅讓系統更容易理解和維護，還使得正確性驗證成為可能——每一層只需要確保自己與下一層的接面正確即可。

## 信號量（Semaphore）

為了協調多個程序對共享資源的存取，Dijkstra 在 THE 系統中引入了**信號量**（semaphore）這一同步原語。P（proberen，測試）和 V（verhogen，增加）操作提供了一種簡單而優雅的方式來解決同步問題，避免了忙式等待（busy waiting）的低效率。

Dijkstra 在論文中寫道：「階層式結構對於設計的邏輯健全性和實作的正確性驗證至關重要。」

## 延伸閱讀

- [THE multiprogramming system - Wikipedia](https://en.wikipedia.org/wiki/THE_multiprogramming_system)
- [Edsger Dijkstra - Wikipedia](https://en.wikipedia.org/wiki/Edsger_Dijkstra)
- [信號量 - Wikipedia](https://zh.wikipedia.org/wiki/%E4%BF%A1%E8%99%9F%E9%87%8F)
