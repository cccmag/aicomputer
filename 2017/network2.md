# WebRTC 標準化與即時通訊

## 瀏覽器內建即時通訊

2017 年，WebRTC（Web Real-Time Communication）技術在各主要瀏覽器中達到實質性的互操作性。雖然 WebRTC 的規格在 2011 年就已提出，但 2017 年是這個技術真正成熟並被大規模採用的一年。

WebRTC 允許瀏覽器和行動應用程式無需安裝外掛即可進行即時語音、視訊通話和資料傳輸。它由三組核心 API 組成：

- **getUserMedia**：存取攝影機和麥克風
- **RTCPeerConnection**：建立和管理點對點連線
- **RTCDataChannel**：低延遲的點對點資料傳輸

## QUIC 與 WebRTC 的協同

2017 年，Google 在 WebRTC 中生大量部署了 QUIC 協定。QUIC 是 Google 設計的基於 UDP 的傳輸層協定，解決了 TCP 在即時通訊中的頭部阻塞問題。QUIC 後來被 IETF 標準化為 HTTP/3。

WebRTC + QUIC 的組合讓即時通訊的品質大幅提升——更好的壅塞控制、更快的連線建立、更好的行動網路適應性。

## 應用場景

2017 年，WebRTC 的應用場景從早期的瀏覽器通話擴展到：

- **遠距會議**：Zoom、Google Meet、Microsoft Teams 使用 WebRTC
- **遊戲直播**：Twitch 和 YouTube Gaming 使用 WebRTC 進行串流
- **線上教育**：ClassIn、VIPKID 等教育平台
- **醫療保健**：遠距醫療應用的即時視訊

## 延伸閱讀

- [WebRTC 官方網站](https://webrtc.org/)
- [WebRTC 標準 - W3C](https://www.w3.org/TR/webrtc/)
