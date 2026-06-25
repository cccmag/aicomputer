# Docker 容器技術的發源

## dotCloud 的內部工具

2011 年，一家名為 dotCloud 的平台即服務（PaaS）新創公司正處於創業的關鍵階段。dotCloud 提供多語言應用託管服務，支援 Python、Ruby、Node.js、Java 等多種執行環境。為了管理這些異質環境，dotCloud 的核心開發者 Solomon Hykes 創建了一個內部工具——最初被稱為「dotCloud 平台上的容器引擎」。

這個工具利用了 Linux 核心的 cgroups（控制群組）和 namespaces（命名空間）功能，將應用程式及其依賴打包在一個隔離的容器中執行。容器不僅提供了虛擬機器的隔離性，還具有啟動快速、資源開銷低、便於遷移的優點。

## 從內部到開源

2011 年這個內部工具尚不為外界所知，但它的核心概念已經成形。Docker 的設計目標可以概括為：「Build, Ship, and Run Any App, Anywhere」。這個理念源自 dotCloud 作為 PaaS 廠商的痛點——如何在不同的基礎設施上一致地執行應用程式。

## 容器化的未來

Docker 在 2011 年仍處於孕育階段。但回顧歷史，dotCloud 在 2011 年開發的容器技術正是日後 DevOps 運動、微服務架構、雲端原生應用的技術起點。2013 年 Docker 開源後徹底改變了軟體部署和作業的樣貌。

## 延伸閱讀

- [Docker 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Docker_(software))
- [dotCloud 與 Docker 的起源](https://www.docker.com/company/)
