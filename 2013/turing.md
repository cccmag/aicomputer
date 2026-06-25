# 2013 年圖靈獎：Leslie Lamport

## 分散式系統的奠基者

2013 年 ACM 圖靈獎頒給了 Leslie Lamport，表彰他「對分散式計算系統在理論與實務上的基礎性貢獻，特別是時鐘與事件排序、Paxos 共識演算法、以及容錯分散式系統的邏輯架構」。

Lamport 於 1941 年出生於紐約市，在麻省理工學院取得學士學位後，於布蘭戴斯大學取得博士學位。他的職業生涯大部分在 SRI International、Digital Equipment Corporation 和 Microsoft Research 度過。

## 邏輯時鐘與事件排序

Lamport 在 1978 年的開創性論文「Time, Clocks, and the Ordering of Events in a Distributed System」中，提出了**邏輯時鐘**（Logical Clock）的概念。

在分散式系統中，由於各節點的實體時鐘不可能完全同步，傳統的時間戳無法可靠地用於確定事件的先後順序。Lamport 的解決方案是：每個事件分配一個邏輯計數器（Lamport timestamp），節點之間的訊息交換會攜帶這個計數器。透過這種方式，即使沒有全域時鐘，系統也可以建立事件的部分排序（partial ordering）。

## Paxos 共識演算法

Lamport 在 1989 年提出了 Paxos 演算法——一個在可能發生故障的分散式系統中達成共識的協定。Paxos 解決了「拜占庭將軍問題」的實用版本：在一個分散式系統中，即使某些節點可能故障，所有非故障節點仍然需要對某個值達成一致。

Paxos 演算法後來成為 Google Chubby、Apache ZooKeeper、etcd 等分散式共識服務的理論基礎。Lamport 以一種不尋常的方式發表了這篇論文——他以古希臘 Paxon 議會的寓言故事來描述演算法，使論文在一開始被審稿者拒絕，因為「不夠嚴肅」。

## LaTeX 的創造者

除了分散式系統理論，Lamport 還是一個廣泛使用的工具的作者——LaTeX。Lamport 在 1980 年代基於 Donald Knuth 的 TeX 排版系統創建了 LaTeX，提供了一個更高層次的文件製作系統。

LaTeX 的核心理念是「讓作者專注於內容，而不是排版」。作者使用標記語言描述文件結構（章節、標題、引用），LaTeX 自動處理排版和美學。LaTeX 成為學術界，特別是在數學、物理和電腦科學領域的標準文件格式。

## 圖靈獎演講

Lamport 在圖靈獎演講中回顧了分散式系統理論的發展歷程，並分享了他對「正確性」的執著——他認為分散式系統應該在設計時就證明其正確性，而不是等到實際運行時才除錯。

## 延伸閱讀

- [Leslie Lamport - ACM Turing Award](https://amturing.acm.org/award_winners/lamport_1205376.cfm)
- [Leslie Lamport - Wikipedia](https://en.wikipedia.org/wiki/Leslie_Lamport)
- [Paxos 演算法](https://en.wikipedia.org/wiki/Paxos_(computer_science))
