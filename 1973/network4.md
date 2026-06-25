# NIC 與 Whois 服務

## 誰在網路上？

隨著 ARPANET 從 1969 年的 4 個節點成長到 1973 年的 40 多個節點，一個新的問題出現了：**你如何知道某人在網路上？** 如果你要發送電子郵件給一台不在你這個站點的使用者，你需要知道他們的位址——但當時沒有黃頁，沒有目錄服務，只有靠口耳相傳。

## NIC 的成立

為了解決這個問題，DARPA 在 1972 年成立了**網路資訊中心**（Network Information Center, NIC），委託史丹佛研究所（SRI）的 Elizabeth "Jake" Feinler 管理。NIC 是 ARPANET 的「電話總機」——它的任務是維護所有網路使用者和主機的聯絡資訊。

1973 年，NIC 開發了 **WHOIS** 服務——一個可以查詢 ARPANET 使用者、主機、和網路資源的線上目錄。使用者可以透過 NIC 的特定主機來查詢誰擁有一個特定的帳號、某個主機的 IP 位址是什麼、或某個組織的網路聯絡人是誰。

## 第一個網路目錄

WHOIS 的早期版本非常簡單。NIC 維護一個純文字檔案（`WHOIS.TXT`），裡面包含了所有 ARPANET 使用者的記錄——姓名、電子郵件地址、電話號碼、所屬機構。任何人都可以透過傳送電子郵件或使用 TELNET 連接到 NIC 的主機來查詢這個檔案。

這個看似簡單的服務，在當時解決了一個重要的社會問題：**網路需要某種形式的身分識別和目錄服務才能正常運作**。WHOIS 的設計——以中央目錄為基礎的查詢服務——後來被 DNS（Domain Name System）繼承並發揚光大。

## NIC 的後續

NIC 在 ARPANET 的成長中扮演了關鍵角色。Feinler 和她的團隊不僅管理 WHOIS，還負責：

- 分配主機名稱（在 DNS 發明之前）
- 維護 ARPANET 的網路地圖
- 發布 RFC 文件（Request for Comments）
- 提供使用者支援和技術文件

1980 年代，WHOIS 被 IANA（網際網路號碼分配機構）接管，成為網域名稱註冊的核心服務。至今，WHOIS 仍然是網際網路基礎設施的重要組成部分——雖然它的隱私問題在 GDPR 時代引發了大量討論。

## 延伸閱讀

- [WHOIS 歷史 - Wikipedia](https://en.wikipedia.org/wiki/WHOIS)
- [網絡資訊中心歷史 - Wikipedia](https://en.wikipedia.org/wiki/Network_Information_Center)
- [WHOIS 與 NIC 歷史 - Google 搜尋](https://www.google.com/search?q=WHOIS+service+NIC+1973+ARPANET)
