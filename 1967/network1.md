# ARPANET 的設計文件：Larry Roberts 在 SOSP 的提案

## 從概念到藍圖

1967 年 10 月，在田納西州加特林堡的 SOSP 會議上，Larry Roberts 發表了題為「Multiple Computer Networks and Intercomputer Communication」的論文。這是 ARPANET 的第一份完整系統設計文件。

Roberts 在論文中解釋了為什麼要把電腦連結成網路：讓一台電腦的使用者能夠呼叫遠端系統來執行程式，從而共享稀有的計算資源。這個概念在當時是革命性的——大多數人仍然認為電腦是孤立的裝置。

## IMP 概念的提出

會議中一個關鍵的技術決策來自 Wesley Clark。Clark 建議不要讓主機電腦直接互連，而是使用一種專用的迷你電腦來處理網路通訊。這些電腦後來被稱為 IMP（Interface Message Processor，介面訊息處理器）。

這個設計決策至關重要：它將網路功能從主機電腦中解放出來，讓不同型號、不同作業系統的電腦都可以加入網路，只需要各自連接一個 IMP 即可。

## 與 Davies 的相遇

在 SOSP 會議上，Roberts 遇到了英國國家物理實驗室的 Roger Scantlebury——Donald Davies 團隊的一員。Scantlebury 介紹了他們在分組交換（packet switching）方面的研究工作。Roberts 立刻意識到，Davies 的分組交換正是 ARPANET 需要的核心技術。

這次偶然的相遇改變了網際網路的歷史走向。

## 延伸閱讀

- [Larry Roberts 與 ARPANET](https://www.livinginternet.com/i/ii_roberts.htm)
- [SOSP 1967 論文](https://researchr.org/publication/sosp-1967)
- [分組交換歷史 - Wikipedia](https://zh.wikipedia.org/wiki/%E5%88%86%E7%BB%84%E4%BA%A4%E6%8D%A2)
