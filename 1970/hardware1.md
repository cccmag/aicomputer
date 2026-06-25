# DEC PDP-11/20 發表：16位元迷你電腦的里程碑

## 從 PDP-8 到 PDP-11

1970 年 1 月，DEC（Digital Equipment Corporation）宣布推出 PDP-11/20，這是一台 16 位元的迷你電腦，定價約 20,000 美元。它的設計由 Harold McFarland 主導，Gordon Bell 提供支援，從 Carnegie Mellon 大學的研究中汲取靈感。

PDP-11 採用了多項革命性設計。它的指令集是所謂的「正交指令集」——所有指令都能使用所有定址模式，極大簡化了程式設計。它引入了 **Unibus** 架構，將記憶體與 I/O 裝置統一在同一位址空間中，讓外部裝置可以透過直接記憶體存取（DMA）與系統溝通。

## 技術規格與創新

PDP-11/20 的 CPU（KA11）完全由離散 TTL 邏輯構成，是整個 PDP-11 家族中唯一不使用微程式設計的型號。主要原因在於 1970 年還不存在足夠快且便宜的唯讀記憶體（ROM）。它有八個 16 位元暫存器，六個通用暫存器加上堆疊指標和程式計數器。主記憶體使用磁芯記憶體，最大可達 56 KB（28 KWords）。

PDP-11 的設計影响了後來的 x86 和 Motorola 68000 架構。Intel 在設計 8086 時參考了 PDP-11 的暫存器模型和定址模式。

## 市場成功與歷史地位

PDP-11 最終賣出了約 60 萬台，生產週期從 1970 年一直延續到 1997 年。它成為 UNIX 作業系統的第一個主要平台，C 語言的誕生地，也是 DEC 史上最成功的產品線。

## 延伸閱讀

- [DEC PDP-11 - Wikipedia](https://en.wikipedia.org/wiki/PDP-11)
- [PDP-11 歷史 - Computer History Museum](https://www.computerhistory.org/timeline/1970/)
