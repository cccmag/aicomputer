# MS-DOS 1.0：PC 的作業系統

## IBM PC-DOS 的誕生

1981 年 8 月，隨著 IBM PC 5150 的出貨，Microsoft 的 MS-DOS 以 PC-DOS 1.0 的名稱首次亮相。這是一個 16 KB 的磁碟作業系統——包含一個命令列直譯器（COMMAND.COM）、檔案管理核心（IBMDOS.COM）、基本 I/O 系統（IBMBIO.COM）——所有這些都可以放在一片 160 KB 的軟碟上。

MS-DOS 1.0 支援的檔案系統是 FAT12——一個簡潔的檔案系統設計，支援 8.3 檔案名稱格式（8 字元名稱 + 點 + 3 字元副檔名）。這是 Microsoft 的 FAT（File Allocation Table）檔案系統的首次亮相，後來成為 PC 相容機的事實標準。

## 命令列介面

MS-DOS 的命令列使用 A> 提示符號，包含以下基本命令：
- DIR（列出目錄）
- COPY（複製檔案）
- TYPE（顯示檔案內容）
- ERASE/DEL（刪除檔案）
- RENAME（重新命名）
- FORMAT（格式化磁碟）

MS-DOS 沒有目錄樹狀結構（子目錄支援在 2.0 版才加入，1983 年）。每個磁碟機使用一個字母（A:、B: 等）來標示。

## 延伸閱讀

- [MS-DOS - Wikipedia](https://en.wikipedia.org/wiki/MS-DOS)
- [PC-DOS 歷史 - IBM](https://www.ibm.com/history/personal-computer)
