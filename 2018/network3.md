# 雲端運算的混合雲趨勢

## 混合雲成為主流

2018 年，混合雲（Hybrid Cloud）成為雲端運算領域最重要的策略趨勢。企業不再面臨「上雲或不上雲」的選擇，而是如何在私有雲、公有雲和邊緣環境之間取得平衡。

混合雲的驅動因素：

- **資料主權**：某些資料受法規限制必須留在特定地理位置或本地
- **延遲敏感應用**：製造業的即時控制、金融交易等需要超低延遲
- **既有投資**：大型企業已經在本地資料中心投入了大量資金
- **合規需求**：金融、醫療、政府機構對資料儲存有嚴格規範

## 三強的應對

2018 年，三大雲端廠商都推出了混合雲策略：

- **AWS Outposts**（2018 年 re:Invent 預覽）：AWS 原生的硬體裝置，可在本地提供 AWS 服務
- **Azure Stack**：已在 2017 年推出，2018 年獲得更多客戶採用
- **GCP Anthos**（當時以 Cloud Services Platform 的名稱在 2018 年推出）：在 Kubernetes 框架上統一管理混合雲和多雲環境

## Kubernetes 作為混合雲層

Kubernetes 在 2018 年更加確立了作為混合雲通用抽象層的地位。由於 Kubernetes 可以部署在任何基礎設施上（公有雲、私有雲、邊緣），它成為了應用程式的可移植層——開發者可以用同一套工具和 API 管理跨環境的應用。

2018 年，CNCF 的生態持續成長——Helm 成為 Kubernetes 的套件管理工具，Prometheus 成為監控標準，Envoy 成為服務網格的主流代理。

## 延伸閱讀

- [AWS re:Invent 2018](https://aws.amazon.com/blogs/aws/)
- [Microsoft Azure Hybrid Cloud](https://azure.microsoft.com/en-us/solutions/hybrid-cloud-app/)
- [Google Cloud Anthos](https://cloud.google.com/anthos)
