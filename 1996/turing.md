# 1996 年圖靈獎：Amir Pnueli

## 時序邏輯與程式驗證的先驅

Amir Pnueli 是 1996 年 ACM 圖靈獎得主，授獎理由是「開創性地將時序邏輯（Temporal Logic）引入計算機科學，以及對程式驗證與系統認證的重大貢獻」。

Pnueli 是以色列計算機科學家，在魏茨曼科學研究所度過大部分職業生涯。他的博士背景是數學（1967 年，魏茨曼科學研究所），但他在 1970 年代轉向計算機科學後，做出了改變整個領域的貢獻。

## 時序邏輯的引入

Pnueli 在 1977 年發表了劃時代的論文「The Temporal Logic of Programs」。在這篇論文中，他首次將哲學與數理邏輯中的時序邏輯應用於電腦程式的推理。

時序邏輯的核心創新在於：傳統邏輯只能描述「什麼為真」（what is true），而時序邏輯可以描述「什麼最終會變為真」（what will eventually be true）以及「什麼始終為真」（what is always true）。這對於描述並發系統的行為至關重要。

Pnueli 引入的關鍵運算子包括：
- **□ (always)**：某命題總是成立
- **◇ (eventually)**：某命題最終會成立
- **○ (next)**：某命題在下一個狀態成立
- **U (until)**：某命題一直成立直到另一個命題成立

## 程式驗證的革命

Pnueli 的工作將程式驗證從靜態的輸入輸出規範擴展到動態的行為規範。這對於以下領域尤其重要：

- **並發系統**：多執行緒程式的死鎖檢測
- **即時系統**：飛機控制、醫療設備等時間關鍵系統
- **通訊協定**：網路協定的正確性驗證

他的研究成果催生了模型檢驗（Model Checking）這個完整的驗證領域—— Edmund Clarke、E. Allen Emerson 和 Joseph Sifakis 因此獲得了 2007 年的圖靈獎。

## 影響與遺產

Pnueli 的時序邏輯已成為計算機科學的標準工具：
- 硬體設計中廣泛使用時序邏輯規範
- 軟體工程中的形式化方法（Formal Methods）以時序邏輯為基礎
- 時序邏輯被整合進多種程式語言和設計工具

Pnueli 獲獎後繼續活躍於研究前沿，直到 2009 年去世。

## 延伸閱讀

- [Amir Pnueli - ACM Turing Award](https://amturing.acm.org/award_winners/pnueli_4725172.cfm)
- [Amir Pnueli - Wikipedia](https://en.wikipedia.org/wiki/Amir_Pnueli)
- [時序邏輯 - Wikipedia](https://zh.wikipedia.org/wiki/%E6%97%B6%E5%BA%8F%E9%80%BB%E8%BE%91)
