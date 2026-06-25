# 四節點 ARPANET 的誕生：網際網路的雛形

## 1969 年的時間線

1969 年是 ARPANET 從計畫到現實的關鍵之年。以下是這一年的四台 IMP 交付時間表：

**8 月**：第一台 IMP 運送到 UCLA，安裝在 Boelter Hall 的 3420 室。BBN 的工程師與 UCLA 的團隊完成了 SDS Sigma 7 主機的連接測試。

**10 月 1 日**：第二台 IMP 安裝在 Stanford Research Institute（SRI）。SRI 的 SDS 940 主機成功連接到 IMP。

**10 月 29 日**：UCLA 與 SRI 之間進行了第一次主機對主機的通訊——完成了人類史上第一次遠端電腦連線（詳見 network1.md）。

**11 月**：第三台 IMP 安裝在加州大學聖塔芭芭拉分校（UCSB），連接 IBM 360/75 主機。

**12 月**：第四台 IMP 安裝在猶他大學，連接 DEC PDP-10 主機。

到 1969 年底，ARPANET 的四節點網路全部連線完成。

## 節點的角色

每個節點都提供了獨特的運算資源：

- **UCLA**：作為網路測量中心（Network Measurement Center），由 Leonard Kleinrock 領導，負責監控和測試網路的性能
- **SRI**：作為網路資訊中心（Network Information Center），負責文件化和協調工作，運行 Engelbart 的 NLS 系統
- **UCSB**：提供圖形顯示和互動計算能力
- **猶他大學**：提供圖形處理和模式識別研究資源

## 網路拓撲

最初的 ARPANET 拓撲是一條線：（UCLA — SRI — UCSB — 猶他大學）。每對相鄰的節點之間透過 50 kbps 的 AT&T 租用電話線路連接。

這個最初的拓撲雖然簡單，但已經能夠驗證分組交換網路的關鍵特性：
- **分散式控制**：沒有中央節點
- **儲存轉發**：訊息可以透過中間節點轉發
- **容錯性**：雖然當前拓撲中斷一條鏈路就會分割網路，但理論上的分散式控制已經建立

## 從四節點到全球網路

ARPANET 在 1969 年的成功驗證了分組交換網路的可行性。1970 年，東岸的 BBN、MIT、哈佛等機構陸續加入。1972 年，ARPANET 公開展示時，已經有 37 個節點。

1983 年，ARPANET 從 NCP 切換到 TCP/IP 協議——這被認為是現代網際網路的起點。1990 年，ARPANET 正式退役，由更龐大的 NSFNET 和後來的商業網際網路取代。

但一切的起點，是 1969 年那間窗戶緊閉的房間裡，四個 IMP 閃爍的指示燈。

## 延伸閱讀

- [ARPANET 首次連線 - DARPA](https://www.darpa.mil/news/features/arpanet)
- [UCLA 的回顧](https://alumni.ucla.edu/ucla-history-45/)
- [最初的 ARPANET 拓撲圖](https://www.computinghistory.org.uk/det/5613/)
