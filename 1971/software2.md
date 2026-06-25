# LISP 語言的發展：AI 與函數式程式設計

## 從 McCarthy 到 LISP 1.5

John McCarthy 在 1958 年於 MIT 開發了 LISP（LISt Processing）語言，並在 1960 年發表了經典論文「Recursive Functions of Symbolic Expressions and Their Computation by Machine」。到 1971 年，LISP 已經發展到 LISP 1.5 版本，配備了完整的直譯器和編譯器。

LISP 的核心概念是：**程式就是資料，資料就是程式**。LISP 的語法——S 表達式（S-expression）——使用括號嵌套列表來表示一切：

```lisp
(define (factorial n)
  (if (= n 0)
      1
      (* n (factorial (- n 1)))))
```

## LISP 的革命性貢獻

LISP 引入了多項改變計算機科學的概念：
- **垃圾回收**（Garbage Collection）：自動回收不再使用的記憶體
- **高階函式**：函式可以接受函式作為參數，也可以回傳函式
- **遞迴**：LISP 第一個將遞迴作為主要的控制流程機制
- **符號運算**：LISP 對符號而非純數字的處理能力，使它成為 AI 研究的理想語言

## 1971 年的 AI 世界

在 1971 年，LISP 是人工智慧領域的主導語言。McCarthy 於 1965 年在史丹佛創立的 AI 實驗室（SAIL）是 LISP 研究的重鎮。DARPA 贊助了多個 LISP 專案，包括自動定理證明、自然語言處理和機器人規劃。

LISP 機（LISP Machine）的概念也在這個時期開始醞釀——專門設計用來高效執行 LISP 程式的計算機。這最終在 1970 年代後期導致了 MIT 的 CADR 機器。

## 延伸閱讀

- [LISP (programming language) - Wikipedia](https://en.wikipedia.org/wiki/Lisp_(programming_language))
- [John McCarthy 的 LISP 論文](http://www-formal.stanford.edu/jmc/recursive.html)
