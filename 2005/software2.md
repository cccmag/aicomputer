# Ruby on Rails 1.0：Web 開發框架的革命

## 從 Basecamp 到改變世界

2005 年 12 月 13 日，David Heinemeier Hansson（DHH）發布了 Ruby on Rails 1.0。這不是一個從零開始的專案——Rails 誕生於 37signals 公司開發 Basecamp 專案管理工具的過程。DHH 從 Basecamp 的程式碼中提煉出一個通用的 Web 開發框架，並於 2004 年 7 月以開放原始碼方式發布了第一個公開版本。

Rails 的核心哲學可以用幾個關鍵詞概括：
- **約定優於配置（Convention over Configuration）**：框架預設合理的慣例，開發者只需指定與慣例不同的部分
- **不要重複自己（Don't Repeat Yourself, DRY）**：每一段知識在系統中只有一個表示
- **敏捷開發**：快速迭代、測試驅動、持續整合

## 技術架構

Rails 整合了完整的 Web 開發棧：
- **Active Record**：ORM（物件關聯對映）層，將資料庫表對應到 Ruby 物件
- **Action Pack**：Controller 和 View 層，處理 HTTP 請求和回應
- **Action Mailer**：郵件發送和接收
- **Active Support**：工具類庫，擴充 Ruby 核心類別
- **Prototype & Script.aculo.us**：JavaScript 函式庫，支援 AJAX 互動

## 影響

Rails 對 Web 開發產生了深遠的影響。它的「約定優於配置」理念被幾乎所有後來的 Web 框架借鑑（包括 Laravel、Django、Spring Boot）。它的「Scaffold」（脚手架）概念讓開發者可以在幾分鐘內建立一個可運作的 CRUD 應用程式。Rails 也將測試驅動開發（TDD）推向主流。

Rails 的成功還帶動了 Ruby 語言的普及——一個在 2004 年還相對冷門的語言，因 Rails 而成為 Web 開發的主流選擇。DHH 在 2005 年證明了一個框架可以改變一個語言的命運。
