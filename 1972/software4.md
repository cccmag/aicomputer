# PL/M：第一個微處理器高階語言

## 一位教授與 Intel 的邂逅

Gary Kildall 在 1972 年取得華盛頓大學電腦科學博士學位後，在加州的 Naval Postgraduate School 任教。他獲得了經費來建立一個電腦實驗室，並透過管道向 Intel 取得了 Intellec 開發系統。

某天，Kildall 去找 Intel 的微電腦軟體部門經理 Hank Smith，解釋了他想在 Intel 8008 上實作高階語言的構想。Smith 聽不懂——「高階語言對微處理器有什麼用？」Kildall 解釋說，程式設計師可以寫 `X = Y + Z`，然後程式會自動將它轉換成組合語言。Smith 當場打電話給一位客戶，客戶表示有興趣，於是他告訴 Kildall：「去做吧。」

## PL/M 的設計

PL/M（Programming Language for Microcomputers）以 IBM 的 PL/I 和 XPL 為基礎。它的語法簡化自 PL/I，去除了複雜的功能，專注於微處理器系統程式設計的需求。

關鍵設計決策包括：

- 編譯成高效的機器碼（不是直譯）
- 直接對應到 8008 的暫存器和記憶體模型
- 靜態型別檢查
- 結構化控制流程（if-then-else、do-while、case）

最初 PL/M 編譯器執行在 PDP-10 大型主機上，透過交叉編譯產生 8008 的機器碼，然後用打孔紙帶載入目標系統。

## 催生 CP/M

PL/M 對電腦歷史的最大貢獻，或許不是語言本身，而是它催生了 CP/M 作業系統。為了讓 8080 能夠控制軟碟機，Kildall 用 PL/M 寫了一個磁碟作業系統——這後來成為 CP/M（Control Program for Microcomputers），第一個廣泛使用的微電腦作業系統。

CP/M 和它的 BIOS 概念（將硬體相依部分隔離在一個模組中）直接啟發了 MS-DOS，而 MS-DOS 又啟發了 Windows。一條從 PL/M 延伸到現代桌面系統的傳承路線於焉形成。

## 延伸閱讀

- [PL/M - Wikipedia](https://en.wikipedia.org/wiki/PL/M)
- [Gary Kildall - Wikipedia](https://en.wikipedia.org/wiki/Gary_Kildall)
- [PL/M 歷史 - Google 搜尋](https://www.google.com/search?q=PL/M+Gary+Kildall+1972+1973)
