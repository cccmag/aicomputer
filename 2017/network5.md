# React Native 與 Flutter 的跨平台之爭

## React Native 的成熟

2017 年是 React Native 從新興框架走向成熟的一年。經過兩年的社群發展，採用 React Native 的大型專案越來越多：Instagram、Airbnb、Walmart、Uber Eats 等都在生產環境中使用 React Native。

Facebook 在 2017 年持續改進 React Native——引入了更快的 Hot Reloading、改進了 ListView 效能、推出了更好的導航解決方案。社群也開發了豐富的三方函式庫生態。

然而，挑戰也開始出現：Airbnb 在 2017 年宣布開始從 React Native 遷移到純原生開發，原因是效能瓶頸和除錯困難。

## Flutter 的雛形

2017 年，Google 在 I/O 大會上預覽了 Flutter——一個全新的開源行動應用 SDK，使用 Dart 語言開發。Flutter 與 React Native 在設計哲學上有根本性的不同：

- **自繪引擎**：Flutter 不使用平台原生元件，而是用 Skia 引擎自行繪製所有 UI
- **Dart 語言**：AOT 編譯為原生機器碼，減少 JavaScript 橋接層的開銷
- **Hot Reload**：與 React Native 類似的快速迭代體驗

## 影響與方向

Flutter 的出現標誌著跨平台開發進入了一個新階段——不再只是 JavaScript 與 WebView 的故事。Flutter 的自繪引擎路線雖然在 2017 年還處於 beta 階段，但為後續的市場格局奠定了基礎。

這場競爭最終促進了所有框架的進步——React Native 後來引入了 Fabric 渲染器來改善效能，Flutter 則在 2018 年發布 1.0 正式版。

## 延伸閱讀

- [React Native 2017 回顧](https://reactnative.dev/blog/2017)
- [Google Flutter 預覽](https://flutter.dev/)
