# Intel 8008：8 位元微處理器的先驅

## 來自 Datapoint 的委託

Intel 8008 的故事始於德州電腦終端機公司 Datapoint（原名 CTC）。Datapoint 正在開發 Datapoint 2200 可程式終端機，需要一顆 8 位元 CPU。1969 年，他們請 Intel 和德州儀器（TI）分別製作一顆單晶片處理器。

TI 先退出了這個專案。Intel 的工程師們——包括 Vic Crisman 和 Hal Feeney——在 4004 之後開始設計 8008。由於 Datapoint 對晶片封裝引腳數的限制（18 引腳），8008 採用了復用的位址/資料匯流排設計。

## 技術規格

8008 在 1971 年 11 月完成設計（比 4004 稍晚宣布，1972 年 4 月正式上市）：
- **架構**：8 位元
- **電晶體數量**：3,500
- **時脈速度**：500 kHz（後期版本可達 800 kHz）
- **製程**：10 μm p-MOS
- **包裝**：18 引腳 DIP
- **位址空間**：16 KB
- **指令集**：48 條指令

## 意外的傳承

有趣的是，Datapoint 對 8008 的設計並不滿意——晶片速度比他們預期的慢，而且 18 引腳的限制造成了效能瓶頸。Datapoint 最終用 TTL 邏輯元件自行建造了 CPU。

但 8008 的指令集架構被證明極具生命力。它的指令集設計直接影響了 Intel 8080（1974），而 8080 又影響了 8086——x86 架構的起源。換句話說，每台現代 PC 的處理器都間接源自 Datapoint 2200 的設計需求。

## 延伸閱讀

- [Intel 8008 - Wikipedia](https://en.wikipedia.org/wiki/Intel_8008)
- [Datapoint 2200 與 8008 的故事](https://www.computerhistory.org/revolution/digital-logic/12/280)
