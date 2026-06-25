# Intel Pentium III 與 SSE 指令集

## Katmai 核心的登場

1999 年 2 月 26 日，Intel 正式推出了 Pentium III 處理器。這款代號 Katmai 的處理器是 Pentium II 的後繼產品，初期版本與 Pentium II 非常相似，使用相同的 0.25 µm 製程和 Slot 1 插槽。

首批推出的速度是 450 MHz 和 500 MHz，隨後在 5 月推出 550 MHz，8 月推出 600 MHz 版本。

## SSE 指令集

Pentium III 最重要的新增功能是 SSE（Streaming SIMD Extensions）指令集，這是一組 70 條新指令，專門針對浮點運算和多媒體處理進行優化。SSE 是 Intel 對 AMD 3DNow! 技術的回應，後來發展成為 SSE2、SSE3、SSSE3 等更完整的指令集家族。

SSE 讓處理器可以在單一指令中同時處理多個資料，顯著提升了 3D 圖形、影片編碼和科學運算的效能。

## 處理器序號爭議

Pentium III 引入了備受爭議的處理器序號（Processor Serial Number, PSN）功能。每個 Pentium III 晶片在製造過程中都被嵌入了一個獨一無二的序號，軟體可以透過 CPUID 指令讀取。

隱私倡導者強烈反對這項功能，認為它可能被用來追蹤使用者的網路活動。部分使用者因此轉向 AMD Athlon。Intel 後來在 Pentium 4 中移除了這項功能，但多年後又以 PPIN 的形式悄悄重新引入。

## Coppermine 核心

1999 年 10 月 25 日，Intel 推出了 Pentium III Coppermine 核心。這款處理器採用 0.18 µm 製程，最大的改進是將 L2 快取整合到處理器核心內部（稱之為片載快取），實現了全速運作和更低的延遲。

Coppermine 在同頻率下比 Katmai 平均效能提升 30%，是 Pentium III 系列中最成功的版本。

## 延伸閱讀

- [Pentium III - Wikipedia](https://zh.wikipedia.org/zh-tw/%E5%A5%94%E9%A8%B0III)
- [SSE 指令集 - Wikipedia](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions)
