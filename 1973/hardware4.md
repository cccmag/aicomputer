# Motorola 6800 的設計啟程

## 貝爾實驗室的出走者

1973 年，Motorola 的 Semiconductor Products Division 在亞利桑那州 Mesa 開始了 6800 微處理器的設計工作。專案由 Tom Bennett 領導，核心工程師 Chuck Peddle 後來成為這個專案的關鍵人物。

有趣的是，Peddle 原本在通用電氣（GE）工作，參與了一個家用電腦專案——但 GE 在 1972 年取消了這個計畫。Peddle 帶著對微型電腦的熱情加入了 Motorola。同時，Motorola 的團隊中也包含了從 Bell Labs 和 IBM 出走的工程師。

## 設計理念

Motorola 6800 的設計目標與 Intel 8008 截然不同。8008 是為 Intel 4004 的升級市場設計的，而 6800 從一開始就被設計為**完整的微型計算機系統**。

關鍵設計決策：

- **單一 +5V 電源**：8008 需要多組電源（+5V、-9V 等），而 6800 僅需單一 +5V 電源，大大簡化了系統設計
- **統一位址空間**：記憶體和 I/O 在同一位址空間中定址（不像 Intel 架構需要特殊的 IN/OUT 指令）
- **最小支援晶片**：Motorola 同時開發了 6870 時脈產生器、6850 串列介面、6820 並列介面等配套晶片，構成完整的「M6800 家族」

## 比 Intel 8080 晚一步？

6800 預計在 1974 年初發表。但 Intel 的 8080（1974 年 4 月）搶先上市，而且效能更高。6800 直到 1974 年底才正式量產。

儘管如此，6800 的架構設計在許多方面都更優雅——特別是其整齊的指令編碼和簡單的定址模式。它被廣泛用於嵌入式系統、工業控制和早期個人電腦（如 SWTPC 6800、MITS Altair 680）。

更重要的是，Chuck Peddle 在 1974 年離開 Motorola 加入 MOS Technology，用相同的設計理念創造了 6502 微處理器——這顆晶片將用於 Apple II、Commodore PET 和 Nintendo 紅白機，成為歷史上最暢銷的微處理器之一。

## 延伸閱讀

- [Motorola 6800 - Wikipedia](https://en.wikipedia.org/wiki/Motorola_6800)
- [Motorola 6800 歷史 - Google 搜尋](https://www.google.com/search?q=Motorola+6800+1973+microprocessor+design)
