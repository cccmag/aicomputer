# NSFNET 啟動：美國學術網路骨幹

## 從 ARPANET 到 NSFNET

1985 年，美國國家科學基金會（NSF）啟動了 NSFNET 計畫。目標是連結全美五個超級電腦中心——Princeton、Pittsburgh、UCSD、UIUC 和 Cornell——以及國家大氣研究中心（NCAR），讓全美研究人員都能共享這些超級電腦的計算資源。

NSFNET 採用 TCP/IP 協定——這是一個重要的決定。當時還有其他協定可選（OSI、DECNET、SNA），但 NSF 選擇了 TCP/IP，因為它已經在 ARPANET 上經過驗證，而且在 Berkeley UNIX 中免費可用。

## 三層架構

NSFNET 的網路架構分為三個層次：

**骨幹網路**：連接超級電腦中心的高速線路（最初 56 kbps）。

**區域網路**：每個地理區域的區域網路（如 MIDnet、BARRNet、SURAnet），連接區域內的大學和研究機構。

**校園網路**：每個大學自己的 TCP/IP 校園網路。

這種三層架構允許 NSF 以合理的成本覆蓋全國：NSF 投資骨幹和區域網路，大學自行建設校園網路。

## 歷史意義

NSFNET 在 1986 年正式營運，但 1985 年的啟動決策至關重要。NSFNET 後來從 56 kbps 升級到 T1（1988）、T3（1991），最終於 1995 年退役——但那時商業網際網路已經成形。可以說，NSFNET 是網際網路從政府研究計畫過渡到商業基礎設施的橋樑。

## 延伸閱讀

- [NSFNET - Wikipedia](https://en.wikipedia.org/wiki/National_Science_Foundation_Network)
- [NSFNET 歷史 - IBM](https://www.ibm.com/history/nsfnet)
