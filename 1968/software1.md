# Dijkstra 的怒吼：「Go To 語句是有害的」

## 一封信改變了程式設計

1968 年 3 月，《Communications of the ACM》刊登了一封讀者來信，標題是「Go To Statement Considered Harmful」，作者是荷蘭電腦科學家 Edsger W. Dijkstra。這封只有兩頁的短文，成了電腦科學史上最具影響力的文獻之一。

Dijkstra 開門見山地寫道：「多年來我觀察到，程式設計師的品質與他們所寫程式中 go to 語句的密度成反比。」他接著解釋，go to 語句之所以有害，是因為它破壞了程式的結構，使程式難以理解、驗證和維護。

## 結構化程式設計的理論基礎

Dijkstra 的論證建立在一個關鍵洞察上：程式的靜態文字和動態執行過程之間存在巨大的認知鴻溝。當程式設計師閱讀一串程式碼時，他需要在大腦中模擬程式的執行路徑。如果程式充滿了無條件的 go to 跳躍，執行路徑就會像一碗義大利麵一樣錯綜複雜。

這一論證的理論基礎來自 1966 年 Böhm 與 Jacopini 的論文：「任何程式都可以只用三種控制結構——順序（sequence）、選擇（if-then-else）、重複（do-while）——來實現」。也就是說，go to 從理論上就不是必需的。

## 程式碼範例

傳統的「義大利麵」寫法：

```
    IF X > 0 GO TO 100
    GO TO 200
100  Y = X * 2
    GO TO 300
200  Y = -X
300  Z = Y + 1
```

對應的結構化寫法：

```
    IF X > 0 THEN
        Y = X * 2
    ELSE
        Y = -X
    END IF
    Z = Y + 1
```

第二種寫法清楚地反映了程式的邏輯結構，讀者不需要在腦中模擬跳躍路徑。

## 深遠的影響

Dijkstra 的信引發了程式設計界長達數年的激烈辯論。反對者認為，在某些低層次操作（如中斷處理、例外狀況處理）中，go to 是必要的。但最終，結構化程式設計的理念取得了壓倒性的勝利。

這場辯論的影響超出語言設計本身。它標誌著程式設計從「手工藝」向「工程學」的轉變——程式不僅要能正確執行，還要易於理解和維護。此後，Pascal、C、Ada 等語言都提供了豐富的結構化控制結構，而 go to 被降級為一種偶爾使用的救急工具。

## 延伸閱讀

- [Go To Statement Considered Harmful 原文](https://web.archive.org/web/20070703050443/www.acm.org/classics/oct95)
- [Edsger W. Dijkstra - Wikipedia](https://zh.wikipedia.org/wiki/%E8%89%BE%E5%85%B9%E6%A0%BC%C2%B7%E6%88%B4%E5%85%8B%E6%96%AF%E5%9D%A6)
- [結構化程式設計 - Wikipedia](https://zh.wikipedia.org/wiki/%E7%BB%93%E6%9E%84%E5%8C%96%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1)
