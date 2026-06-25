# 羅伯斯與馬里爾：合作式網路的藍圖

## 第一篇分時電腦網路論文

1966 年 10 月，Lawrence G. Roberts 和 Tom Marill 在 Fall AFIPS Conference 上發表了題為「Toward a Cooperative Network of Time-Shared Computers」的論文，記錄了他們在電腦網路領域的早期實驗。

這篇論文的重要性在於，它首次描述了如何透過撥接線路將兩台分時電腦連結起來——這在當時是一個激進的概念。大多數電腦仍然是批次處理系統，使用者透過打孔卡片提交工作，數小時後才能拿到結果。分時系統已經算是前衛，而將分時系統互相連結則是一個更大的跳躍。

## 實驗的成果

Roberts 和 Marill 在 MIT 林肯實驗室的 TX-2 電腦上進行了實驗。他們成功地將 TX-2 透過撥接電話線連接到其他電腦，實現了初步的遠端存取。雖然速度很慢，可靠性也有待改善，但他們證明了這個概念是可行的。

這項實驗為後來的 ARPANET 提供了重要的技術依據和經驗教訓。Roberts 在論文中探討了：

- 如何處理不同電腦之間的資料格式差異
- 如何在不可靠的電話線路上確保資料傳輸的正確性
- 如何設計網路協定來管理連線

## Arden-Galler-Westervelt 論文

同一年，Arden、Galler、Westervelt 和 O'Brien 發表了另一篇對網路發展至關重要的論文：「Program and Addressing Structure in a Time-Sharing Environment」（JACM，1966 年 1 月）。

這篇論文概述了使用動態位址轉譯（DAT）來實現虛擬記憶體的架構，而虛擬記憶體是分時系統能夠安全地隔離不同使用者程式、同時讓它們共享記憶體的關鍵技術。這項工作直接影響了 IBM System/360 Model 67 的設計，而 360/67 上的分時系統（如 MTS）後來成為 ARPANET 早期發展的重要平臺。

## 分時與網路的交會

1966 年的這兩篇論文——一篇關於電腦網路，另一篇關於分時系統的虛擬記憶體——共同描繪了未來運算的圖景：多個使用者透過終端機存取遠端電腦，而這些電腦之間又透過網路互相連接、共享資源。這正是現代雲端運算的最早藍圖。

## 延伸閱讀

- [Lawrence Roberts 論文 - Living Internet](https://www.livinginternet.com/i/ii_roberts.htm)
- [Toward a Cooperative Network of Time-Shared Computers - AFIPS 1966](https://www.google.com/search?q=%22Toward+a+Cooperative+Network+of+Time-Shared+Computers%22+1966)
- [IBM System/360 Model 67 - Wikipedia](https://en.wikipedia.org/wiki/IBM_System/360_Model_67)
