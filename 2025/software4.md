# Meta Llama 4：開源多模態的里程碑

## Instagram 上的意外發表

2025 年 4 月 5 日，Meta CEO Mark Zuckerberg 在 Instagram 上宣布了 **Llama 4** 系列模型——這是 Llama 系列首次採用 MoE（混合專家）架構，也是 Meta 迄今為止最先進的開源 AI 模型。

## 三種型號

Llama 4 包含三個版本：

**Llama 4 Scout（170 億活躍參數 / 16 專家）**
- 業界領先的 **1000 萬 token 上下文視窗**
- 適合長文件摘要、大規模程式碼庫推理
- 單張 H100 GPU 即可運行

**Llama 4 Maverick（170 億活躍參數 / 128 專家 / 總計 4000 億參數）**
- 主力助手模型，專為對話與創作設計
- 在編碼、推理、多語言與影像基準上超越 GPT-4o 與 Gemini 2.0 Flash
- 與 DeepSeek V3.1 相當但活躍參數不到一半

**Llama 4 Behemoth（2880 億活躍參數 / 2 兆總參數 / 仍在訓練）**
- 號稱世界上最聰明的開源 LLM 之一
- 在 STEM 基準上超越 GPT-4.5、Claude 3.7 Sonnet 與 Gemini 2.0 Pro

## 原生多模態

Llama 4 是 Meta 第一個**原生多模態**的開源模型——從預訓練階段就同時處理文字與圖像（early fusion）。這讓 Llama 4 可以直接理解圖像、圖表與文件掃描，無需外掛視覺編碼器。

## 開源生態系的影響

Llama 4 的開源策略（與 DeepSeek 相同採用 MIT 授權）加劇了 AI 產業的開放與封閉路線之爭：

- Llama 4 的下載量在發布首週就超過百萬次
- 多家初創公司基於 Llama 4 開發垂直應用
- 部分國家政府開始建立基於 Llama 4 的官方 AI 系統

## 延伸閱讀

- [Llama 4 發布 - Meta AI](https://ai.meta.com/blog/llama-4-multimodal-intelligence/)
- [Llama 4 技術報告 - Meta](https://ai.meta.com/research/publications/the-llama-4-herd-of-models/)
