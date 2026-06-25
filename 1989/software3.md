# NeXTSTEP：物件導向作業系統的先驅

## 從 Mach 到 NeXTSTEP

NeXTSTEP 是 NeXT 電腦的作業系統，它的開發始於 1986 年，到 1989 年隨著 NeXT Computer 的正式出貨而完整發布。NeXTSTEP 的軟體堆疊由幾個層次構成：

底層是 **Mach 核心**——由卡內基美隆大學開發的微核心作業系統，負責行程管理、記憶體處理和中斷處理。Mach 之上是 **BSD Unix** 環境，提供 POSIX API、網路協定和開發工具。

最上層是 **NeXTSTEP 的圖形使用者介面**——基於 Display PostScript 技術，這意味著螢幕上和紙張上的文字與圖形使用相同的繪圖模型。這是一個極為先進的設計決策。

## 革命性的開發環境

NeXTSTEP 最令人驚嘆的部分是它的開發工具：

- **Interface Builder**：可視化介面設計工具，開發者可以拖放 UI 元件，然後直連到後端程式碼
- **Objective-C**：物件導向的 C 語言擴展，支援動態綁定
- **Application Kit**：一套完整的 UI 組件庫

這些工具讓開發者能夠以極快的速度建立圖形化的應用程式。Tim Berners-Lee 選擇 NeXT 來開發第一個網頁瀏覽器，正是因為 NeXTSTEP 讓他能夠「在幾個月內完成在其他平台上需要一年才能做到的事」。

## 從 NeXTSTEP 到 Mac OS X

1997 年 Apple 收購 NeXT 後，NeXTSTEP 的核心技術——Mach 核心、Objective-C 和 Interface Builder——成為了 Mac OS X 的基礎。現代的 macOS、iOS、iPadOS 的本質都是 NeXTSTEP 的後代。

## 延伸閱讀

- [NeXTSTEP - Wikipedia](https://en.wikipedia.org/wiki/NeXTSTEP)
- [Mach 核心 - Wikipedia](https://en.wikipedia.org/wiki/Mach_(kernel))
- [Objective-C - Wikipedia](https://zh.wikipedia.org/wiki/Objective-C)
