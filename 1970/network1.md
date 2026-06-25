# ARPANET NCP 協定：網路標準化的關鍵一步

## 主機對主機通訊的需求

ARPANET 在 1969 年成功連接了四個節點後，下一個挑戰是：如何讓不同型號的主機之間可以標準化地通訊？UCLA 的 Steve Crocker 主導的 Network Working Group（NWG）承擔了這個任務。

NWG 由來自 UCLA、SRI、UCSB 和猶他大學的研究生組成——包括 Jon Postel、Vint Cerf 等人。他們在 1970 年初發表了 RFC 33「New HOST-HOST Protocol」，定義了 ARPANET 的第一套主機對主機通訊協定。

## NCP 的設計

NCP（Network Control Program 或 Network Control Protocol）在 1970 年 12 月 15 日完成部署。它實作了三個層次的功能：

**Host-Host Protocol**：管理兩個主機之間的連線建立、資料傳輸和流量控制。它使用 32 位元的 socket 編號來標識主機上的特定程式。

**Initial Connection Protocol (ICP)**：定義了兩台主機上的程式如何建立雙向通訊。ICP 使用一對單向連線（read connection 和 write connection）來構成一個雙向通道。

**應用層協定**：TELNET（遠端登入）和 FTP（檔案傳輸）建立於 NCP 之上。

## 歷史意義

NCP 是網際網路協定發展的第一步。它證明了分組交換網路上的主機對主機通訊是可行的，為後來的 TCP/IP 協定提供了寶貴的經驗。NCP 在 1983 年 1 月 1 日被 TCP/IP 全面取代——這一天被稱為「旗幟日」（Flag Day）。

Steve Crocker 在 1969 年創立的 RFC（Request for Comments）系列文件，至今仍是網際網路標準的文件化機制。

## 延伸閱讀

- [Network Control Protocol - Wikipedia](https://en.wikipedia.org/wiki/Network_Control_Protocol_(ARPANET))
- [RFC 33 - New HOST-HOST Protocol](https://www.rfc-editor.org/rfc/rfc33)
