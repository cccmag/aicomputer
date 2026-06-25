# 多核心處理器：從雙核到四核

## 時脈競賽的終結

Intel Pentium 4 時代的「時脈競賽」——追求更高的 GHz 數字——在 2004 年左右因功耗和散熱問題而終結。產業轉向了多核心架構：在同一顆晶片封裝多個處理器核心來提升效能。

2008 年是多核心處理器全面進入主流市場的一年。Intel 的 Core 2 Quad 系列和 AMD 的 Phenom 系列將四核心處理器帶到了消費級價位。同時，Intel 在 11 月正式發布了 Nehalem 微架構的 Core i7 處理器（代號 Bloomfield）——整合記憶體控制器、QPI 互連、三通道 DDR3、並重新引入超執行緒。

## 從雙核到多核的轉變

2008 年的處理器市場景觀：

| Intel | 核心數 | AMD | 核心數 |
|-------|--------|-----|--------|
| Core 2 Duo E8000 系列 | 雙核 | Athlon X2 | 雙核 |
| Core 2 Quad Q9000 系列 | 四核 | Phenom X3 | 三核 |
| Core i7-9xx (Nehalem) | 四核 (八執行緒) | Phenom X4 | 四核 |

AMD 的 Phenom 處理器引入了獨特的三核心設計——一種利用有缺陷的四核心晶片來服務主流市場的策略。

## 程式設計的挑戰與機會

多核心處理器的普及對軟體開發產生了深遠影響。摩爾定律不再能自動提升單執行緒程式的效能——程式設計師需要學習平行程式設計。

OpenMP、Intel TBB（Threading Building Blocks）、以及 POSIX Threads 等平行程式設計技術在 2008 年獲得了更多關注。在消費領域，多核心讓使用者可以同時執行多個應用程式而不會降低系統回應速度。

## 延伸閱讀

- [多核心處理器 - Wikipedia](https://zh.wikipedia.org/wiki/%E5%A4%9A%E6%A0%B8%E5%A4%84%E7%90%86%E5%99%A8)
- [Intel Core i7 (Nehalem) 發表](https://www.intel.com/pressroom/archive/releases/2008/20081117comp.htm)
