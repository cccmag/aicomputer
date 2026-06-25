# 分組無線電網路 PRNET：移動中連網

## 麵包車裡的節點

1976 年，SRI International 將一輛 GMC 廂型車改裝為行動網路節點——這就是後來被稱為「Packet Radio Van」的行動分組無線電實驗平台。這輛車配備了 Collins Radio 製造的無線電收發器、一個 LSI-11 微型電腦，以及 SRI 開發的 TCP 客戶端軟體。

## 第一次雙網路連線

1976 年 8 月 27 日，這輛麵包車停在 Portola Valley 的 Rossotti's 酒吧旁。研究人員從車內將資料透過無線電網路（PRNET）發送到 ARPANET，再經由 TCP 協議路由到目的地。這是人類歷史上**第一次成功的兩網路 TCP/IP 通訊**——一台移動中的車輛透過無線電連接到固定的封包交換網路，證明了異質網路互連的可行性。

## 技術架構

PRNET（Packet Radio Network）採用擴頻技術（spread spectrum），工作在 400/100 kbps 的雙速率模式下。它由 BBN、Collins Radio、SRI 和 UCLA 共同設計和實現，SRI 負責系統整合與技術指導。這項技術後來被應用於軍用無線電網路，也為蜂巢式通訊的封包資料傳輸奠定了基礎。

## 延伸閱讀

- [Packet Radio Van - Wikipedia](https://en.wikipedia.org/wiki/Packet_Radio_Van)
- [SRI Internetworking - SRI](https://www.sri.com/hoi/internetworking/)
