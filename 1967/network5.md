# IBM 二元同步通訊：早期網路協定

## 資料連結的先驅

1967 年，IBM 推出了二元同步通訊（Binary Synchronous Communications, BSC 或 Bisync）——一種調節字符資料在傳輸線路上流動速度的通信技術。Bisync 是早期電腦網路中最重要的通訊協定之一。

Bisync 是一種半雙工（half-duplex）協定，意味著資料可以在兩個方向上傳輸，但同一時間只能有一個方向。它使用特定的控制字符來標記訊息的開始和結束，並透過檢查和（checksum）來偵測傳輸錯誤。

## 技術特點

Bisync 的主要功能包括：
- 同步傳輸（使用時鐘信號而非起始位元來同步）
- 透明模式（允許在資料中傳輸任何位元組合）
- 錯誤偵測與自動重傳請求
- 支援點對點和多點連線配置

## 從專屬到標準

Bisync 是 IBM 的專屬協定，但它被廣泛採用，成為 1970 年代大型主機通訊的標準方式。後來 IBM 開發了 SDLC（同步資料鏈路控制），被國際標準化為 HDLC（高階資料鏈路控制），影響了 X.25、Frame Relay 等協定。

Bisync 的設計哲學——在不可靠的線路上實現可靠的資料傳輸——是所有後續通訊協定的共同基礎。

## 延伸閱讀

- [Binary Synchronous Communications - Wikipedia](https://en.wikipedia.org/wiki/Binary_Synchronous_Communications)
- [IBM 通訊協定歷史 - Google 搜尋](https://www.google.com/search?q=IBM+Bisync+1967+%E9%80%9A%E4%BF%A1%E5%8D%94%E5%AE%9A)
