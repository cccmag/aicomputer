# 1986 年圖靈獎：John Hopcroft & Robert Tarjan

## 資料結構與圖論演算法的奠基者

1986 年，ACM 圖靈獎第二次同時頒發給兩位獲獎者：康乃爾大學的 John Hopcroft 和普林斯頓大學的 Robert Tarjan。授獎理由是「表彰他們在演算法與資料結構的設計與分析方面的基礎性貢獻」。

Hopcroft 和 Tarjan 的合作是電腦科學史上最高產的合作之一。他們共同開發了多項至今仍是教科書標準內容的演算法和資料結構。

## 深度優先搜尋的系統化

Hopcroft 和 Tarjan 最重要的貢獻之一是將深度優先搜尋（DFS）從一個直覺式的圖形遍歷方法提升為系統化的演算法工具。他們展示了 DFS 可以用來解決一系列看似無關的圖論問題：

**強連通分量（Strongly Connected Components）**：Tarjan 演算法可以用一次 DFS 找到有向圖中的所有強連通分量。

**雙連通分量（Biconnected Components）**：DFS 可以找到圖中的橋和關節點，用於網路可靠性分析。

**平面性測試（Planarity Testing）**：Hopcroft 和 Tarjan 在 1974 年發表了第一個線性時間的平面圖測試演算法。

## 並查集與攤銷分析

Tarjan 在資料結構方面的貢獻包括：

**並查集（Union-Find / Disjoint Set）**：Tarjan 展示了帶有路徑壓縮和按秩合併的並查集可以在近乎常數的時間內執行操作。這個資料結構的攤銷時間分析是攤銷分析的經典案例。

**伸展樹（Splay Tree）**：一種自我調整的二元搜尋樹。

**配對堆積（Pairing Heap）**：一個在實踐中高效的堆積資料結構。

## 教科書的影響

Hopcroft 與 Jeffrey Ullman 合著的《The Design and Analysis of Computer Algorithms》（1974）是演算法領域的經典教科書。Tarjan 的《Data Structures and Network Algorithms》（1983）則是資料結構領域的重要參考。

## 延伸閱讀

- [John Hopcroft - ACM Turing Award](https://amturing.acm.org/award_winners/hopcroft_1096987.cfm)
- [Robert Tarjan - ACM Turing Award](https://amturing.acm.org/award_winners/tarjan_1092048.cfm)
- [Tarjan's SCC 演算法 - Wikipedia](https://en.wikipedia.org/wiki/Tarjan%27s_strongly_connected_components_algorithm)
