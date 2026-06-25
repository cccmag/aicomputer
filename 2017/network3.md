# Service Mesh 與 Istio 的誕生

## 微服務的新挑戰

隨著微服務架構在 2016-2017 年間的快速普及，一個新問題開始浮現：當一個系統有數十甚至數百個服務時，服務間的通訊管理（流量控制、安全性、可觀察性）變得極其複雜。傳統方案是將這些邏輯嵌入到每個服務的程式碼中——但這導致了重複工作和不一致的實作。

Service Mesh 的概念在 2016 年由 Buoyant 公司的 William Morgan 首次提出，並在 2017 年成為一個重要的技術運動。Service Mesh 的核心思想是將服務間通訊的邏輯從應用程式程式碼中分離出來，在基礎設施層處理。

## Istio 的誕生

2017 年 5 月，Google、IBM 和 Lyft 聯合發布了 Istio 1.0（beta 版本）。Istio 建立在 Lyft 的 Envoy 代理之上，提供了一套完整的 Service Mesh 功能：

- **流量管理**：金絲雀部署、A/B 測試、藍綠部署
- **安全性**：服務間 mTLS、身分認證和授權
- **可觀察性**：分散式追蹤、指標收集、記錄

這些功能對應用程式程式碼完全透明——開發者不需要修改程式碼就能獲得這些能力。

## 技術架構

Istio 的架構分為控制平面（Control Plane）和資料平面（Data Plane）：

- **資料平面**：Envoy 作為 Sidecar 代理注入到每個 Pod 中，攔截所有進出流量
- **控制平面**：Pilot（路由）、Mixer（政策與遙測）、Citadel（安全）、Galley（配置驗證）

這個 Sidecar 模式成為 Service Mesh 的標準模式。

## 延伸閱讀

- [Istio 官方網站](https://istio.io/)
- [Service Mesh 介紹](https://istio.io/latest/about/service-mesh/)
