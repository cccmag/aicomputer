# Dijkstra 的守衛命令：並行程式設計的理論突破

## 一分耕耘，一分收獲

1975 年，Edsger W. Dijkstra 發表了他最具影響力的論文之一——「Guarded Commands, Non-determinacy and Formal Derivation of Programs」（守衛命令、非決定性與程式的形式推導）。這篇論文標誌著他在程式語言設計和並行程式設計理論上的一個重要突破。

Dijkstra 引入的「守衛命令」（guarded command）是一種全新的控制結構：一個由條件（guard）和命令（command）組成的配對，只有當條件為真時，對應的命令才會被執行。語法如下：

```
if x ≥ 0 → x := x
[] x < 0 → x := -x
fi
```

當多個守衛同時為真時，非決定性地選擇其中一個執行——這種非決定性是 Dijkstra 最核心的貢獻之一。

## 非決定性的意義

傳統的程式語言中，程式的行為是完全確定的：給定相同的輸入，必定產生相同的輸出。Dijkstra 的非決定性打破了這個假設——在多個可行的選擇中，程式可以任意選擇一個來執行。

這在並行程式設計中至關重要。當多個行程同時競爭資源時，執行順序是不確定的。Dijkstra 的守衛命令提供了一種優雅的方式來處理這種不確定性，而不需要依賴於低階的鎖定機制。

守衛命令也為理論電腦科學提供了新的方向。Dijkstra 發展了一套基於「弱最強前置條件」（weakest precondition）的程式正確性證明方法，讓程式設計師可以在寫程式碼的同時證明其正確性。

## 影響

守衛命令的觀念直接影響了並行程式語言的設計——如 Occam、Ada 的選擇語句、和 Go 語言的 select 語句。它也對分散式系統、非同步程式設計和模型檢驗（model checking）等領域產生了深遠影響。

## 延伸閱讀

- [Dijkstra 的守衛命令論文](https://www.cs.utexas.edu/users/EWD/ewd04xx/EWD418.PDF)
- [Edsger Dijkstra - Wikipedia](https://zh.wikipedia.org/wiki/%E8%89%BE%E5%BE%B7%E8%92%99%C2%B7%E8%BF%AA%E7%A7%91%E6%96%AF%E7%89%B9%E6%8B%89)
- [守衛命令語言 - Google 搜尋](https://www.google.com/search?q=Guarded+commands+Dijkstra+1975)
