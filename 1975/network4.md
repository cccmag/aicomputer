# TCP 協定的持續演化

## 從論文到規格

Cerf 和 Kahn 在 1974 年 5 月發表 TCP 論文後，接下來的一年是將理論轉化為可實作規格的關鍵時期。1975 年，多個研究團隊開始嘗試實作 TCP，從中發現了原始設計中的問題和不足。

最重要的版本迭代是 RFC 675（1974 年 12 月）後續的討論。Cerf 與史丹福大學的研究生們——特別是 Yogen Dalal 和 Carl Sunshine——在 1975 年協同撰寫了多份 RFC，詳細說明了 TCP 的連線建立、序列號管理、流量控制和壅塞控制機制。

## 史丹福的 TCP 實作

1975 年，史丹福大學的團隊在 Cerf 的指導下開始開發 TCP 的首次實作。這個實作在一個改良版的 PRIME 計算機系統上運行，並與 BBN 的 Gateway 路由器進行了互操作性測試。

這段時期的關鍵發現包括：

- 原始的 TCP 規範將流量控制和錯誤控制混在一起，導致實作複雜
- 需要在主機和閘道器之間進行更清晰的職責劃分
- 封包重組的緩衝區管理在高延遲網路上是一個嚴峻的挑戰

這些經驗累積最終促成了 1978 年 TCP 協議被拆分為 TCP 和 IP 兩個獨立層次的決定。

## 網路層的思考

1975 年的另一個重要發展是 Cerf 開始將網路層（IP）與傳輸層（TCP）的概念分開。原始的 TCP 設計試圖在同一個協定中處理路由（網路層功能）和可靠性（傳輸層功能），隨著實作經驗的累積，拆分的好處越來越明顯。

## 跨大西洋的連接

1975 年，ARPANET 透過 SATNET 成功地與挪威和英國建立了連接。雖然這條跨大西洋鏈路速度緩慢（初期僅 9.6 kbit/s），但它驗證了 TCP 在全球範圍內運作的可行性。

## 延伸閱讀

- [TCP 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
- [RFC 675 - Internet Transmission Control Program](https://www.rfc-editor.org/rfc/rfc675)
- [TCP 協定設計史 - Google 搜尋](https://www.google.com/search?q=TCP+protocol+evolution+1975+Cerf+Stanford)
