# HTML 與 HTTP：全球資訊網的技術基礎

## 從概念到規範

1990 年，Tim Berners-Lee 在 CERN 的 NeXT 電腦上開發 WorldWideWeb 程式的過程中，同時定義了全球資訊網的三項核心技術：

**URI（Uniform Resource Identifier）**：為每一個資源提供一個唯一的位址。Berners-Lee 選擇了 `http://` 作為協定前綴，後面跟著伺服器名稱和檔案路徑。這個方案的成功來自它的簡單和直觀。

**HTML（HyperText Markup Language）**：標記語言的設計借鑒了 SGML（Standard Generalized Markup Language）的概念，但比 SGML 簡化了許多。HTML 使用成對的「標籤」來標記文件的結構元素——標題、段落、清單和最重要的超連結。

**HTTP（HyperText Transfer Protocol）**：一個極簡的請求-回應協議。最初的 HTTP/0.9 只有一個方法（GET），伺服器返回純 HTML，然後關閉連線。沒有 HTTP 標頭、沒有 cookie、沒有 multipart 響應——簡單到極致。

## 設計哲學：最小可行產品

Berners-Lee 的設計哲學可以總結為「最小可行產品」。他刻意將 HTML 和 HTTP 設計得非常簡單，因為：

- 簡單的標準更容易被廣泛實作
- 低門檻讓更多人能夠參與內容創作
- 功能可以逐步添加（向後相容）

這種哲學與 OSI 的「設計完整再實現」形成鮮明對比。歷史證明，Berners-Lee 的策略是正確的。

## 從規範到標準

1990 年的 HTML 和 HTTP 規範還是私人的技術備忘錄，而非正式的國際標準。Berners-Lee 在 1991 年將第一個公開的文件發布到 Usenet 上。1994 年，他創立了 W3C（World Wide Web Consortium）來負責 Web 標準的制訂。

## 延伸閱讀

- [HTML 歷史 - W3C](https://www.w3.org/History/19921103-hypertext/hypertext/WWW/MarkUp/MarkUp.html)
- [HTTP 歷史 - W3C](https://www.w3.org/Protocols/HTTP/AsImplemented.html)
- [URIs, URLs, and URNs - W3C](https://www.w3.org/TR/uri-clarification/)
