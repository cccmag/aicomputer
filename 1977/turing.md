# 1977 年圖靈獎：John Backus

## FORTRAN 之父

1977 年的 ACM 圖靈獎頒給了 John Backus，表彰他對程式語言和計算方法的深遠貢獻。Backus 最為人知的成就是領導了 FORTRAN（Formula Translation）的開發——這是第一個高階程式語言，誕生於 1957 年的 IBM。

## FORTRAN 的革命

在 FORTRAN 之前，程式是用組合語言或機器碼寫的。FORTRAN 讓科學家和工程師可以用接近數學符號的方式來表達計算——例如 `A = B + C * D`。這不僅大幅提高了生產力，也讓程式碼可以被更多人理解。

Backus 的團隊在 1954 到 1957 年間開發了 FORTRAN。當時許多專家認為這不可能成功——高階語言編譯出來的程式碼絕對無法與手寫的組合語言效率相比。但 Backus 團隊的編譯器產生了令人驚訝的有效程式碼，證明了編譯器技術的可行性。

## BNF 記法

Backus 的第二項偉大貢獻是 **BNF（Backus-Naur Form）**——一種用來正式定義程式語言語法的記法。他在 1959 年為 ALGOL 58 的報告中提出了這種記法（後來由 Peter Naur 完善）。

BNF 的概念非常簡單：用一系列「產生式規則」（production rules）來描述語言的結構。例如：
```
<digit> ::= 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9
<number> ::= <digit> | <number> <digit>
```

BNF 讓程式語言的設計從模糊的文字描述變成了精確的數學形式。它是編譯器設計、語言規範和理論電腦科學的基礎工具。

## 函數式程式設計 FP

獲獎後，Backus 在圖靈獎演講「Can Programming be Liberated from the von Neumann Style?」中提出了對傳統馮紐曼式程式語言的嚴厲批評，並介紹了他設計的函數式程式語言 FP。這場演講影響深遠，被認為是函數式程式設計運動的重要里程碑。

## 延伸閱讀

- [John Backus - ACM Turing Award](https://amturing.acm.org/award_winners/backus_0703524.cfm)
- [BNF - Wikipedia](https://en.wikipedia.org/wiki/Backus%E2%80%93Naur_form)
