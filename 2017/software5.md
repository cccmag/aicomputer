# gRPC 框架的普及

## 微服務間的通訊革命

2017 年，gRPC 從 Google 內部專案成長為開源微服務通訊的主流方案。gRPC 最初由 Google 在 2015 年開源，但到了 2017 年，隨著微服務架構的廣泛採用和 Kubernetes 生態的成熟，gRPC 開始真正流行。

gRPC 是一個高效能、開源的遠端程序呼叫（RPC）框架，基於 HTTP/2 協定和 Protocol Buffers（protobuf）序列化格式。與傳統的 REST/JSON 方案相比，gRPC 提供了更低的延遲、更小的訊息體積和更嚴格的型別定義。

## 技術優勢

gRPC 的核心優勢來自其技術選擇：

- **HTTP/2 多路複用**：單一連線支援多個並行請求，消除 HOL 阻塞
- **Protocol Buffers**：二進制序列化比 JSON 小 3-10 倍，解析速度快 20-100 倍
- **雙向串流**：支援 server streaming、client streaming 和 bidirectional streaming
- **程式碼生成**：從 proto 檔案自動生成客戶端和伺服器程式碼

## 生態擴展

2017 年，gRPC 在以下領域獲得了廣泛採用：

- **微服務內部通訊**：取代 REST 成為服務間通訊的首選
- **IoT 與邊緣運算**：輕量級的 protobuf 訊息適合帶寬受限的場景
- **機器學習服務**：TensorFlow Serving 使用 gRPC 提供模型推論服務

gRPC 的成功也催生了 gRPC-Web——讓瀏覽器端的 JavaScript 應用可以使用 gRPC 進行通訊。

## 延伸閱讀

- [gRPC 官方網站](https://grpc.io/)
- [gRPC 介紹](https://grpc.io/docs/what-is-grpc/introduction/)
