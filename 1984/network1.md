# DNS 設計定案：Mockapetris 的分散式命名

## 從概念到規格

1983 年 11 月，Paul Mockapetris 發表了 DNS 的基本概念（RFC 882）和實作規格（RFC 883）。1984 年，這份設計開始從論文走向實作——這是 DNS 從理論走向現實的關鍵一年。

Mockapetris 在 USC/ISI 撰寫了第一個 DNS 實作，代號「Jeeves」，執行在 TOPS-20 作業系統上。Jeeves 實作了遞迴查詢、快取和區域傳輸等核心功能。

## 分散式管理的哲學

DNS 的設計哲學反映了網際網路的核心價值：分散式控制。在 DNS 之前，HOSTS.TXT 由 SRI NIC 集中管理——每次新增一台主機都必須通知中央管理員。DNS 讓每個組織可以自行管理自己的域名空間，不需要中央授權。

這在政治和組織層面上是一個重要的里程碑：它意味著網路成長的控制權從中央分散到了各地。沒有這個設計，網際網路無法擴展到今日的規模。

## 1984 年的部署進展

1984 年，部分主機開始實驗性地使用 DNS 進行名稱解析。雖然 HOSTS.TXT 仍然是主流，但 DNS 的優勢——尤其是對於不斷成長的校園網路——已經開始顯現。Berkeley 的 4.2BSD 整合了 BIND（Berkeley Internet Name Domain）的早期版本，使得 DNS 用戶端廣泛部署。

## 延伸閱讀

- [Paul Mockapetris - Wikipedia](https://en.wikipedia.org/wiki/Paul_Mockapetris)
- [DNS 歷史 - ACM SIGCOMM 1988 論文](https://dl.acm.org/doi/10.1145/52324.52338)
