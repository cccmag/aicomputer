# MySQL 的誕生：開放資料庫的開端

## TcX 的內部工具

1994 年，瑞典公司 TcX AB 的程式設計師 David Axmark、Allan Larsson 和 Michael「Monty」Widenius 開始開發一個名為 MySQL 的關聯式資料庫管理系統。

MySQL 的起源是 TcX 對 mSQL（一個小型 SQL 引擎）的不滿足——它太慢而且缺乏某些功能。Widenius 決定從頭編寫一個更好、更快的 SQL 引擎。他參考了 mSQL 的 API 設計，但所有底層代碼都是重新實現的。

## 設計哲學

MySQL 從一開始就做出了幾個重要的設計決策：

- **速度優先**：MySQL 的目標是「比任何免費資料庫更快」
- **簡單易用**：安裝和設定非常簡單，遠比其他資料庫系統容易上手
- **多執行緒架構**：利用執行緒而非多行程來處理並行請求
- **嵌入式支援**：可以作為程式庫內嵌到應用程式中

## 開源的決定

1994 年，MySQL 還只是一個 TcX 內部的專案名稱（以 Widenius 的女兒 My 命名）。原始碼在 TcX 內部開發使用，尚未對外公開。

但 MySQL 採用的商業模式（雙重授權）和其優秀的效能，讓它在 1990 年代末期成為「LAMP」棧（Linux + Apache + MySQL + PHP/Perl/Python）的核心，驅動了整個 Web 2.0 時代。

雖然 1994 年的 MySQL 還遠不是一個成熟的開源資料庫，但它是這項技術的起點。到 2001 年，MySQL 已經擁有超過 200 萬個安裝——成為世界上最受歡迎的開源資料庫管理系統。

## 延伸閱讀

- [MySQL 歷史 - Wikipedia](https://en.wikipedia.org/wiki/MySQL)
- [Michael Widenius 訪談](https://opensource.com/article/18/1/michael-widenius-mysql)
