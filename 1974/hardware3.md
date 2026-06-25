# IBM System/370 虛擬記憶體架構正式成熟

## 從爭議到標準

IBM System/370 在 1970 年推出時，最受爭議的缺失就是沒有支援虛擬記憶體。當時其他廠商如 Burroughs、GE/Honeywell、RCA 都已在其系統中實現了虛擬記憶體，IBM 卻為了相容於 System/360 而遲遲不導入。

1972 年 8 月，IBM 宣布了 System/370 Advanced Function，為所有 S/370 機器增加了動態位址轉譯（DAT）硬體。但真正的成熟是在 1974 年——此時 MVS（Multiple Virtual Storage）作業系統已出貨，VM/370 也穩定運行，虛擬記憶體成為 IBM 大型主機的核心功能。

## 技術架構

System/370 的虛擬記憶體使用 24 位元虛擬位址空間（16 MB），透過 DAT 硬體將虛擬位址映射到實體記憶體。它採用分頁（paging）機制，頁面大小為 4 KB，並支援段（segment）表與頁（page）表的兩層轉譯結構。

這套架構的關鍵創新在於：

- 程式可以使用比實體記憶體更大的位址空間
- 多個程式可以同時存在於記憶體中，彼此隔離
- 作業系統可以在不同程式之間動態分配實體記憶體

## 作業系統生態

1974 年，S/370 上有四個主要的虛擬儲存作業系統：

- **OS/VS1**：單一虛擬儲存，適合單一大型應用
- **OS/VS2 (SVS)**：單一虛擬儲存的進化版
- **MVS (Multiple Virtual Storage)**：每個使用者有自己的虛擬空間，成為後來 IBM 大型主機的標準
- **VM/370**：虛擬機器監控器，允許多個作業系統同時運行

MVS 在 1974 年 3 月正式出貨，成為 IBM 史上最重要的作業系統之一，其後代 z/OS 至今仍在運行。

## 延伸閱讀

- [IBM System/370 - Wikipedia](https://en.wikipedia.org/wiki/IBM_System/370)
- [虛擬記憶體歷史 - Wikipedia](https://en.wikipedia.org/wiki/Virtual_memory)
- [MVS 歷史 - Google 搜尋](https://www.google.com/search?q=MVS+1974+IBM+virtual+memory)
