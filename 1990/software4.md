# HTML 與 HTTP 規範起草

## 全球資訊網的技術基礎

1990 年，Tim Berners-Lee 在實作 WorldWideWeb 瀏覽器和伺服器的過程中，同時起草了全球資訊網的幾項核心技術規範。這些規範在當時還沒有正式的標準文件，而是寫在簡單的技術備忘錄和程式碼註解中。

**HTML（HyperText Markup Language）**： Berners-Lee 設計了一種非常簡單的標記語言來描述文件的結構。最初的 HTML 只有不到 20 個標籤，包括：

- `<TITLE>`：文件標題
- `<H1>` 到 `<H6>`：標題層級
- `<P>`：段落
- `<A HREF="...">`：超連結（最具革命性的標籤）
- `<IMG>`：圖片（在稍後版本中加入）
- `<UL>`、`<OL>`、`<LI>`：清單
- `<DL>`、`<DT>`、`<DD>`：定義清單

**HTTP（HyperText Transfer Protocol）**： HTTP 是一個極簡的客戶端-伺服器協定。最初的 HTTP/0.9 非常簡單：

- 客戶端建立 TCP 連線到伺服器的 80 埠
- 發送 `GET /path/to/file` 指令
- 伺服器返回 HTML 內容，然後關閉連線

沒有 HTTP 標頭、沒有 cookie、沒有狀態管理——簡單到極致。

## 為什麼簡單很重要

HTML 和 HTTP 的極簡設計是全球資訊網成功的關鍵因素之一。與 X.400 或 SGML 等複雜標準不同，HTML 和 HTTP 的門檻極低：

- 任何大學新生都可以在幾小時內學會寫 HTML
- 任何人類語言都可以使用 URL 來連結資源
- 任何平台都可以實作 HTTP 客戶端或伺服器

「足夠好但不完美」的設計哲學讓 WWW 得以迅速擴散，取代了 Gopher、WAIS、HyperCard 等競爭方案。

## 延伸閱讀

- [HTML 歷史 - Wikipedia](https://zh.wikipedia.org/wiki/HTML)
- [HTTP - Wikipedia](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)
- [第一個 HTML 規範 - W3C](https://www.w3.org/History/19921103-hypertext/hypertext/WWW/MarkUp/MarkUp.html)
