# MUMPS：為醫療而生的程式語言

## 從麻州總醫院出發

1966 年，Neil Pappalardo 在波士頓的麻州總醫院（Massachusetts General Hospital）開發了 MUMPS（Massachusetts General Hospital Utility Multi-Programming System），後來的標準名稱簡稱為 M。

MUMPS 的誕生源於一個非常實際的需求：醫院的資訊系統需要同時處理多個使用者的即時請求，並且能夠高效處理醫療記錄這種結構化但非關聯式的資料。當時傳統的檔案系統和資料庫技術都不足以勝任這項任務。

## 獨特的設計選擇

MUMPS 採用了與當時主流程式語言截然不同的設計：

- **內建資料庫**：MUMPS 將程式語言與資料庫管理系統整合為一體，變數自動持久儲存在磁碟上
- **多維稀疏陣列**：使用字串索引的多維陣列（global arrays）作為核心資料結構，特別適合醫療記錄這種稀疏且層次分明的資料
- **多使用者支援**：從設計之初就內建了並發控制和多使用者存取能力
- **字串處理**：具備強大的字串操作功能，適合處理文字為主的醫療記錄

## 醫療領域的霸主

MUMPS 在醫療資訊系統中取得了非凡的成功：

- **VistA**：美國退伍軍人事務部的整合醫療資訊系統完全以 MUMPS 為基礎
- **Epic**：全球最大的電子健康記錄（EHR）供應商之一，其核心系統源自 MUMPS 傳統
- **Intersystems Cache**：MUMPS 的商業後繼者，至今仍在醫療領域廣泛使用

儘管 MUMPS 從未在主流軟體開發中普及，但在醫療資訊領域，它的影響力持續了超過半個世紀。

## 與時代的連結

MUMPS 誕生的 1960 年代，正是分時系統（time-sharing）開始崛起的時代。MUMPS 對多使用者的原生支援，反映了當時電腦使用模式從批次處理向互動式分時的重大轉變。這種「程式語言即資料庫」的整合式設計理念，在某種程度上預示了後來 NoSQL 資料庫和嵌入式資料庫的出現。

## 延伸閱讀

- [MUMPS - Wikipedia](https://en.wikipedia.org/wiki/MUMPS)
- [Neil Pappalardo - Wikipedia](https://en.wikipedia.org/wiki/Neil_Pappalardo)
- [VistA - Wikipedia](https://en.wikipedia.org/wiki/VistA)
