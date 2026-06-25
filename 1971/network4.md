# FTP 協定的發展：檔案傳輸的標準化

## 共享資源的需求

ARPANET 的核心目標之一是資源共享。在 1971 年，TELNET 已經實現了遠端登入，但使用者還需要一種標準化的方法來在電腦之間傳輸檔案。

FTP（File Transfer Protocol）的設計工作由 Network Working Group 的 Abhay Bhushan 主導。1971 年 4 月 16 日，Bhushan 發表了 RFC 114「A File Transfer Protocol」，定義了 ARPANET 上的標準檔案傳輸方法。

## FTP 的設計原則

FTP 的設計考慮了以下關鍵場景：
- **從遠端系統下載檔案到本地**
- **從本地上傳檔案到遠端系統**
- **在兩個遠端系統之間傳輸檔案**
- **目錄和檔案管理操作**

FTP 使用兩個連線：一個控制連線用於傳送指令，一個資料連線用於傳送檔案內容。這個分離設計讓伺服器可以在傳送檔案的同時接收新的指令。

## 早期的挑戰

原始 FTP 規範相當基本。它支援三種傳輸模式：
- **Stream mode**：資料以連續的位元組串流傳送
- **Block mode**：資料被分為區塊傳送
- **Compressed mode**：使用執行長度編碼壓縮資料

FTP 的開發在 1970 年代持續演化，最終在 1985 年標準化為 RFC 959——至今仍是網際網路的標準協定。

## 歷史意義

FTP 的開發展示了 ARPANET 應用的成長路徑：從基本的遠端登入，到標準化的檔案傳輸，再到後來的電子郵件和新聞群組。每一層應用都建立在前一層的基礎之上。

## 延伸閱讀

- [RFC 114 - A File Transfer Protocol](https://www.rfc-editor.org/rfc/rfc114)
- [FTP 歷史 - Wikipedia](https://en.wikipedia.org/wiki/File_Transfer_Protocol)
