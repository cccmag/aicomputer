# IRC：即時聊天的誕生

## Jarkko Oikarinen 的創造

1988 年 8 月，芬蘭歐魯大學（University of Oulu）的學生 Jarkko Oikarinen 為了改進校內 BBS 系統的通訊功能，寫出了 Internet Relay Chat（IRC）的原始碼和第一個伺服器。

IRC 的靈感來自 Unix 的 `talk` 程式——但 `talk` 只支援一對一通訊。Oikarinen 想要一個可以讓多人同時參與的聊天系統。他的解決方案是建立一個客戶端-伺服器架構，允許多個使用者在不同「頻道」（channel）中即時交流。

## IRC 的架構

IRC 的基本設計非常優雅且高效：

- **分散式伺服器網路**：多個 IRC 伺服器可以互相連接，形成一個全球網路
- **頻道**：以 # 開頭的聊天室，使用者可以加入或離開
- **私訊**：一對一的私人訊息
- **操作者（Operator）**：頻道管理員，可以踢人或設定主題
- **暱稱（Nickname）**：每個使用者以暱稱而非真實姓名參與

## 文化影響

IRC 在 1990 年代成為了網際網路上最重要的社交平台之一。軟體開發者使用 IRC 來協作開源專案（Linux 的核心開發者就大量使用 IRC），一般使用者則用它來結交來自世界各地的朋友。

IRC 也見證了重大歷史事件：1991 年蘇聯政變期間，IRC 使用者從莫斯科即時分享消息；1993 年俄羅斯憲政危機期間，IRC 同樣被用作資訊傳播管線。

與現代的 Slack 和 Discord 相比，IRC 的設計簡單到幾乎樸素（純文字、沒有檔案傳輸內建支援），但這種簡單正是它存活到今日的原因。

## 延伸閱讀

- [IRC - Wikipedia](https://zh.wikipedia.org/wiki/IRC)
- [Jarkko Oikarinen - Wikipedia](https://en.wikipedia.org/wiki/Jarkko_Oikarinen)
- [IRC 歷史 - Google 搜尋](https://www.google.com/search?q=IRC+history+1988+Oikarinen)
