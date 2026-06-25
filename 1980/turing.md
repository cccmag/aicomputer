# 1980 年圖靈獎：Tony Hoare

## Quicksort 的發明者

Charles Antony Richard Hoare（Tony Hoare）是 1980 年 ACM 圖靈獎得主，授獎理由是「對程式語言的定義與設計的基礎貢獻」。

Hoare 最廣為人知的成就是 Quicksort 演算法——他於 1959-1960 年在莫斯科大學學習機器翻譯時構思的。當時他需要排序資料，靈感來自於「將數列分成兩半、分別排序、再合併」的想法（雖然 Quicksort 最著名的版本是原地排序，不需要合併步驟）。

Quicksort 的平均時間複雜度為 O(n log n)，在實踐中通常比其他 O(n log n) 演算法（如 mergesort、heapsort）更快。至今 Quicksort 仍然是使用最廣泛的通用排序演算法之一。

## Hoare Logic 與程式驗證

Hoare 的另一項重大貢獻是 Hoare Logic（1969）——一套用於形式化驗證程式正確性的公理系統。Hoare Logic 使用「三元組」{P} C {Q} 來描述：如果執行前條件 P 成立，執行程式 C 後，條件 Q 一定會成立。

Hoare Logic 為程式正確性的形式化證明奠定了基礎，影響了後續所有關於程式驗證的研究。Hoare 後來回憶自己在 ALGOL W 中發明了 null reference，稱之為「我的十億美元錯誤」。

## CSP：並行計算的模型

Hoare 在 1978 年發表的 CSP（Communicating Sequential Processes）為並行計算提供了一個優雅的數學模型。CSP 使用「行程」（process）和「通道」（channel）作為基本抽象——行程之間透過通道進行同步訊息傳遞。

CSP 直接影響了 Occam 程式語言、Go 語言的 goroutine 和 channel 設計，以及 Erlang 的 actor 模型。2000 年代 CSP 仍然是並行程式設計的理論基礎。

## 延伸閱讀

- [Tony Hoare - ACM Turing Award](https://amturing.acm.org/award_winners/hoare_4622167.cfm)
- [Tony Hoare - Wikipedia](https://en.wikipedia.org/wiki/Tony_Hoare)
- [Quicksort - Wikipedia](https://en.wikipedia.org/wiki/Quicksort)
