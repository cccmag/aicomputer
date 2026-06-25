# Docker 開源：容器化的起點

## dotCloud 的賭注

2013 年 3 月，dotCloud 公司的創辦人 Solomon Hykes 在 PyCon 上宣布開源 dotCloud 的內部容器專案——Docker。這個決定改變了 dotCloud 的命運，也改變了整個軟體產業。

Docker 的核心概念非常簡單：將應用程式及其所有依賴（程式庫、系統工具、設定檔）打包在一個稱為「容器」（container）的標準化單元中。這個容器可以在任何 Linux 系統上執行，無論是開發者的筆電、測試伺服器、還是雲端生產環境。

## 容器 vs 虛擬機器

Docker 容器與傳統虛擬機器的差異是理解 Docker 革命的關鍵：
- **虛擬機器**：每個 VM 包含完整的作業系統、核心、以及應用程式。啟動需要數分鐘，佔用數 GB 磁碟空間。
- **Docker 容器**：所有容器共用主機的作業系統核心，只打包應用程式和必要的依賴。啟動只需數秒，佔用數 MB 空間。

Docker 善用了 Linux 核心的 cgroups（資源隔離）和 namespaces（進程隔離）功能，實現了接近 VM 的安全隔離性，同時保持了接近原生執行的效能。

## 生態系統的爆發

Docker 開源後迅速獲得開發者社群的熱烈擁抱。GitHub 上的 Docker 專案成為 2013 年成長最快的開源專案之一。Docker 的成功催生了 Docker Hub（映像檔倉庫）、Docker Compose（多容器編排）、以及日後的容器編排大戰（Kubernetes vs Docker Swarm vs Mesos）。

Docker 開源也象徵著 DevOps 運動的成熟——開發者和維運人員使用同一套容器規範來建置、測試和部署軟體，從根本上消除了「在我的機器上可以執行」的困境。

## 延伸閱讀

- [Docker - Wikipedia](https://en.wikipedia.org/wiki/Docker_(software))
- [Docker 開源的故事](https://www.docker.com/company/)
