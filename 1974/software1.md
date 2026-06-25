# CP/M 的誕生：第一個微電腦作業系統

## 從 PL/M 到作業系統

1974 年，Gary Kildall 正在為 Intel 擔任顧問，協助開發 Intellec-8 微處理器開發系統。他發現 Intel 8080 雖然功能強大，卻缺乏一個能夠管理磁碟儲存的作業系統。於是，他利用閒暇時間寫了一套稱為 CP/M（Control Program for Microcomputers）的軟體。

CP/M 最初運行在 Intel Intellec-8 上，搭配 Shugart Associates 的 8 吋軟碟機。Kildall 用他自己設計的 PL/M（Programming Language for Microcomputers）語言來撰寫——這可能是第一個用高階語言寫成的作業系統。

## 革命性的架構

CP/M 提出了三層架構：

**CCP（Console Command Processor）**：負責處理使用者輸入的命令列指令。

**BDOS（Basic Disk Operating System）**：提供檔案系統服務，包括檔案建立、讀寫、刪除等操作。

**BIOS（Basic Input/Output System）**：這是 CP/M 最重要的創新——一個硬體抽象層，將作業系統與底層硬體隔離開來。電腦製造商只需要為自己的硬體撰寫 BIOS，就可以讓 CP/M 在其機器上運行。

這個設計讓 CP/M 成為第一個真正的跨平台微電腦作業系統。後來 MS-DOS 也採用了類似的架構設計。

## Intel 的錯失

Kildall 曾向 Intel 提議以 20,000 美元的價格出售 CP/M。Intel 拒絕了——他們認為微處理器的軟體生態並不重要。這個決定事後被視為 Intel 史上最大的錯誤之一。

Kildall 於是和妻子 Dorothy 在 1975 年創立了 Digital Research 公司，開始銷售 CP/M。到 1981 年，CP/M 運行在超過 3,000 種不同的電腦型號上，為 DRI 帶來了 540 萬美元的年收入。

## 延伸閱讀

- [CP/M - Wikipedia](https://zh.wikipedia.org/wiki/CP/M)
- [Gary Kildall 回憶錄 - IEEE Spectrum](https://spectrum.ieee.org/cpm-creator-gary-kildalls-memoirs-released-as-free-download)
- [CP/M 歷史 - Google 搜尋](https://www.google.com/search?q=CP/M+history+1974+Gary+Kildall)
