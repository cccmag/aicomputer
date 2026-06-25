# OpenAI Sora：文字轉影片的飛躍

## 技術預覽的震撼

2024 年 2 月 15 日，OpenAI 無預警地展示了 **Sora**——一個可以從文字描述生成最長 60 秒影片的 AI 模型。Sora 的演示影片在網路上瞬間引爆討論：

- 「一隻金毛獵犬在雪地裡奔跑」——毛髮的物理動態令人驚嘆
- 「東京街頭的霓虹燈夜晚，一位時尚女性行走」——光影與反射自然逼真
- 「紙船在咖啡杯中航行」——液體模擬與物理互動的精確

Sora 的生成品質遠超當時已有的任何文字轉影片模型，包括 Runway Gen-2、Pika 和 Stability AI 的 Stable Video Diffusion。

## 技術核心

Sora 是一種**擴散模型**（diffusion model），但它與傳統的文字轉圖像擴散模型有本質上的不同。Sora 在大量影片資料上進行訓練，學習了物體的物理行為、光線與材質的互動、場景的持續性（object permanence）等概念。

關鍵的創新在於，Sora 能夠理解物體在三維空間中的存在——即使物體暫時移出畫面，回來時仍然保持一致的外觀與位置。這是影片生成領域中最困難的問題之一。

## 延遲的正式發布

技術預覽後，Sora 並沒有立即開放。OpenAI 表示需要進行安全測試、紅隊演練與內容審核機制的建立。Sora 最終在 **2024 年 12 月 9 日**正式向 ChatGPT Plus 與 Pro 用戶開放，距離預覽已過了十個月。

## 產業衝擊

Sora 的出現對創意產業產生了深遠的影響：

- **電影與廣告**：AI 生成影片的成本優勢可能顛覆傳統製作流程
- **版權爭議**：訓練資料中是否包含受版權保護的 YouTube 影片？
- **深偽造假**：高品質 AI 影片增加了選舉期間假資訊的風險

## 延伸閱讀

- [Sora 介紹 - OpenAI](https://openai.com/index/sora/)
- [Sora 技術報告 - OpenAI](https://openai.com/index/video-generation-models-as-world-simulators/)
