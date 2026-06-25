# Knuth 的《程式設計藝術》：電腦科學的聖經

## 一本書的誕生

1968 年，Addison-Wesley 出版了 Donald Knuth 的《The Art of Computer Programming, Volume 1: Fundamental Algorithms》。這本 634 頁的巨著原本只是 Knuth 計畫中的「一本書」，但隨著寫作過程的推進，它擴展成了七卷的系列——至今仍在陸續出版中。

1962 年，還是加州理工學院研究生的 Knuth 被 Addison-Wesley 邀請撰寫一本關於編譯器設計的書。他提出了一個更宏大的計劃：以十二個章節涵蓋整個電腦程式設計的理論基礎。這個計劃後來就成了 TAOCP。

## 內容與方法

第一卷的主題包括：

- 演算法的基本概念（什麼是演算法、數學歸納法、漸進分析）
- 數學基礎（數論、排列組合、斐波那契數列、生成函數）
- MIX 虛擬計算機：Knuth 設計了一台教學用電腦 MIX，所有演算法都用 MIX 組合語言實作。這讓讀者可以在不依賴特定硬體的情況下學習程式設計的底層原理。
- 資訊結構（堆疊、佇列、鏈結串列、樹、垃圾回收）

每一章節都附有大量精心設計的習題，從簡單的練習題到尚未解決的研究問題不等。Knuth 為習題設計了難度評級系統，並為所有習題提供了解答（至少暗示）。

## 對程式設計方法的影響

TAOCP 的出版意義深遠。在 1968 年以前，程式設計大多被視為一種實用技術，缺乏系統性的理論基礎。Knuth 的書第一次將演算法分析——預測程式的執行時間和記憶體使用量——建立在嚴格的數學基礎上。

Knuth 對於演算法的分析方法——包括大 O 符號的系統使用、平均情況與最壞情況的分析、生成函數在演算法分析中的應用——成為了電腦科學的標準工具。

## 與結構化程式的對話

值得注意的是，Knuth 對 go to 語句的態度比 Dijkstra 溫和。他在 1974 年的論文「Structured Programming with go to Statements」中論證，在某些情況下（如跳出多重迴圈、錯誤處理），go to 可以提高程式的可讀性和效率。這種務實的態度——追求程式碼的清晰而不是教條地遵守規則——也影響了一代程式設計師。

## 延伸閱讀

- [TAOCP 官方網站 - Stanford](https://cs.stanford.edu/~knuth/taocp.html)
- [The Art of Computer Programming - Wikipedia](https://zh.wikipedia.org/wiki/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BC%96%E7%A8%8B%E8%89%BA%E6%9C%AF)
- [Donald Knuth - Wikipedia](https://zh.wikipedia.org/wiki/%E9%AB%98%E5%BE%B7%E7%BA%B3)
