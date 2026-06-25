# AWS Graviton2/3：ARM 伺服器處理器的崛起

## 從 x86 到 ARM 的雲端轉變

AWS 在 2018 年推出了第一代 Graviton 處理器，但 2021 年的 Graviton2 和 Graviton3 才真正展示了 ARM 架構在雲端伺服器市場的潛力。這些處理器由 AWS 旗下的 Annapurna Labs 設計，基於 ARM 的 Neoverse 架構。

**Graviton2**（2019 年底推出，2021 年廣泛採用）基於 ARM Neoverse N1 核心，採用 7nm 製程，提供了比同類 x86 執行個體高達 40% 的性價比提升。

**Graviton3**（2021 年底發表）則基於 Neoverse V1 核心，採用 5nm 製程，在浮點運算、加密和機器學習工作負載上表現更佳。

## 採用情況

2021 年，越來越多的客戶開始在 Graviton 上運行生產工作負載：

- **Amazon 內部**：Amazon.com、Alexa、Amazon DynamoDB 和 Amazon Elasticache 等核心服務大量使用 Graviton
- **Snapchat**、**Twitter** 和 **Netflix** 等大型客戶也開始遷移
- **容器化工作負載**：Graviton 在 ECS、EKS 和 Fargate 中得到了廣泛支援

Graviton 的經濟優勢十分明顯——對於大規模雲端部署，轉向 ARM 可以節省 20-40% 的運算成本。

## ARM 生態系統的成熟

Graviton 的成功解決了 ARM 伺服器生態系統的關鍵瓶頸——軟體相容性。到 2021 年：

- 大多數 Linux 發行版已經良好支援 ARM64
- 主流語言直譯器（Python、Node.js、Ruby）和編譯器（GCC、LLVM）完全支援 ARM
- Docker 容器在 ARM64 上運行無縫
- 許多 SaaS 工具開始提供 ARM64 版本

## 產業影響

AWS Graviton 的成功鼓舞了其他 ARM 伺服器晶片的開發：Ampere Computing 推出了 80 核的 Altra 處理器，Nvidia 推出了基於 ARM 的 Grace CPU 超級晶片。ARM 伺服器的時代正在來臨。
