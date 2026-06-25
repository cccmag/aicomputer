# Google Edge TPU：邊緣 AI 的硬體方案

## Cloud TPU 到 Edge TPU

2018 年，Google 在 Cloud Next 大會上宣布了 Edge TPU（Tensor Processing Unit）——一個專為邊緣裝置設計的專用 ASIC 晶片，用於在裝置端執行機器學習推論。

Edge TPU 是 Google TPU 家族的一員——Cloud TPU v2 和 v3 在 2017-2018 年用於資料中心的訓練，而 Edge TPU 則關注於推論效率和功耗。它的功耗僅約 2 瓦，但可以提供 4 TOPS（每秒兆次運算）的 INT8 推論效能。

## 邊緣運算的硬體生態

Edge TPU 不僅是一個晶片，而是一個完整的邊緣 AI 平台：

- **Coral Dev Board**：內建 Edge TPU 的開發板
- **Coral USB Accelerator**：USB 介面的 Edge TPU 加速器
- **Coral Camera**：與 Edge TPU 整合的攝影機模組

這個生態簡化了從模型訓練（使用 TensorFlow）到邊緣部署的流程——開發者可以在 Cloud TPU 或 GPU 上訓練模型，然後量化並部署到 Edge TPU 上執行。

## 產業意義

Edge TPU 的推出代表了 AI 硬體從雲端向邊緣的擴展趨勢。在製造業的視覺檢測、零售業的智慧分析、醫療影像等場景中，邊緣推論可以實現低延遲、離線運作和更好的資料隱私。

Edge TPU 的競爭對手包括 NVIDIA Jetson（GPU 方案）和 Intel Movidius（VPU 方案）。三者在功耗、效能的目標有所不同——Edge TPU 在極低功耗場景下具有優勢。

## 延伸閱讀

- [Google Edge TPU 介紹](https://cloud.google.com/edge-tpu)
- [Coral 平台](https://coral.ai/)
