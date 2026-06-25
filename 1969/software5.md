# PDP-7 上的程式設計：組合語言與除錯

## 一臺被遺忘的電腦

1969 年夏季，Ken Thompson 在貝爾實驗室發現了一臺 DEC PDP-7 迷你電腦。PDP-7 是 1965 年推出的 18 位元機器，在當時已經算是過時的型號——貝爾實驗室甚至不確定它還能不能用。

但這臺機器有一個關鍵優勢：它配備了一臺優秀的圖形顯示終端——DEC 340 CRT 顯示器——可以顯示向量圖形。對於 Thompson 的 Space Travel 遊戲來說，這比電傳打字機（Teletype）要好得多。

## 程式開發的原始條件

在 PDP-7 上進行程式開發是一項極其艱苦的工作。當時的開發流程是：

1. 在 GECOS 系統（GE 635）上用交叉組譯器（cross-assembler）將程式碼組譯為 PDP-7 的機器碼
2. 將機器碼輸出到打孔紙帶上
3. 將紙帶拿到 PDP-7 前面，用紙帶閱讀機載入
4. 執行並測試
5. 發現錯誤後，回到 GECOS 修改原始碼，從步驟 1 重新開始

這個流程意味著每次編譯-執行週期可能需要數小時。除錯的資訊主要來自 PDP-7 前端面板上的指示燈——一排排紅色和綠色的 LED 是唯一反映電腦內部狀態的視覺回饋。

## PDP-7 的組合語言

Thompson 為 PDP-7 撰寫的程式全部使用組合語言。以下是一個 PDP-7 組合語言的典型片段（示意）：

```
        LAW     0       / 將 0 載入累加器
        DAC     COUNT   / 儲存到 COUNT 變數
LOOP,   LAW     COUNT   / 載入 COUNT
        SAD     MAX     / 與 MAX 比較
        JMP     DONE    / 如果等於，跳到 DONE
        ISZ     COUNT   / COUNT 加 1
        JMP     LOOP    / 繼續迴圈
DONE,   HLT             / 暫停
```

這種程式風格需要程式設計師清楚地了解每個指令的執行週期、暫存器的數量與用途、以及記憶體的位址配置。

## 從組合語言到 B 語言

Thompson 很快意識到，在 PDP-7 上只用組合語言開發 Unix 既耗時又容易出錯。他需要一種高階語言——但要足夠簡單，能在 PDP-7 有限的記憶體中運行。

1969 年，Thompson 將 BCPL 語言精簡為 B 語言——一種沒有型別的直譯式語言。他為 PDP-7 撰寫了第一個 B 語言直譯器。雖然 B 語言的速度很慢，但它讓 Thompson 可以更快地開發 Unix 的工具。

B 語言的實現過程本身就是一個程式設計的成就：在只有 4 Kwords 記憶體（相當於 8 KB）的機器上，Thompson 要同時容納 B 直譯器、編輯器和 Unix 核心。

## 這個經驗的意義

PDP-7 的開發環境——極端的資源限制、原始的開發工具、必須親自理解每一個硬體細節——對 Thompson 和 Ritchie 的設計哲學產生了深遠的影響。Unix 之所以如此精簡和優雅，部分原因正是因為它誕生在一個資源如此匱乏的環境中。

正如 Ritchie 後來所說：「Unix 之所以簡潔，不是因為我們刻意追求簡潔，而是因為我們別無選擇。」

## 延伸閱讀

- [PDP-7 - Wikipedia](https://en.wikipedia.org/wiki/PDP-7)
- [Unix 程式碼早期歷史 - CHM](https://computerhistory.org/blog/the-earliest-unix-code-an-anniversary-source-code-release/)
- [Thompson 的 Unix 口述歷史](https://www.tuhs.org/Archive/Documentation/OralHistory/expotape.htm)
