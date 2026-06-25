# Edgar Codd 的關聯式資料庫模型

## 問題的本質

1970 年，IBM 聖荷西研究實驗室的 Edgar F. Codd 在《Communications of the ACM》上發表了一篇 12 頁的論文：「A Relational Model of Data for Large Shared Data Banks」。

當時的資料庫系統主要使用兩種模型：層次模型（IBM 的 IMS）和網路模型（CODASYL 規範）。這兩種模型都要求程式設計師透過指標導航來存取資料——應用程式必須知道資料的物理結構。Codd 認為這是一個根本性的缺陷：使用者的資料檢視應該與儲存方式無關。

## 關聯式模型的數學基礎

Codd 提出用數學中的「關係」（relation）概念來組織資料。一個關係本質上就是一張由行（tuple）和列（attribute）組成的表格：

```
Employee(Name, Dept, Salary)
Smith    | Sales | 50000
Jones    | Eng   | 60000
```

Codd 定義了一組關聯式運算——選擇（select）、投影（project）、連結（join）等——形成了一個完整的關聯式代數（relational algebra）。他的關鍵洞察是：查詢應該描述「想要什麼」而不是「如何取得它」。

## 資料獨立性

Codd 論文的中心概念是「資料獨立性」（data independence）：應用程式不應該因為資料的內部表示改變而受影響。這在當時是一個革命性的想法——IBM 自己的 IMS 團隊最初對這個模型不屑一顧，因為 IMS 已經是一個商業成功的產品。

## 對未來的影響

Codd 的論文直到 1970 年代末才開始產生實際影響，但一旦落地，就徹底改變了資料庫產業。System R（IBM）、Ingres（Berkeley）和 Oracle 等系統將關聯式模型轉化為實際產品。SQL 語言成為標準查詢語言，時至今日仍是資料管理的基石。Codd 在 1981 年獲得圖靈獎。

## 延伸閱讀

- [Codd 的關聯式模型論文 - ACM](https://dl.acm.org/doi/10.1145/362384.362685)
- [Edgar F. Codd - Wikipedia](https://en.wikipedia.org/wiki/Edgar_F._Codd)
