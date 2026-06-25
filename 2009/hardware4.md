# 多核心與 GPU 運算的整合

## CPU 與 GPU 的界線模糊

2009 年是異質運算（Heterogeneous Computing）概念開始崛起的一年。傳統上，CPU 是通用處理器，GPU 是專用於圖形渲染的處理器。但隨著 GPU 的可程式化能力不斷增強，越來越多的人開始思考：為什麼不把 GPU 用於非圖形的通用運算？

Nvidia 在 2007 年推出了 CUDA（Compute Unified Device Architecture）平台，讓開發者可以使用 C 語言在 GPU 上撰寫通用程式。2009 年，CUDA 已經進入了第二個版本，支援雙精度浮點數、3D 紋理、以及更完善的除錯工具。

## GPGPU 的應用突破

GPGPU（General-Purpose computing on Graphics Processing Units）在 2009 年找到了幾個重要的應用場域：

**科學運算**：分子動力學模擬（如 NAMD）、天體物理學模擬、氣候模型——GPU 可以將某些計算加速數十倍。

**金融建模**：蒙地卡羅模擬和風險分析——華爾街開始大量採購配備 Tesla GPU 的伺服器。

**影像處理**：Photoshop 開始利用 GPU 來加速濾鏡和效果處理。

## AMD 的 ATI Stream 與 OpenCL

Nvidia 的 CUDA 是封閉的——只能在 Nvidia GPU 上執行。2009 年，AMD 推出了 ATI Stream 技術，而 Apple 提出了 OpenCL（Open Computing Language）標準——一種可以在 CPU、GPU 和其他處理器上執行的異質運算框架。

OpenCL 被提交到 Khronos Group 成為業界開放標準。2009 年 8 月，Apple 在 Mac OS X Snow Leopard 中首次加入了 OpenCL 支援。這代表 GPU 運算不再受限於單一廠商——任何支援 OpenCL 的裝置都可以用於通用運算。

## 延伸閱讀

- [CUDA - Wikipedia](https://zh.wikipedia.org/wiki/CUDA)
- [OpenCL - Wikipedia](https://zh.wikipedia.org/wiki/OpenCL)
- [GPGPU 歷史](https://en.wikipedia.org/wiki/General-purpose_computing_on_graphics_processing_units)
