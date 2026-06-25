# Hadoop：MapReduce 與大數據時代的開端

## Google 的兩篇論文

2006 年的 Hadoop 源自於 Google 的兩篇基礎性論文：
- **MapReduce（2004）**：Jeffrey Dean 和 Sanjay Ghemawat 描述了 Google 的分散式運算框架，將資料處理抽象為 Map（映射）和 Reduce（歸約）兩個階段
- **Google File System（2003）**：Sanjay Ghemawat、Howard Gobioff 和 Shun-Tak Leung 描述了 Google 的分散式檔案系統

## Doug Cutting 與 Lucene

Doug Cutting 是 Apache Lucene（全文檢索搜尋引擎函式庫）和 Apache Nutch（開源 Web 爬蟲）的創始人。在開發 Nutch 的過程中，Cutting 意識到需要一個能夠處理大規模資料的分散式計算框架。Google 的 MapReduce 和 GFS 論文給了他方向。

Cutting 決定將 Nutch 中的分散式運算元件獨立出來，創造一個「開源的 MapReduce 實作」。他的兒子當時正在玩一個黃色大象玩偶，名叫「Hadoop」——Cutting 就將這個專案命名為 Hadoop。

## Hadoop 的里程碑

2006 年，Hadoop 在 Apache 軟體基金會中從 Nutch 子專案提升為獨立的一級專案。這個時間點的核心發展包括：

- **HDFS（Hadoop Distributed File System）**：GFS 的開源實現，將大檔案分割成區塊（block，預設 64MB）並複製到多個節點
- **Hadoop MapReduce**：MapReduce 模型的開源實現，支援在數百到數千個節點上平行處理
- **Yahoo! 的採用**：Yahoo! 在 2006 年建立了第一個大規模 Hadoop 叢集，用於搜尋引擎的索引建構

## 影響

Hadoop 讓「大數據」從 Google 的專有技術變成了任何人都可以使用的開放工具。到 2008 年，Hadoop 已成為處理大量資料的事實標準，被 Yahoo!、Facebook、Twitter、LinkedIn 等公司廣泛使用。Hadoop 的生態系統（Hive、Pig、HBase、ZooKeeper、Spark 等衍生產品的基礎）後來成長為整個資料工程產業的技術基礎。
