# DDR4 記憶體標準化

## 下一代記憶體的到來

2014 年 9 月，JEDEC 固態技術協會正式發布 DDR4 SDRAM 標準。DDR4 是第四代雙倍資料率同步動態隨機存取記憶體，旨在取代自 2007 年就已服役的 DDR3。

DDR4 的主要規格進步包括：
- **更高的資料傳輸率**：DDR4 的標準速度從 1600 MT/s 起跳，最高可達 3200 MT/s
- **更低的工作電壓**：從 DDR3 的 1.5V 降至 1.2V，功耗降低約 35%
- **更大的容量**：DDR4 單顆晶片容量可達 16 Gb（DDR3 最大為 8 Gb）

## 技術創新

DDR4 引入了多項架構改進。其中最重要的是**銀行群組**（Bank Group）架構。傳統的 DDR3 記憶體銀行是對稱的，而 DDR4 將銀行劃分為多個群組，每個群組可以獨立存取。這使得記憶體控制器可以同時發送多個指令到不同的銀行群組，大幅提升了資料吞吐量。

DDR4 還加入了**偽開端**（Pseudo-Open Drain）I/O 技術，取代了 DDR3 的波端子（SSTL）介面，進一步降低了功耗。

## 產業過渡

DDR4 從標準制定到廣泛採用經歷了數年的過渡期。2014 年 Intel 的 Haswell-E 處理器（HEDT 平台）率先支援 DDR4，但主流市場的轉移直到 2015 年 Skylake 處理器上市後才開始。到 2010 年代末期，DDR4 已成為記憶體市場的絕對主流。

## 延伸閱讀

- [DDR4 SDRAM - Wikipedia](https://en.wikipedia.org/wiki/DDR4_SDRAM)
- [JEDEC DDR4 標準](https://www.jedec.org/standards-documents/docs/jesd79-4)
