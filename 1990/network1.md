# Archie：第一個網路搜尋引擎

## 當網際網路還沒有 Google

1990 年，全球資訊網尚未普及，網際網路上的資源主要存放在 FTP 伺服器上。當時要找一個檔案只有兩種方法：記住伺服器的位址和目錄路徑，或在 Usenet 上向其他人詢問。

加拿大麥基爾大學（McGill University）的學生 Alan Emtage 決定解決這個問題。他寫了一個程式，可以定期掃描已知的 FTP 伺服器，取得其檔案清單並建立索引。然後使用者可以透過一個簡單的介面來搜尋這個索引。

他將這個系統命名為 **Archie**——根據 Emtage 的說法，這個名字只是一個簡化版的「archive」（歸檔），沒有更深層的意義。

## 運作方式

Archie 的架構非常簡單：

1. **收集**：Archie 每 30 天掃描一次全球的公開 FTP 伺服器
2. **索引**：將所有的檔案名稱和路徑建立成一個可搜尋的資料庫
3. **搜尋**：使用者可以透過 telnet 連線到 Archie 伺服器，或使用本地端的 Archie 客戶端，輸入關鍵字來搜尋檔案

搜尋方式很簡單——只匹配檔案名稱，不分析檔案內容。但它已經足夠有用，Archie 迅速在全球流行起來。

## 歷史意義

Archie 被廣泛認為是第一個網際網路搜尋引擎。它證明了在非結構化的網路資源中建立索引和搜尋的可行性。

Archie 直接啟發了後來的搜尋工具：

- **Gopher**（1991）提供了選單式的瀏覽
- **Veronica**（1992）將 Archie 的概念應用到 Gopher 空間
- **Jughead** 是 Veronica 的簡化版
- **World Wide Web Wanderer**（1993）是第一個 Web 爬蟲

Archie 在 1990 年代中期被 WWW 取代，但它的核心概念——爬取、索引、檢索——仍然是所有現代搜尋引擎的基礎。

## 延伸閱讀

- [Archie (搜尋引擎) - Wikipedia](https://en.wikipedia.org/wiki/Archie_(search_engine))
- [Alan Emtage - Wikipedia](https://en.wikipedia.org/wiki/Alan_Emtage)
- [搜尋引擎歷史 - Wikipedia](https://en.wikipedia.org/wiki/Search_engine_history)
