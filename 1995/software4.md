# PHP：個人首頁工具的崛起

## Rasmus Lerdorf 的工具集

1995 年，丹麥裔加拿大程式設計師 Rasmus Lerdorf 用 C 語言寫了一組簡單的 Perl 腳本，用來追蹤誰在瀏覽他的線上履歷。這組腳本後來演變為「Personal Home Page Tools」（個人首頁工具），簡稱 PHP。

PHP/FI 1.0（FI 代表 Form Interpreter）在 1995 年發布。它的功能非常簡單：接收表單資料、與資料庫互動、在 HTML 中嵌入動態內容。

## 從一個人的工具到全球生態

Lerdorf 最初並沒有打算創建一個新的程式語言——他只是需要一個更方便的方法來建立動態網頁。CGI（Common Gateway Interface）腳本需要編譯或透過 Perl 執行，每次請求都要啟動一個新的程序，效率很低。

PHP 的創新在於：它是一種內嵌於 HTML 的腳本語言，由 Web 伺服器作為模組載入，不需要單獨的程序啟動。Apache mod_php 的架構讓 PHP 的執行效率遠高於 CGI 方案。

## 語言的演進

1995 年的 PHP/FI 與今天的 PHP 截然不同：
- 沒有物件導向支援
- 基本的字串和陣列處理
- 一些簡單的資料庫函數（如 mSQL 和 MySQL）
- 語法與 Perl 相似但更簡化

PHP 在 1997 年由 Zeev Suraski 和 Andi Gutmans 重寫了核心解析器（Zend Engine），開始了向企業級語言的演進。

## 延伸閱讀

- [PHP 歷史 - PHP.net](https://www.php.net/manual/en/history.php.php)
- [Rasmus Lerdorf - Wikipedia](https://en.wikipedia.org/wiki/Rasmus_Lerdorf)
- [PHP/FI - Wikipedia](https://en.wikipedia.org/wiki/PHP)
