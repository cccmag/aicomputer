# Unix 的誕生：從 Space Travel 到作業系統

## Multics 取消後的真空

1969 年 4 月，貝爾實驗室正式退出了 Multics 合作計畫。這個決定讓 Ken Thompson、Dennis Ritchie、Doug McIlroy 等研究人員失去了他們習慣的分時運算環境——一台 GE-645 主機和一個雖然不完美但至少是互動式的作業系統。

Thompson 非常沮喪。他已經習慣了在 Multics 上進行互動式程式開發，而貝爾實驗室的其他電腦——GE 635 上的 GECOS 批次處理系統——只能接受打孔卡片，等待數小時甚至數天才能拿到結果。

## Space Travel 遊戲

在等待管理層批准購買新電腦的過程中，Thompson 開發了一個稱為「Space Travel」的遊戲。這是一個太陽系模擬程式——玩家可以駕駛太空船在各個行星之間巡航，甚至在星球表面著陸。

Thompson 先是在 Multics 上用 Fortran 寫了這個遊戲——但每次執行要花費 75 美元的 CPU 費用。他將其移植到 GECOS 上——但顯示效果很差，只能透過打字輸入指令來控制太空船。

## PDP-7 的發現

Thompson 在貝爾實驗室發現了一臺被遺忘的 PDP-7 迷你電腦。PDP-7 是 DEC 在 1965 年推出的 18 位元機器，配備 4 Kwords 的磁芯記憶體和一個優秀的圖形顯示終端。

Thompson 和 Ritchie 將 Space Travel 移植到了 PDP-7 上——他們寫了一個浮點運算套件、一套圖形字元和一個即時除錯系統。全部都用 PDP-7 組合語言撰寫，透過 GECOS 上的交叉組譯器產生紙帶，然後手動載入到 PDP-7 中。

## 檔案系統的誕生

在開發 Space Travel 的過程中，Thompson 開始思考一個更根本的問題：能否在 PDP-7 上實現一個類似 Multics 的檔案系統？

他與 Rudd Canaday 和 Dennis Ritchie 在辦公室的黑板上反覆討論。有一天，他們用一台口述錄音機錄下了整個設計討論——這就是著名的「chalk file system」。

1969 年夏季，Thompson 的妻子帶著剛出生的兒子去加州探親。Thompson 利用這一個月的獨處時間，將黑板上的設計變成了真正的程式碼：

- 第一週：作業系統核心
- 第二週：Shell（命令列直譯器）
- 第三週：編輯器（ed）
- 第四週：組譯器（as）

當 Thompson 的妻子回來時，PDP-7 上已經運行著一個小而完整的作業系統——Unix 誕生了。（Unix 這個名字直到 1970 年才由 Brian Kernighan 提出，是對 Multics 的一句俏皮話）。

## 延伸閱讀

- [Unix 的誕生 - Bell Labs](https://www.nokia.com/bell-labs/unix-history/takeshape.html)
- [Dennis Ritchie 的回憶](https://www.nokia.com/bell-labs/about/dennis-m-ritchie/hist.pdf)
- [最早的 Unix 程式碼 - Computer History Museum](https://computerhistory.org/blog/the-earliest-unix-code-an-anniversary-source-code-release/)
