# AMD Opteron：64 位元 x86 的開端

## 歷史性的發布

2003 年 4 月 22 日，AMD 在紐約正式發表 Opteron 處理器——這是世界上第一款相容 x86 架構的 64 位元處理器。代號 Sledgehammer 的 Opteron 徹底改變了伺服器處理器的競爭格局。

Opteron 的核心創新是 AMD64 指令集擴充，它在不破壞既有 32 位元軟體相容性的前提下，增加了 64 位元運算能力。這與 Intel Itanium 採用的 EPIC 架構完全不同：Itanium 無法高效執行 32 位元程式碼，而 Opteron 可以無縫地同時執行兩種程式。

## 技術架構

Opteron 採用了數項關鍵技術：

- **整合記憶體控制器**：直接整合 DDR SDRAM 控制器於處理器核心，大幅降低記憶體存取延遲
- **HyperTransport 互連**：使用高速點對點匯流排連接處理器與 I/O 系統，取代傳統的前端匯流排
- **直連架構**：多處理器系統中每個 CPU 都可以直接存取自己的記憶體，再透過 HyperTransport 存取其他 CPU 的記憶體

## 市場影響

Opteron 的發布讓 AMD 首次在高利潤的伺服器市場站穩腳跟。IBM 在發布當天即宣布將推出 Opteron 伺服器，Microsoft 也承諾開發 64 位元版本的 Windows Server 2003。Opteron 的成功最終迫使 Intel 在 2004 年跟進 x86-64 指令集（Intel 稱之為 EM64T），終結了 Itanium 成為唯一 64 位元 x86 路徑的企圖。
