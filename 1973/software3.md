# C 語言的持續發展

## 第二年的 C

如果說 1972 年是 C 語言的誕生之年，1973 年就是它的成長之年。Dennis Ritchie 在貝爾實驗室持續改進 C 的設計，修正語法上的不一致，並增強編譯器的能力。

1973 年最重要的進展是 C 編譯器的自我宿主（self-hosting）——編譯器本身開始用 C 語言來撰寫，不再依賴組合語言或 B 語言來編譯自己。這是一個語言成熟的重要里程碑。

## Unix V4：完全用 C 重寫

1973 年 11 月，Ken Thompson 和 Dennis Ritchie 在第四屆 SOSP（作業系統原理研討會）上發表了一篇關於 Unix 的論文。這篇論文描述的 Unix 第四版已經用 C 語言**完全重寫了核心**——這是有史以來第一個用高階語言實作的可移植作業系統核心。

有趣的是，Ritchie 後來承認，如果不是為了寫這篇論文，他們可能不會這麼快完成完全重寫的工作。論文截止日期驅動了工程進度——這是軟體工程史上反覆出現的模式。

## C 的演進：1973 年版的特性

1973 年的 C 與我們今天熟悉的 C 還有一些差異：

- 結構體（struct）已經出現，但賦值還不能直接複製結構體
- 沒有聯合體（union）——這個特性要等到 1978 年的 K&R C
- 沒有 unsigned 修飾詞
- 函數的參數型別宣告還沒有標準化
- long long、float（而非 double 為預設）等細節尚未確定

但核心語法——表達式、控制流程、函數、指標、陣列——已經與最終的 C 非常接近。

## 影響

1973 年的 C 語言已經足夠成熟，可以用來撰寫真正的作業系統。這證明了 Ritchie 最初的設計信念：一個高階語言可以產生足夠高效的程式碼來做系統程式設計。這個信念——以及它的實際驗證——改變了軟體產業的面貌。

## 延伸閱讀

- [C 語言發展史 - Dennis Ritchie](https://www.bell-labs.com/usr/dmr/www/chist.html)
- [Unix 歷史 - Bell Labs](https://www.bell-labs.com/usr/dmr/www/hist.html)
- [C 語言 1973 - Google 搜尋](https://www.google.com/search?q=C+language+1973+Unix+rewrite)
