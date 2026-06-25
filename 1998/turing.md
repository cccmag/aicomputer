# 1998 年圖靈獎：Jim Gray

## 資料庫與交易處理的巨人

Jim Gray 是 1998 年 ACM 圖靈獎得主，授獎理由是「表彰他對資料庫與交易處理研究的開創性貢獻，以及他在系統實現上的卓越領導力」。

Gray 的職業生涯橫跨了資料庫領域從學術研究到商業產品的整個發展過程。他曾在 IBM、DEC、Microsoft 任職，是少數在學術界和工業界都取得頂尖成就的人。

## 交易處理的理論基礎

Gray 最重要的貢獻之一是建立了交易處理（Transaction Processing）的理論框架。他在 1970 年代與 Andreas Reuter 共同提出了 **ACID** 原則——資料庫交易的四個基本屬性：

- **原子性（Atomicity）**：交易全部完成或全部不完成
- **一致性（Consistency）**：交易前後資料庫保持一致狀態
- **隔離性（Isolation）**：並發交易的執行結果與序列化執行一致
- **持久性（Durability）**：已提交的交易結果永久保存

ACID 原則至今仍是所有關聯式資料庫的設計基石，從 Oracle 到 PostgreSQL、從 MySQL 到 SQL Server。

## Two-Phase Commit

Gray 在交易處理中的另一項關鍵貢獻是 **兩階段提交（Two-Phase Commit, 2PC）** 協定——確保分散式資料庫中跨多個節點的交易要麼全部成功，要麼全部失敗。這是分散式資料庫一致性的核心機制。

## 資料庫的系統實現

Gray 在系統實現方面貢獻卓著：

- **System R**：在 IBM 參與了第一個實作 SQL 的關聯式資料庫系統
- **DEC Data Distributor**：分散式資料庫管理系統
- **Microsoft SQL Server**：在微軟領導 SQL Server 的架構設計，使其成為企業級資料庫產品

他還是「資料庫效能基準測試」（Database Benchmark）概念的先驅，提出了評估資料庫系統效能的標準方法。

## 神秘失蹤

Jim Gray 在 2007 年 1 月 28 日獨自駕船出海後失蹤，儘管進行了大規模搜索，至今仍未找到。他的失蹤是計算機科學界的巨大損失。2012 年，ACM 授予他 inaugural ACM - AAAI Allen Newell Award 的特別追認。

## 延伸閱讀

- [Jim Gray - ACM Turing Award](https://amturing.acm.org/award_winners/gray_3649936.cfm)
- [Jim Gray - Wikipedia](https://en.wikipedia.org/wiki/Jim_Gray_(computer_scientist))
- [The Transaction Processing Concept - Jim Gray 論文](https://www.microsoft.com/en-us/research/people/gray/)
