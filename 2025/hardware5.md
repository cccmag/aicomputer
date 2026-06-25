# Google Ironwood TPU：第六代 AI 加速器

## Hot Chips 2025 的發表

2025 年 8 月的 Hot Chips 研討會上，Google 發表了第六代 TPU——**Ironwood**。這是 Google 為訓練與推理新一代 AI 模型（特別是 Gemini 3）而設計的超大規模 AI 加速器。

## 規格與效能

Ironwood 的規模驚人：

- **雙晶片設計**：首次使用兩個計算晶片，FP8 運算達 4614 TFLOPS
- **8 組 HBM3E 記憶體堆疊**：192 GiB 容量、7.3 TB/s 頻寬
- **9216 顆 Ironwood 晶片互通**：透過光學電路交換器（OCS）共享記憶體
- **共享 HBM 記憶體容量**：1.77 PB
- **42.5 Exaflops ML 運算**（FP8 精度）
- **每瓦效能比前代提升 2 倍**
- **第三代液冷散熱基礎設施**：超過 1GW 的生產經驗

## 架構創新

Ironwood 引入了多項重要的架構創新：

- **第四代 Sparsecore**：用於嵌入層（embedding）與集合通訊（collectives）卸載
- **邏輯修復（Logic Repair）**：提升良率
- **AI 輔助 ALU 電路設計**：使用 AI 優化電路布局
- **動態電壓頻率調節**：最佳化每瓦效能
- **內建信任根（iROT）**：安全計算支援
- **沉默資料損壞（SDC）緩解機制**

## Google Cloud 的部署

Ironwood 將在 Google Cloud 上提供服務。Google 表示多個 Ironwood 超級運算單元（superpod）可透過擴展（scale-out）達到 **Zettaflops 等級**的運算能力。

## 延伸閱讀

- [Google Ironwood - Hot Chips 2025](https://hc2025.hotchips.org/assets/program/conference/day2/61_Google_Ironwood-Final.pdf)
- [Google TPU 發展 - Google Cloud](https://cloud.google.com/tpu)
