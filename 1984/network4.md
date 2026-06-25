# INMOS Transputer T414：平行處理的先鋒

## 一台晶片上的電腦

1984 年，英國的 INMOS 公司發表了 Transputer T414——一顆專為平行處理設計的微處理器。Transputer 的設計理念極為大膽：把處理器、記憶體和通訊鏈路整合在同一顆晶片上。

T414 是 32 位元處理器，執行速度高達 10 MIPS，內建 2KB SRAM，並配備四個雙向序列通訊鏈路（links）。每條鏈路的傳輸速度可達 20 Mbps。這些鏈路允許 Transputer 與其他 Transputer 直接連接，形成任意拓撲的平行處理網路。

## Occam 語言

Transputer 的設計與程式語言 Occam 緊密結合。Occam 以 Communicating Sequential Processes（CSP）為理論基礎——這是 Tony Hoare 提出的並行計算模型。在 Occam 中，程式設計師可以描述多個平行程序，透過通道（channel）進行通訊——這與 Transputer 的硬體架構完美對應。

## 未被實現的願景

Transputer 在技術上非常先進，但商業上並未取得成功。IBM PC 的統治地位使得以 x86 為核心的傳統架構持續主導市場，平行處理的市場需求在 1980 年代還不夠成熟。

不過，Transputer 的概念——多核心、晶片內網路、並行程式語言——在 21 世紀多核心時代重新變得重要。現代 GPU 的數百個核心、Intel Xeon Phi、以及各種 AI 加速器，在某種程度上都是 Transputer 願景的延續。

## 延伸閱讀

- [Transputer - Wikipedia](https://en.wikipedia.org/wiki/Transputer)
- [INMOS - Wikipedia](https://en.wikipedia.org/wiki/INMOS)
