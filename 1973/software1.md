# Smalltalk-72 登上 Alto

## 從 Nova 到 Alto

Smalltalk-72 的第一個直譯器在 1972 年 10 月完成於 Data General Nova 迷你電腦上。但 Alan Kay 始終認為 Nova 只是一個暫時的開發平台——他的願景是讓 Smalltalk 執行在個人的、位元圖顯示的、有滑鼠的機器上。1973 年 4 月，這個願望實現了：Dan Ingalls 將 Smalltalk-72 移植到了第一台出廠的 Xerox Alto 上。

這是電腦史上一次關鍵的結合。Alto 提供了硬體基礎——高解析度位元圖顯示器、滑鼠、鍵盤、足夠的記憶體和磁碟儲存。Smalltalk 提供了軟體靈魂——物件導向的程式語言、即時互動的開發環境、以及 Alan Kay 對「Dynabook」的願景。

## Smalltalk-72 的哲學

Smalltalk-72 的設計與當時所有程式語言都截然不同：

- **一切皆物件**：甚至數字 3 也是一個物件，可以接收訊息。`3 + 4` 實際上是向物件 `3` 發送訊息 `+ 4`
- **沒有強制型別**：型別是執行時期決定的事務
- **視覺化開發環境**：使用者可以在圖形介面中瀏覽類別層次、檢查物件狀態、動態修改程式碼
- **即時回饋**：修改程式碼後不需要編譯——效果立即可見

## Demo 與影響

1973 年，Alan Kay 帶著 Alto 上的 Smalltalk 在美國各地進行演示。其中最著名的一次是在 MIT 人工智慧實驗室——在場的 Carl Hewitt 被 Smalltalk 的訊息傳遞機制深深影響。Hewitt 後來發展了 Actor 模型，成為並行程式設計的重要理論基礎。

Smalltalk-72 的演示讓許多人第一次理解「物件導向程式設計」的真正含義。它不像 Simula 67 那樣將類別視為資料抽象的工具，而是將物件視為獨立的、有行為能力的計算實體——一組「微型電腦」透過網路（訊息傳遞）協同工作。

## 延伸閱讀

- [Smalltalk 早期歷史 - Alan Kay](http://www.metaobject.com/papers/Smallhistory.pdf)
- [Smalltalk-72 指令手冊 (1976)](http://www.bitsavers.org/pdf/xerox/parc/techReports/SSL-76-6_Smalltalk-72_Instruction_Manual_Mar76.pdf)
- [Smalltalk 歷史 - Google 搜尋](https://www.google.com/search?q=Smalltalk-72+Alto+1973+Xerox+PARC)
