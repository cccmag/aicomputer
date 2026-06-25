# IBM IMS：為阿波羅計畫打造的資料庫巨輪

## 登月任務的零件管理危機

1960 年代，美國 NASA 的阿波羅計畫面臨一個驚人的管理挑戰：一艘太空船由超過五百萬個零件組成，每一項零件都需要追蹤其供應商、版本、庫存與工程變更。當時的解決方案是打孔卡片和紙本記錄，效率極低且容易出錯。

1965 年，北美航空（North American Rockwell，阿波羅太空船的主承包商）與 IBM 合作，著手開發一套能夠管理這項複雜任務的軟體系統。

## ICS/DL/I 的誕生

IBM 的 Uri Berman 與 Rockwell 的 Peter Nordyke 最早在 IBM 7010 電腦上開發了名為「DATE」（Disk Applications in a Teleprocessing Environment）的雛形系統。Berman 做出了一個關鍵設計決策：將資料的物理儲存與使用者介面的邏輯分離。這個決策後來演化為 DL/I（Data Language/Interface）——一種獨立的資料存取介面。

1966 年，IBM、Rockwell 與 Caterpillar Tractor 組成了聯合開發團隊，在加州 Downey 展開了 ICS/DL/I（Information Control System and Data Language/Interface）的開發。1968 年 8 月 14 日，第一個「READY」訊息出現在 Rockwell 的 IBM 2740 終端機上——IMS 正式上線。

## 階層式資料模型

IMS 採用階層式（hierarchical）資料模型：資料組織成樹狀結構，從根段（root segment）開始，向下延伸出子段。例如，一個太空船零件記錄可能包含一個根段（零件編號、名稱），下面有多個子段（供應商資訊、工程變更記錄）。

這個模型在當時是非常先進的抽象概念。在此之前，應用程式必須直接處理磁帶或磁碟上的原始資料結構。IMS 讓應用程式可以透過 DL/I 的標準函式呼叫來存取資料，無須關心底層的儲存細節。

## 商業化與深遠影響

1969 年，IBM 將 ICS 重新命名為 IMS/360（Information Management System/360）並推向市場。IMS 獲得了巨大的商業成功：1988 年時已有 7,000 個安裝點，至今仍是全球銀行、航空與保險業的核心交易處理平台。

IMS 開創了資料庫管理系統的商業模式，證明了「將軟體從客製化專案轉變為標準化產品」的可行性。它與後來的 CICS、Db2 共同定義了 IBM 在企業級資料處理領域數十年的領導地位。

## 延伸閱讀

- [IBM IMS 歷史 - IBM](https://www.ibm.com/history/information-management-system)
- [IMS 概述 - Wikipedia](https://zh.wikipedia.org/wiki/IBM_Information_Management_System)
- [IMS: Then and Now - Pearson](https://ptgmedia.pearsoncmg.com/images/0131856715/samplechapter/0131856715_ch01.pdf)
