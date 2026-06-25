# Ethernet 的發明：5 月 22 日的備忘錄

## 從 ALOHA 到 Ethernet

1972 年，Bob Metcalfe 在哈佛大學攻讀博士學位時，讀到了 Norman Abramson 關於 ALOHAnet 的論文。他意識到 ALOHA 的隨機存取協定雖然效率不高（最大通道利用率只有 18%），但背後的概念——多個節點共享同一條通訊通道——具有巨大的潛力。

1973 年，Metcalfe 在 Xerox PARC 工作。PARC 內已經有數十台 Alto 電腦，但沒有任何方式可以讓它們互相通訊或共享即將問世的雷射印表機。Metcalfe 的任務是：設計一個高速區域網路，讓所有 Alto 能夠連接到雷射印表機。

## 5 月 22 日備忘錄

1973 年 5 月 22 日，Metcalfe 撰寫了一份名為「**Alto Ethernet**」的備忘錄。這份備忘錄包含了一張粗糙的示意圖，描述了 Ethernet 的基本架構：

- 使用**同軸電纜**（coaxial cable）作為共享傳輸媒介
- 採用**CSMA/CD**（載波偵聽多重存取／碰撞偵測）協定
- 裝置在傳送前先「偵聽」通道是否空閒
- 如果發生碰撞（兩個裝置同時傳送），等待隨機時間後重試

Metcalfe 將這個系統命名為「Ethernet」，靈感來自 19 世紀物理學的「光以太」（luminiferous ether）概念——一種假想的、充滿宇宙的電磁波傳播介質。Ethernet 意味著這個網路可以跨越任何傳輸媒介。

## 第一次運作

1973 年 11 月 11 日，Ethernet 首次實際運作。第一條 Ethernet 連線以 2.94 Mbps 的速度運行，連接了 PARC 內的 Alto 電腦。這個速度在當時是驚人的——比 ARPANET 的 56 Kbps 線路快了將近 53 倍。

Ethernet 解決了 ALOHAnet 的效率問題：在傳送前先偵聽通道（carrier sense），大幅減少了碰撞的機率。同時，如果發生碰撞，偵測機制（collision detection）讓裝置可以立即停止傳送並重試，而不是像 ALOHA 那樣等待一段時間才發現。

## Ethernet 的遺產

1973 年的備忘錄──加上 Metcalfe、David Boggs、Butler Lampson 和 Charles Thacker 在 1975 年申請的專利（US 4,063,220）——奠定了區域網路的基礎。Metcalfe 在 1979 年離開 Xerox 創立了 3Com，致力於 Ethernet 的商業化和標準化。

Ethernet 從最初的 2.94 Mbps（1973）發展到 10 Mbps（1980 年標準化）、100 Mbps（1995）、1 Gbps（1999）、10 Gbps（2002），直到今日的 400 Gbps。它是史上最成功、最長壽的網路技術之一。

## 延伸閱讀

- [Ethernet 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Ethernet)
- [Bob Metcalfe - Wikipedia](https://en.wikipedia.org/wiki/Robert_Metcalfe)
- [Ethernet 發明歷史 - Google 搜尋](https://www.google.com/search?q=Bob+Metcalfe+Ethernet+1973+May+22)
