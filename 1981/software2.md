# SMTP 協定：電子郵件的標準化

## 從實驗到標準

電子郵件在 1970 年代早期就已在 ARPANET 上使用——Ray Tomlinson 在 1971 年發送了第一封網路電子郵件。但早期的郵件傳輸協定各不相同，不同系統之間無法互通。

1981 年，Jonathan Postel 和 Joyce Reynolds 在 RFC 788 中定義了 SMTP（Simple Mail Transfer Protocol）。SMTP 是一個基於文字的協定——客戶端（Client）透過 TCP 連線到伺服器（Server）的 25 號通訊埠，以一系列 ASCII 命令傳送郵件。

## SMTP 的運作

一個典型的 SMTP 連線如下：
```
HELO client.example.com
MAIL FROM:<user@example.com>
RCPT TO:<recipient@other.org>
DATA
From: user@example.com
To: recipient@other.org
Subject: Hello

Hello, this is a test.
.
QUIT
```

SMTP 的「簡單」是刻意為之——使用純文字、人類可讀的指令、不需要複雜的狀態管理。這種設計讓 SMTP 極易實作和除錯，也讓它快速成為電子郵件傳送的標準協定。

## 延伸閱讀

- [SMTP - Wikipedia](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol)
- [RFC 788 - SMTP (1981)](https://datatracker.ietf.org/doc/html/rfc788)
- [Jonathan Postel - Wikipedia](https://en.wikipedia.org/wiki/Jon_Postel)
