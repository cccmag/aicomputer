# Intel 386SL：筆記型電腦的省電晶片

## 行動計算的關鍵突破

1990 年，Intel 推出了 386SL 處理器——這是 Intel 第一款專為筆記型電腦設計的晶片。在此之前，可攜式電腦使用的都是桌機版本的處理器，並未針對省電做最佳化。

386SL 與 386DX 的主要差異在於：

- **系統管理模組（SMM, System Management Mode）**：這是一個新增的處理器模式，允許在不中斷應用程式的情況下降低功耗
- **整合記憶體控制器**：減少主機板上的晶片數量，降低功耗和空間需求
- **時脈停止功能**：在工作負載低時可以暫停處理器時脈

## SMM 的長遠影響

System Management Mode 是 386SL 引入的最重要創新之一。當系統進入閒置狀態時，作業系統可以觸發 SMM，讓處理器降低電壓、停止時脈，甚至關閉周邊裝置的電源。當使用者觸碰鍵盤或滑鼠時，系統能在幾毫秒內恢復正常運作。

SMM 後來成為所有 x86 處理器的標準功能，對筆記型電腦的電池續航至關重要。

## 從 386SL 到 Centrino

386SL 的成功讓 Intel 意識到行動市場的重要性。在接下來的十年中，Intel 持續推出專為筆記型電腦設計的處理器版本（如 486SL、Pentium MMX、Pentium III-M），最終在 2003 年推出了 Centrino 平台，將處理器、晶片組和無線網路整合為一。

386SL 的推出標誌著 PC 產業正式意識到：行動計算不是桌機的附屬品，而是一個需要專門設計的獨立產品類別。

## 延伸閱讀

- [Intel 386SL - Wikipedia](https://en.wikipedia.org/wiki/Intel_386SL)
- [筆記型電腦歷史 - Wikipedia](https://en.wikipedia.org/wiki/Laptop)
- [System Management Mode - Wikipedia](https://en.wikipedia.org/wiki/System_Management_Mode)
