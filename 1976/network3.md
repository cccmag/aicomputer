# TCP 協議的設計：Cerf 與 Kahn 的草稿

## 網路中的網路

1973 年，Vint Cerf 和 Bob Kahn 開始設計一種能夠連結不同分組交換網路的通訊協議。他們的概念在 1974 年的 IEEE Trans. on Communications 論文中首次公開，標題為「A Protocol for Packet Network Intercommunication」。到 1976 年，這個被稱為 TCP（Transmission Control Protocol）的協定已經有了初步的實作和測試版本。

## TCP 的關鍵設計

TCP 的核心創新是解決了三個根本問題：

**端到端確認**：確保資料在跨越不同網路時不會遺失。

**重新傳輸**：當資料包丟失時自動重送。

**流量控制**：防止發送方淹沒接收方。

最關鍵的設計決策是將網路可靠性放在端點而非網路中間節點——這個被稱為「端到端原則」（end-to-end argument）的理念後來成為網際網路架構的基石。

## 從理論到實作

1976 年，Cerf 和 Kahn 的團隊已經在 ARPANET、PRNET 和 SATNET 上進行了 TCP 的早期實作測試。SRI 的麵包車測試不只是技術演示，更是對 TCP 協定設計的實戰驗證。這些草稿和實作經驗最終在 1981 年固化為 RFC 791（IP）和 RFC 793（TCP）。

## 延伸閱讀

- [TCP/IP 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite)
- [Cerf & Kahn 1974 論文 - Google 搜尋](https://www.google.com/search?q=A+Protocol+for+Packet+Network+Intercommunication+Cerf+Kahn+1974)
