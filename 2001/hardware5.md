# IBM Cell 處理器合作計畫啟動

## 三方合作

2001 年 3 月 12 日，Sony Computer Entertainment、IBM 和 Toshiba 正式宣布合作研發代號為「Cell」的全新晶片架構。這項合作的三方各自貢獻了核心能力：

- **SCEI**：提供對互動娛樂和寬頻應用的深刻理解
- **IBM**：提供先進的半導體技術和電腦架構設計能力
- **Toshiba**：提供系統 LSI 和高量產製造經驗

三方共同投資超過 4 億美元，在德州奧斯汀設立了 STI 設計中心。

## 技術願景

Cell 的設計目標極為大膽——打造一顆「超級電腦單晶片」（supercomputer-on-a-chip），目標效能達到 PlayStation 2 的 100 倍以上。

Cell 的核心是一個 64 位元的 Power 架構處理器核心，加上多個「協同處理器」（Synergistic Processor Elements, SPE）。這些 SPE 是專為資料密集型運算優化的高效能核心，擅長浮點數運算和多媒體處理。

## 設計理念

Cell 的架構體現了幾個重要的設計理念：

**異質多核心**：不同類型的核心（通用核心 + 專用核心）協同工作，各自負責最擅長的任務。

**頻寬優先**：Cell 設計了高效的環狀匯流排（Element Interconnect Bus），提供超高的內部資料頻寬，確保各個核心之間的資料流通不形成瓶頸。

**寬頻網路概念**：Cell 從設計之初就考慮了寬頻網路的需求——每顆 Cell 晶片都可以透過高速介面與其他 Cell 晶片連接。

## 後續發展

Cell 處理器最終被用於 PlayStation 3（2006 年）、IBM 的 Cell 工作站和超級電腦（如 Roadrunner——2008 年成為全球第一台突破 Petaflops 的超級電腦）。Cell 的設計理念——異質多核心、專用加速器——影響了後來 GPU 通用計算和 SoC 設計的發展方向。

## 延伸閱讀

- [Cell 處理器 - Wikipedia](https://en.wikipedia.org/wiki/Cell_(microprocessor))
- [IBM Cell 處理器文檔](https://www-306.ibm.com/chips/techlib/techlib.nsf/products/Cell)
