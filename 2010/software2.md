# AngularJS 的開始：前端框架的新時代

## Misko Hevery 的 Side Project

2010 年，Google 工程師 Misko Hevery 開始開發一個名為 AngularJS 的前端 JavaScript MVC 框架。Hevery 最初是在業餘時間為了解決 Web 應用開發中的一些痛點而創建了這個專案——特別是他對傳統 HTML 與動態資料綁定之間的重複性工作感到不滿。

AngularJS 的核心創新是「宣告式」的 HTML 模板。傳統的 jQuery 風格開發涉及大量的 DOM 操作命令——程式設計師需要明確告訴瀏覽器如何更新使用者介面。AngularJS 引入了一種綁定機制，開發者只需要宣告資料模型與 HTML 元素之間的關係，Angular 會自動處理 DOM 更新。

## 雙向資料綁定

AngularJS 最引人注目的功能是雙向資料綁定（two-way data binding）。在傳統的 Web 開發中，如果一個輸入框的值發生變化，開發者必須手動更新資料模型；如果資料模型發生變化，又必須手動更新使用者介面。

AngularJS 自動處理了這個同步過程：當資料模型改變時，檢視自動更新；當檢視改變時（如使用者輸入），資料模型自動更新。這個模式大幅簡化了表單處理和即時資料更新的程式碼。

## 相依注入

AngularJS 從 Google 的 Java 框架（如 Guice）引入了相依注入（Dependency Injection）的概念——這是傳統 JavaScript 開發中不常見的設計模式。在 Angular 中，開發者不需要手動建立服務、控制器和其他元件的實例——框架會自動注入所需的依賴項。

## 對 Web 開發的深遠影響

AngularJS 在 2010 年還只是一個業餘專案——它在 2012 年才發布 1.0 正式版。但它所引領的方向——前端 MVC 框架、雙向資料綁定、單頁應用（SPA）——深刻影響了之後的整個前端生態系統。React、Vue、Ember 等框架都以不同的方式回應了 AngularJS 提出的問題。

## 延伸閱讀

- [AngularJS - Wikipedia](https://zh.wikipedia.org/wiki/AngularJS)
- [Misko Hevery 談 AngularJS 的起源](https://www.youtube.com/watch?v=idYGcYGLjls)
- [AngularJS 設計文件](https://docs.angularjs.org/guide/introduction)
