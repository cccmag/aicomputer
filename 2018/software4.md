# Vue.js 3.0 開發方向

## 重大重新設計

2018 年 9 月，Vue.js 的創始人尤雨溪（Evan You）在公開場合分享了 Vue.js 3.0 的開發計畫和設計目標。Vue.js 是中國開發者社群中最受歡迎的前端框架之一，在全球也有大量使用者。

Vue 3.0 的核心設計目標包括：

- **更好的 TypeScript 支援**：框架本身用 TypeScript 重寫
- **Composition API**：受 React Hooks 啟發的函數式元件邏輯組合方式
- **更小的體積**：Tree-shaking 支援，可以消除未使用的功能
- **更高效的渲染**：基於 Proxy 的響應式系統取代 Object.defineProperty
- **Fragments、Teleport、Suspense**：新的內建元件

## Composition API

Composition API 是 Vue 3.0 最受關注的變革。在 Vue 2.x 中，元件的邏輯是按照 data、methods、computed 等選項組織的。當一個元件的功能複雜時，關注同一個問題的程式碼會被分散在不同的選項中。

Composition API 允許開發者按照功能將相關的邏輯組織在一起——類似於 React Hooks 但提供了更靈活的抽象能力。尤雨溪將此設計描述為讓 Vue 可以同時提供 Options API 和 Composition API 兩套方式。

## 生態的準備

2018 年的 Vue 生態仍然以 Vue 2.x 為主。Vue 3.0 的開發歷時兩年（2018-2020），最終在 2020 年 9 月正式發布。2018 年的這些設計討論對整個前端社群產生了影響——Angular 和 React 也在這個時期改進了各自的響應式方案。

## 延伸閱讀

- [Vue 3.0 計畫](https://github.com/vuejs/rfcs)
- [Vue 3 設計目標](https://v3-migration.vuejs.org/)
