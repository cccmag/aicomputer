# MIPS R2000：商業化 RISC 架構

## 精簡指令集的崛起

1984 年，John Hennessy 在史丹佛大學的研究團隊開發了 MIPS（Microprocessor without Interlocked Pipeline Stages）架構——這是 RISC（精簡指令集電腦）概念的重要實踐。

Complex Instruction Set Computer（CISC）的設計哲學——讓硬體提供豐富的指令來簡化程式設計師的工作——在主導了 1970 到 1980 年代初期的處理器設計後，開始面臨挑戰。Hennessy 和柏克萊的 David Patterson 各自提出了相反的觀點：與其讓指令越來越複雜，不如讓指令非常簡單，但用優化的編譯器和管線化執行來達到更高的效能。

## MIPS R2000 的技術特徵

MIPS R2000 是第一個商業化的 RISC 處理器晶片組，雖然正式出貨在 1986 年，但其設計工作和架構定義在 1984 年已經展開。R2000 的關鍵設計包括：

**固定長度 32 位元指令**：所有指令大小相同，簡化了解碼邏輯和管線控制。

**載入-儲存架構**：只有載入（load）和儲存（store）指令能存取記憶體，所有運算都在暫存器之間進行。

**延遲槽（delay slot）**：在分支指令後安排一個無論跳轉與否都會執行的指令位置。

## 歷史定位

MIPS R2000 是 RISC 從學術論文走向商業產品的關鍵一步。它的成功驗證了 Patterson 和 Hennessy 的理論——精簡指令集可以比複雜指令集更快、更省電。R2000 被用於 SGI 圖形工作站、DECstation 和嵌入式系統，為後來的 ARM 和 RISC-V 鋪平了道路。

## 延伸閱讀

- [MIPS R2000 - Wikipedia](https://en.wikipedia.org/wiki/R2000_microprocessor)
- [John Hennessy - Wikipedia](https://en.wikipedia.org/wiki/John_L._Hennessy)
