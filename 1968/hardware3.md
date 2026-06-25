# Honeywell DDP-516：ARPANET 的心臟

## 迷你電腦的意外角色

1968 年，ARPANET 的設計者面臨一個關鍵決策：網路節點應該用什麼電腦？設計團隊的領導者 Larry Roberts 原先設想直接用大型主機（mainframe）互相連接。但 Wesley Clark 在 1967 年提出了一個極具遠見的建議——使用獨立的迷你電腦來處理網路通訊任務，這些電腦後來被稱為 IMP（Interface Message Processor）。

Clark 的邏輯很簡單：如果每台主機都要直接參與網路通訊，那麼不同型號、不同作業系統的電腦之間將難以協調。使用專門的迷你電腦處理網路功能，可以讓主機與網路之間的介面標準化。

## BBN 的選擇

1968 年底，BBN（Bolt, Beranek and Newman）公司獲得了 ARPANET 的 IMP 開發合約。BBN 的團隊——包括 Severo Ornstein、Bob Kahn、David Walden 等人——需要選擇一款適合的迷你電腦作為 IMP 的硬體平台。

他們考慮了多款機器，最終選擇了 Honeywell DDP-516。這是一款 16 位元的迷你電腦，配備 4K 到 32K 字的磁芯記憶體，具備高可靠性與靈活的 I/O 能力。為了滿足 ARPANET 的需求，BBN 為 DDP-516 增加了專門的硬體——包括一個 24 位元的平行介面（parallel interface）來連接主機，以及一個數據機介面來連接 50 kbps 的電話線路。

## 技術細節

每個 IMP 實際上是一台專用的分組交換電腦，運行 BBN 開發的特殊軟體。它的工作包括：
- 接收來自本地主機的訊息，分割成更小的分組（packet）
- 根據路由表將分組轉發給鄰近的 IMP
- 接收來自其他 IMP 的分組，重組成完整的訊息，傳送給本地主機
- 執行錯誤檢查（checksum）與重傳機制
- 管理 32 條邏輯鏈路（logical links）

DDP-516 的處理能力雖然僅有約 0.5 MIPS，但對於分組交換的任務已經足夠。BBN 的工程師在軟體中實現了動態路由、流量控制與錯誤恢復機制——這些都是網路設計中的開創性工作。

## 從 IMP 到網際網路

第一台 IMP 在 1969 年 8 月交付給 UCLA。到 1969 年底，四台 IMP 分別安裝在 UCLA、SRI、UCSB 和猶他大學，形成了 ARPANET 的最初四節點網路。每台 IMP 的造價約為 10 萬美元。

Honeywell DDP-516 在網路歷史上的地位獨特：它既是硬體，也是網路架構的具體實現。這款原本用於工業控制的迷你電腦，意外地成為了網際網路的第一代路由器。

## 延伸閱讀

- [IMP - Wikipedia](https://en.wikipedia.org/wiki/Interface_Message_Processor)
- [BBN 與 ARPANET - Computer History Museum](https://www.computerhistory.org/revolution/networking/18/222)
- [Honeywell DDP-516 歷史](https://en.wikipedia.org/wiki/Honeywell_DDP-516)
