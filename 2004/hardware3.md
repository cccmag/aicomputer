# ARM Cortex 架構：行動晶片的新起點

## ARM11 與 Cortex 的過渡

2004 年，ARM 公司發表了 Cortex 架構，取代了經典的 ARM11 系列。Cortex 分為三個子系列：Cortex-A（應用處理器）、Cortex-R（即時處理器）、Cortex-M（微控制器）。這個分類反映了 ARM 意識到不同市場需要針對性最佳化的核心設計。

Cortex-A8 是第一個 Cortex-A 系列核心，採用了新的 ARMV7-A 指令集。與 ARM11 相比，Cortex-A8 引入了：
- 雙重管線的超純量設計（dual-issue superscalar）
- NEON SIMD 單元（多媒體加速）
- TrustZone 安全擴充
- 13 級整數管線和 10 級向量管線

## 技術突破

Cortex-A8 的核心面積僅約 4mm²，功耗低於 300mW，但效能足以與低階 x86 處理器競爭。這使得它成為智慧型手機和平板電腦的理想選擇。ARM 的授權商業模式讓多家半導體公司（德州儀器、三星、飛思卡爾等）可以生產 Cortex-A8 晶片，形成了一個龐大的生態系統。

## 深遠影響

Cortex 架構的推出時機恰到好處——兩年後 iPhone 問世，再兩年後 Android 開始普及。Cortex-A8 成為第一代 iPhone（2007 年使用 Samsung S5L8900 晶片）和早期 Android 手機的核心。可以說，2004 年的 Cortex 架構為後來十年行動運算的爆炸式成長提供了引擎。

Cortex-M 系列則在嵌入式領域產生了巨大影響——從智慧型手錶到家電，從感測器到工業控制，Cortex-M 處理器的出貨量最終達到了數百億顆。
