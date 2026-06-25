# Elasticsearch 的開發：全文檢索的現代化

## 從 Compass 到 Elasticsearch

2009 年，Shay Banon——一位居住在倫敦的軟體工程師——開始開發 Elasticsearch。Banon 原本在開發一個名為 Compass 的搜尋引擎庫（基於 Apache Lucene），但他對 Compass 的複雜性和架構限制感到不滿。

Elasticsearch 的設計目標是解決 Lucene 和 Compass 的關鍵問題：設定過於複雜、部署困難、缺乏分散式支援、以及 API 不夠友善。Banon 決定從頭開始建立一個全新的搜尋引擎——一個可以透過 RESTful API 進行分散式全文檢索的系統。

## 架構創新

Elasticsearch 的技術架構融合了幾項關鍵技術選擇：

**基於 Lucene**：底層使用 Apache Lucene 作為索引引擎——Lucene 是當時最成熟、效能最高的全文檢索庫。Elasticsearch 在 Lucene 之上提供了分散式管理、叢集協調和 REST API。

**JSON 與 RESTful API**：所有操作——索引、搜尋、管理——都是透過 HTTP RESTful API 進行的，請求和回應使用 JSON 格式。這讓任何程式語言都可以輕鬆使用 Elasticsearch。

**分散式架構**：Elasticsearch 原生支援分散式部署——資料自動分片、複製和負載平衡。叢集可以從一個節點無縫擴展到數百個節點。

**近即時搜尋**：文件被索引後，幾乎立即就可以被搜尋到——通常在 1 秒內。

## 對搜尋和日誌分析產業的影響

Elasticsearch 後來成為了 ELK Stack（Elasticsearch、Logstash、Kibana）的核心，徹底改變了日誌分析和全文檢索的市場。2010 年代，Elasticsearch 成為了最受歡迎的企業搜尋引擎之一。

## 延伸閱讀

- [Elasticsearch - Wikipedia](https://zh.wikipedia.org/wiki/Elasticsearch)
- [Elasticsearch 歷史](https://www.elastic.co/blog/foundation-of-elastic)
- [Apache Lucene](https://lucene.apache.org/)
