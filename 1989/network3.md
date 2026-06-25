# FDDI：光纖分散式資料介面

## 100 Mbps 的骨幹技術

1989 年，ANSI 標準化了一個稱為 FDDI（Fiber Distributed Data Interface，光纖分散式資料介面）的網路技術。FDDI 使用光纖作為傳輸介質，提供 100 Mbps 的頻寬——這在當時是一個巨大的飛躍。

FDDI 使用雙環（dual-ring）拓撲結構：兩個光纖環以相反方向傳輸資料。當其中一個環故障時，系統可以在 100 毫秒內自動切換到另一個環。這種容錯設計使 FDDI 成為當時骨幹網路建設的首選方案。

## 技術特性

FDDI 的主要技術參數包括：

- **傳輸速率**：100 Mbps
- **最大節點數**：500 個（每個環）
- **環路長度**：最長 100 公里
- **傳輸介質**：多模或單模光纖
- **存取方法**：記號環（Token Ring）協議

FDDI 使用記號傳遞（token passing）機制來控制存取——網路上只有持有特殊「記號」的節點才能發送資料，從而避免了碰撞問題。

## FDDI 與 Ethernet 的競爭

1989 年，FDDI 是高速骨幹網路的主要技術選項，而此時 Ethernet 主流還是 10Base5 和 10Base2 的 10 Mbps 速度。FDDI 的 100 Mbps 對需要高效能的校園網路和企業骨幹極具吸引力。

然而，FDDI 的價格非常昂貴——網路界面卡和光纖佈線的成本遠高於 Ethernet。當 100 Mbps 的 Fast Ethernet（1995）和 Gigabit Ethernet（1998）出現後，FDDI 逐步被淘汰。

雖然 FDDI 在商業上最終沒能站穩腳跟，但它的雙環容錯設計影響了後續的 SONET/SDH 光纖網路標準。

## 延伸閱讀

- [FDDI - Wikipedia](https://en.wikipedia.org/wiki/Fiber_Distributed_Data_Interface)
- [ANSI FDDI 標準 - Google 搜尋](https://www.google.com/search?q=FDDI+1989+standard+100+Mbps)
- [光纖網路歷史 - Wikipedia](https://en.wikipedia.org/wiki/Fiber-optic_communication)
