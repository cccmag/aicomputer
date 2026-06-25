# Firebird 資料庫：InterBase 的開源分支

## 開源的契機

Firebird 的起源可以追溯到 Borland 公司的 InterBase 資料庫。2000 年 7 月，Borland 以開放原始碼許可證發布了 InterBase 6.0 的原始碼——由於財務困難，Borland 在 1999 年停止了 InterBase 的開發。

兩名澳洲開發者下載了剛剛發布的原始碼，在 SourceForge 上建立了 Firebird 專案。僅用了一週時間，Firebird 社群就已經形成。

## Firebird 1.0

2002 年 3 月 11 日，Firebird 1.0 正式發布，支援 Linux、Microsoft Windows 和 Mac OS X。隨後在幾個月內，Solaris、FreeBSD 和 HP-UX 的移植版本也陸續推出。

Firebird 1.0 本質上是 InterBase 6.0 的程式碼清理版本——修復了建置系統中的錯誤和長期存在的 Bug，但未加入大量的新功能。

## 技術特色

Firebird 作為一款關聯式資料庫管理系統（RDBMS），具有以下特色：

**完整 SQL 支援**：支援 SQL-92 標準的大多數功能，包括子查詢、觸發器、預存程序和檢查約束

**多重世代架構（MGA）**：Firebird 使用獨特的版本化架構實現了讀取操作不阻塞寫入操作，讀取者永遠不會等待——這對高並發的讀取密集型應用極具吸引力

**極小的安裝尺寸**：核心資料庫引擎只有幾 MB，適合嵌入式應用

**ACID 相容**：完整支援交易處理的原子性、一致性、隔離性和持久性

## 社群驅動的發展

Firebird 的開發完全由社群驅動。在 Borland 停止 InterBase 開發到源碼開放的過渡期，一個活躍的開發者社群已經形成。這個社群包含了設計師、測試者、工具開發者和支援志願者。

Firebird 在 2003 年被 SAS Institute 選為嵌入式資料庫，這對其發展是一個重要的商業肯定。

## 延伸閱讀

- [Firebird 資料庫 - Wikipedia](https://en.wikipedia.org/wiki/Firebird_(database_server))
- [Firebird 官方網站](https://firebirdsql.org/)
