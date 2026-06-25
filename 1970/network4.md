# TELNET 協定：遠端登入的誕生

## 遠端登入的需求

ARPANET 的核心目標是讓一台電腦的使用者能夠使用遠端系統的資源。為了實現這個目標，需要一個標準化的方法來建立遠端終端連線——這就是 TELNET 協定。

TELNET（Teletype Network Protocol）是 ARPANET 上最早定義的應用層協定之一，由 Network Working Group 在 1970 年開發。它的設計目標是提供一個通用的、雙向的、面向字元的通訊服務。

## 網路虛擬終端

TELNET 引入了一個關鍵概念：**網路虛擬終端**（Network Virtual Terminal，NVT）。NVT 是一個假想的標準終端，定義了最基本的顯示和控制能力。用戶端的 TELNET 程式將本地終端的特性轉換為 NVT 格式，伺服器端的 TELNET 程式再將 NVT 轉換為伺服器能理解的形式。

```
使用者終端 <-> TELNET 用戶端 <-> NVT <-> TELNET 伺服器 <-> 應用程式
```

這個架構解決了一個根本性問題：不同廠商的終端（如 DEC VT100、IBM 3270、Teletype ASR33）使用不同的控制碼，透過 NVT 抽象層，任何終端都可以與任何遠端系統通訊。

## TELNET 選項協商

TELNET 還定義了一套選項協商機制，允許用戶端和伺服器動態協商功能，如回顯模式、行模式、終端類型等。這為後來的協定設計提供了重要範例。

## 延伸閱讀

- [TELNET Protocol - RFC 15](https://www.rfc-editor.org/rfc/rfc15)
- [TELNET - Wikipedia](https://en.wikipedia.org/wiki/Telnet)
