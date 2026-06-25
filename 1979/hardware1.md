# Motorola 68000：16/32 位元的革命

## 從 6800 到 68000

1979 年，Motorola 發表了 MC68000 微處理器——一顆擁有 68,000 個電晶體的 16/32 位元 CISC 晶片。它的名稱正是來自電晶體數量，這個命名方式後來成為 Motorola 68k 系列的傳統。

68000 的內部架構是 32 位元的——擁有 8 個 32 位元資料暫存器和 7 個 32 位元位址暫存器——但為了降低封裝成本和系統設計難度，外部資料匯流排僅為 16 位元。這讓它被稱為「16/32 位元處理器」。

## 架構特點

68000 最受開發者喜愛的特性是其平坦的 24 位元位址空間（16 MB），完全不需要記憶體分段（segmentation）。相比之下，Intel 8086 的 segmented 記憶體模型讓程式設計變得複雜許多。

68000 的指令集高度正交（orthogonal）——大部分指令可以使用所有定址模式。它內建了使用者／管理者雙模式保護、完整的例外與中斷向量表，以及支援位置無關程式碼（PIC）的 PC-relative 定址模式。

## 歷史地位

68000 在 1980 年代被廣泛應用於多款革命性電腦：Apple Macintosh 128K（1984）、Commodore Amiga（1985）、Atari ST（1985），以及 Sega Mega Drive 遊戲主機（1988）。它的大平面位址空間與優雅的架構，讓它成為圖形使用者介面（GUI）電腦的首選處理器。

## 延伸閱讀

- [Motorola 68000 - Wikipedia](https://en.wikipedia.org/wiki/Motorola_68000)
- [Motorola 68000 系列 - Wikipedia](https://en.wikipedia.org/wiki/Motorola_68000_series)
