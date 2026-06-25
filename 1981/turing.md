# 1981 年圖靈獎：Edgar Codd

## 關聯式資料庫之父

Edgar F. Codd（Ted Codd）是 1981 年 ACM 圖靈獎得主，授獎理由是「對資料庫管理系統的理論與實踐的基礎與持續貢獻」。

Codd 1914 年出生於英格蘭的波特蘭島，在牛津大學學習數學和化學。二戰期間他在皇家空軍擔任飛行員。戰後他前往美國，在 IBM 工作。1960 年代他在 IBM 聖荷西研究實驗室開發了關聯式資料庫模型。

## 1970 年的開創性論文

1970 年，Codd 在《ACM Communications》上發表了「A Relational Model of Data for Large Shared Data Banks」——這是資料庫領域史上最重要的論文之一。

Codd 提出將資料以**關係**（relation，即表／table）的形式儲存：

- 每個關係由一個**表頭**（屬性名稱）和一組**元組**（tuple，即行／row）組成
- 資料操作透過**關聯式代數**（relational algebra）進行——包括選擇（σ）、投影（π）、聯集（∪）、差集（−）、笛卡兒積（×）和更名（ρ）等運算
- 使用者無需關心資料的實體儲存方式——只需要透過高階查詢語言操作邏輯結構

## Codd 的後續工作

Codd 在 1971 年提出了關聯式代數和關聯式微積分——查詢語言的數學基礎。這些工作直接影響了 SQL（Structured Query Language）的設計，也為後來所有的關聯式資料庫管理系統提供了理論框架。

Codd 對「真正的關聯式」非常執著——他定義了 12 條規則（Codd's 12 rules）來判斷一個資料庫系統是否真的關聯式。他對市面上一些不完全實作關聯式的產品（包括 IBM 自己的早期產品）提出了尖銳的批評。1985 年，他離開 IBM，與他人共同創立了關聯式資料庫公司。

## 延伸閱讀

- [Edgar F. Codd - ACM Turing Award](https://amturing.acm.org/award_winners/codd_1000892.cfm)
- [Edgar F. Codd - Wikipedia](https://en.wikipedia.org/wiki/Edgar_F._Codd)
- [關聯式模型 - Wikipedia](https://en.wikipedia.org/wiki/Relational_model)
