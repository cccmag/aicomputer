# XML 1.0：可擴展標記語言的標準化

## 從 SGML 到 XML

1997 年，W3C 發布了 XML 1.0 的提案推薦標準（1998 年 2 月正式成為推薦標準）。XML（eXtensible Markup Language）是由 W3C 的 XML 工作小組開發的，主要設計者包括 Jon Bosak、Tim Bray、James Clark 等人。

XML 是 SGML（Standard Generalized Markup Language，1986 年 ISO 標準）的簡化子集。SGML 功能極其強大但也極度複雜，導致實作困難。XML 保留了 SGML 的核心能力——自定義標記語言——但移除了大部分複雜特性。

## 設計目標

XML 的設計目標包括：
- **直接可用於網際網路**：與 HTTP 和 Unicode 相容
- **廣泛適用性**：適用於各種不同的應用領域
- **與 SGML 相容**：可以輕鬆將 SGML 文件轉換為 XML
- **易於實作**：不需要 SGML 那樣的複雜解析器
- **可選的正式簡潔性**：XML 文件應該是人類可讀的

## 語法規則

XML 定義了一套嚴格的語法規則：
- 必須有根元素（root element）
- 所有開始標籤必須有對應的結束標籤
- 標籤必須正確嵌套
- 屬性值必須用引號括起來
- 空元素必須以 /> 結尾
- 區分大小寫

這些規則聽起來繁瑣，但它們確保了 XML 文件可以被任何標準的 XML 解析器處理——無需事先知道文件的結構。

## 影響

XML 在 1998 到 2005 年間成為資料交換的標準格式。SOAP、XSLT、RSS、SVG、XHTML、DocBook、Microsoft Office 的 Open XML 格式——這些都基於 XML。雖然 JSON 後來在 Web API 領域取代了 XML 的主流地位，但 XML 在文件管理和企業整合領域仍然是不可或缺的。

## 延伸閱讀

- [XML 1.0 規範 - W3C](https://www.w3.org/TR/xml/)
- [XML 歷史 - W3C](https://www.w3.org/XML/hist2002)
- [XML - Wikipedia](https://en.wikipedia.org/wiki/XML)
