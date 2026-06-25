# Intel Core 2 Duo：Netburst 時代的終結

## Netburst 的教訓

2000 年至 2004 年間，Intel 堅持 Netburst 微架構——以極高的時脈速度（最終達到 3.8 GHz）來追求效能，代價是極高的功耗和發熱。Pentium 4 的 Prescott 核心（90nm，2004 年）的 TDP 高達 130W，效能功耗比遠不如競爭對手 AMD 的 K8 架構。

Intel 在 2004 年被迫取消了 4 GHz Pentium 4 的開發計畫——Netburst 架構已走到極限。Intel 的架構團隊從以色列海法（Haifa）的研發中心調出了 Pentium M（Banias/Dothan）的設計團隊，由 Mooly Eden 領導，開始開發一個全新的微架構。

## Core 的誕生

2006 年 7 月 27 日，Intel 正式推出了 Core 2 Duo 處理器（代號 Conroe）。Core 2 Duo 的設計哲學與 Netburst 完全相反：
- **寬動態執行**（Wide Dynamic Execution）：每個時脈週期可解碼 4 條指令（Netburst 為 3 條）
- **智慧型電源管理**：細粒度的時脈閘控（clock gating），閒置核心可以完全關閉
- **共享 L2 快取**：兩個核心共享 4MB L2 快取，減少記憶體延遲
- **64 位元支援**：EM64T（Intel 的 AMD64 相容實現）

效能測試顯示：Core 2 Duo E6700（2.67 GHz）在各項測試中平均領先 Pentium D 960（3.6 GHz）約 40%，而 TDP 僅為 65W——Pentium D 的 130W 的一半。

## 市場影響

Core 2 Duo 讓 Intel 從效能的追趕者重新變成領導者。AMD 的 Athlon 64 X2 在 2005 年曾短暫領先，但 Core 2 Duo 的效能優勢讓 AMD 在接下來近十年都無法超越。這個處理器改變了消費者對「高效能低功耗」的認知——在此之後，「每瓦效能」（performance per watt）成為處理器評估的核心指標。

Core 2 Duo 不僅用在桌上型電腦，其行動版本 Core 2 Duo Merom 成為了 2006 年 MacBook Pro 的處理器。Core 微架構的基礎設計一直沿用到 2015 年的 Skylake——將近十年的統治。
