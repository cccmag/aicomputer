# DIX Ethernet：區域網路的標準化

## 三家公司聯手

1970 年代初期，Xerox PARC 的 Robert Metcalfe 在設計一個高速區域網路，最初稱為「Alto Aloha Network」。1973 年，Metcalfe 將這個系統改名為「Ethernet」，靈感來自於「ether」（以太）——一種假設的電磁波傳播介質。

到了 1980 年，Ethernet 的市場化機會成熟了。Xerox 與 DEC（Digital Equipment Corporation）和 Intel 合作，發布了 DIX Ethernet 標準——名稱來自三家公司名稱的首字母。這個版本的 Ethernet 定義了 10 Mbps 的傳輸速度、同軸電纜（粗纜，10BASE5）作為傳輸介質、最長 500 米的網路區段。

## CSMA/CD 協定

Ethernet 使用 CSMA/CD（Carrier Sense Multiple Access with Collision Detection）協定來管理網路存取。簡單來說：節點在傳送前先聽（Carrier Sense），如果沒有人傳送就傳送；如果兩個節點同時傳送導致碰撞（Collision），它們就等待一段隨機時間後重新嘗試。

DIX Ethernet 規格後來提交給 IEEE 802 委員會，經過小幅修改後成為 IEEE 802.3 標準（1983 年正式發布）。Ethernet 的成功在於其簡潔、成本效益好，而且隨著技術進步速度不斷提升——從 10 Mbps 到 100 Mbps、1 Gbps、10 Gbps 直到今天的 400 Gbps。

## 延伸閱讀

- [Ethernet - Wikipedia](https://en.wikipedia.org/wiki/Ethernet)
- [Robert Metcalfe - Wikipedia](https://en.wikipedia.org/wiki/Robert_Metcalfe)
