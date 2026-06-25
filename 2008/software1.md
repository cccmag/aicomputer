# Google Chrome 瀏覽器與 V8 引擎

## 瀏覽器的新時代

2008 年 9 月 2 日，Google 發布了 Chrome 瀏覽器的第一個公開測試版（Windows 版）。這是自 2004 年 Firefox 1.0 以來，瀏覽器市場最重要的一次新進者登場。

Chrome 不是又一個基於 Mozilla 或 WebKit 的瀏覽器外殼。雖然它使用了 WebKit 渲染引擎，但 Chrome 幾乎從頭開始重新設計了瀏覽器的每一個部分。Google 發布了一本名為《Google Chrome 的漫畫書》的技術漫畫來解釋 Chrome 的設計決策。

## V8 JavaScript 引擎

Chrome 最革命性的技術是 V8 JavaScript 引擎。傳統的 JavaScript 引擎——如 Firefox 的 SpiderMonkey 或 Safari 的 JavaScriptCore——是直譯器，將 JavaScript 原始碼一行一行地轉換為機器碼執行。

V8 採用了完全不同的策略：它使用即時編譯（JIT，Just-In-Time Compilation）技術，將 JavaScript 原始碼編譯為原生機器碼再執行。V8 還引入了精確的垃圾回收機制、內聯快取（inline caching）、以及隱藏類別（hidden class）來優化物件屬性存取。

## 安全性與隔離

Chrome 的另一個設計核心是程序隔離。每個分頁（tab）都在獨立的作業系統行程中執行。如果一個分頁崩潰或掛起，不會影響其他分頁或瀏覽器本身。這個設計借鑒了現代作業系統的行程隔離概念。

## 延伸閱讀

- [Google Chrome - Wikipedia](https://zh.wikipedia.org/wiki/Google_Chrome)
- [Chrome 漫畫書](https://www.google.com/googlebooks/chrome/)
- [V8 JavaScript 引擎](https://v8.dev/)
