# WSL 2：Microsoft 擁抱 Linux 核心

## 從 WSL 1 到 WSL 2

2019 年 5 月，Microsoft 在 Build 開發者大會上宣布了 WSL 2（Windows Subsystem for Linux 2），這是一項從根本上改變 Windows 與 Linux 關係的技術。WSL 1 透過翻譯層（lxss.sys 和 lxcore.sys）將 Linux 系統呼叫轉譯為 Windows NT 核心系統呼叫，性能一直受限。

WSL 2 採用了完全不同的方法：在 Hyper-V 虛擬機器中執行一個真正的 Linux 核心。這意味著 WSL 2 提供了 100% 的 Linux 系統呼叫相容性，大幅提升了檔案 I/O 性能——在某些測試中比 WSL 1 快了 3 到 5 倍。

## 對開發者社群的影響

WSL 2 的推出標誌著 Microsoft 對開發者的態度發生了根本性轉變。執行長 Satya Nadella 的「Microsoft 愛 Linux」不再只是口號：

- 開發者可以在 Windows 上無縫執行 Docker 容器
- 使用原生 Linux 工具鏈（gcc、gdb、perf 等）
- 透過 VS Code Remote - WSL 插件獲得流暢的開發體驗

## 戰略意義

WSL 2 是 Microsoft 雲端優先戰略的一部分。透過讓 Windows 成為 Linux 開發的一等公民，Microsoft 降低了開發者從 Mac 或 Linux 遷移到 Windows 的障礙，同時強化了 Azure 作為 Linux 雲端平台的定位。到 2019 年底，WSL 2 已經預裝在 Windows 10 2020 年 5 月更新中。
