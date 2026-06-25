# TCP/IP 正式成為 ARPANET 標準

## 旗日的前奏

1982 年 1 月 1 日，TCP/IP 被美國國防通信局（DCA）正式指定為 ARPANET 的標準主機協定。這個決策啟動了為期一年的全面過渡——從 NCP 到 TCP/IP——最終在 1983 年 1 月 1 日完成的「旗日」（Flag Day）全面切換。

TCP/IP 取代 NCP 的主要理由：
- NCP 只能在 ARPANET 內部使用，無法跨網路通訊
- TCP/IP 提供了網路層互通性——不同類型的網路可以自由連接
- TCP 提供了比 NCP 更好的流量控制和錯誤恢復能力

## 分層架構的威力

TCP/IP 的分層設計是其在技術上勝出的關鍵：
- **應用層**：Telnet、FTP、SMTP 等
- **傳輸層**：TCP、UDP
- **網路層**：IP（負責路由和位址分配）
- **鏈結層**：Ethernet、ARPANET、分組無線電等

每一層只需明確定義上下層的介面，內部實作可以完全獨立。這意味著新的應用程式、新的傳輸技術、新的硬體可以在不影響其他層的情況下加入網路。

## 延伸閱讀

- [網際網路歷史 - Internet Society](https://www.internetsociety.org/internet/history-internet/brief-history-internet/)
- [Flag Day - Wikipedia](https://en.wikipedia.org/wiki/Flag_Day_(computing))
