# UNIX 移植到 PDP-11：作業系統的里程碑

## 從 PDP-7 到 PDP-11

UNIX 最初由 Ken Thompson 在 1969 年於貝爾實驗室的 PDP-7 上開發。但 PDP-7 已經過時，而且團隊不能真正擁有這台機器。Thompson 和 Dennis Ritchie 需要一台更強大的電腦。

1970 年夏天，貝爾實驗室購買了一台 PDP-11/20，價格約 65,000 美元。這台機器是 DEC 剛推出的最新產品，甚至連磁碟都尚未到貨。直到 12 月，Thompson 才正式開始將 UNIX 移植到 PDP-11 上。

## 移植過程

移植工作在 PDP-11/20 上進行，使用兩台 Teletype Model 33 ASR 終端機。由於 UNIX 和所有工具都是為 PDP-7 的 18 位元架構設計的，移植到 16 位元的 PDP-11 需要大幅改寫組合語言程式碼。

Thompson 用 PDP-11 組合語言從頭編寫了核心、檔案系統、命令列直譯器（shell）以及基本的工具程式。在這個過程中，他也開發了 B 語言作為系統程式的開發工具。

## 命名的起源

Brian Kernighan 在 1970 年提出了「UNIX」這個名字，它來自對 Multics 的諧音雙關——Multics 代表「Multiplexed Information and Computing Service」，而 UNIX 代表「Uniplexed Information and Computing Service」。最早還被開玩笑地拼成「Unics」（eunuchs 的諧音）。

## 從內部工具到開放系統

最初 UNIX 只是貝爾實驗室專利部門的文書處理工具——因為 UNIX 需要文字處理能力來獲得經費資助。Douglas McIlroy 和 Lee McMahon 支援了這項提案。

UNIX 的第一個實際應用是支援貝爾實驗室專利部門的打字員，他們使用 UNIX 上的 ed 編輯器和 roff 排版工具處理專利申請文件。UNIX 的可靠性使專利部門成為貝爾實驗室內第一個正式採用 UNIX 的團隊。

這最終說明了「好的工具往往不是被規劃出來的，而是從實際需求中成長起來的」。

## 延伸閱讀

- [UNIX 歷史 - Nokia Bell Labs](https://www.bell-labs.com/unix-history/)
- [History of Unix - Wikipedia](https://en.wikipedia.org/wiki/History_of_Unix)
