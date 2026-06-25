# UUCP 與 Usenet 通訊：分佈式討論的起源

## UUCP 協定

UUCP（Unix-to-Unix Copy Protocol）是 1970 年代末期在 Bell Labs 開發的一套協定，用於在 Unix 系統之間透過數據機和電話線傳輸檔案和電子郵件。UUCP 使用批次處理模式——系統在預定的時間撥號到遠端系統，交換排隊中的消息，然後掛斷。

這種儲存轉發（store-and-forward）模式雖然效率不高（訊息可能要經過多個中間節點、花費數小時才能送達），但它不需要專用線路或持續連線，成本極低。

## Usenet 的技術架構

1979 年建立的 Usenet 依賴 UUCP 來傳輸新聞文章。每篇文章被分配一個唯一的 Message-ID，透過 newsgroups 分類。當一個節點連接到另一個節點時，它會交換各自沒有的文章。

Usenet 最初使用「A-news」軟體套件，後來被 Mark Horton 和 Matt Glickman 編寫的「B-news」取代。B-news 支援了 Usenet 從數個站點到數百個站點的爆炸式成長。Usenet 的分散式架構設計對後來 P2P 網路和社交媒體產生了深遠影響。

## 延伸閱讀

- [UUCP - Wikipedia](https://en.wikipedia.org/wiki/UUCP)
- [Usenet 歷史 - Columbia University](http://www.columbia.edu/~rh120/ch106.x02)
