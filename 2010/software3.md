# Apple 內部 Swift 語言的開發

## 一個秘密專案的開始

2010 年，Apple 的 Chris Lattner——LLVM 專案的核心開發者——開始在業餘時間啟動了一個全新的程式語言設計專案。這個專案後來被命名為 Swift，但直到 2014 年的 WWDC 才被公開。

Swift 的誕生背景是 Apple 對 Objective-C 的限制感到不滿。Objective-C 雖然在 1980 年代被設計為 Smalltalk 風格的物件導向語言，但它在型別安全、效能、記憶體管理和語法現代化方面都存在問題。Apple 需要一個新的語言來為接下來十年的 iOS 和 Mac 開發提供動力。

## Swift 的設計目標

Lattner 在 2010 年確定的 Swift 設計目標：

**安全**：消除 Objective-C 中常見的程式設計錯誤——空指標解參考、數值溢位、未初始化的變數。Swift 引入了 optional 型別和強制初始化來達到這個目標。

**現代**：Swift 借鑒了多種語言的設計——包括 Ruby、Python、Haskell、Rust 和 C#——融入了函數式程式設計概念（map、filter、reduce）、模式匹配、泛型和型別推斷。

**快速**：Swift 基於 LLVM 編譯器基礎設施，可以生成與 C 語言匹敵的原生機器碼。

**Objective-C 互操作性**：Swift 必須能夠與現有的 Objective-C 程式碼無縫互通——這是一個務實的設計決策，讓開發者可以逐步遷移而非全部重寫。

## 對未來的深遠意義

雖然 Swift 在 2010 年只是一個人的 side project，但它代表了 Apple 對開發者生態系統的長期投資。Swift 最終在 2014 年發布，成為了 iOS、macOS、watchOS 和 tvOS 的主要開發語言，也作為開源語言在 Linux 和伺服器端被廣泛使用。

## 延伸閱讀

- [Swift - Wikipedia](https://zh.wikipedia.org/wiki/Swift)
- [Chris Lattner 的 Swift 歷史](https://oleb.net/2020/swift-history/)
- [Swift 開源專案](https://swift.org/)
