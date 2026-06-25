# Pentium Pro 處理器：P6 架構的誕生

## 第一個 P6 產品

1995 年 11 月 1 日，Intel 發表了 Pentium Pro 處理器，代號「P6」。這是第一個基於 P6 微架構的產品——這個架構後來被用於 Pentium II、III、M 和 Core 系列處理器，成為 Intel 最具影響力的架構之一。

Pentium Pro 的時脈版本包括 150、166、180 和 200 MHz。它包含 550 萬個電晶體，每秒可執行 4.4 億條指令（MIPS）。這是 Intel 的第一個純 32 位元處理器，完全移除了 16 位元相容模式。

## 架構創新

Pentium Pro 引入了多項關鍵技術：

**超標量執行**：每個時脈週期可以發射最多 5 條指令，並透過亂序執行引擎優化指令流。

**動態執行**：處理器可以在執行期間重新排序指令，以充分利用執行單元。Intel 稱之為「動態執行技術」，包括：
- 多重分支預測
- 資料流分析
- 推測執行

**三路叢集式快取**：L2 快取封裝在同一個卡匣中，與處理器緊密耦合。雖然不是整合在晶粒上，但透過專用匯流排連接，大大減少了延遲。

## 32 位元的純粹主義

Pentium Pro 的設計目標是 32 位元伺服器和工作站。它在 16 位元程式碼上的效能反而低於原來的 Pentium——這是一個策略判斷失誤，因為 Windows 95 的大量應用仍然是 16 位元的。Intel 後來在 Pentium II 中修正了這個問題。

## 延伸閱讀

- [Pentium Pro - Wikipedia](https://en.wikipedia.org/wiki/Pentium_Pro)
- [P6 微架構 - Wikipedia](https://en.wikipedia.org/wiki/P6_\(microarchitecture\))
- [Intel 處理器歷史 - Intel](https://www.intel.com/content/www/us/en/history/history-of-intel-processors.html)
