# 2008 年圖靈獎：Barbara Liskov

## 資料抽象的先驅

2008 年的 ACM 圖靈獎頒給了 Barbara Liskov——她是繼 2006 年的 Frances Allen 之後，第二位獲得圖靈獎的女性。授獎理由是「對程式語言與系統設計的理論與實務基礎的貢獻，特別是在資料抽象、容錯和分散式計算方面的開創性工作」。

Barbara Liskov 在 1968 年獲得了史丹佛大學的電腦科學博士學位——她是美國第一批獲得電腦科學博士學位的女性之一。她的博士論文「A Program to Play Chess Endgames」研究了西洋棋殘局的演算法。

## CLU：抽象資料類型的實現

Liskov 最著名的貢獻是在 1970 年代領導開發了 CLU 程式語言。CLU 引入了「抽象資料類型」（Abstract Data Type）的概念——將資料結構與操作封裝在一起，外部只能透過定義好的介面來存取。

今天我們視為理所當然的許多概念——類別（class）、泛型（generics）、迭代器（iterator）、例外處理（exception handling）——都可以追溯到 CLU 的設計。CLU 不是最受歡迎的語言，但它對後來語言（Java、C++、C#、Python）的影響至深。

## Liskov 替代原則

Liskov 還提出了計算機科學中最著名的設計原則之一——Liskov 替代原則（Liskov Substitution Principle, LSP）：

> 「如果 S 是 T 的子類型，那麼任何使用 T 型別物件的程式都可以被 S 型別的物件替代，而不會改變該程式的任何期望屬性。」

簡單來說：子類別應該可以被父類別取代而不破壞程式的正確性。例如，如果一個函式接受「矩形」物件，那麼傳入「正方形」物件也應該正常工作——這意味著正方形不應該繼承自矩形（如果在矩形中我們可以獨立改變長和寬）。

## 分散式系統的基礎

Liskov 在 MIT 還領導了分散式計算研究，設計了 Argus 系統——一個支援分散式程式的程式語言與執行環境。Argus 引入了原子交易（atomic transactions）的概念來處理分散式容錯，影響了後來的分散式資料庫和雲端計算系統。

## 延伸閱讀

- [Barbara Liskov - ACM Turing Award](https://amturing.acm.org/award_winners/liskov_1108679.cfm)
- [Barbara Liskov - Wikipedia](https://zh.wikipedia.org/wiki/%E5%B7%B4%E8%8A%AD%E6%8B%89%C2%B7%E5%88%A9%E6%96%AF%E7%A7%91%E5%A4%AB)
- [CLU 程式語言](https://en.wikipedia.org/wiki/CLU_(programming_language))
