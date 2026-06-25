# Node.js 誕生：Ryan Dahl 的伺服器端 JavaScript

## 從 Ruby 到 JavaScript

2009 年，Ryan Dahl 在 JSConf 歐洲會議上發表了 Node.js——一個基於 Chrome V8 JavaScript 引擎的伺服器端執行環境。Dahl 原本是 Ruby 和 C 語言開發者，但他對 Ruby 的平行處理能力感到失望。他需要一個能處理大量並發連線的平台——特別是當 HTTP 長連線和 WebSocket 等技術開始流行時。

Dahl 的靈感來自於一個簡單的觀察：I/O 操作（檔案讀取、網路請求和資料庫查詢）是大多數 Web 應用程式的效能瓶頸，而傳統的執行緒模型在處理大量並發 I/O 時效率低下。

## 事件驅動與非阻塞 I/O

Node.js 的核心設計哲學是事件驅動（event-driven）和非阻塞 I/O（non-blocking I/O）。在傳統的同步 I/O 模型中，當程式讀取一個檔案時，執行緒會被阻塞直到資料返回。在 Node.js 中，I/O 操作會立即返回，並在完成時觸發一個回呼函式。

這個設計的關鍵優勢是單一執行緒（event loop）可以處理數千個並發連線。在傳統的多執行緒 Web 伺服器中，每個連線需要一個執行緒——執行緒切換的開銷和記憶體消耗限制了可處理的並發數量。

## npm 與生態系統的誕生

與 Node.js 一同誕生的還有 npm——Node Package Manager。npm 是世界上最大的套件管理器之一，讓開發者可以輕鬆發布和安裝 JavaScript 套件。

Node.js 的第一個版本支援 Linux 和 Mac OS X（Windows 版本由社群透過 Cygwin 支援）。最初的 API 比較簡陋——許多今天視為核心的功能（如檔案系統操作、HTTP 模組）在 1.0 版本之前都在快速演變。

## 延伸閱讀

- [Node.js - Wikipedia](https://zh.wikipedia.org/wiki/Node.js)
- [Ryan Dahl 的 JSConf 演講 (2009)](https://www.youtube.com/watch?v=ztspvPYybIY)
- [npm - Wikipedia](https://en.wikipedia.org/wiki/Npm_(software))
