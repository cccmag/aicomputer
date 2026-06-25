# PWA（漸進式網頁應用）概念的萌芽

## 網頁應用的新願景

2013 年，瀏覽器供應商和網頁開發者開始認真思考一個問題：網頁應用能否提供與原生應用相媲美的使用者體驗？這個問題的答案在接下來的幾年中逐漸凝聚為 PWA（Progressive Web App，漸進式網頁應用）的概念。

PWA 的核心技術要素在 2013 年已經部分成形：
- **Service Worker**：雖然標準尚未定稿，但瀏覽器供應商已經開始討論在瀏覽器背景執行 JavaScript 的可能性
- **App Shell 模型**：將應用程式的基礎架構（shell）與內容分離，確保每次載入時立即顯示 UI
- **離線快取**：透過 Cache API 和 localStorage 實現的基本離線功能

## Google 的推動

2013 年，Google 的 Chrome 團隊開始研究「安裝到主畫面」功能——讓使用者可以將網頁應用新增到手機的主畫面，獲得接近原生應用的啟動體驗。這項實驗最終演變為 PWA 的 manifest.json 規範。

## 與原生應用的對比

PWA 的目標是結合網頁（無需安裝、即時更新、可被搜尋引擎索引）和原生應用（離線運作、硬體存取、推播通知）的優點。雖然 2013 年的 PWA 概念尚未成熟，但它代表了網頁應用從「文件瀏覽」到「應用平台」的重要轉向。

## 延伸閱讀

- [PWA - Wikipedia](https://en.wikipedia.org/wiki/Progressive_web_app)
- [Google PWA 介紹](https://web.dev/progressive-web-apps/)
