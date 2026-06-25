# React Native 開源：跨平台行動開發

## Facebook 的「Learn Once, Write Anywhere」

2015 年 3 月 26 日，在 Facebook F8 開發者大會上，Facebook 宣布開源 React Native——一個用於建構原生行動應用程式的框架。不同於當時流行的「Write Once, Run Anywhere」跨平台方案，Facebook 的口號是「Learn Once, Write Anywhere」。

React Native 的核心創新在於：它讓開發者使用 JavaScript 和 React 來建構應用程式，但渲染的是真正的原生 UI 元件——而不是 WebView。這意味著應用程式能獲得與純原生開發相同的性能和外觀。

## 技術架構

React Native 在 iOS 上使用 JavaScriptCore 引擎來執行 JavaScript 程式碼，透過一個非同步的橋接層與原生執行緒通訊。開發者編寫的 JSX 元件會被映射到對應的原生元件（如 UIView 或 Android View）上。

這種架構帶來了三個關鍵優勢：

- **快速迭代**：開發者可以在不必重新編譯完整應用程式的情況下即時預覽變更
- **共享程式碼**：業務邏輯和部分 UI 邏輯可以在 iOS 和 Android 之間共享
- **原生性能**：使用者體驗與純原生應用無異

## 產業影響

React Native 在發布後迅速受到歡迎。Facebook 自家應用（如 Facebook Groups、Ads Manager）率先採用了這項技術。到 2015 年底，Airbnb、Walmart、Uber 等大型科技公司也開始導入 React Native。

React Native 的成功也刺激了其他跨平台框架的發展——包括 Google 後來推出的 Flutter。

## 延伸閱讀

- [React Native 官方網站](https://reactnative.dev/)
- [React Native 發布公告](https://engineering.fb.com/2015/03/26/android/react-native-bringing-modern-web-techniques-to-mobile/)
