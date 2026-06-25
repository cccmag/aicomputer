# Google 的開始：PageRank 與搜尋革命

## BackRub 研究專案

1997 年，史丹佛大學的博士生 Larry Page 和 Sergey Brin 開始了一個名為「BackRub」的研究專案。他們正在研究網頁之間的連結結構——並很快發現了一個重要的模式：網頁可以透過被其他網頁連結的次數來評定重要性。

BackRub 的目標是建立一個更好的搜尋引擎。當時的搜尋引擎（Altavista、Lycos、Excite）主要依賴關鍵詞匹配——搜尋結果中充斥著關鍵詞堆砌的垃圾頁面。

## PageRank 的核心洞察

PageRank 的基本原則是：
- 將網頁 A 到網頁 B 的超連結視為 A 對 B 的「投票」
- 來自高權重（高 PageRank）網頁的投票權重更高
- 投票權重會隨著投票者的被投票數而遞迴定義

數學上，PageRank 可以用特徵向量（eigenvector）來描述——這讓 Google 從一開始就與其他搜尋引擎有著本質上的不同。

Page 和 Brin 在 1998 年發表了著名的論文「The Anatomy of a Large-Scale Hypertextual Web Search Engine」，發表在第七屆 WWW 會議上。

## 史丹佛大學的環境

史丹佛大學在 Google 的誕生過程中扮演了關鍵角色：
- 提供伺服器硬體（Page 和 Brin 使用了校園內的多台工作站）
- 允許使用教育網路的頻寬進行網頁爬取
- 提供專利申請的法律協助
- 支持技術轉移（後來以 180 萬美元出售 PageRank 專利給 Google）

## 延伸閱讀

- [PageRank - Wikipedia](https://en.wikipedia.org/wiki/PageRank)
- [BackRub - Google](https://about.google/)
- [The Anatomy of a Large-Scale Hypertextual Web Search Engine - Stanford](http://infolab.stanford.edu/~backrub/google.html)
