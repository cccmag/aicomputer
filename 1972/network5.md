# INWG 與國際網路標準化

## 第一次國際網路會議

1972 年 10 月，在 ICCC 會議期間，來自世界各地的網路研究者在華盛頓特區聚集，討論一個共同的問題：**如何讓不同國家的網路互相通訊？**

這個會議產生了**國際網路工作組**（International Network Working Group, INWG）。Vint Cerf 被選為第一任主席，成員包括了法國的 Louis Pouzin（CYCLADES 計畫）、英國的 Donald Davies 和 Roger Scantlebury（NPL）、美國的 Steve Crocker 等人。

## 不同路徑，同一個問題

1972 年，世界上已經有幾個獨立發展的分組交換網路：

- **ARPANET**（美國）：使用 NCP 協定，由 IMP 路由器互連
- **NPL Network**（英國）：Donald Davies 在國家物理實驗室的單節點網路
- **CYCLADES**（法國）：Louis Pouzin 在法國的網路研究，引入了「資料報」（datagram）概念
- **ALOHAnet**（夏威夷）：無線分組網路

每個網路都有自己的協定、封包格式、定址方式。如何讓它們互相連接？這是 INWG 要解決的核心問題。

## 思想交鋒

INWG 的討論充滿了激烈的思想交鋒：

- **虛擬電路 vs 資料報**：ARPANET 的 NCP 採用虛擬電路（建立連線後才傳輸資料），而 CYCLADES 的 Louis Pouzin 極力主張資料報（每個封包獨立路由）更靈活

- **集中式 vs 分散式控制**：ARPANET 的 IMP 網路採用集中式路由計算，但 INWG 中的研究者開始探索分散式路由

- **可靠網路 vs 端點可靠**：ARPANET 的設計讓網路本身保證可靠傳輸，但 Kahn 和 Cerf 的新構想讓端點主機負責可靠性

這些辯論直接塑造了網際網路的架構。資料報概念最終在 TCP/IP 中獲得勝利；端到端原則成為網際網路的基石；INWG 的國際合作模式也被後來的 IETF（網際網路工程任務組）所繼承。

## 延伸閱讀

- [INWG 歷史 - Google 搜尋](https://www.google.com/search?q=International+Network+Working+Group+INWG+1972)
- [網路互連早期歷史 - Wikipedia](https://en.wikipedia.org/wiki/Internetworking)
