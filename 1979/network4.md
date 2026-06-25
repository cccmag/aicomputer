# ARPANET 從 NCP 到 TCP 的過渡

## 網際網路的架構分歧

ARPANET 自 1969 年開始運行，最初使用 NCP（Network Control Protocol）作為傳輸協定。但到了 1970 年代末，NCP 的限制日益明顯：它不具備錯誤控制機制、無法處理網路壅塞、只能在同一網路（ARPANET）中使用。

1974 年，Vint Cerf 和 Bob Kahn 發表了 TCP 協定的設計論文。1979 年，TCP/IP 協定族仍在開發和測試中。這一年在威斯康辛大學舉辦的研討會上，研究人員開始討論從 NCP 過渡到 TCP 的具體計畫。

## 網路控制中心

1979 年，ARPANET 的網路控制中心（NCC）已經發展成熟，能夠監控數十個 IMP（Interface Message Processor）的運行狀態。與此同時，許多大學和研究機構正在建立各自的區域網路（LAN），如 Ethernet——這為後來 TCP/IP 作為不同網路之間的統一協定創造了需求。

ARPANET 在 1983 年 1 月 1 日正式從 NCP 切換到 TCP/IP——這一天被稱為「旗日」（Flag Day）。1979 年的討論和測試是這個重要過渡的關鍵準備階段。

## 延伸閱讀

- [ARPANET 歷史 - Living Internet](https://www.livinginternet.com/i/ii_arpanet.htm)
- [TCP/IP 起源 - Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite)
