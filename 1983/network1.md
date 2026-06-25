# TCP/IP 正式啟用：網際網路的誕生日

## 旗艦級的協定轉換

1983 年 1 月 1 日，ARPANET 正式從 NCP（Network Control Protocol）切換到 TCP/IP（Transmission Control Protocol / Internet Protocol）。這一天被公認為網際網路（Internet）的正式誕生日。

切換的技術挑戰巨大。ARPANET 在當時已經連結了上百台主機，所有節點必須在同一時間完成轉換，否則無法通訊。Dan Lynch 在 USC/ISI 負責這項任務，David Clark 擔任網際網路工作小組主席。Jon Postel 則負責協議號碼的分配。

## 為什麼 TCP/IP 是革命性的

NCP 是為單一網路（ARPANET）設計的協議，它假設所有節點在同一個網路內。TCP/IP 則完全不同：它是為了「網際間通訊」（internetworking）設計的。IP 負責在不同網路之間路由封包，TCP 負責在不可靠的網路上提供可靠的連線。

這意味著不再是 ARPANET 一個網路——而是一個由網路組成的網路（internet）。任何執行 TCP/IP 的網路都可以與其他 TCP/IP 網路互通。

## 全球效應

TCP/IP 的標準化導致了多個效應：美國國防部宣布 TCP/IP 為官方標準；Berkeley 將 TCP/IP 整合進 4.2BSD UNIX；CSNET、MILNET 等網路開始使用 TCP/IP 互連。網際網路的規模從此開始指數級成長。

## 延伸閱讀

- [TCP/IP 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite)
- [RFC 801 - NCP/TCP 轉換計畫](https://www.rfc-editor.org/rfc/rfc801)
