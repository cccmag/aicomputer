# Stable Diffusion 開源：AI 繪圖的民主化

## 從 DALL-E 到 Stable Diffusion

2022 年，文字生成圖像的 AI 技術迎來了爆發。DALL-E 2 在 4 月由 OpenAI 推出，Midjourney 在 7 月進入公開測試——但真正改變遊戲規則的，是 2022 年 8 月 22 日由 Stability AI 發布的 Stable Diffusion。

Stable Diffusion 的與眾不同在於它是**開源的**——模型權重被公開釋出，任何人都可以在自己的電腦上執行。這與 DALL-E 2（僅透過 API 提供）和 Midjourney（僅透過 Discord 機器人提供）形成了鮮明對比。

## 技術原理

Stable Diffusion 是一種「潛在擴散模型」（Latent Diffusion Model）：

1. **變分自編碼器（VAE）**：將圖像壓縮到潛在空間中，大幅降低計算成本
2. **UNet 架構**：在潛在空間中進行迭代去噪
3. **文字編碼器（CLIP）**：將文字提示轉換為條件嵌入
4. **擴散過程**：從隨機噪聲開始，逐步去噪生成圖像

相較於 DALL-E 2 的 120 億參數，Stable Diffusion 僅有約 8.9 億參數——這使得它可以在消費級 GPU（4GB VRAM 以上）上運行。這項技術突破了 Google 的 Imagen 和 Parti 等模型對超大規模計算資源的依賴。

## 生態系統的爆炸

Stable Diffusion 的開源釋出引發了一系列創新：

- **DreamStudio**：Stability AI 的官方 Web 界面
- **Automatic1111 Web UI**：社群開發的功能最全面的本地界面
- **ControlNet**：精確控制生成圖像姿勢和構圖的擴展
- **LoRA**：低秩適應——小型可插拔的模型微調模組
- **Dreambooth**：用少量圖片訓練特定的主題或風格
- **Civitai**：使用者分享和發現模型與 LoRA 的社群平台

## 爭議與風險

Stable Diffusion 的開源特性也帶來了嚴重的問題：

- **成人內容生成**：大量使用者利用模型生成不當內容——包括非自願的 deepfakes
- **著作權訴訟**：藝術家和圖庫公司（如 Getty Images）起訴 Stability AI 未經授權使用受版權保護的圖像進行訓練
- **偏見與刻板印象**：模型在訓練資料中的偏見被反映在生成的圖像中
- **Deepfakes 與虛假訊息**：生成的真實感圖像可能被用於造假和誤導

## 歷史意義

Stable Diffusion 的開源釋出對 AI 產業產生了深遠的影響。它證明了開源 AI 模型可以與封閉的商業模型競爭——後續的 Llama 和 Mistral 等開源語言模型沿襲了這一路線。它也引發了關於 AI 訓練資料版權的全球性法律爭議——這個問題直到 2026 年仍然沒有完全解決。
