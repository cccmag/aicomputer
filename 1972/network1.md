# Cerf 與 Kahn 開始 TCP/IP 設計

## 從夏威夷到網際網路

1972 年秋天，在夏威夷大學的一場 ALOHAnet 研討會上，兩位年輕人相遇了。Vint Cerf 剛從 UCLA 取得博士學位，正在史丹佛大學擔任助理教授。Bob Kahn 則剛被 Larry Roberts 招募到 DARPA 的 IPTO 辦公室，負責網路技術的研究。

Kahn 面臨一個棘手的問題：ARPANET 正在成長，但它的 NCP（Network Control Protocol）只適用於同質網路——所有的節點都必須是 ARPANET 的 IMP。如果要把分組無線電網路、衛星網路和 ARPANET 連接起來，NCP 完全無法勝任。

## 網路互連的構想

Kahn 在 1972 年構思了一個革命性的概念——**開放式架構網路**（open-architecture networking）。核心想法是：

1. 每個網路可以有自己的內部協定和技術
2. 網路之間透過「閘道器」（gateway）連接
3. 所有主機只需遵循一個共同的「網際網路協定」
4. 網路不保證可靠傳送——可靠性由端點主機負責

這個「端到端原則」（end-to-end principle）後來成為網際網路架構的基石。

## 合作的開始

1972 年，Cerf 和 Kahn 開始密集討論這個新的網路互連協定。Cerf 擁有 NCP 設計的豐富經驗（他在 UCLA 參與了原始的 NCP 開發），Kahn 則帶來了硬體架構和軍事通訊的視角。

他們在 1973 年初開始正式撰寫協定規格，並在 1973 年底將論文提交給 IEEE Transactions on Communications——這就是 1974 年 5 月發表的經典論文「A Protocol for Packet Network Intercommunication」。

雖然 TCP/IP 的完整規格要到 1974 年才由 RFC 675 正式定義，但**1972 年是這一切的起點**——Cerf 和 Kahn 在夏威夷研討會上的相遇，開啟了人類歷史上最重要的通訊協定設計。

## 延伸閱讀

- [Vint Cerf 與 Bob Kahn 歷史 - Computer Timeline](http://www.computer-timeline.com/timeline/vint-cerf-and-bob-kahn/)
- [TCP/IP 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite)
- [Cerf 與 Kahn TCP/IP 設計 - Google 搜尋](https://www.google.com/search?q=Vint+Cerf+Bob+Kahn+TCP+IP+1972+1973)
