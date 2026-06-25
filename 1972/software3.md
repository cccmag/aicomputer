# Smalltalk-72：物件導向的黎明

## 一頁程式碼的賭注

1972 年 9 月，Alan Kay 在 Xerox PARC 打了一個賭：基於訊息傳遞（message passing）概念的程式語言核心，可以用「一頁程式碼」實作出來。大約第八天的早晨，一個可運作的直譯器誕生了——這就是 Smalltalk-72。

Kay 在 1970 年加入 Xerox PARC，擔任學習研究小組（Learning Research Group）的負責人。他的願景是創造一台「Dynabook」——像筆記本一樣便攜、像書本一樣直覺的個人電腦，讓孩子們也能用它來學習和創造。Smalltalk 就是這個願景的軟體核心。

## 第一個實作

1972 年 10 月，Dan Ingalls 用約 700 行的 BASIC 在 Data General Nova 迷你電腦上實作了第一個 Smalltalk-72 直譯器。同年 11 月，Alan Kay 在 MIT 人工智慧實驗室展示了這個系統。

Smalltalk-72 的語法與後來版本截然不同，但核心概念已經確立：

- **萬物皆物件**：數字、字串、編輯器、編譯器都是物件
- **物件透過訊息傳遞溝通**：`receiver message` 是唯一的語法形式
- **類別與實例**：類別定義物件的行為模板，實例是具體的物件
- **動態型別**：型別在執行時期決定

## 位元圖形系統

1972 年 12 月底，Ted Kaehler 實作了 Smalltalk-72 的第一套位元圖畫線程式。這對於 Alan Kay 的願景至關重要——如果 Dynabook 要成為孩子們的創作工具，它必須能夠繪製圖形。

這套位元圖系統後來成為 Xerox Alto 圖形使用者介面的核心技術，並透過 Smalltalk 的 MVC（Model-View-Controller）架構影響了後續所有 GUI 應用程式的設計模式。

## 影響與傳承

Smalltalk-72 雖然只在 PARC 內部使用，但它的概念透過 PARC 的參訪（特別是 1979 年 Steve Jobs 的著名參訪）間接影響了 Apple Lisa 和 Macintosh 的設計。更重要的是，Smalltalk 的訊息傳遞架構直接啟發了 Carl Hewitt 在 MIT 發展的 Actor 模型——一種基於並行獨立代理程式的計算理論。

Smalltalk 在 1976 年演化為 Smalltalk-76（效能顯著提升），1980 年公開釋出 Smalltalk-80，並最終滋養了 Objective-C、Java、Python、Ruby 等現代物件導向語言。

## 延伸閱讀

- [Smalltalk 早期歷史 - Alan Kay](http://www.metaobject.com/papers/Smallhistory.pdf)
- [Smalltalk - Wikipedia](https://en.wikipedia.org/wiki/Smalltalk)
- [Smalltalk-72 歷史 - Google 搜尋](https://www.google.com/search?q=Smalltalk-72+1972+Xerox+PARC)
