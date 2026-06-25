# BBN TELNET 與電子郵件

## TELNET 協定的誕生

1972 年，Bolt Beranek and Newman（BBN）的工程師們正在開發 ARPANET 的第一套標準遠端終端機協定——TELNET。

在 ARPANET 之前，要連接到遠端電腦，使用者必須有該電腦專用的終端機和數據機連線。TELNET 的目標是：讓任何 ARPANET 主機上的使用者，都能像本機終端機一樣登入到任何其他主機。這在當時被稱為「網路虛擬終端機」（Network Virtual Terminal, NVT）的概念。

TELNET 規格（RFC 318）在 1972 年由 Jon Postel 和 Steve Crocker 等人制定。它定義了一種以 ASCII 為基礎的雙向文字通訊協定，並包含了選項協商機制——允許客戶端和伺服器協商終端類型、頁面大小等參數。

雖然 TELNET 今日已被 SSH 取代，但它的設計哲學——定義一個最小的共通協定，再透過協商擴展——深刻影響了後續的網路協定設計。

## 電子郵件的革命

1972 年也是電子郵件歷史的關鍵年份。Ray Tomlinson 在 BBN 已經在 1971 年發明了網路電子郵件——他選擇了 @ 符號來分隔使用者名稱和主機名稱。但到了 1972 年，隨著 ARPANET 的成長，電子郵件開始從一個實驗性工具轉變為網路上的「殺手級應用」。

Tomlinson 為 TENEX 作業系統寫了兩個程式：`SNDMSG`（發送訊息）和 `READMAIL`（讀取郵件）。它們使用了 FTP 協定的基礎來在機器之間傳輸郵件檔案。

## 電子郵件成為主流

1972 年 7 月，Larry Roberts——ARPANET 的計畫經理——寫了第一個電子郵件管理程式，可以列出郵件清單、選擇性閱讀、回覆和轉發。這讓電子郵件從單純的訊息傳送變成了完整的通訊工具。

到 1972 年底，電子郵件已經佔據了 ARPANET 流量的 75%。這個從未預料到的使用模式，證明了網路最大的價值不在於共享計算資源——原始設計目標——而是在於人與人之間的通訊。

## 延伸閱讀

- [TELNET 協定歷史 - Wikipedia](https://en.wikipedia.org/wiki/Telnet)
- [Ray Tomlinson 與電子郵件 - Google 搜尋](https://www.google.com/search?q=Ray+Tomlinson+email+1972+@)
- [RFC 318 - TELNET Protocol](https://datatracker.ietf.org/doc/html/rfc318)
