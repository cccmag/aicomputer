# TCP/IP 三網路連線：網際網路的誕生

## 麵包車的歷史之旅

1977 年 11 月 22 日，一個下雨的星期三，SRI 的 Packet Radio Van 行駛在舊金山灣區的公路上。車上的 LSI-11 電腦透過無線電網路發送資料——這些資料跨越了 ARPANET、SATNET 和 PRNET 三種截然不同的網路，最終抵達南加州大學的資訊科學研究所。

這是人類歷史上第一次成功的**三網路 TCP 連線**。許多歷史學家認為這才是真正的「網際網路誕生日」，因為網際網路的本質就是多個網路的互連（inter-networking）。

## 資料的路徑

資料從麵包車上的無線電節點出發：
1. 經 **PRNET（分組無線電網路）** 到 SRI Menlo Park
2. 轉入 **ARPANET** 到 BBN（波士頓）
3. 經海底電纜越洋到挪威
4. 再到倫敦大學學院
5. 經 **SATNET（衛星分組網路）** 跨大西洋回到美國
6. 最後經 ARPANET 到達 USC/ISI

整個路徑經過了三種網路、五大洲以上、超過 35 人參與。

## TCP 的勝利

這次測試證明了 TCP 協議可以無縫地跨越異質網路——有線、無線、衛星——而不需要底層網路做任何修改。這是「端到端原則」的第一次大規模實證。

## 延伸閱讀

- [Packet Radio Van - Wikipedia](https://en.wikipedia.org/wiki/Packet_Radio_Van)
- [三網路測試 - SRI](https://www.sri.com/hoi/internetworking/)
