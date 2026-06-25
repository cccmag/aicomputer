# UNIX System V 與標準化

## AT&T 的商業化路線

1984 年，AT&T 被美國司法部強制拆分後，貝爾系統的解體使得 AT&T 需要尋找新的收入來源。AT&T 決定積極商業化 UNIX——這個原本只是在貝爾實驗室內部使用的作業系統。

System V 是 AT&T 官方發布的 UNIX 商業版本。1984 年的 System V Release 2（SVR2）引入了重要的新功能：訊號量（semaphores）、共享記憶體、訊息佇列——這些 System V IPC（程序間通訊）機制成為 UNIX 程式設計的重要組成部分。

## UNIX 陣營的分裂

1984 年，UNIX 已經分裂成兩個主要分支：AT&T 的 System V 和柏克萊的 BSD。System V 被 AT&T 積極推廣給硬體製造商，BSD 則在學術界和網路社群中流行。兩者之間的指令、API 和管理工具存在許多不相容之處。

這個分裂導致了所謂的「UNIX 戰爭」——硬體製造商必須選擇支援 System V 還是 BSD，軟體開發者必須決定針對哪個版本開發。這個分裂一直持續到 1990 年代，直到 POSIX 標準和 Linux 的出現才逐漸統一。

## 影響

System V 的 IPC 機制——訊號量、共享記憶體、訊息佇列——雖然設計老舊，但仍然是現代 Linux 系統的標準組成部分。System V 的 init 系統（執行層級）也被 Linux 採用，直到 systemd 的出現才被取代。

## 延伸閱讀

- [UNIX System V - Wikipedia](https://en.wikipedia.org/wiki/UNIX_System_V)
- [UNIX 歷史 - Wikipedia](https://en.wikipedia.org/wiki/History_of_Unix)
