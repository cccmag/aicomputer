# NCP 的設計：第一個主機間通訊協議

## 需要一個共同語言

ARPANET 的核心挑戰是：如何讓不同型號、不同作業系統的電腦互相通訊？UCLA 使用 SDS Sigma 7（運行獨有的作業系統），SRI 使用 SDS 940（運行 GENIE 分時系統），UCSB 使用 IBM 360/75（運行 OS/360），猶他大學使用 DEC PDP-10（運行 TENEX）。

這些系統的字組大小、字元編碼、檔案系統、I/O 機制都完全不同。要使它們能夠交換資料，需要一個共同的「語言」——也就是協議。

## Network Working Group 的工作

1968 年至 1969 年間，Network Working Group（NWG）——主要由 Crocker、Postel、Carr、Rulifson 等研究生組成——在多次會議中逐步設計了這個協議。

他們的設計哲學是務實的：先做出簡單可用的東西，再逐步改進。最初的協議設計只解決最基本的問題：

**連線建立（Connection Establishment）**：一個主機如何發起與另一個主機的通訊？NWG 設計了透過 IMP 的「link 0」進行連線協商的機制。主機 A 透過 link 0 發送「連線請求」給主機 B，B 同意後分配一個新的鏈路號碼進行數據傳輸。

**資料傳輸（Data Transfer）**：一旦連線建立，資料被分割成訊息（message）進行傳輸。每條訊息最多 8,080 bits，再加上 16 bits 的標頭。

**流量控制（Flow Control）**：使用 RFNM 機制——每條鏈路上最多只能有一個未確認的訊息。

## NCP 的演進

1969 年，NWG 的設計還在早期階段。真正的 NCP（Network Control Program）要到 1970 年才被最終確定並在 1970 年 12 月部署。但在 1969 年，NWG 已經確立了關鍵的設計方向：

- 對稱式主機-主機協議（symmetric host-host protocol）
- 基於連線的服務（connection-oriented service）
- 流量控制與錯誤恢復
- 多工多個連線到單一硬體介面

這些設計決策深刻地影響了後來 TCP（Transmission Control Protocol）的設計。事實上，RFC 1 中描述的連接建立機制——使用 IMP 的 link 機制——是 TCP 連線建立的概念前身。

## 協議疊代的範例

NWG 的開發過程是協議設計的典範。他們不是一次性設計出完整的協議，而是透過 RFC 文件不斷疊代：

- RFC 1（1969年4月）：初始概念
- RFC 36（1970年3月）：協議註釋
- RFC 54（1970年6月）：正式規範
- 1970 年 12 月：NCP 在 ARPANET 上部署

這種疊代式、開放參與的協定設計方法，成為了後來 IETF 的標準工作模式。

## 延伸閱讀

- [NCP - Wikipedia](https://en.wikipedia.org/wiki/Network_Control_Protocol_(ARPANET))
- [RFC 6529 - 歷史回顧](https://datatracker.ietf.org/doc/html/rfc6529)
- [ARPANET 協議如何運作](https://twobithistory.org/2021/03/08/arpanet-protocols.html)
