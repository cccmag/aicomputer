# LINQ 的出現：資料查詢的語言整合

## C# 3.0 的隱藏革命

2006 年，雖然 LINQ（Language Integrated Query）作為 .NET Framework 3.5 和 C# 3.0 的一部分要到 2007 年才正式發布，但主要的設計工作已經在 2006 年完成。LINQ 是 Anders Hejlsberg（C# 的首席架構師）領導的 Microsoft 團隊從 2004 年開始的一項重大創新。

LINQ 的根本問題是：「為什麼查詢資料庫的語言（SQL）和查詢記憶體中物件的語言（C#/VB.NET）完全不同？」LINQ 的目標是將查詢能力整合到程式語言本身中。

## LINQ 的技術基礎

LINQ 引入了一組語言擴充功能，這些功能單獨來看都有用，但組合在一起產生了革命性效果：

- **擴充方法（Extension Methods）**：可以在不修改原始類別的情況下，為既有型別增加方法
- **匿名型別（Anonymous Types）**：編譯器自動產生唯讀的 .NET 型別
- **隱式型別區域變數（var）**：讓編譯器推斷變數型別
- **物件和集合初始化器（Object/Collection Initializers）**：簡化物件的建構
- **Lambda 運算式**：匿名函式的簡潔語法
- **運算式樹（Expression Trees）**：將 Lambda 運算式表示為資料結構，而非可執行程式碼——這是 LINQ 將 C# 查詢轉換為 SQL 的關鍵機制

## LINQ to Everything

LINQ 的優雅之處在於它的擴充性——透過實作 `IEnumerable<T>` 或 `IQueryable<T>`，任何資料來源都可以被 LINQ 查詢：

- **LINQ to Objects**：記憶體內集合的查詢
- **LINQ to SQL**：SQL Server 資料庫的查詢，自動將 LINQ 運算式轉換為 T-SQL
- **LINQ to XML**：XML 文件的查詢和操作
- **LINQ to Entities**：Entity Framework 的查詢介面

## 影響

LINQ 是程式語言設計史上的一個重要里程碑。它第一次展示了一種通用語言可以優雅地處理多種不同資料模型（關聯式資料庫、XML、物件圖）。LINQ 的概念影響了後來的許多語言和框架——包括 Scala 的 for comprehensions、Kotlin 的序列操作、JavaScript 的 Array 方法、Rust 的 Iterator trait。雖然 C# 不是第一個整合查詢能力的語言，但 LINQ 的設計優雅和 Visual Studio 的工具支援（IntelliSense 偵錯）使其成為整合查詢語言的經典範例。
