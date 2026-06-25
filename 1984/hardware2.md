# IBM PC/AT：80286 與 16 位元標準

## 個人電腦的效能躍進

1984 年 8 月 14 日，IBM 推出了 PC/AT（Advanced Technology），搭載 Intel 80286 處理器。PC/AT 是 IBM PC 家族的第二代重大升級，代表個人電腦從 8 位元正式跨入 16 位元時代。

PC/AT 的核心是 Intel 80286，主頻 6 MHz（後來的型號升級到 8 MHz）。80286 有兩個重要特性：真正的 16 位元資料匯流排（相對於 8088 的 8 位元外部匯流排）和保護模式（Protected Mode）。保護模式允許處理器存取多達 16MB 的記憶體，並提供了硬體層級的記憶體保護。

## 規格與影響

PC/AT 配備 256KB RAM（可擴充至 3MB）、1.2MB 高密度軟碟機、20MB 硬碟、以及新的 84 鍵鍵盤（AT 鍵盤）。售價約 5,290 美元。

PC/AT 也引入了許多延續數十年的標準：AT 主機板尺寸、AT 電源供應器、以及 ISA 16 位元匯流排。這些標準使 PC/AT 不僅是一台電腦，更是一個產業平台。

## 80286 的遺憾

80286 的保護模式雖然技術上先進，但與 8086 的執行模式（Real Mode）不相容——開機時只能在 Real Mode 下執行 DOS，無法在保護模式下執行 DOS 應用。這個問題直到 80386 的虛擬 8086 模式才被解決。因此 80286 的保護模式從未被充分利用。

## 延伸閱讀

- [IBM PC/AT - Wikipedia](https://en.wikipedia.org/wiki/IBM_Personal_Computer/AT)
- [Intel 80286 - Wikipedia](https://en.wikipedia.org/wiki/Intel_80286)
