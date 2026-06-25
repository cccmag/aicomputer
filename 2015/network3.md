# 物聯網通訊協定 MQTT 與 CoAP 的崛起

## 輕量級通訊的需求

2015 年，隨著物聯網裝置的大量普及，傳統的 HTTP 協定在資源受限的裝置上顯得不適合。HTTP 的標頭開銷大、連線建立成本高、不支援發布/訂閱模型。這催生了 MQTT 與 CoAP 兩種輕量級協定的快速採用。

## MQTT

MQTT（Message Queuing Telemetry Transport）是一種極輕量的發布/訂閱訊息傳輸協定，由 IBM 在 1990 年代開發，2014 年成為 OASIS 標準，並在 2015 年獲得廣泛採用。

MQTT 的設計要點：

- **最小封包開銷**：最小的控制封包僅 2 個位元組
- **發布/訂閱模型**：支援一對多、多對一通訊
- **三種 QoS 等級**：從最多一次傳送到嚴格一次傳送
- **保留訊息**：新訂閱者可以立即獲取最新狀態

## CoAP

CoAP（Constrained Application Protocol）是 IETF 為受限裝置設計的 Web 傳輸協定，本質上是 HTTP 的 UDP 等效物。它基於 REST 架構，支援 GET/POST/PUT/DELETE 方法，但使用 UDP 而非 TCP 來減少開銷。

CoAP 的關鍵特性包括對資源發現、多播支援和非同步訊息交換的內建支援。

## 影響

MQTT 和 CoAP 在 2015 年成為物聯網領域的標準通訊協定。AWS IoT、Azure IoT 和 Google IoT Core 都在 2015-2016 年間加入了對這兩種協定的支援。到 2020 年，MQTT 已經成為物聯網通訊的事實標準。

## 延伸閱讀

- [MQTT 協定規範](https://mqtt.org/)
- [CoAP 協定 - RFC 7252](https://tools.ietf.org/html/rfc7252)
