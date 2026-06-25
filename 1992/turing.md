# 1992 年圖靈獎：Butler Lampson

## 分散式個人運算的建築師

Butler Lampson 是 1992 年 ACM 圖靈獎得主，獲獎理由是「對分散式個人運算環境及其實作技術的貢獻：工作站、網路、作業系統、程式設計系統、顯示器、安全性和文件出版。」

Lampson 的圖靈獎代表了一個罕見的成就——他不僅是一位理論家，更是一位將理論化為實際系統的建築師。他在 Xerox PARC 的工作定義了個人電腦的基本架構。

## Alto：第一部現代個人電腦

1973 年，Lampson 作為 Xerox PARC 的技術領導者，設計了 Alto——第一部具備今日個人電腦所有核心特徵的機器：
- 位元映射（bitmap）顯示器（600 x 800 畫素）
- 滑鼠作為標準輸入設備
- 乙太網路（Ethernet）連接
- 雷射印表機（Lampson 設計了電子系統）
- 圖形化使用者介面（GUI）
- WYSIWYG 文字編輯器

Alto 從未被商業化，但它所做的設計決策——個人擁有專屬電腦而非共享大型主機——徹底改變了運算環境。

## 乙太網路與分散式系統

Lampson 參與了乙太網路的設計——這項由 Bob Metcalfe 發明的區域網路技術。更重要的是，Lampson 設計了運行在 Alto 和乙太網路之上的軟體系統：

- **Alto 作業系統**：單使用者系統，所有服務皆透過網路存取
- **Grapevine 名稱伺服器**：處理網路中不斷變更的命名和驗證
- **Juniper 檔案系統**：可靠的分散式檔案儲存
- **遠端程序呼叫（RPC）**：讓一台電腦的程式呼叫另一台電腦的程式

這些系統共同建立了「個人工作站/區域網路/伺服器」的運算範式——一個完全取代了終端機/大型主機範式的架構。

## Mesa 語言與 Interpress

Lampson 在 PARC 期間還參與了兩項重要的程式語言和文件技術：
- **Mesa 語言**：一種系統實作語言，結合了強型別檢查和模組化設計
- **Interpress**：裝置無關的文件描述語言——PostScript 的前身

Mesa 解決了大型系統開發中的型別安全和模組化問題，其設計影響了 Java 和 C# 等後來的語言。

## 圖靈獎演講

Lampson 的圖靈獎演講〈How to Build a Highly Available System Using Consensus〉探討了如何在分散式系統中達成共識——這是 Paxos 演算法及其應用的討論。他用「要讓分散式系統可靠，你需要共識」的簡單命題，展開了一個影響分散式運算領域的演講。

## 延伸閱讀

- [Butler Lampson - ACM Turing Award](https://amturing.acm.org/award_winners/lampson_1142421.cfm)
- [Butler Lampson - Wikipedia](https://en.wikipedia.org/wiki/Butler_Lampson)
- [Alto 電腦 - Computer History Museum](https://www.computerhistory.org/revolution/personal-computers/17/300)
