# BCPL：通往 C 語言的橋樑

## 劍橋的偶然產物

1966 年，英國劍橋大學的 Martin Richards 開發了一種新的程式語言——BCPL（Basic Combined Programming Language）。BCPL 的前身是 CPL（Combined Programming Language），一個由劍橋和倫敦大學共同設計但過於複雜的語言——有人開玩笑說 CPL 的 C 代表「Cambridge」，P 代表「Plus」，L 代表「Language」，合起來就是「CPlusPlusLanguage」。

Richards 簡化了 CPL，去除了一些高層次但難以實現的特性，得到了一種精簡、優雅且功能強大的系統程式設計語言。

## BCPL 的設計哲學

BCPL 的設計非常簡約：

**無型別系統**：BCPL 只有一種資料型別——word（字）。所有變數都是 word，型別由操作符決定而非變數宣告。這使得編譯器非常簡單。

**基於堆疊的記憶體管理**：BCPL 使用堆疊（stack）來管理記憶體。函數呼叫和區域變數都在堆疊上分配，不需要複雜的記憶體管理機制。

**指標的指標**：BCPL 支援「rvalue」和「lvalue」的概念——變數的值和變數的位址——這是指標運算的雛形。

**語法的簡潔性**：BCPL 的語法非常簡潔，使用 `/` 和 `//` 作為註解，用 `{` 和 `}` 作為區塊標記（後來被 C 採用）。

## BCPL 程式碼範例

以下是一個 BCPL 程式的片段——計算階乘：

```
GET "libhdr"

LET fact(n) = n=0 -> 1, n*fact(n-1)

LET start() BE
$(  LET i = 0
    FOR i = 0 TO 10 DO
        writef("fact(%N) = %N*N", i, fact(i))
$)
```

這個範例展示了 BCPL 的幾個特點：使用 `LET` 宣告變數、用 `->` 表示條件運算式（類似於 C 的 `?:`）、用 `$( ... $)` 作為區塊標記。

## 從 BCPL 到 B 到 C

BCPL 的歷史意義在於它直接啟發了兩個後繼語言：

**B 語言**：1969 年，Ken Thompson 為 PDP-7 上的 Unix 開發了 B 語言。他從 BCPL 中借鑒了大部分語法，但為了適應 PDP-7 有限的記憶體（僅 4 Kwords），做了進一步的精簡。B 語言是一種直譯式語言，使用 Thompson 撰寫的直譯器執行。

**C 語言**：1971 年左右，Dennis Ritchie 在 B 語言的基礎上添加了資料型別和結構，發展出了 C 語言。C 語言保留了 BCPL 和 B 的精簡風格，但加入了豐富的資料型別系統、強型別檢查和預處理器。

## 深遠影響

BCPL 的極簡設計理念——「少即是多」——深刻地影響了 C 語言的設計。C 語言繼承了 BCPL 對程式設計師的信任：它假設程式設計師知道自己在做什麼，並給予他們接近硬體的能力。

這個設計哲學——後來被稱為「系統程式設計語言的實用主義」——與 Dijkstra 和 Wirth 等人提倡的結構化方法形成了有趣的張力。BCPL 和 C 追求的是效率和靈活性，而非純潔性和可證明性。

## 延伸閱讀

- [BCPL 語言 - Wikipedia](https://en.wikipedia.org/wiki/BCPL)
- [Martin Richards - BCPL 參考手冊](https://www.cl.cam.ac.uk/~mr10/BCPL.html)
- [B 語言 - Wikipedia](https://en.wikipedia.org/wiki/B_(programming_language))
