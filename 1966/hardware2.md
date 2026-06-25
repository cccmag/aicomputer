# IBM System/360 Model 91：順序外執行的先驅

## 預告已久的超級電腦

1964 年 IBM 發表 System/360 系列時，同時預告了高效能機型「Model 90」的存在。這款機器最終以 System/360 Model 91 之名於 1966 年 1 月正式發表，成為當時 IBM 效能最強大的電腦。

Model 91 的設計目標是挑戰 CDC 6600（當時世界上最快的電腦），專為太空探索、理論天文學、次原子物理和全球氣象預測等超高密度科學計算而生。

## 超越時代的架構創新

Model 91 最引人注目的技術突破，是它支援「順序外指令執行」（out-of-order execution）——這是電腦架構史上第一次實現這項功能。處理器能夠在執行時期自動從循序的程式碼中發掘並行性，讓多條邏輯上獨立的指令同時執行。

例如，雖然一次浮點加法需要 2 個週期、一次浮點乘法需要 3 個週期，但 Model 91 可以在 3 個週期內同時處理 2 次加法和 1 次乘法，而非循序執行所需的 7 個週期。

這項架構的核心——Tomasulo 演算法——由 IBM 工程師 Robert Tomasulo 設計，後來在 1997 年為他贏得了 ACM Eckert-Mauchly 獎。Tomasulo 演算法透過暫存器重新命名（register renaming）和通用保留站（reservation stations），巧妙地解決了資料冒險（data hazards）問題。

## 內部組織

Model 91 的中央處理單元由五個高度自主的單元組成，可同時運作：

- 處理器儲存單元（Processor Storage）
- 儲存匯流排控制單元（Storage Bus Control）
- 指令處理單元（Instruction Processor）
- 定點處理單元（Fixed-Point Processor）
- 浮點處理單元（Floating-Point Processor）

主機週期時間為 60 奈秒，儲存週期為 780 奈秒，資料流寬度為 8 位元組。這些數據在 1966 年是頂尖水準。

## 商業上的挫折

儘管技術上極具突破性，Model 91 在市場上卻遭遇了失敗。它比預期晚了 9 個月才出貨——第一部機器於 1967 年 10 月才送達 NASA 戈達德太空飛行中心，1968 年 1 月才開始正式運轉。IBM 在 1967 年就停止了訂單接受。

有趣的是，IBM 花了將近 30 年——直到 1990 年代中期——才再次推出採用順序外執行的商業機器。Model 91 的架構創新遠遠領先於它的時代。

## 延伸閱讀

- [IBM System/360 Model 91 - Wikipedia](https://en.wikipedia.org/wiki/IBM_System/360_Model_91)
- [Tomasulo 演算法 - Wikipedia](https://en.wikipedia.org/wiki/Tomasulo%27s_algorithm)
- [Out-of-order processing - IBM Journal 1967](https://american.cs.ucdavis.edu/academic/readings/papers/ibm360-91.pdf)
