# WebAssembly 初登場：瀏覽器的新時代

## 瀏覽器原生程式碼

2016 年是 WebAssembly（Wasm）從概念走向標準的關鍵一年。2015 年，Google、Microsoft、Mozilla、Apple 四大瀏覽器廠商聯合宣布了這個新的二進制指令格式。2016 年 3 月，WebAssembly 的 MVP 版本開始在各大瀏覽器中進行實驗性實現。

WebAssembly 的目標是解決一個長期困擾 Web 開發者的問題：JavaScript 雖然靈活強大，但在運算密集的任務（遊戲、影音編輯、科學計算）中效能遠遠不足。WebAssembly 提供了一個低階的二進制格式，可以讓 C/C++、Rust 等語言編譯的程式碼在瀏覽器中以接近原生的速度執行。

## 技術設計

WebAssembly 的設計特點：

- **二進制格式**：比 JavaScript 小且解析速度快得多
- **類型安全**：嚴格的類型系統，避免常見的安全性漏洞
- **線性記憶體**：沙箱化的記憶體模型
- **流式編譯**：可以在下載完成前就開始編譯

## 發展歷程

2016 年 10 月，Mozilla 的 Servo 工程師展示了首個 WebAssembly 的實際演示——在瀏覽器中以接近原生速度執行 Unreal Engine 4 遊戲。同年 12 月，WebAssembly 的 MVP 版本提交了最初的二進制格式規格草案。

## 深遠影響

WebAssembly 從根本上改變了 Web 平台的運算能力邊界。它讓開發者可以將桌面級應用的效能帶到瀏覽器中——遊戲引擎、影像處理、密碼學、資料庫等都可以在瀏覽器中高效執行。

2016 年的起步階段雖然還在實驗中，但已經為後續的 WebAssembly 生態奠定了基礎。

## 延伸閱讀

- [WebAssembly 官方網站](https://webassembly.org/)
- [WebAssembly 設計文件](https://github.com/WebAssembly/design)
