# Intel Prescott 與散熱危機：NetBurst 的終點

## 90 奈米的挫折

2004 年 2 月，Intel 發布了代號 Prescott 的 Pentium 4 處理器——這是 Intel 首款採用 90 奈米製程的桌上型 CPU。Prescott 的管線深度達到了驚人的 31 級（相較於 Northwood 的 20 級），目的是為了實現更高的時脈速度。Intel 的目標是讓 Pentium 4 在 2005 年達到 4 GHz。

但 Prescott 遭遇了嚴重的散熱問題。它的 TDP（熱設計功耗）在 3.2 GHz 時達到 103W，遠高於 Northwood 的 82W。漏電流（由於閘極氧化層過薄導致的量子穿隧效應）讓 Prescott 在閒置時也比前代產品更耗電。

## 散熱的噩夢

Prescott 的散熱問題不僅是工程上的挑戰，更成為了公關危機。使用者發現 Prescott 系統的風扇噪音巨大、機箱燙手、電費帳單增加。硬體愛好者戲稱 Prescott 為「Preshott」（熱火）和「空間加熱器」。

為了解決問題，Intel 引入了 Thermal Monitor 機制——當晶片溫度過高時自動進行時脈降低（throttling），但這導致了效能下降。更糟糕的是，在相同時脈下，Prescott 的效能經常不如舊的 Northwood——更長的管線在分支預測失敗時會付出更高的代價。

## 策略轉向

Prescott 的失敗導致了深遠的後果：2004 年 5 月，Intel 取消了下一代 NetBurst 處理器 Tejas 和 Jayhawk 的開發。CEO Craig Barrett 承認 Intel 遇到了「散熱牆」。公司開始重新思考處理器設計策略——從追求時脈速度轉向追求每瓦效能。這個轉向在 2006 年以 Core 2 Duo 的形式開花結果。
