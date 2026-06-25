# Robert Dennard 與 DRAM 的發明

## 單電晶體記憶單元

1966 年，IBM 研究員 Robert H. Dennard 發明了動態隨機存取記憶體（DRAM）單元——以一顆電晶體和一個電容器儲存一個位元的資訊。這項專利於 1968 年提出申請（US Patent 3,387,286），成為半導體記憶體史上最重要的發明之一。

與當時佔據主導地位的磁芯記憶體和靜態 RAM（SRAM）相比，Dennard 的設計只需要一個電晶體來儲存每個位元，而 SRAM 通常需要 4 到 6 個電晶體。這使得 DRAM 能夠以遠低於 SRAM 的成本實現高密度儲存。

## 工作原理

DRAM 的運作原理相當優雅：每個記憶單元由一個 MOSFET（金屬氧化物半導體場效電晶體）和一個電容器組成。電容器儲存代表資料的電荷（有電荷代表 1，無電荷代表 0），電晶體則作為開關來控制對電容器的讀取和寫入。

然而，電容器會隨著時間漏電，因此 DRAM 需要定期「刷新」（refresh）——重新讀取並寫入每個位元以防止資料遺失。這個動態特性正是「動態 RAM」名稱的由來。

## 深遠的影響

DRAM 的發明對電腦產業產生了革命性的影響：

- **密度大幅提升**：較小的單元面積使 DRAM 可以在相同晶片面積上儲存更多資料
- **成本急遽下降**：每 bit 成本的降低使大容量主記憶體成為可能
- **標準化**：DRAM 成為電腦主記憶體的標準技術，一直沿用至今

到了 1970 年代中期，DRAM 幾乎完全取代了磁芯記憶體，成為電腦主記憶體的霸主。即使到了 2020 年代，DRAM 仍然是所有電腦、伺服器和智慧型手機中不可或缺的核心元件。

Dennard 的另一項重要貢獻是「Dennard Scaling」（丹納德縮放定律），他觀察到隨著電晶體尺寸縮小，功率密度保持不變，這項觀察主導了半導體產業數十年的發展方向。

## 延伸閱讀

- [Robert H. Dennard - IBM Research](https://en.wikipedia.org/wiki/Robert_H._Dennard)
- [DRAM 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Dynamic_random-access_memory)
- [Dennard Scaling - Wikipedia](https://en.wikipedia.org/wiki/Dennard_scaling)
