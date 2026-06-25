# 1991 年圖靈獎：Robin Milner

## LCF、ML 與 CCS 三冠王

Robin Milner（1934-2010）是 1991 年 ACM 圖靈獎得主，獲獎理由是「三項獨立而完整的成就：1) LCF——邏輯可計算函數的機械化，可能是第一個基於理論且實用的機器輔助證明工具；2) ML——第一個包含多型型別推斷和型別安全例外處理機制的語言；3) CCS——一套通用的並發理論。」

這三項貢獻橫跨了程式語言、形式驗證和並發計算理論三大領域，每一項都足以讓一個人獲得圖靈獎。

## LCF：機器輔助證明

1970 年代初期，Milner 在史丹佛人工智慧實驗室工作時，開始開發 LCF（Logic of Computable Functions）系統。LCF 是 Dana Scott 的邏輯可計算函數理論的機械化實作——一個讓使用者可以在電腦上構建和驗證形式證明的工具。

LCF 的核心創新是「定理」資料型別——只有在遵守邏輯推理規則的情況下才能產生這種型別的物件。這意味著任何一個 Theorem 物件的存在都代表一個有效的證明。這種「邏輯核心」的設計至今仍然是證明輔助工具的標準方法。

## ML：元語言

為了實作 LCF，Milner 需要一個適合處理符號運算和邏輯推理的語言。他設計了 ML（Meta Language，元語言），作為 LCF 系統的「金屬語言」。

ML 引入了兩項開創性的技術：
- **多型型別推斷**（polymorphic type inference）：程式設計師不需要宣告型別，編譯器會自動推斷。這是 Hindley-Milner 型別系統的核心——它在表達力和型別安全性之間取得了完美的平衡。
- **型別安全的例外處理**：在型別系統中整合了例外處理機制。

ML 後來發展為 Standard ML（SML）和 OCaml 等語言，其型別系統影響了 Haskell、Rust 和 Swift 等現代語言。

## CCS：通訊系統演算

1980 年，Milner 發表了《A Calculus of Communicating Systems》（CCS），建立了一套描述和分析並發系統的數學理論。CCS 將並發系統中的通訊視為基本運算，並引入了「觀測等價」（observational equivalence）的概念——兩個系統如果從外部觀察者的角度無法區分，它們就是等價的。

CCS 後來延伸為 π-演算（π-calculus），成為行動並發系統的標準理論框架。Milner 的並發理論深刻影響了程式語言設計、通訊協定驗證和分散式系統的研究。

## 圖靈獎演講

Milner 在 1993 年發表的圖靈獎演講〈Elements of Interaction〉中，探討了從順序計算到互動計算的範式轉移。他論證說，隨著分散式系統和並發系統的重要性日益增加，計算機科學需要一套以「互動」為核心的基礎理論——而不僅僅是傳統的函數式計算模型。

## 延伸閱讀

- [Robin Milner - ACM Turing Award](https://amturing.acm.org/award_winners/milner_1569367.cfm)
- [Robin Milner - Wikipedia](https://en.wikipedia.org/wiki/Robin_Milner)
- [ML 語言歷史](https://en.wikipedia.org/wiki/ML_(programming_language))
