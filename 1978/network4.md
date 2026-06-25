# TCP/IP 協定集的成熟

## 從測試到標準化

1978 年是 TCP 協定從單一實驗走向標準化的重要一年。1977 年 11 月的三網路測試成功證明了 TCP 的可行性後，Cerf、Kahn 和他們的同事開始將 TCP 的功能拆分為兩個獨立的協定：TCP（傳輸控制協定，負責可靠的資料流傳輸）和 IP（網際網路協定，負責路由和封包轉發）。

這個拆分發生在 1978 年左右——最初 TCP 是一個單一的協定，同時處理端到端可靠性（後來歸 TCP）和網路路由（後來歸 IP）。將兩者分離的決定讓 IP 層可以保持簡單，而 TCP 層可以獨立演化。

## 國防部的採用

1978 年，美國國防部助理部長（C3I）正式下令採用基於 TCP 和 IP 的國防部標準主機對主機協定。這項決定讓 TCP/IP 從一個學術研究專案升級為美國軍方的正式標準。DCA 也開始主導 ARPANET 從 NCP 到 TCP/IP 的轉換計畫。

## 100 台主機的挑戰

ARPANET 超過 100 台主機的規模給 TCP/IP 的設計帶來了壓力。路由表的大小、封包擁塞控制、端到端確認的效率——這些問題在小型實驗網路中不明顯，但在大規模網路中就變得至關重要。

## 延伸閱讀

- [TCP/IP 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite)
- [DoD TCP/IP 採用 - Google 搜尋](https://www.google.com/search?q=DoD+standard+TCP+IP+1978)
