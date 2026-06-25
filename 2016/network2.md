# React 16 / Fiber 架構重寫

## 從 Stack 到 Fiber

2016 年，Facebook 的 React 團隊開始了一個名為「React Fiber」的重大架構重寫計畫。這個計畫的背景是：React 15 及其之前的版本使用了一個「堆疊協調器」（Stack Reconciler），其同步遞迴的渲染方式無法被打斷——當元件樹很深時，UI 更新會阻塞主執行緒，導致使用者感知的卡頓。

React Fiber 從根本上改變了這個架構。它將渲染工作分解為可中斷的小單元（fiber），並實現了一套排程系統，讓 React 可以根據幀率來決定何時執行渲染工作、何時暫停讓給瀏覽器處理其他任務。

## 非同步渲染

Fiber 最關鍵的創新是引入了非同步渲染（Async Rendering）的概念：

- **優先級排程**：高優先級更新（如使用者輸入）可以跳隊先處理
- **增量渲染**：渲染工作可以分散到多個幀中完成
- **錯誤邊界**：引入了更優雅的錯誤處理機制

## 對前端生態的影響

React Fiber 在 2016 年作為實驗性專案存在，直到 2017 年 9 月才正式發布為 React 16。但這項工作在 2016 年的啟動本身就具有重要意義——它為 React 生態注入了新的活力，激發了社群對渲染效能和排程機制的深入討論。

Fiber 架構也為 React 帶來的新功能（如 Suspense、Hooks、Concurrent Mode）奠定了基礎。

## 延伸閱讀

- [React Fiber 架構](https://github.com/acdlite/react-fiber-architecture)
- [React 16 發布公告](https://reactjs.org/blog/2017/09/26/react-v16.0.html)
