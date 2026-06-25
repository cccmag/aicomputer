# Arduino Yún 與物聯網開發

## 物聯網時代的開發平台

2012 年，Arduino 團隊發表了 Arduino Yún——一款專為物聯網應用設計的開發板。Yún 的特殊之處在於它搭載了兩顆處理器：一顆 ATmega32U4 微控制器（運行 Arduino 程式），另一顆 Atheros AR9331 處理器（運行 Linux 系統，基於 OpenWrt）。

這種雙處理器架構讓 Yún 同時擁有 Arduino 的即時控制能力和 Linux 的網路連接能力。開發者可以在 Arduino 端控制感測器和執行器，同時透過 Linux 端連接 Wi-Fi、處理 HTTP 請求、以及執行 Python 或 Node.js 腳本。

## 技術規格

Arduino Yún 支援 802.11b/g/n Wi-Fi、乙太網路、USB 主機、Micro SD 卡槽。Linux 端提供 REST API 和 Bridge 函式庫，讓 Arduino 端可以輕鬆呼叫 Linux 端的服務。

## 物聯網開發的里程碑

Yún 的發表象徵著物聯網開發從專業嵌入式工程師走向一般軟體開發者和業餘愛好者的趨勢。它降低了建立網路連結裝置的門檻，讓更多人可以參與物聯網應用的原型開發。與 Raspberry Pi 不同，Arduino Yún 的目標是連接感測器和控制實體世界，而非作為一個通用電腦。

## 延伸閱讀

- [Arduino Yún - Wikipedia](https://en.wikipedia.org/wiki/Arduino_Y%C3%BAn)
- [Arduino 官方網站](https://www.arduino.cc/)
