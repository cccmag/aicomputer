# Nvidia Blackwell Ultra B300 與 Rubin 路線圖

## GTC 2025 的硬體盛宴

2025 年 3 月 18 日，Nvidia CEO 黃仁勳在 GTC 2025 上發表了新一代 GPU 路線圖，覆蓋了從 2025 年到 2028 年的硬體規劃。最主要的發布是 Blackwell 架構的升級版——**Blackwell Ultra（B300）**。

## Blackwell Ultra B300

Blackwell Ultra 基於 Blackwell 架構的中期升級：

- **記憶體大幅提升**：HBM3e 從 192 GB（B200）增加到 288 GB，採用 12 層堆疊（12-Hi）
- **FP4 密集運算提升 50%**：相較於 GB200
- **GB300 NVL72 機櫃系統**：72 顆 Blackwell Ultra GPU + 36 顆 Grace CPU，提供 1.5 倍於 GB200 NVL72 的 AI 效能
- **HGX B300 NVL16**：LLM 推理速度比 Hopper 世代快 11 倍
- **Dynamo 推理框架**：開源推理服務軟體，最大化 AI 工廠的 token 收益

## Vera Rubin 架構 (2026)

Nvidia 預告了 2026 年的新一代架構 **Vera Rubin**：

- **Vera CPU**：88 個自訂 Arm 核心、176 執行緒
- **Rubin GPU**：每顆 50 petaflops FP4 推理效能
- **HBM4 記憶體**：288 GB，頻寬比 Blackwell Ultra 提升 62.5%
- **NVLink 6**：260 TB/s 總頻寬
- **Vera Rubin NVL144 系統**：3.6 exaflops FP4 效能

## 2027-2028 的遠景

- **Rubin Ultra（2027）**：4 晶片設計、1 TB HBM4e 記憶體、15 exaflops FP4、NVLink 7
- **Feynman（2028）**：以物理學家 Richard Feynman 命名，採用下一代 HBM 記憶體

## 延伸閱讀

- [Blackwell Ultra 發布 - Nvidia Newsroom](https://nvidianews.nvidia.com/news/nvidia-blackwell-ultra-ai-factory-platform-paves-way-for-age-of-ai-reasoning)
- [Nvidia GTC 2025 主題演講 - Nvidia](https://www.nvidia.com/gtc/)
