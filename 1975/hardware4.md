# Tandem NonStop：容錯運算的濫觴

## 容錯的起源

1974 年底，James Treybig 創立了 Tandem Computers 公司，目標非常明確：設計一台永遠不會當機的電腦。1975 年，Tandem 的工程團隊開始開發 NonStop 系統——世界上第一台專為容錯而設計的商用電腦。

Treybig 的靈感來自於他在惠普時觀察到的現象：隨著企業越來越依賴電腦，系統當機的成本也越來越高。銀行、航空訂位系統、證交所——這些應用需要 24/7 不間斷運作。

## NonStop 的設計哲學

Tandem NonStop 的設計圍繞著一個核心理念：冗餘（redundancy）。每個關鍵元件都有備份（處理器、記憶體、匯流排、電源、磁碟），任何單一元件的故障都不會導致系統停止運作。

NonStop 使用了獨特的「雙重匯流排」架構，兩個處理器之間透過高速匯流排連接，保持同步。當一個處理器故障時，另一個處理器會自動接手。作業系統 Guardian 也為容錯而設計——它可以在不中斷系統運作的情況下重新啟動故障的處理器。

## 影響

Tandem 的 NonStop 系統在銀行業、股票交易和電信系統中獲得了巨大的成功。雖然 Tandem 後來在 1997 年被康柏（Compaq）收購，最終成為惠普的一部分，但其容錯架構影響了後來的叢集系統、容錯伺服器和雲端架構。

NonStop 最令人難忘的展示是：Tandem 工程師在客戶面前拔掉電源線，系統繼續運作——因為它同時連接著兩組電源。

## 延伸閱讀

- [Tandem Computers - Wikipedia](https://en.wikipedia.org/wiki/Tandem_Computers)
- [NonStop 系統架構](https://en.wikipedia.org/wiki/NonStop_(server_computers))
- [Tandem 容錯電腦歷史 - Google 搜尋](https://www.google.com/search?q=Tandem+NonStop+1975+fault+tolerant+computer)
