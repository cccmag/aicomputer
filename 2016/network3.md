# Progressive Web Apps 概念的推廣

## 融合 Web 與原生

2016 年，Progressive Web Apps（PWA）成為前端開發領域最熱門的概念之一。PWA 是由 Google 提出的 Web 應用新標準，旨在將原生應用的優勢——離線支援、推播通知、主畫面安裝——帶入 Web 平台。

PWA 的核心技術包括：

- **Service Worker**：在背景執行的 JavaScript 執行緒，負責快取管理和離線支援
- **Web App Manifest**：JSON 檔案，定義應用名稱、圖示、主題色等
- **HTTPS**：安全連線的前置要求
- **響應式設計**：適應各種螢幕尺寸

## 技術突破：Service Worker

2016 年最大的進展是 Service Worker API 的標準化和瀏覽器支援。Service Worker 是一個與頁面獨立的事件驅動 worker，可以攔截網路請求、管理快取、處理推播事件。它讓 Web 應用可以實現真正的離線體驗。

Google 在 I/O 2016 上大力推廣 PWA，展示了 Twitter Lite、Flipkart Lite 等 PWA 案例，這些應用在性能和用戶參與度上都有顯著提升。

## 產業影響

PWA 概念的推廣改變了行動開發的格局。對於許多小型企業和內容型網站，PWA 提供了一個比原生應用更便宜、更易維護的選擇。它特別適合網路基礎設施較差的地區——輕量級、離線支援、不需從應用商店安裝。

PWA 並未取代原生應用，但它在特定場景下提供了一個極具競爭力的替代方案。

## 延伸閱讀

- [PWA 概述 - Google](https://web.dev/progressive-web-apps/)
- [Service Worker - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
