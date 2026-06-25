# 分組交換的奠基之年

## 三條獨立的路徑

1966 年是分組交換（packet switching）概念從理論走向實踐的關鍵年份。值得注意的是，這個概念在同一時期被三個不同的人獨立提出，各自為了解決不同的問題：

- **Paul Baran**（美國蘭德公司，1960-1964）：為美國空軍設計能夠在核戰中存活的通訊網路，提出了「分散式通訊網路」和「訊息區塊交換」
- **Donald Davies**（英國國家物理實驗室，1965）：在設計全國性資料網路時獨立提出了「分組交換」（packet switching）這個術語
- **Larry Roberts**（ARPANET，1966-1967）：在設計 ARPANET 時應用了上述概念

## 1966 年的關鍵交會

1966 年，Roberts 在加入 ARPA 後，開始認真設計 ARPANET 的通訊技術。他在 1967 年 10 月的 ACM SOSP 會議上見到了英國國家物理實驗室的 Roger Scantlebury，這位 Davies 團隊的成員介紹了他們在分組交換方面的研究。

Roberts 立刻意識到，分組交換正是他所需要的技術。他後來寫道：「Davies 的分組交換概念，與 Baran 的分散式網路理念結合，再加上 Clark 提出的 IMP（Interface Message Processor）架構，構成了 ARPANET 的技術基礎。」

## 為什麼是分組交換？

在分組交換出現之前，傳統的電話網路使用「電路交換」（circuit switching）——在通話期間建立一條專用線路。這種方式適合語音通訊，但對電腦資料傳輸極不經濟：

- 電腦通訊是突發性的（bursty），大部分時間線路是空閒的
- 電路交換在沒有資料傳輸時仍然佔用頻寬
- 分組交換讓多台電腦共享同一條線路，大幅提升效率

## IMP 概念的提出

同一年，Wesley Clark 提出了一個關鍵的架構創新：不讓主機電腦直接連接，而是使用專用的迷你電腦來管理網路通訊。這些被稱為「介面訊息處理器」（Interface Message Processors, IMP）的裝置，負責處理分組交換、路由選擇和錯誤控制，讓主機電腦可以專注於計算任務。

這個設計決策對 ARPANET 的成功至關重要。

## 延伸閱讀

- [Paul Baran - Wikipedia](https://en.wikipedia.org/wiki/Paul_Baran)
- [Donald Davies - Wikipedia](https://en.wikipedia.org/wiki/Donald_Davies)
- [分組交換 - Wikipedia](https://zh.wikipedia.org/wiki/%E5%88%86%E7%BB%84%E4%BA%A4%E6%8D%A2)
