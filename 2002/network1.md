# Amazon Web Services 概念的醞釀

## 從電子商務到雲端運算

2002 年，Amazon 不僅是一家線上書店——它已經發展成為一家大型的電子商務平台。在營運過程中，Amazon 的工程師們開發了一套複雜的內部基礎設施來處理大規模的網站流量、儲存和運算需求。

這套基礎設施包括：

- **分散式資料儲存**：處理產品目錄、使用者和訂單資料
- **大規模運算叢集**：處理搜尋索引、推薦系統和價格比較
- **內容分發網路**：確保全球使用者都可以快速存取
- **支付處理系統**：安全處理信用卡交易和退款

## 貝佐斯的洞察

Amazon CEO Jeff Bezos 在 2002 年左右有了一個關鍵的洞察：Amazon 為了營運電子商務網站而開發的基礎設施——儲存、運算、資料庫、訊息佇列——本身就是有價值的產品。其他公司的開發者也需要這些服務，但他們不想要（也沒有能力）自己建構。

Bezos 在 2002 年向 Amazon 內部發出了著名的 API 命令（Mandate）：所有團隊必須透過 API 來溝通，任何不能透過 API 完成的工作都應該被自動化。這項政策強制 Amazon 內部的所有系統都具備了成為外部服務的條件。

## 初期服務

2002 年 7 月，Amazon 推出了第一批 Web Services：

**Amazon Web Services (AWS)**：一個讓開發者可以在自己的網站中整合 Amazon 內容和功能的 API 平台。最初的功能包括：

- **Alexa Web 資訊服務**：網站流量和排名資料
- **Amazon E-Commerce Service**：Amazon 產品目錄的 API 存取
- **Amazon Simple Queue Service (SQS) 的前身**：訊息佇列的早期概念

這些 2002 年的服務還非常初級——真正的雲端運算服務（EC2 和 S3）要到 2006 年才推出。但 2002 年確立的基本理念——將 Amazon 的內部基礎設施作為服務提供給外部開發者——是 AWS 的起點。

## 延伸閱讀

- [Amazon Web Services - Wikipedia](https://zh.wikipedia.org/zh-hant/%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%91%E7%AB%AF%E8%BF%90%E7%AE%97%E6%9C%8D%E5%8A%A1)
- [AWS 歷史 - Amazon](https://aws.amazon.com/cn/about-aws/)
