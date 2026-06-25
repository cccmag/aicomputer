# Microservices 架構的崛起

## 從單體到微服務

2016 年是微服務架構（Microservices Architecture）從概念走向主流的一年。微服務的思想是將大型應用程式拆分為一組小型的、獨立部署的服務，每個服務負責單一的業務功能，並透過輕量級協定（通常是 HTTP/REST 或 gRPC）進行通訊。

這個概念並非 2016 年才提出——但這一年，由於 Docker 容器和 Kubernetes 編排技術的成熟，微服務從理論進入了大規模實踐。

## 企業採用潮

2016 年，Netflix、Amazon、Uber 等一線科技公司分享了他們的微服務實戰經驗：

- **Netflix**：開源了完整的微服務工具鏈（Eureka、Hystrix、Zuul、Ribbon）
- **Amazon**：內部數千個微服務的架構經驗成為業界標竿
- **Uber**：基於微服務的領域驅動設計

## 挑戰與反彈

微服務雖然帶來了獨立部署、技術多樣性、可擴展性等優勢，但也引入了分散式系統的固有複雜性：服務發現、分散式追蹤、資料一致性、網路延遲等。

Martin Fowler 與 James Lewis 在 2014 年的經典文章是微服務運動的理論基礎，而 2016 年的實務經驗則讓人們開始認識到——微服務並不是免費的午餐，需要成熟的 DevOps 文化和基礎設施支援。

## 延伸閱讀

- [Microservices - Martin Fowler](https://martinfowler.com/articles/microservices.html)
- [Netflix 微服務開源](https://netflix.github.io/)
