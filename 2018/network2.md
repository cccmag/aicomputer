# HTTP/3 與 QUIC 協定

## 新一代 HTTP 協定

2018 年，HTTP/3 的標準化進程在 IETF（網際網路工程任務組）取得了重要進展。HTTP/3 基於 Google 設計的 QUIC 傳輸協定，後者在 2012 年首次部署，經過數年的實戰驗證後開始向 IETF 標準推進。

HTTP/3 目標是解決 HTTP/2 的頭部阻塞（Head-of-Line Blocking）問題——當 HTTP/2 中使用 TCP 傳輸時，一個遺失的封包會阻塞其後所有資料流。

## QUIC 的設計

QUIC（Quick UDP Internet Connections）建立在 UDP 之上，而不是依賴 TCP。這讓 QUIC 可以自行實現可靠的傳輸層功能：

- **0-RTT 連線建立**：重訪時無需握手，立即發送資料
- **多路複用無阻塞**：一個資料流的封包遺失不會影響其他流
- **TLS 1.3 內建加密**：協定層級預設加密
- **更好的壅塞控制**：獨立的流控制，更平滑的傳輸

## 部署與影響

2018 年，QUIC 和 HTTP/3 已經在 Google 的服務中廣泛部署——YouTube、Google Search、Gmail、Google Maps 等都在使用。Facebook 也在 2018 年開始測試 QUIC。

Google 的公開數據顯示 QUIC 帶來了顯著的改善——YouTube 的重新緩衝率降低了 18-30%，Google 搜尋的頁面載入時間減少了 2-8%。

## 延伸閱讀

- [IETF QUIC 工作組](https://datatracker.ietf.org/wg/quic/about/)
- [QUIC，HTTP/3 的未來](https://blog.cloudflare.com/the-road-to-quic/)
