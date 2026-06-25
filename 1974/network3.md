# PRNET：封包無線電網路的開端

## 無線的分組交換

1974 年，DARPA 啟動了 PRNET（Packet Radio Network）計畫，由 Bob Kahn 推動。PRNET 的目的是將分組交換的概念延伸到無線通訊環境中，讓移動中的車輛和野戰部隊能夠透過無線電波傳送資料封包。

PRNET 是 Kahn 的網路互連願景中的關鍵一環。他的目標是建立一個能夠跨越有線網路（ARPANET）、無線網路（PRNET）和衛星網路（SATNET）的統一架構——這個願景最終催生了 TCP/IP。

## 技術挑戰

PRNET 面臨的有線網路完全不同的挑戰：

- **隱藏終端問題**：兩個無線電站可能無法直接偵測到對方，但都在同一個基地台的範圍內
- **碰撞偵測困難**：無線電環境中不像乙太網路那樣可以可靠地偵測碰撞
- **頻寬有限**：早期的封包無線電速度只有 100-400 kbit/s
- **節點移動**：網路拓撲會因為節點的移動而持續變化

PRNET 使用 ALOHA 協定的變體來解決通道存取問題，並引入了一系列新的路由和協定設計。

## 影響與遺產

PRNET 的經驗對 TCP/IP 的設計產生了深遠的影響。Kahn 和 Cerf 在設計 TCP 時，特別考慮了無線網路的需求——包括封包遺失、延遲變化和動態路由等問題。

PRNET 的技術後來演變為 1980 年代和 1990 年代的各種無線資料網路，並間接影響了現代的 Wi-Fi 和行動通訊網路設計。

## 延伸閱讀

- [PRNET 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Packet_Radio_Network)
- [DARPA 網路研究歷史 - Google 搜尋](https://www.google.com/search?q=PRNET+DARPA+1974+packet+radio+network)
- [ALOHA 協定 - Wikipedia](https://en.wikipedia.org/wiki/ALOHAnet)
