# Nvidia Kepler GPU 架構

## GPU 運算的飛躍

2012 年 3 月，Nvidia 發表了 Kepler 架構（代號 GK104），這是 GeForce 600 系列的基礎。Kepler 是 Fermi 架構的後繼者，在效能和功耗效率上實現了巨大飛躍。

Kepler 的設計哲學與 Fermi 截然不同。Fermi 專注於高效能運算，在 GPU 中加入了完整的快取層次結構和 ECC 記憶體支援，代價是電晶體數量龐大。Kepler 則回到遊戲效能的優先考量，同時大幅改善每瓦效能。

## SMX 核心

Kepler 引入了 SMX（Streaming Multiprocessor）核心設計。每個 SMX 包含 192 個 CUDA 核心，是 Fermi SM 的 6 倍。GK104 總共有 8 個 SMX，合計 1,536 個 CUDA 核心。

SMX 的設計實現了更高的核心密度和更好的功耗效率。GeForce GTX 680 的 TDP 僅為 195W，與上代 GTX 580（244W）相比大幅降低，但效能提升約 30-40%。

## GPU Boost 技術

Kepler 引入了 GPU Boost 技術——一種動態時脈調整機制。在 GPU 溫度允許的範圍內，系統會自動提高核心時脈以獲得最大效能。這是 GPU 領域第一次引入類似 Intel Turbo Boost 的動態超頻機制。

## 延伸閱讀

- [Nvidia Kepler - Wikipedia](https://en.wikipedia.org/wiki/Kepler_(microarchitecture))
- [Nvidia GPU 架構歷史](https://www.nvidia.com/en-us/about-nvidia/corporate-timeline/)
