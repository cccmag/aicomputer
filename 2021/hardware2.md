# Intel 12th Gen Alder Lake：大小核混合架構

## 突破性的架構設計

2021 年 10 月 27 日，Intel 正式發表了第 12 代 Core 處理器——代號 Alder Lake——這是 x86 處理器歷史上最具革命性的設計之一。Alder Lake 採用了「Performance-core + Efficient-core」混合架構（類似 ARM 的 big.LITTLE），將高性能核心（P-cores，代號 Golden Cove）與高效率核心（E-cores，代號 Gracemont）整合在單一晶片上。

P-cores 針對單執行緒和延遲敏感的工作負載進行了優化，而 E-cores 則擅長處理多執行緒背景任務。Intel Thread Director 技術智慧地將任務分配給合適的核心類型——這項技術是 Intel 與 Microsoft 共同開發的，需要 Windows 11 的支援。

## 具體規格

旗艦型號 Core i9-12900K 擁有 8 個 P-core（16 執行緒）+ 8 個 E-core（8 執行緒），總計 16 核 24 執行緒。在單核性能上，Alder Lake 重新奪回了對 AMD Ryzen 5000 的領先優勢——多核性能也因 E-core 的加入而大幅提升。

## 製程和新平台

Alder Lake 採用了 Intel 7 製程（此前稱為 10nm Enhanced SuperFin）——雖然不是命名上的最新製程，但實際性能提升顯著。

新平台支援：
- **LGA 1700 插座**：散熱器安裝孔距改變
- **DDR5 記憶體**和 **PCIe 5.0**：率先支援下一代記憶體和擴展標準
- **DDR4 相容**：部分主機板同時支援 DDR4，方便過渡

## 深層意義

Alder Lake 的混合架構代表了 Intel 在製程領先不再時的設計創新。它證明了即使沒有最先進的製程，透過創新的架構設計仍然可以實現競爭優勢。這種混合設計在後續的 Raptor Lake（第 13 代）中得到了完善和擴展。
