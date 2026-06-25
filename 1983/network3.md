# DNS 概念誕生：Mockapetris 的 RFC 882/883

## HOSTS.TXT 的瓶頸

在 DNS 誕生之前，網際網路使用一個名為 HOSTS.TXT 的純文字檔案來維護主機名稱與 IP 位址的對應關係。這個檔案由 SRI 的 NIC 集中維護，所有主機定時下載更新。

到了 1983 年，這個做法已經無法應付網路成長的速度。HOSTS.TXT 的大小不斷增加，更新的延遲越來越長，而且單一節點的故障會影響整個網路的名稱解析。

## Mockapetris 的解方

1983 年 11 月，USC/ISI 的 Paul Mockapetris 發表了 RFC 882 和 RFC 883，提出了域名系統（Domain Name System, DNS）的設計。關鍵創新包括：

**階層式命名空間**：域名以點分隔（如 example.com），形成樹狀結構。根伺服器 → 頂級域（.com、.org）→ 二級域 → 子域。

**分散式資料庫**：不再由單一主機維護所有記錄，而是由成千上萬的名稱伺服器各自維護自己管轄的區域（zone）。查詢可以沿著樹狀結構遞迴進行。

**快取機制**：解析器可以快取查詢結果，減少對上層伺服器的負載。

## 歷史定位

DNS 是網際網路能夠擴展到今日規模的關鍵基礎設施。沒有 DNS，使用者必須記住 IP 位址才能上網。DNS 的設計理念——分散式、階層式、可快取——成為後來許多分散式系統的範本。

## 延伸閱讀

- [DNS 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Domain_Name_System)
- [RFC 882](https://www.rfc-editor.org/rfc/rfc882)
- [RFC 883](https://www.rfc-editor.org/rfc/rfc883)
