# Kubernetes 開源：容器編排的未來

## Google 的容器經驗

2014 年 6 月 7 日，Google 宣布開源 Kubernetes——一個基於 Google 內部容器管理系統 Borg 經驗開發的容器編排平台。Kubernetes 在希臘語中意為「舵手」或「領航員」。

Google 在容器技術上擁有超過十年的內部經驗。Borg 自 2003 年就開始管理 Google 的全球資料中心，調度數十億個容器。Kubernetes 是 Borg 的開源版本，吸收了 Google 多年來在大規模容器管理中的經驗教訓。

## 核心概念

Kubernetes 引入了一系列核心抽象概念：
- **Pod**：最小的部署單元，一個 Pod 包含一個或多個共享網路和儲存的容器
- **Service**：一組 Pod 的穩定網路端點
- **Deployment**：宣告式更新 Pod 的期望狀態
- **ConfigMap 和 Secret**：將設定與應用程式容器分離

Kubernetes 的關鍵創新在於宣告式（declarative）管理——使用者描述「我想要什麼樣的最終狀態」，Kubernetes 自動計算如何從當前狀態到達目標狀態，而不是下達一步步的操作指令。

## 競爭格局

Kubernetes 開源時，容器編排領域已經存在多個解決方案：Docker 自家的 Docker Swarm、Apache Mesos、以及 HashiCorp 的 Nomad。Kubernetes 雖然起步較晚，但挾 Google 的技術品牌和強大的社群凝聚力，迅速成長為主導方案。

Kubernetes 的開源也象徵著雲端原生（Cloud Native）運動的真正開始。2015 年，Google 與 Linux 基金會合作成立了雲端原生計算基金會（CNCF），以 Kubernetes 為核心建立了一個完整的雲端原生技術生態。

## 延伸閱讀

- [Kubernetes - Wikipedia](https://zh.wikipedia.org/wiki/Kubernetes)
- [Kubernetes 官方文件](https://kubernetes.io/)
