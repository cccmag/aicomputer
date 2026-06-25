# 1978 年圖靈獎：Robert Floyd

## 程式驗證的開創者

1978 年的 ACM 圖靈獎頒給了 Robert W. Floyd，表彰他在程式邏輯驗證、編譯器技術和演算法設計方面的開創性貢獻。Floyd 是史丹佛大學的教授，他的工作深刻影響了電腦科學中關於「正確性」的思考方式。

## Floyd 歸納斷言

Floyd 最重要的貢獻是提出了一種**用數學邏輯來證明程式正確性**的方法。他在 1967 年的論文「Assigning Meanings to Programs」中引入了**歸納斷言方法**（inductive assertion method）。

基本概念是：在程式的關鍵位置插入斷言（assertions）——用一階邏輯表達的條件式。例如，在一個迴圈之前和之後加上不變量（invariant），如果能夠證明：
1. 進入迴圈前斷言成立（初始化）
2. 每次迴圈迭代後斷言仍然成立（保持性）
3. 迴圈結束時斷言蘊含了期望的結論（終止性）

那麼這個程式的正確性就得到了數學證明。這個方法後來被 Tony Hoare 發展為 Hoare 邏輯——程式驗證理論的基石。

## Floyd-Warshall 演算法

Floyd 與 Stephen Warshall 各自獨立發現了**所有點最短路徑演算法**（Floyd-Warshall Algorithm）。這個優雅的演算法使用動態規劃來計算圖中所有頂點對之間的最短路徑，時間複雜度為 O(V³)。即使在今天，Floyd-Warshall 仍然是圖論和網路路由中最基礎的演算法之一。

```pseudo
for k from 1 to |V|
    for i from 1 to |V|
        for j from 1 to |V|
            if dist[i][j] > dist[i][k] + dist[k][j]
                dist[i][j] = dist[i][k] + dist[k][j]
```

## 編譯器與語法分析

Floyd 在編譯器設計和語法分析領域也有重要貢獻。他的作品包括早期對運算子優先級分析（operator precedence parsing）的形式化研究，以及對程式語言語意學的數學基礎的探索。

## 圖靈獎演講

Floyd 的圖靈獎演講「The Paradigms of Programming」探討了程式設計範式的演化。他呼籲程式設計師不僅要關心程式是否「跑得起來」，更要關心程式是否「正確」——這個觀點在軟體工程尚未成熟的 1970 年代是相當前瞻的。

## 延伸閱讀

- [Robert Floyd - ACM Turing Award](https://amturing.acm.org/award_winners/floyd_1002572.cfm)
- [Floyd-Warshall 演算法 - Wikipedia](https://en.wikipedia.org/wiki/Floyd%E2%80%93Warshall_algorithm)
