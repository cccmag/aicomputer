# UNIX 第二版：用 C 改寫的作業系統

## 從組合語言到 C

1969 年夏天，Ken Thompson 在貝爾實驗室的 PDP-7 上寫出了第一版 Unix。這個作業系統完全用 PDP-7 的組合語言撰寫——這是當時所有作業系統的標準做法。但 Thompson 和 Dennis Ritchie 明白，組合語言寫的作業系統無法輕易移植到其他機器上。

1971 年，Unix 被移植到 PDP-11 上，仍然是組合語言。但 1972 年，一個重要的轉折發生了：Ritchie 的 C 語言已經足夠成熟，Thompson 和 Ritchie 開始用 C 改寫 Unix。

## Unix 第二版（V2）

1972 年發布的 Unix 第二版是電腦史上的里程碑。核心中約有一半的程式碼用 C 語言重新實作，剩下的部分——特別是與底層硬體互動的驅動程式和中斷處理——仍保留組合語言。

這次重寫的意義不僅在於技術，更在於哲學：作業系統不再被綁死在特定的硬體架構上。如果一個新的機器平台出現，理論上只需要寫一個 C 編譯器和重新實作底層硬體介面，就可以將 Unix 移植過去。

## 管線（pipe）的誕生

Unix V2 引入了一個後來成為系統設計經典的概念——**管線**（pipe）。這個概念是 Thompson 在 1972 年某天晚上突然想到的，他花了一個晚上實作了管線機制。

管線讓程式設計師可以用 `|` 符號將兩個程式的輸出和輸入連接起來：

```
who | wc -l
```

這個簡單的「程式 A 的輸出餵給程式 B 的輸入」模型，體現了 Unix 的核心哲學：撰寫只做好一件事的程式，並將它們組合起來完成複雜的任務。

## 對未來的深遠影響

Unix 以 C 語言重寫的決定，最終導致了：

- 1973 年的 Unix V4 用 C 完全重寫核心
- 1970 年代末的 BSD Unix
- 1980 年代的 System V 和各種商業 Unix
- 1991 年的 Linux
- 現代幾乎所有作業系統的核心概念

## 延伸閱讀

- [Unix 歷史 - Bell Labs](https://www.bell-labs.com/usr/dmr/www/hist.html)
- [Unix 歷史 - Wikipedia](https://en.wikipedia.org/wiki/History_of_Unix)
- [UNIX 第二版 - Google 搜尋](https://www.google.com/search?q=UNIX+second+edition+1972+C+language)
