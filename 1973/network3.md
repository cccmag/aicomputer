# Cerf 與 Kahn 的 TCP 論文

## 從加州到世界

1973 年春天，Vint Cerf（史丹佛大學助理教授）和 Bob Kahn（DARPA 計畫經理）開始聯手設計新一代的網路互連協定。他們各自帶著不同的經驗進入這個合作：

Cerf 在 UCLA 參與了 ARPANET 最初的 NCP 開發，深刻理解主機到主機通訊的需求。Kahn 在 BBN 參與了 IMP 的設計，最近則在 DARPA 負責分組無線電網路專案。他們的共同目標是設計一個可以連接不同類型網路的「網際網路協定」。

## 端到端原則

Kahn 的關鍵洞見來自對軍事通訊的理解：在戰爭中，網路節點可能隨時被摧毀。傳統的電路交換（如電話網路）在這種環境下無法運作，因為它依賴於路徑上所有節點的共同狀態。

Cerf 和 Kahn 提出的解決方案後來被稱為**端到端原則**：

1. 網路只負責一件事：盡力傳送封包（best-effort delivery）
2. 可靠性由端點主機負責：主機偵測封包是否遺失，必要時重傳
3. 網路的中間節點（路由器／閘道器）不需要維護任何連線狀態
4. 封包可以透過不同路徑到達目的地，即使部分網路毀滅

這個設計哲學與當時電信網路的思維完全相反。電信網路將智慧放在網路中心（交換機），而 Cerf 和 Kahn 將智慧放在網路的邊緣（主機）。

## 1973 年底的論文

1973 年底，Cerf 和 Kahn 完成了論文「A Protocol for Packet Network Intercommunication」（分組網路互通的協定），並提交給 IEEE Transactions on Communications。這篇論文在 1974 年 5 月正式發表。

論文中描述了：

- 一種可以在不同網路之間路由封包的協定
- 採用「閘道器」（gateway）來連接不同網路
- 封包（稱為「資料報」datagram）的概念
- TCP 作為端到端的可靠傳輸層

值得一提的是，Cerf 和 Kahn 在這篇論文中創造了「網際網路」（internet）這個詞——作為「互連網路」（internetworking）的簡稱。

## 後續發展

TCP 的完整規格（RFC 675）在 1974 年 12 月由 Cerf、Yogen Dalal 和 Carl Sunshine 共同完成。1978 年，TCP 被拆分為 TCP 和 IP 兩個協定。1983 年 1 月 1 日，ARPANET 正式從 NCP 切換到 TCP/IP——這一天被視為現代網際網路的誕生日。

## 延伸閱讀

- [Cerf/Kahn 1974 論文文本](http://www.cs.princeton.edu/courses/archive/fall06/cos561/papers/cerf74.pdf)
- [TCP/IP 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite)
- [TCP 論文歷史 - Google 搜尋](https://www.google.com/search?q=Cerf+Kahn+A+Protocol+for+Packet+Network+Intercommunication+1973)
