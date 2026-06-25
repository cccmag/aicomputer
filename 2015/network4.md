# HTTP/2 標準化：更快更安全的網路

## 從 HTTP/1.1 到 HTTP/2

2015 年 5 月，IETF 正式發布 HTTP/2 標準（RFC 7540），這是 HTTP 協定自 1999 年 HTTP/1.1 以來最重大的更新。HTTP/2 的核心目標是解決 HTTP/1.1 長期以來的效能問題——特別是在載入現代網頁時的瓶頸。

HTTP/2 的設計基於 Google 在 2009 年開發的 SPDY 協定，借鑒了 SPDY 在 Google 服務中大規模部署的經驗教訓。

## 主要改進

HTTP/2 引入了以下關鍵創新：

- **多路複用**：單一 TCP 連線可以同時傳送多個請求和回應，消除了 HTTP/1.1 的 HOL（Head-of-Line）阻塞問題
- **伺服器推送**：伺服器可以主動將客戶端尚未請求但預期需要的資源送到快取
- **二進制分幀**：將訊息分割為更小的幀，支援優先級和流量控制
- **標頭壓縮**：使用 HPACK 演算法減少重複標頭的開銷

## 部署與影響

HTTP/2 在標準化之前就已經開始部署。Google 的 SPDY 從 2009 年開始就在 Chrome 和 Google 伺服器上使用。2015 年標準發布後，所有主要瀏覽器（Chrome、Firefox、Safari、Edge）迅速支援 HTTP/2。Nginx、Apache、IIS 等主要 Web 伺服器也在年內添加了 HTTP/2 支援。

HTTP/2 的採用標誌著現代 Web 效能優化的新時代——開發者不再需要做許多 HTTP/1.1 時代的 workaround（如 sprite、concatenation、domain sharding）。

## 延伸閱讀

- [HTTP/2 RFC 7540](https://tools.ietf.org/html/rfc7540)
- [HTTP/2 說明 (Google)](https://developers.google.com/web/fundamentals/performance/http2/)
