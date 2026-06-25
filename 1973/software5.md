# 結構化程式設計的普及

## Dijkstra 的呼聲

1968 年 Edsger Dijkstra 的〈GOTO 陳述被認為有害〉引發了程式設計界的激烈辯論。到了 1973 年，這場辯論已經從學術爭論轉變為實際的程式設計實踐。結構化程式設計——使用順序、選擇（if-then-else）和反覆（do-while）三種基本控制結構來組織程式——開始成為主流。

## 結構化程式設計的核心原則

1973 年，瑞士計算機科學家 Niklaus Wirth 在〈ACM Computing Surveys〉上發表了一篇影響深遠的論文「系統化程式設計」（Systematic Programming），進一步將 Dijkstra 的理念系統化。Wirth 提出了「逐步求精」（stepwise refinement）的方法論：從高層次的問題描述開始，逐步細化到可執行的程式碼。每一步都只引入少量的新細節，程式的正確性可以透過逐步驗證來確保。

同年，Wirth 正在發展他的程式語言 Pascal。Pascal 從設計上就強制結構化——它沒有 GOTO 陳述，所有的控制結構都是結構化的。這讓 Pascal 成為結構化程式設計教學的理想工具。

## 對硬體的影響：THE 系統的啟示

Dijkstra 在 THE 系統中使用的分層架構（hierarchical layering）不僅影響了作業系統設計，也影響了硬體設計。1973 年，越來越多的系統設計者意識到：分層抽象（layer abstraction）是管理複雜性的關鍵工具，無論這個複雜性來自軟體還是硬體。

Alto 的微程式架構也體現了類似的思想——在微碼層上實現處理器指令集，讓軟體層（作業系統和應用程式）可以忽略底層的硬體細節。

## 結構化程式設計的批評與遺產

結構化程式設計並非沒有批評者。一些程式設計師（特別是系統程式設計師）認為，完全禁止 GOTO 會導致不必要的複雜性——某些情況下（如錯誤處理、中斷服務常式）GOTO 是最自然的方式。

但無論如何，1973 年的結構化程式設計運動奠定了一個重要的共識：**程式碼首先是給人讀的，其次才是給機器執行的**。這個理念——以及從中發展出來的程式碼審查（code review）、團隊程式設計（egoless programming）等實踐——最終定義了現代軟體工程的專業標準。

## 延伸閱讀

- [結構化程式設計 - Wikipedia](https://en.wikipedia.org/wiki/Structured_programming)
- [Niklaus Wirth - Wikipedia](https://en.wikipedia.org/wiki/Niklaus_Wirth)
- [結構化程式設計歷史 - Google 搜尋](https://www.google.com/search?q=structured+programming+1973+Dijkstra+Wirth)
