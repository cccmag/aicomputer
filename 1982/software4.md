# TCP/IP 協定族：網際網路的共通語言

## 從 NCP 到 TCP/IP 的過渡

1982 年 1 月 1 日，美國國防部宣布 TCP/IP 正式取代 NCP（Network Control Protocol）成為 ARPANET 的標準主機控制協定。這是一個漫長過渡期的關鍵里程碑。

TCP/IP 協定族包含多個層級的協定：
- **IP（Internet Protocol）**：負責將資料分組傳送到目標位址，不保證送達
- **TCP（Transmission Control Protocol）**：在 IP 之上提供可靠的串流傳輸
- **UDP（User Datagram Protocol）**：提供無連線的資料傳送
- **ICMP（Internet Control Message Protocol）**：網路診斷與錯誤訊息

## 跨網路的互通

TCP/IP 的核心價值在於：它為不同的底層網路技術（Ethernet、ARPANET、分組無線電、衛星網路）提供了一個統一的網路層（Internet Layer）。任何網路——無論其底層技術為何——只要實作了 IP 協定，就可以與其他網路互通。

1982 年，TCP/IP 仍處於早期階段，但它的架構已經證明了自己的價值：隱藏底層差異、提供可靠的端到端通訊、支援動態路由。這個設計在接下來的四十年中只進行了小幅修改——這證明了 Cerf 和 Kahn 原始設計的遠見。

## 延伸閱讀

- [Internet Protocol Suite - Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite)
- [TCP/IP 歷史](https://www.internetsociety.org/internet/history-internet/brief-history-internet/)
