# GPU 運算與 NVIDIA Volta 架構

## Volta 的突破

2017 年 5 月，NVIDIA 正式發布 Volta 架構及其首款產品 Tesla V100 加速器。Volta 是 NVIDIA 深度學習加速策略的重要里程碑，專為 AI 訓練與高效能運算設計。

V100 採用 TSMC 12nm FFN 製程，整合了 210 億個電晶體，配備 5120 個 CUDA 核心和 640 個 Tensor Core。Tensor Core 是 Volta 架構的最大創新——專門用於加速深度學習訓練中的矩陣乘法運算，可提供最高 120 TFLOPS 的深度學習效能。

## Tensor Core 的意義

Tensor Core 是 NVIDIA 在 AI 加速領域的關鍵技術護城河。與標準 CUDA 核心不同，Tensor Core 在一個時脈週期內可以完成 4×4 矩陣的乘法和累加運算——這在神經網路的訓練中是最核心的計算模式。

NVIDIA CEO Jensen Huang 在 GTC 2017 上將 Volta 描述為「世界上最大的處理器晶片」，並展示了它在 ResNet-50 等基準測試中的領先表現。

## GPU 運算的產業影響

2017 年，GPU 已不僅是顯示卡，而是 AI 時代的運算核心。AWS、Azure、Google Cloud 都在這一年大規模部署了 GPU 實例。百度、Google、Facebook、Microsoft 等 AI 大廠都使用 V100 進行模型訓練。

Volta 的推出也加劇了 NVIDIA 與 AMD 在 GPU 運算市場的差距——AMD 的 Vega 架構雖然也在 2017 年推出，但在深度學習效能上顯著落後。

## 延伸閱讀

- [NVIDIA Volta 架構](https://www.nvidia.com/en-us/data-center/volta-gpu-architecture/)
- [Tesla V100 規格](https://www.nvidia.com/en-us/data-center/v100/)
