# React 框架的開源

## Facebook 內部工具的誕生

2013 年 5 月 29 日，在 Facebook 的 JSConf 大會上，軟體工程師 Tom Occhino 發表了 React——一個用於建構使用者介面的 JavaScript 函式庫。React 由 Jordan Walke 在 Facebook 內部開發，最初用於 Facebook 的廣告管理系統。

## 虛擬 DOM

React 的核心創新是**虛擬 DOM**（Virtual DOM）。傳統的網頁開發中，每當資料變化時，開發者需要直接操作 DOM 來更新畫面——這在複雜應用中容易導致效能問題和程式碼混亂。

React 的做法是：開發者宣告 UI 應該長什麼樣子（透過 JSX 語法和 render 函數），React 負責計算如何高效地更新實際 DOM。React 維護一個記憶體中的虛擬 DOM 樹，當資料變化時，React 比對新舊虛擬 DOM 的差異（diffing），然後只對實際 DOM 進行最小量的變更。

## 元件化架構

React 的另一個核心概念是**元件化**（component-based architecture）。UI 被分解成獨立、可復用的小元件，每個元件封裝了自己的狀態和渲染邏輯。這種架構與傳統的 MVC（Model-View-Controller）範式截然不同——React 嚴格來說只負責 View 層，但透過元件化和單向資料流，它改變了整個前端應用的組織方式。

## 產業影響

React 在開源初期並未立即獲得廣泛採用。開發者對 JSX（在 JavaScript 中寫 HTML markup）和單向資料流感到陌生。但隨著 Facebook 生態的壯大，以及 React Native（2015）、React 的 hook 機制（2019）的推出，React 逐漸成為前端開發的事實標準。

## 延伸閱讀

- [React - Wikipedia](https://en.wikipedia.org/wiki/React_(JavaScript_library))
- [React 官方文件](https://react.dev/)
