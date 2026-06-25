# 硬碟技術：從 ATA 到 Serial ATA

## 平行 ATA 的極限

2002 年，傳統的平行 ATA（Parallel ATA，也稱為 IDE）硬碟介面遇到了發展瓶頸。ATA/133 是平行 ATA 的最後一個版本，理論傳輸速率為 133 MB/s——但平行傳輸的訊號干擾、線纜長度限制和電壓問題已經讓這個介面難以進一步提速。

40 針的平行排線不僅佔用機殼空間，還阻礙了機殼內的空氣流通——這在追求散熱效能的時代成為了一個實際問題。

## Serial ATA 的誕生

2002 年，Serial ATA 國際組織（SATA-IO）發布了 Serial ATA 1.0 規格。SATA 從根本上改變了儲存介面的設計：

**序列傳輸**：使用差分訊號的點對點序列連接，取代了平行匯流排的多裝置共享架構

**更高頻寬**：SATA 1.0 提供 1.5 Gbps（約 150 MB/s）的傳輸速率，考慮到編碼開銷後實際傳輸速率與 ATA/133 相當

**更細的線纜**：7 針的 SATA 資料線纜比 40 針的 ATA 排線細得多，便於佈線和散熱

**熱插拔支援**：SATA 設計了原生熱插拔能力，這是伺服器和儲存陣列的重要功能

**電壓更低**：SATA 使用 250 mV 的訊號電壓（比 ATA 的 5 V 低得多），功耗更低

## 對產業的影響

SATA 的標準化在 2002 年啟動了硬碟介面的世代交替。在接下來的幾年中，SATA 迅速取代了 Parallel ATA 成為主流的儲存介面。SATA 的發展也為後來的 SSD 時代做好了準備——SSD 使用與 SATA 相同的介面標準。

## 硬碟容量里程碑

2002 年，硬碟的儲存密度持續提升。Maxtor 和 Seagate 開始出貨 160 GB 到 200 GB 的 3.5 吋硬碟——這在 1999 年還被認為是不可想像的容量。

## 延伸閱讀

- [Serial ATA - Wikipedia](https://zh.wikipedia.org/wiki/Serial_ATA)
- [硬碟歷史 - Wikipedia](https://en.wikipedia.org/wiki/Hard_disk_drive_history)
