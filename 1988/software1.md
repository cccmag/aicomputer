# ANSI C 標準化：C 語言的統一

## 從 K&R 到標準 C

1978 年，Brian Kernighan 和 Dennis Ritchie 出版了《The C Programming Language》第一版，這本書定義了所謂的「K&R C」。然而，隨著 C 語言在 1980 年代的廣泛使用，各家編譯器廠商對語言的擴展造成了相容性問題。

1983 年，美國國家標準協會（ANSI）成立了 X3J11 委員會，負責將 C 語言標準化。經過六年的討論、草案和修訂，ANSI C 標準在 1989 年正式完成，稱為 ANSI X3.159-1989，通常簡稱 C89。1990 年，ISO 採納了這個標準，稱為 ISO/IEC 9899:1990 或 C90。

## 標準化的新特性

相較於 K&R C，C89 加入了重要的新特性：

- **函數原型（Function Prototypes）**：從 C++ 借鑒，允許在呼叫前宣告函數的參數型別
- **void 型別**：明確表示函數不返回任何值
- **const 修飾詞**：定義不可修改的變數
- **volatile 修飾詞**：告知編譯器變數可能被外部改變
- **enum 列舉型別**：定義一組具名的整數常數
- **signed / unsigned**：明確指定整數的有無符號
- **標準函式庫**：規範了 stdio.h、stdlib.h、string.h 等標準標頭檔

## 深遠的影響

ANSI C 的標準化產生了深遠的影響：

- 程式碼可以在不同平台之間移植
- 新的 C 編譯器有了明確的實作參考
- C 語言的教學有了統一的教材基礎
- 為 C++ 的標準化鋪平了道路

C89/C90 是 C 語言的基石，後續的 C99、C11 等標準都在此基礎上擴展。三十多年後，C89 仍然是嵌入式系統和低階程式設計中使用最廣泛的 C 標準之一。

## 延伸閱讀

- [ANSI C - Wikipedia](https://zh.wikipedia.org/wiki/ANSI_C)
- [C 語言歷史 - Dennis Ritchie](https://www.bell-labs.com/usr/dmr/www/chist.html)
- [C89 標準文件](https://www.iso.org/standard/17782.html)
