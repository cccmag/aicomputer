# 2014 年圖靈獎：Michael Stonebraker

## 資料庫系統的革命者

2014 年 ACM 圖靈獎頒給了 Michael Stonebraker，表彰他「對現代資料庫系統的底層概念和實作做出的基礎性貢獻」。

Stonebraker 於 1943 年出生於麻薩諸塞州，在普林斯頓大學取得學士學位，在密西根大學取得博士學位。他於 1974 年加入加州大學柏克萊分校，在那裡開始了他對資料庫系統的終身研究。

## Ingres

Stonebraker 的第一個重大貢獻是 Ingres（Interactive Graphics and Retrieval System）資料庫。Ingres 起源於 1970 年代中期的一項柏克萊大學研究計畫，旨在探索關聯式資料庫的實際應用。

Ingres 引入了多項重要的資料庫技術：查詢分解（query decomposition）——將複雜查詢分解為多個簡單查詢；基於成本的查詢最佳化（cost-based query optimization）——根據資料分布統計選擇最有效率的執行計畫；以及 ACID（原子性、一致性、隔離性、持久性）交易模型。

Ingres 在 1980 年代被商業化為 Ingres Corporation，與 IBM 的 DB2 和 Oracle 的資料庫展開競爭。雖然 Ingres 的商業成功有限，但它催生了大量後續資料庫系統。

## PostgreSQL

Ingres 的後繼者是更加著名的 PostgreSQL。Stonebraker 在 1986 年啟動了 Postgres（Post-Ingres）計畫，目標是建立一個支援「物件導向」功能的關聯式資料庫。

Postgres 引入了規則系統（rule system）、過程語言（procedural language）、使用者自訂型別（user-defined types）和時間旅行查詢（time-travel queries）等創新概念。1996 年，Postgres 更名為 PostgreSQL，以反映其 SQL 支援的成熟度。

PostgreSQL 於 1996 年以 BSD 授權開源，成為全球最受歡迎的開源關聯式資料庫之一。它的影響力涵蓋了學術研究、商業應用和雲端基礎設施。

## 後續貢獻

Stonebraker 對資料庫的貢獻遠不止 Ingres 和 PostgreSQL。他在 2000 年代後期仍持續發表創見，包括：
- **C-Store**（2005）：一個基於列式儲存的關聯式資料庫，後被商業化為 Vertica
- **H-Store**（2007）和 **VoltDB**：記憶體式 OLTP 資料庫，舍棄了磁碟導向的設計假設
- **SciDB**：專為科學資料設計的陣列資料庫

Stonebraker 在 2014 年與其博士生 Samuel Madden 共同獲得了圖靈獎。他的學術遺產不僅包括資料庫系統的技術貢獻，還包括他培養的一代資料庫研究者和開發者。他曾說：「資料庫系統是電腦科學中最接近工程的領域——我們建造的是真實的、可運行的系統。」

## 延伸閱讀

- [Michael Stonebraker - ACM Turing Award](https://amturing.acm.org/award_winners/stonebraker_1172121.cfm)
- [Michael Stonebraker - Wikipedia](https://en.wikipedia.org/wiki/Michael_Stonebraker)
- [Ingres 資料庫歷史](https://en.wikipedia.org/wiki/Ingres_(database))
