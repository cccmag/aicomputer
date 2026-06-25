# ALOHAnet 對網路設計的啟發

## 夏威夷的無線網路

1968 年，夏威夷大學的 Norman Abramson 和 Franklin Kuo 開始設計一個獨特的通訊系統——用無線電波將分散在夏威夷各島嶼上的電腦連接起來。這個系統在 1971 年正式啟用，稱為 ALOHAnet。

ALOHAnet 的設計面臨一個根本性挑戰：在無線環境中，不像有線網路那樣可以精確控制誰在什麼時候發送資料。多個終端機可能同時傳送，造成碰撞（collision）。

## 隨機存取的革命

Abramson 的解決方案在今天看來簡單而優雅：**隨機重傳**。當一個節點有資料要發送時，它就直接發送。如果發生了碰撞（發送節點在一段時間內沒有收到確認），就等待一個隨機的時間間隔後重試。

這個協定被稱為 **ALOHA**（或純 ALOHA）。它與 ARPANET 採用的分組交換截然不同——ARPANET 的 IMP 之間使用精確的時序控制來避免碰撞，而 ALOHA 則用統計方法來處理衝突。

1972 年，ALOHA 的效率被改良為**時槽 ALOHA**（Slotted ALOHA）：將時間劃分為固定長度的時槽，節點只能在時槽開始時傳送。這將最大通道利用率從 18%（純 ALOHA）提升到 37%。

## 對 Ethernet 和 TCP/IP 的影響

ALOHAnet 的隨機存取概念具有深遠的影響：

**Ethernet**（1973 年，Xerox PARC）：Bob Metcalfe 在改良 ALHOA 的基礎上設計了 CSMA/CD（載波偵聽多重存取／碰撞偵測），解決了 ALOHA 的效率問題。

**TCP/IP**：Cerf 和 Kahn 在 1972 年的 ALOHAnet 研討會上相遇，直接促成了 TCP/IP 的設計。TCP 的擁塞控制和重傳機制，從根源上借鑒了 ALOHA 的隨機重傳概念。

1972 年正是這些思想交匯的關鍵時刻：ALOHAnet 不僅證明了無線分組網路的可行性，也為後來網際網路的兩個核心技術——Ethernet 和 TCP/IP——提供了理論基礎。

## 延伸閱讀

- [ALOHAnet - Wikipedia](https://en.wikipedia.org/wiki/ALOHAnet)
- [Norman Abramson - Wikipedia](https://en.wikipedia.org/wiki/Norman_Abramson)
- [ALOHA 網路歷史 - Google 搜尋](https://www.google.com/search?q=ALOHAnet+1971+1972+Norman+Abramson)
