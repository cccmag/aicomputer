# Novell NetWare：檔案伺服器概念

## 從磁碟分享到檔案分享

1983 年，Novell 推出了 NetWare——歷史上第一個以檔案伺服器（file server）為核心的區域網路作業系統。當時市場上的網路系統大多採用「磁碟分享」（disk sharing）模式：用戶端直接存取伺服器上的磁碟區塊，由用戶端自行管理檔案鎖定和同步。

Novell 的創見在於：讓伺服器來管理檔案層級的存取控制。用戶端向伺服器請求檔案讀寫，伺服器負責鎖定、排隊、快取——這就是「檔案伺服器」（file server）概念。這個差異看似細微，卻讓 NetWare 在安全性、穩定性和效能上遠勝競爭者。

## Snipes 與技術驗證

Novell 的開發團隊還做了一件有趣的事：為了測試網路效能，他們寫了一個叫做 Snipes 的文字模式遊戲——這是人類史上第一個為商業個人電腦網路設計的多人遊戲。Snipes 讓多個使用者可以在同一網路上互相射擊，證明了 NetWare 的低延遲通訊能力。

## 市場成功

NetWare 在 1983 年最初運行在 Novell 自製的 Motorola 68000 伺服器上（稱為 S-Net）。1985 年版的 NetWare 86 支援 Intel 8086，讓任何 PC 都可以當伺服器。NetWare 最終成為 1980 年代和 1990 年代初期區域網路的標準，市佔率一度超過 70%。

## 延伸閱讀

- [NetWare - Wikipedia](https://en.wikipedia.org/wiki/NetWare)
- [Novell 歷史 - networkencyclopedia.com](https://networkencyclopedia.com/netware/)
