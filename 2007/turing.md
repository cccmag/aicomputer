# 2007 年圖靈獎：Edmund Clarke、Allen Emerson、Joseph Sifakis

## 模型檢測的誕生

2007 年的 ACM 圖靈獎頒給了三位電腦科學家：Edmund M. Clarke、E. Allen Emerson 和 Joseph Sifakis，表彰他們在模型檢測（Model Checking）領域的開創性貢獻。模型檢測是一項自動驗證有限狀態系統是否滿足特定規範的技術。

傳統的程式驗證方法依賴手工建構的數學證明，既耗時又容易出錯。模型檢測提供了一種自動化的替代方案：給定一個系統模型和一組邏輯規範，模型檢測演算法會自動檢查系統是否滿足規範。

## Clarke 與 Emerson 的開創

1981 年，當時在哈佛大學的 Edmund Clarke 與他的博士生 Allen Emerson 發表了第一篇關於模型檢測的論文——「Design and Synthesis of Synchronization Skeletons Using Branching Time Temporal Logic」。這篇論文首次提出了使用 CTL（Computation Tree Logic，計算樹邏輯）來描述系統規範，並透過圖形演算法來自動驗證系統。

Clarke 和 Emerson 的關鍵洞見是：將系統建模為有限狀態機，將規範表達為時序邏輯公式，然後透過窮舉狀態空間搜尋來檢查系統是否滿足規範。雖然狀態爆炸問題限制了它的應用範圍，但這項技術在硬體驗證中立即展現了巨大的實用價值。

## Sifakis 的獨立貢獻

Joseph Sifakis 在法國科學研究中心（CNRS）獨立開發了一套類似的模型檢測方法。他的工作聚焦於即時系統的驗證，以及模型檢測的工業化應用。Sifakis 後來共同創立了 Verimag 實驗室，並在 2008 年與他人共同創立了工具公司。

## 工業影響

模型檢測從理論概念發展為工業標準工具。硬體公司（如 Intel、IBM、AMD）使用模型檢測來驗證處理器設計的正確性。軟體公司則用於檢查協定規範、嵌入式系統和安全關鍵系統。

符號模型檢測（Symbolic Model Checking）的發明——使用二元決策圖來高效表示狀態空間——將可驗證的狀態數量從數百萬提升到了數十億。這項技術已成為晶片設計中不可或缺的一部分。

## 延伸閱讀

- [Edmund Clarke - ACM Turing Award](https://amturing.acm.org/award_winners/clarke_1167964.cfm)
- [Allen Emerson - ACM Turing Award](https://amturing.acm.org/award_winners/emerson_1241076.cfm)
- [Joseph Sifakis - ACM Turing Award](https://amturing.acm.org/award_winners/sifakis_1335702.cfm)
- [模型檢測 - Wikipedia](https://zh.wikipedia.org/wiki/%E6%A8%A1%E5%9E%8B%E6%A3%80%E6%B5%8B)
