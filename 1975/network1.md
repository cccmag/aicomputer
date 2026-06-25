# Ethernet 的誕生：區域網路的基礎

## Metcalfe 的博士論文

1973 年，Bob Metcalfe 在哈佛大學的博士論文中描述了一種新的區域網路通訊技術——乙太網路（Ethernet）。1975 年，Xerox 為乙太網路申請了專利，Metcalfe、David Boggs、Chuck Thacker 和 Butler Lampson 被列為發明人。

Metcalfe 當時在 Xerox PARC 工作，他需要一種方式將 PARC 的 Alto 工作站連接到雷射印表機和彼此之間。他從夏威夷的 ALOHAnet 網路獲取靈感——ALOHA 是一種無線電封包交換網路，使用隨機存取通道的技術。

## Ethernet 的技術核心

最初的乙太網路以 3 Mbps 的速度在同軸電纜上運作，採用 CSMA/CD（載波感知多重存取／碰撞偵測）的協定：

- **載波感知**：傳送前先聽一下，如果線路上有資料傳輸就等待
- **碰撞偵測**：傳送過程中監聽線路，如果檢測到碰撞則停止並等待隨機時間後重試

這種設計既簡單又優雅——所有的節點共享同一條電纜，不需要中央控制器，每個節點自行協調。

## 為什麼叫 Ethernet

Metcalfe 取名「乙太網路」是基於 19 世紀物理學中假想的「乙太」（以太，Ether）概念——一種充滿所有空間、傳播光波的介質。在 Metcalfe 的類比中，同軸電纜就是傳送資料的「乙太」。

有趣的是，Xerox 最初對乙太網路並不熱衷。他們認為「網路」不是一個有潛力的商業領域，更關注雷射列印和辦公室自動化。直到 1979 年，Xerox 才聯合 DEC 和 Intel 將乙太網路標準化。

## 延伸閱讀

- [Ethernet 歷史 - Wikipedia](https://zh.wikipedia.org/wiki/%E4%B8%80%E5%88%87%E6%9E%B6%E6%9E%84)
- [Bob Metcalfe - Wikipedia](https://en.wikipedia.org/wiki/Robert_Metcalfe)
- [Ethernet 專利與發明 - Google 搜尋](https://www.google.com/search?q=Ethernet+invention+Metcalfe+1975)
