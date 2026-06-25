# Cell 處理器設計：Sony/Toshiba/IBM 合作

## 史無前例的合作

2002 年 4 月 2 日，IBM、Sony、Sony Computer Entertainment 和 Toshiba 正式簽署了多年度合作協議，共同開發先進的半導體技術。這項合作的核心是代號「Cell」的處理器架構設計。

三家公司的分工合作模式在當時是創新的：

- **Sony**（特別是 SCEI）：提出未來互動娛樂的運算需求願景，目標是達到 PlayStation 2 效能的 100 倍
- **IBM**：提供先進的 SOI（絕緣層上矽）製程技術、銅導線技術和 Power 處理器架構
- **Toshiba**：貢獻系統晶片（SoC）設計經驗和高量產製造能力

## 技術挑戰

Cell 的設計目標極為大膽：

- 使用 90 奈米 SOI 製程，晶片特徵尺寸小至 50 奈米
- 開發 300 mm 晶圓的製造工藝
- 在單一晶片上整合處理器、記憶體和通訊功能
- 實現「teraflops」級別的運算效能
- 功耗和成本要適合消費電子產品

## 異質多核心架構

Cell 的架構在當時是革命性的：

**Power 核心（PPE）**：一個 64 位元的 Power 架構通用處理核心，負責作業系統和系統管理

**協同處理器（SPE）**：8 個專為浮點數運算優化的協同處理核心，每個都具有自己的本地儲存（Local Store）和 DMA 引擎

**元件互連匯流排（EIB）**：一個高速的環狀匯流排，連接所有核心和記憶體控制器，提供超高的內部頻寬

## 商業意義

Cell 合作計畫的總投資超過 4 億美元，在德州奧斯汀設立了聯合設計中心，匯集了超過 400 名工程師。這項計畫最終產出了用在 PlayStation 3（2006 年）中的 Cell 處理器，以及用於超級電腦領域的衍生產品。

## 延伸閱讀

- [Toshiba 新聞稿 - Cell 合作 (2002)](https://www.global.toshiba/ww/news/corporate/2002/04/pr0201.html)
- [Cell 處理器 - Wikipedia](https://en.wikipedia.org/wiki/Cell_(microprocessor))
