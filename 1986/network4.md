# DNS 實戰部署：域名系統的啟用

## 從 HOSTS.TXT 到 DNS

1986 年，DNS（域名系統）開始從實驗規格走向生產環境的實際部署。雖然 Mockapetris 在 1983 年就定義了 DNS 的設計，但真正讓數千台主機從 HOSTS.TXT 轉向 DNS 是一個緩慢的過程。

1986 年，部分主機——特別是執行 Berkeley UNIX 的機器——開始將 DNS 作為名稱解析的主要方式。BIND（Berkeley Internet Name Domain）——由柏克萊的學生 Douglas Terry、Mark Painter、David Riggle 和 Songnian Zhou 開發——成為最廣泛使用的 DNS 用戶端和伺服器實作。

## 根伺服器的建立

1986 年，最初的 DNS 根伺服器開始運作。這些伺服器由 Jon Postel 和 USC/ISI 管理，負責維護頂級域（.com、.org、.edu、.gov、.mil）和其他頂級域的授權記錄。

根伺服器的建立是分散式 DNS 系統的核心：它們不需要直接回答所有查詢，只需要指引查詢者到負責特定頂級域的名稱伺服器。一個查詢 example.com 的請求，從根伺服器出發，經過 .com 伺服器，最後到達負責 example.com 的權威伺服器。

## 過渡期的挑戰

DNS 的部署不是一蹴可幾的。1986 年，大多數主機仍然使用 HOSTS.TXT 進行名稱解析。過渡的挑戰包括：

**快取一致性**：DNS 的快取機制導致了更新的延遲。

**容錯設計**：某些 DNS 伺服器的故障曾導致部分地區的名稱解析中斷。

**管理權限的爭議**：誰有權分配頂級域名、誰可以管理根伺服器——這些問題在 1986 年就已經出現，並持續到今日。

## 延伸閱讀

- [DNS 歷史 - ACM SIGCOMM 1988](https://dl.acm.org/doi/10.1145/52324.52338)
- [BIND - Wikipedia](https://en.wikipedia.org/wiki/BIND)
