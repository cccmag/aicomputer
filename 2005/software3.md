# Git 的誕生：Linus Torvalds 十天創造的版本控制系統

## BitKeeper 危機

2005 年，Linux 核心開發社群面臨一場突如其來的危機。多年來，Linux 核心開發使用 BitKeeper——一個由 Larry McVoy 開發的分散式版本控制系統。BitKeeper 對 Linux 核心開發者免費提供，但這項特許協議在 2005 年 4 月被撤銷了。

BitKeeper 的維護者 Andrew Tridgell 試圖逆向工程 BitKeeper 的通訊協定，這激怒了 McVoy，後者決定終止社群對 BitKeeper 的免費使用。Linus Torvalds 別無選擇——他必須為 Linux 核心尋找（或創造）一個新的版本控制系統。

## 十天開發

Torvalds 決定自己寫一個版本控制系統。他的目標明確：
- 分散式架構（不像 CVS 和 Subversion 依賴中央伺服器）
- 極高效能（處理 Linux 核心這種規模的專案）
- 強大的分支和合併支援
- 資料完整性保證（使用 SHA-1 哈希）
- 簡單的設計（「資訊管理員來自地獄」——Torvalds 的幽默描述）

2005 年 4 月 7 日，Torvalds 提交了 Git 的第一個 commit。僅在十天內，他就建立了足以支撐 Linux 核心開發的核心功能。第一版 Git 由七個低階工具組成——`write-tree`、`read-tree`、`commit-tree`、`cat-file`、`update-cache`、`show-diff` 和 `init-db`。

## 交接與演進

Torvalds 在 2005 年 7 月將 Git 的維護工作交給了 Junio Hamano——Hamano 在 Git 發布後一週就開始貢獻程式碼。到 2005 年 12 月，Git 已經發布了超過 34 個版本。Git 後來成為世界上最受歡迎的版本控制系統，驅動著 GitHub、GitLab、Bitbucket 等平台，改變了全球軟體開發的協作方式。
