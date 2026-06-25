# Intel Nehalem 架構：從 Core 到新世代

## 微架構的革新

2007 年，Intel 開始展示 Nehalem 微架構——Core 2 世代處理器的後繼者，也是 Intel 自 2006 年 Core 架構以來最大的一次設計更新。Nehalem 於 2008 年正式量產，但它的設計概念與技術細節在 2007 年就已公開。

Nehalem 最重大的變革是將記憶體控制器整合到處理器核心中。在此之前，記憶體控制器位於北橋晶片組，處理器存取記憶體必須通過前端匯流排（FSB）。整合記憶體控制器（IMC）大幅降低了記憶體延遲，並引入了三通道 DDR3 記憶體支援。

## QuickPath Interconnect

Nehalem 引入了 QuickPath Interconnect（QPI）來取代傳統的前端匯流排。QPI 是一種點對點高速序列互連技術，類似於 AMD 的 HyperTransport。每條 QPI 鏈路提供高達 25.6 GB/s 的雙向頻寬，並支援多處理器系統的無縫擴展。

## 超執行緒回歸

Nehalem 重新引入了超執行緒技術（Hyper-Threading）——這項技術曾在 Pentium 4 中使用過，但在 Core 架構中被取消。在 Nehalem 中，每個核心可以同時執行兩個執行緒，使四核心處理器在作業系統看來有八個邏輯處理器。搭配 Turbo Boost 技術——在散熱與功耗允許的情況下自動提升核心時脈——效能顯著提升。

## 延伸閱讀

- [Nehalem 架構 - Wikipedia](https://en.wikipedia.org/wiki/Nehalem_(microarchitecture))
- [Intel Nehalem 詳細介紹 - AnandTech](https://www.anandtech.com/show/2594)
