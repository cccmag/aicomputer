# 物聯網 MQTT 協定標準化

## 輕量級通訊協定的誕生

2014 年，MQTT（Message Queuing Telemetry Transport）正式成為 OASIS（結構化資訊標準促進組織）的國際標準。MQTT 的設計目標是為物聯網和機器對機器（M2M）通訊提供一個輕量級的發布/訂閱訊息傳遞協定。

MQTT 最初由 IBM 的 Andy Stanford-Clark 和 Arcom（後被 Eurotech 收購）的 Arlen Nipper 在 1999 年開發，用於石油天然氣管線的監控應用。2014 年標準化的 MQTT 3.1.1 版本在原始設計的基礎上增加了標準化的遺囑訊息（Will Message）、更好的安全性支援、以及更清晰的協定規範。

## MQTT 的設計哲學

MQTT 的設計反映了物聯網裝置的嚴苛限制：低頻寬、高延遲、不可靠的網路、以及極有限的運算資源。

MQTT 的最小控制封包僅 2 位元組。它支援三種服務品質（QoS）等級：QoS 0（最多一次）、QoS 1（至少一次）、QoS 2（正好一次）。MQTT 的發布/訂閱模型讓感測器可以將資料發布到某個主題（topic），多個訂閱者可以同時接收這些資料，實現了高效的資料分發。

## MQTT 的應用

MQTT 在 2014 年標準化後迅速被廣泛採用。Facebook Messenger 使用 MQTT 處理即時訊息。AWS IoT、Azure IoT 和 Google Cloud IoT 都將 MQTT 作為核心通訊協定。從智慧家庭到工業自動化、從車聯網到能源管理，MQTT 成為物聯網通訊的事實標準。

## 延伸閱讀

- [MQTT - Wikipedia](https://en.wikipedia.org/wiki/MQTT)
- [MQTT 協定規範](https://mqtt.org/)
