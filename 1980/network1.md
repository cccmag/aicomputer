# DIX Ethernet 2.0：10 Mbps 的統一規範

## 從實驗室到標準

1980 年 9 月 30 日，DEC、Intel 和 Xerox 共同發布了 DIX Ethernet 規範（也稱為「藍皮書」—— Ethernet Blue Book）。這是 Ethernet 的第一個公開標準，定義了 10 Mbps 的實體層和資料鏈結層。

DIX Ethernet 2.0（Ethernet II）規範的關鍵參數：
- 傳輸速率：10 Mbps
- 傳輸介質：50 歐姆 RG-8 同軸電纜（粗纜）
- 最大區段長度：500 米
- 最大節點數：100 個／區段
- 使用 CSMA/CD 協定處理碰撞

## 封包格式

DIX Ethernet 定義了至今仍在使用的 Ethernet 封包格式：前導碼（preamble, 8 bytes）、目的位址（6 bytes）、來源位址（6 bytes）、類型欄位（EtherType, 2 bytes）、資料（46-1500 bytes）、FCS 檢查碼（4 bytes）。

類型欄位（EtherType）是 Ethernet II 與後來 IEEE 802.3 格式的主要差異——它直接標示了上層協定類型（如 0x0800 代表 IPv4、0x0806 代表 ARP），而非封包長度。

## 延伸閱讀

- [Ethernet 框架 - Wikipedia](https://en.wikipedia.org/wiki/Ethernet_frame)
- [Ethernet II - IEEE 802.3 歷史](https://www.ieee802.org/3/)
