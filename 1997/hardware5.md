# Pentium MMX：多媒體指令集的導入

## 第一款 MMX 處理器

1997 年 1 月 8 日，Intel 推出了 Pentium MMX 處理器，時脈版本包括 166 和 200 MHz。Pentium MMX 是原始 Pentium 架構的改良版本——在保留 Socket 7 腳位的同時，加入了 57 條新的 MMX 指令。

6 月，Intel 追加推出了 233 MHz 版本的 Pentium MMX，這是 Socket 7 平台上最快的 Pentium 處理器。

## MMX 技術細節

MMX（MultiMedia eXtension）是 Intel 對多媒體計算的回應。核心概念是 **SIMD（Single Instruction, Multiple Data）**——一條指令同時處理多個資料：

- 將一個 64 位元暫存器視為 8 個 8 位元、4 個 16 位元或 2 個 32 位元的資料
- 對所有資料同時執行同一運算
- 特別適用於影像、音訊、圖形處理

MMX 暫存器實際上與 x87 浮點暫存器共享——這意味著開發者不能同時使用 MMX 和浮點運算，這是一項設計限制。

## 市場定位

Pentium MMX 定位於主流消費市場，與 Pentium Pro（高階市場）和 Pentium II（即將上市）形成產品線區隔：

- **Pentium MMX**：適合遊戲和多媒體的家用 PC
- **Pentium Pro**：適合伺服器和商業應用的高效能平台
- **Pentium II**：整合兩者優點的下一個世代

Pentium MMX 在 Socket 7 平台上執行，主機板選擇廣泛且價格便宜，因此成為 DIY 市場和入門級品牌電腦的首選。

## 延伸閱讀

- [Pentium MMX - Wikipedia](https://en.wikipedia.org/wiki/Pentium_MMX)
- [MMX 指令集 - Wikipedia](https://en.wikipedia.org/wiki/MMX_\(instruction_set\))
- [Intel 處理器歷史 - Intel](https://www.intel.com/content/www/us/en/history/history-of-intel-processors.html)
