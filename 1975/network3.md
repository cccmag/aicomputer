# SATNET：衛星分組交換網路

## 衛星上的封包

SATNET（又稱 Atlantic Satellite Network）是由 DARPA 資助的衛星分組交換網路計畫，於 1975 年開始正式運作。它的目標是探索如何透過地球同步衛星來傳輸資料封包，將美國與歐洲連接起來。

SATNET 是 Bob Kahn 的網路互連願景中的第三塊拼圖（前兩塊是 ARPANET 和 PRNET）。透過將這三種網路連接在一起，Kahn 能夠驗證在不同類型的網路之間傳輸資料的技術可行性。

## 技術挑戰

衛星網路與地面網路有著根本性的差異：

- **高延遲**：地球同步衛星在 36,000 公里的高空，訊號往返時間約為 250-300 毫秒——是地面網路的數百倍
- **頻寬有限**：早期的衛星資料通道速度只有 64 kbit/s 到 2 Mbit/s
- **廣播性質**：衛星訊號可以同時被數千個地面站接收

SATNET 的設計需要考慮這些因素。它使用了一種稱為 PODA（Priority-Oriented Demand Assignment）的通道存取協定來分配衛星頻寬，並針對高延遲環境優化了流量控制和錯誤恢復機制。

## 對 TCP 的影響

Cerf 和 Kahn 在設計 TCP 時，SATNET 的經驗至關重要。高延遲環境中傳統的「發送-等待」式確認協定效率極低，因此 TCP 引入了滑動視窗（sliding window）和選擇性重傳（selective retransmission）的機制。

## 協作網絡的雛形

SATNET 連接著美國的 ARPANET、挪威的 NORSAR（地震監測網路）和英國的 University College London。研究人員可以利用 SATNET 進行跨大西洋的協作研究——這是全球網路協作的早期範例。

## 延伸閱讀

- [SATNET - Wikipedia](https://en.wikipedia.org/wiki/SATNET)
- [衛星通訊歷史](https://en.wikipedia.org/wiki/History_of_satellite_communication)
- [SATNET 與 TCP 的設計 - Google 搜尋](https://www.google.com/search?q=SATNET+DARPA+satellite+packet+switching+1975)
