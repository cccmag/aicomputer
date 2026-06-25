# Berkeley 4.2BSD：TCP/IP 整合入 UNIX

## 網路化的 UNIX

1983 年 8 月，柏克萊大學的 Computer Systems Research Group（CSRG）釋出了 4.2BSD——這是 BSD UNIX 發展史上最重要的一個版本。4.2BSD 的核心貢獻是內建了完整的 TCP/IP 網路協定棧。

此時 TCP/IP 剛在 1983 年 1 月 1 日被 ARPANET 正式採用，但協議棧本身的實作還非常有限。Bill Joy 在柏克萊的團隊與 BBN 合作，將 DARPA 資助開發的 TCP/IP 原始碼整合進 BSD UNIX。這使得任何執行 4.2BSD 的 VAX 或 PDP-11 機器都具備了連接網際網路的能力。

## 對網際網路的催化作用

4.2BSD 的 TCP/IP 實作的重要性在於：它讓網際網路從少數大型主機擴散到數以千計的大學校園和工作站。當時 BSD UNIX 是學術界最流行的作業系統，4.2BSD 的 TCP/IP 支援使得校園網路成為可能。

這個版本還引入了重要的網路工具和系統呼叫：socket 介面成為 Unix 網路通訊的標準 API；sendmail 郵件傳輸代理成為網際網路郵件基礎設施的核心。

## Bill Joy 與 Sun

Bill Joy 在 4.2BSD 開發期間積累的網路技術經驗，直接促成了 Sun Microsystems 的誕生。Sun 的工作站搭載 BSD UNIX，內建 TCP/IP 和 NFS（網路檔案系統），成為 1980 年代網路計算的標準平台。

## 延伸閱讀

- [Berkeley BSD - Wikipedia](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution)
- [4.2BSD 公告](https://www.tuhs.org/Archive/Distributions/UCB/)
