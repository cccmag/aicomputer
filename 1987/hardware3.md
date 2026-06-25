# SPARC 處理器：RISC 架構的商業化

## RISC 從實驗室到市場

1987 年，Sun Microsystems 發表了 SPARC（Scalable Processor ARChitecture）處理器。SPARC 是 RISC（精簡指令集計算）架構的商業化代表，由 David Patterson 和 John Hennessy 在 UC Berkeley 的研究成果衍生而來。

SPARC 的核心設計哲學非常簡單：減少指令的數量，讓每個指令都在一個時脈週期內執行完畢。這與當時主流的 CISC 架構（如 Intel 的 x86）形成鮮明對比——CISC 擁有大量複雜指令，但需要多個時脈週期來執行。

## 技術優勢

第一代 SPARC 處理器採用 32 位元架構，時脈約 20 MHz，但在整數運算性能上明顯優於同頻率的 CISC 處理器。它的關鍵特性包括：

- **暫存器視窗（Register Windows）**：允許函數呼叫時快速切換暫存器組，減少記憶體存取的次數
- **延遲分支（Delayed Branch）**：利用分支指令後的一個指令槽來做有用的工作
- **純載入/儲存架構**：只有 load 和 store 指令能存取記憶體，運算指令只能在暫存器之間進行

## 深遠的影響

SPARC 處理器被廣泛用於 Sun 的工作站和伺服器產品線，從 Sun-4 系列到後來的 UltraSPARC。在 1990 年代，SPARC 是 Unix 工作站市場的主流架構之一，與 MIPS、PA-RISC 和 PowerPC 競爭。

SPARC 的成功驗證了 RISC 架構的商業可行性，也間接促使 Intel 在後來的 Pentium Pro 等處理器中引入 RISC 風格的內部微架構。

## 延伸閱讀

- [SPARC - Wikipedia](https://zh.wikipedia.org/wiki/SPARC)
- [RISC - Wikipedia](https://zh.wikipedia.org/wiki/%E7%B2%BE%E7%AE%80%E6%8C%87%E4%BB%A4%E9%9B%86%E8%AE%A1%E7%AE%97)
- [Sun Microsystems - Wikipedia](https://zh.wikipedia.org/wiki/Sun_Microsystems)
