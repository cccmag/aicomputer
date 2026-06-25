# 1973 年圖靈獎：Charles Bachman

## 資料庫管理系統之父

Charles Bachman 是 1973 年 ACM 圖靈獎得主，獲獎理由是「他在資料庫管理系統領域的傑出貢獻」。他是第一位將圖靈獎頒給資料庫領域的得主——這反映了 1970 年代初期資料庫技術從學術研究走向商業應用的歷史性轉折。

## 整合式資料儲存（IDS）

Bachman 最重要的貢獻是 **整合式資料儲存**（Integrated Data Store, IDS）——世界上第一個資料庫管理系統（DBMS）。這套系統於 1963 年在通用電氣（GE）開發完成，但它的影響在整個 1960 年代和 1970 年代持續發酵。

IDS 是一套**網路式資料模型**（network data model）的實作。不同於 IBM 後來主導的**階層式資料模型**（如 IMS，1968 年），IDS 允許記錄之間存在多對多的關係。

在網路式模型中，資料不是以表格（relational）或樹狀（hierarchical）組織，而是以**圖**（graph）的形式存在。記錄（record）是圖中的節點，而「set」（集合）是節點之間的邊（有向的關聯）。這種模型非常適合描述複雜的真實世界關係——例如，一個零件可以屬於多個供應商，一個供應商可以供應多個零件。

## Bachman 對資料庫理論的貢獻

Bachman 不僅實作了第一個 DBMS，還發展了重要的理論概念：

**資料獨立性**：他主張應用程式應該與資料的實際儲存結構分離。程式設計師應該透過邏輯資料模型來操作資料，而不需要關心資料在磁碟上具體如何存放。這個概念後來成為所有資料庫系統的基本原則。

**導航式資料存取**：Bachman 的網路模型需要程式設計師「導航」通過資料結構——從一個記錄跟隨關聯到另一個記錄。這與 Codd 後來在 1970 年提出的關係模型中宣告式的 SQL 風格截然不同，但在處理複雜的、層次化的查詢時往往更有效率。

**Bachman 圖**：他發明了一種用來視覺化資料庫結構的圖形方法——「Bachman 圖」（Bachman diagram），至今仍在資料建模中使用。

## CODASYL 與資料庫標準化

1960 年代末期，Bachman 成為了 **CODASYL 資料庫任務組**（DBTG）的核心人物。CODASYL 試圖為網路式資料模型制定標準，這項工作在 1971 年和 1973 年分別發布了 DBTG 報告。

然而，Bachman 的網路式模型與 Edgar Codd 在 1970 年提出的**關係模型**之間爆發了激烈的學術論戰。Codd 認為關係模型在數學基礎和資料獨立性上更優越；Bachman 則認為網路模型在實際性能上更強。

這場辯論最終由關係模型獲勝——SQL 和關係資料庫（如 Oracle、DB2、MySQL）主導了後來的資料庫產業。但 Bachman 的貢獻不可磨滅：他證明了電腦可以用來管理複雜的資料關係，並為整個資料庫領域奠定了實踐基礎。

## 圖靈獎演講

Bachman 在 1973 年的圖靈獎演講「The Programmer as Navigator」中，將程式設計師比喻為在資料海洋中航行的航海家。他描繪了一幅資料處理的未來願景——程式設計師將使用高階工具來探索和操作資料，而不再需要關心底層的儲存細節。這個願景——雖然經過了從網路模型到關係模型的技術轉變——最終在資料庫管理系統的普及中實現了。

## 延伸閱讀

- [Charles Bachman - ACM Turing Award](https://amturing.acm.org/award_winners/bachman_0668473.cfm)
- [Charles Bachman - Wikipedia](https://en.wikipedia.org/wiki/Charles_Bachman)
- [Bachman 與資料庫歷史 - Google 搜尋](https://www.google.com/search?q=Charles+Bachman+1973+Turing+Award+database)
