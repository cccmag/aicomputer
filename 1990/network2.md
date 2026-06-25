# Gopher 協議：選單式資訊系統

## 明尼蘇達大學的創作

1990 年，明尼蘇達大學的 Mark McCahill、Farhad Anklesaria、Paul Lindner 和 Daniel Torrey 開發了 Gopher 協議。Gopher 的設計目標是讓校園網路上的資訊發布變得簡單——使用者可以透過層層展開的選單來尋找文件，無需記憶複雜的 FTP 位址或檔案路徑。

Gopher 是一個客戶端-伺服器協議。伺服器提供一個階層式的選單結構，每個選單項目可以指向另一層選單、一個文字檔案、一個搜尋查詢、或幾乎任何一種網路資源。使用者透過 Gopher 客戶端（如原始的 gopher 命令列程式，或圖形化的 TurboGopher）來瀏覽。

## Gopher 的設計哲學

Gopher 的設計哲學與 WWW 有根本性的不同：

- **伺服器主導**：內容的組織結構由伺服器管理員決定，使用者只能按照給定的選單瀏覽
- **沒有超連結**：資訊是線性階層式的，而非網狀連結
- **簡單高效**：Gopher 協議比 HTTP 更簡單，伺服器可以運行在非常低階的硬體上

這些特性讓 Gopher 非常適合大學圖書館、目錄系統和內部資訊發布。

## Gopher 對抗 WWW

1991 年到 1993 年間，Gopher 是網際網路上主流的資訊發布系統之一。許多大學和組織建立了 Gopher 伺服器作為網站的前身。

但 Gopher 最終輸給了 WWW。原因包括：

- Gopher 是階層式的，而 WWW 的超連結提供更靈活的瀏覽方式
- WWW 支援行內圖片和豐富的排版
- WWW 的 HTML 允許內容創作者控制視覺呈現
- Gopher 的收費政策（1993 年明尼蘇達大學宣布對商業使用收費）導致了使用者流失

## 延伸閱讀

- [Gopher (協議) - Wikipedia](https://zh.wikipedia.org/wiki/Gopher)
- [Gopher 與 WWW 之爭 - Google 搜尋](https://www.google.com/search?q=Gopher+protocol+1990+University+of+Minnesota)
- [Floodgap Systems Gopher](https://gopher.floodgap.com/)
