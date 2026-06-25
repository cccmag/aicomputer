# BBN 的 IMP 軟體：為分組交換注入靈魂

## 從硬體到軟體

1968 年 12 月，BBN（Bolt, Beranek and Newman）公司獲得了 ARPANET 的合約，負責開發 Interface Message Processor（IMP）。雖然 Honeywell DDP-516 硬體平台至關重要，但真正讓 IMP 運作的是 BBN 團隊撰寫的軟體。

BBN 的團隊由 Frank Heart 領導，核心成員包括 Severo Ornstein、Bob Kahn、David Walden 和 Bernie Cosell。他們面臨一項艱鉅的任務：在 9 個月內——從 1969 年 1 月到 9 月——交付一台能實際運作的 IMP。

## IMP 軟體的核心功能

BBN 團隊為 DDP-516 撰寫了大約 6,000 行的原始碼，使用 DDP-516 的組合語言。這個軟體實現了以下功能：

**路由（Routing）**：每個 IMP 維護一個動態路由表，根據網路拓撲的變化自動調整轉發路徑。當一個 IMP 失效時，鄰近的 IMP 會自動繞過它。

**流量控制（Flow Control）**：IMP 使用 RFNM（Request for Next Message）機制來防止擁塞。每條鏈路上最多只能有一個未確認的訊息，發送端必須等待接收端返回 RFNM 才能發送下一條訊息。

**錯誤控制（Error Control）**：每個分組都包含 16 位元的 checksum，接收端 IMP 對每個分組進行校驗。發現錯誤時，會要求發送端重傳。

**緩衝區管理（Buffer Management）**：IMP 只有有限的記憶體，必須小心翼翼地管理訊息緩衝區。BBN 團隊設計了一套精巧的緩衝區池管理機制。

## 軟體發展的挑戰

BBN 團隊的工作條件相當艱苦。他們在 DDP-516 上沒有作業系統，所有的程式直接運行在裸機上。除錯工具非常有限——只有一組指示燈和一個前端面板可以用來檢查程式的狀態。

Bob Kahn 後來回憶：「我們用 DDP-516 的前端面板進行除錯，面板上有大量的開關和指示燈。我們必須在腦中跟蹤程式的執行狀態，然後用開關逐條指令地執行程式。」

## 測試與交付

1969 年 8 月，BBN 將第一台 IMP 運送到 UCLA，安裝在 Leonard Kleinrock 的網路測量中心。安裝過程進行得出乎意料地順利——工程師將 IMP 與 UCLA 的 SDS Sigma 7 主機連接後，系統幾乎立刻就開始正常運作。

BBN 的 IMP 軟體在接下來的幾年中持續進化。它處理了 RFC 1 中描述的主機間通訊需求，支援了 NCP 協議的實現，並最終演變為 TCP/IP 協議的測試平台。

## 延伸閱讀

- [BBN 與 IMP 開發 - Living Internet](https://www.livinginternet.com/i/ii_imp.htm)
- [Bob Kahn - Wikipedia](https://en.wikipedia.org/wiki/Bob_Kahn)
- [The IMP Software - BBN 技術報告](https://www.computerhistory.org/collections/catalog/102739067)
