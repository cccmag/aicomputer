# CSMA/CD：乙太網路的核心協定

## 隨機存取的控制

Ethernet 的核心協定 CSMA/CD（Carrier Sense Multiple Access with Collision Detection）源自於 1970 年代早期夏威夷大學的 ALOHAnet 研究。

ALOHAnet 使用了非常簡單的協定：節點想傳就傳（random access），如果發生碰撞，就等一段隨機時間再重試。Xerox PARC 的 Robert Metcalfe 和 David Boggs 在這個基礎上增加了載波感測（先聽後說）和碰撞檢測（邊傳邊聽）的功能。

## CSMA/CD 的運作

CSMA/CD 的四個步驟：
1. **載波感測**：監聽網路，如果線路忙碌則等待
2. **多重存取**：如果線空閒則開始傳送資料
3. **碰撞檢測**：傳送過程中持續監聽，如果偵測到碰撞（訊號超過正常強度），立即停止傳送
4. **隨機重試**：發送阻塞訊號（jam signal），等待一段隨機時間（採用截斷二進制指數退避演算法），然後回到步驟 1

CSMA/CD 的優點是在低負載時延遲極低（節點幾乎不需要等待），而在高負載時也能維持穩定的效能。

## 延伸閱讀

- [CSMA/CD - Wikipedia](https://en.wikipedia.org/wiki/Carrier-sense_multiple_access_with_collision_detection)
- [ALOHAnet - Wikipedia](https://en.wikipedia.org/wiki/ALOHAnet)
