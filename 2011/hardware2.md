# ARM Cortex-A15：行動處理器的飛躍

## 從手機到伺服器

2011 年，ARM 發表了 Cortex-A15 MPCore 處理器核心設計。這不僅是 ARM 架構的一次重大升級，更是 ARM 從嵌入式裝置向高效能運算領域進軍的關鍵一步。

Cortex-A15 的設計目標是「在不犧牲功耗效率的前提下，提供接近入門級筆記型電腦的運算效能」。它引入了 ARMv7-A 架構的多項新特性：支援完整硬體虛擬化（使 ARM 可以執行多個作業系統）、大實體位址擴展（LPAE，支援最多 1TB 實體記憶體）、以及先進的推測執行和分支預測。

## 技術細節

Cortex-A15 在 28nm 製程下運行於 1.0-2.5GHz，每個核心的效能約為前代 Cortex-A9 的 1.5-2 倍。它支援最多 4 核心配置，並整合了 NEON SIMD 引擎和 VFPv4 浮點單元。

最重要的變革是硬體虛擬化支援——這使得 ARM 處理器開始有能力承載伺服器級的工作負載。日後 Applied Micro、AMD 等公司推出的 ARM 伺服器晶片，其技術根源可追溯至 Cortex-A15 的架構設計。

## 行動生態的典範轉移

Cortex-A15 發表後，三星 Exynos 5250、NVIDIA Tegra 4 以及 TI OMAP 5 等晶片都採用了此核心。2011 年 ARM 架構的日益強大，與 Intel x86 在行動市場的挫折形成了鮮明對比。

## 延伸閱讀

- [ARM Cortex-A15 - Wikipedia](https://en.wikipedia.org/wiki/ARM_Cortex-A15)
- [ARM 架構歷史](https://developer.arm.com/architectures)
