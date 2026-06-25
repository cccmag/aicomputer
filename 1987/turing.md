# 1987 年圖靈獎：John Cocke

## RISC 架構之父

John Cocke（1925-2002）是 1987 年 ACM 圖靈獎得主，授獎理由是「對於編譯器設計、計算機架構和 RISC 技術的開創性貢獻」。Cocke 是 IBM 院士，在 IBM 的 Thomas J. Watson 研究中心度過了他的大部分職業生涯。

Cocke 最著名的貢獻是提出了 **RISC（Reduced Instruction Set Computer，精簡指令集計算）** 概念。在 1970 年代中期，Cocke 領導的 IBM 801 專案發現：大多數程式只使用了處理器指令集中的一小部分。與其設計擁有大量複雜指令的處理器（CISC），不如設計一個只包含最常用、最簡單指令的處理器——這些簡單指令可以在一個時脈週期內執行完畢。

## 從經驗觀察到架構革命

801 專案的研究顯示了一個驚人的事實：程式執行時間中，約 80% 的指令只來自指令集中的 20%。像乘法、除法這樣「複雜」的指令很少被使用，卻占據了大量的晶片面積和設計時間。

Cocke 的 RISC 方案是：

- 減少指令數量，只保留最常用的
- 所有指令長度固定，簡化解碼邏輯
- 只有 load 和 store 指令可以存取記憶體
- 大量使用暫存器，減少記憶體存取
- 所有指令都在一個時脈週期內完成

## 商業化的 RISC

IBM 801 雖然沒有直接商業化，但它的概念影響了 1980 年代和 1990 年代的多個 RISC 處理器設計：

- **IBM POWER**（1990）：由 IBM 推出的 RISC 架構，用於 RS/6000 工作站
- **SPARC**（1987）：Sun 的 RISC 架構
- **MIPS**（1985）：由 John Hennessy 在史丹佛開發的 RISC 架構
- **ARM**（1985）：Acorn 的 RISC 架構，後來統治了行動裝置市場

Cocke 的工作不僅改變了處理器設計，也改變了整個計算機產業的方向。他和 John Hennessy 共同被譽為「RISC 之父」。

## 圖靈獎演講

Cocke 在 1987 的圖靈獎演講中回顧了計算機架構的演化，強調了「簡潔就是力量」的設計哲學。他特別提到了編譯器和硬體協同設計的重要性——如果編譯器可以將高階語言高效地翻譯成機器碼，那麼硬體指令集就可以更簡單。

Cocke 還有一句著名的格言：「不要讓完美的成為更好的敵人。」——這句話反映了他務實、以實驗結果為中心的工程哲學。

## 延伸閱讀

- [John Cocke - ACM Turing Award](https://amturing.acm.org/award_winners/cocke_1467266.cfm)
- [John Cocke - Wikipedia](https://en.wikipedia.org/wiki/John_Cocke_(computer_scientist))
- [RISC - Wikipedia](https://zh.wikipedia.org/wiki/精簡指令集計算)
