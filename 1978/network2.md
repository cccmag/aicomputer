# XMODEM 協定：檔案傳輸的標準

## 為了解決一個簡單問題

1978 年，Ward Christensen 和 Randy Suess 在開發 CBBS 時面臨一個實際問題：他們的家相距約 30 英里，需要一種可靠的方式透過電話線傳送檔案。當時的數據機（300 bps）在噪音環境下經常發生傳輸錯誤，而現有的傳輸方式沒有錯誤檢測機制。

Christensen 在 1977 年就開始思考這個問題。1978 年 CBBS 專案期間，他設計並實作了 XMODEM 協定——第一個在 PC 上廣受採用的點對點檔案傳輸協定。

## XMODEM 的工作原理

XMODEM 將檔案分割為 128 位元組的區塊（block）。每個區塊傳送後，接收方會檢查 checksum 來驗證資料是否完整：如果正確，回傳 ACK 確認字元；如果有錯誤，回傳 NAK 要求重新傳送。如果連續 10 次傳送失敗則放棄。

這種「停止-等待自動重送」（Stop-and-Wait ARQ）機制簡單但有效。在 300 bps 的時代，128 位元組區塊的大小是合理的折衷——太大會增加噪音環境下重新傳送的成本，太小會降低效率。

## 影響

XMODEM 後來被擴充為 XMODEM-CRC、XMODEM-1K、YMODEM、ZMODEM 等家族。在 1980 年代和 1990 年代初的 BBS 文化中，XMODEM 是檔案交換的標準方法。它的設計思想——區塊傳送、錯誤檢測、自動重送——影響了後來所有的檔案傳輸協定。

## 延伸閱讀

- [XMODEM - Wikipedia](https://en.wikipedia.org/wiki/XMODEM)
- [Ward Christensen 的 XMODEM 故事 - Google 搜尋](https://www.google.com/search?q=Ward+Christensen+XMODEM+history)
