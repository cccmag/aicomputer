# CERN httpd：第一個網頁伺服器

## 在 NeXT 上運行的歷史

CERN httpd（超文字傳輸協定守護程式）是由 Tim Berners-Lee 在 1990 年底於 CERN 編寫的第一個網頁伺服器軟體。它運行在一台 NeXTcube 工作站上，這台機器有一張手寫標籤：「This machine is a server. DO NOT POWER IT DOWN!!」（這是一台伺服器。請勿關機！！）

最初的 CERN httpd 極為簡單——它只支援在 1990 年定義的 HTTP 0.9 協議。這個版本只有 GET 方法，沒有狀態碼，沒有標頭欄位——客戶端建立連線、發送文件路徑、伺服器回傳檔案內容、然後關閉連線。

## 1991 年的演進

1991 年，Berners-Lee 和 Jean-François Groff（一位在 CERN 加入專案的實習生）持續改進 httpd。他們加入了：
- 支援 CGI（Common Gateway Interface）的前身——允許執行伺服器端腳本
- 目錄列表功能
- MIME 類型映射

到 1991 年底，CERN httpd 已能在多種 Unix 系統上運行——包括 VAX、RS/6000 和 Sun4。CERN 還維護著一個「成為 Web 伺服器」的指南文件，詳述如何下載、編譯和設定 httpd。

## 開源模式的原型

CERN httpd 是第一批採用「自由使用、自由散布」模式的軟體專案之一。CERN 的法律團隊在 1993 年 4 月 30 日正式宣布 WWW 技術進入公共領域，確保任何人都可以不受限制地使用和改良它。

從 1991 年那一行行的 C 程式碼開始，CERN httpd 為現代 Web 伺服器（如 Apache httpd、nginx）奠定了基礎。它的設計哲學——簡單、模組化、易於擴展——至今仍是 Web 伺服器設計的黃金法則。
