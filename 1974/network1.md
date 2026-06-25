# TCP/IP 的誕生：Cerf 與 Kahn 的里程碑論文

## 網路互連的問題

1970 年代初期，世界上的電腦網路各自為政。ARPANET 使用 NCP（Network Control Protocol），其他網路如夏威夷的 ALOHAnet、挪威的 SATNET 等各有不同的協定和封包格式。這些網路之間無法互相通訊。

Vint Cerf 和 Bob Kahn 在 1973 年開始合作解決這個問題。Kahn 當時在 DARPA 的 IPTO 工作，想要連接 ARPANET、PRNET（封包無線電網路）和 SATNET（衛星網路）。Cerf 正在史丹福大學任教。他們的核心問題是：如何讓不同網路之間可以交換資料，即使它們使用完全不同的硬體、協定和封包大小？

## 1974 年 5 月的論文

1974 年 5 月，Cerf 和 Kahn 在《IEEE Transactions on Communications》上發表了題為「A Protocol for Packet Network Intercommunication」的論文。這篇論文描述了傳輸控制協定（TCP）的原始設計，引入了幾個劃時代的概念：

**閘道器（Gateway）**：連接不同網路的中間設備，負責在不同網路之間轉發封包。

**資料報（Datagram）**：一個自包含的封包單位，包含目的地位址，可以被獨立路由。這個概念受到了 Louis Pouzin 在法國 CYCLADES 網路中設計的 datagram 概念的影響。

**TCP 訊息**：資料報內承載的內容，由傳輸控制協定負責確保可靠傳送。

論文中還探討了分段（fragmentation）、重組（reassembly）、流量控制（flow control）、錯誤檢查等重要議題。

## 從 TCP 到 TCP/IP

1974 年描述的 TCP 後來在 1978 年被拆分為 TCP 和 IP 兩個協定，形成了現代網際網路的基礎。1983 年 1 月 1 日，ARPANET 正式從 NCP 切換到 TCP/IP，這一天被視為網際網路的誕生日。

## 延伸閱讀

- [Cerf & Kahn 論文全文](https://www.cs.princeton.edu/courses/archive/fall06/cos561/papers/cerf74.pdf)
- [TCP/IP 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
- [Vint Cerf 與 Bob Kahn - IEEE 里程碑](https://ieeemilestones.ethw.org/Milestones:Transmission_Control_Protocol_(TCP)_and_the_Architecture_of_the_Internet,_1974)
