# 網路控制協定 NCP 與網路互連願景

## NCP 的角色

在 TCP/IP 出現之前，ARPANET 使用的是 NCP（Network Control Protocol）。NCP 由 Steve Crocker 和 UCLA 的網路工作小組（Network Working Group）在 1970 年設計，負責在 ARPANET 上的主機之間建立和維護連線。

NCP 的設計相對簡單：它為上層應用程式（如 Telnet 和 FTP）提供了可靠的位元串流服務。然而 NCP 有一個根本性的限制——它假設網路是可靠的且是同質性的。當 Kahn 和 Cerf 開始思考如何連接不同類型的網路時，NCP 的侷限性就變得明顯了。

## 從 NCP 到 TCP 的過渡

1974 年，ARPANET 上的大多數主機仍然使用 NCP，但 Cerf 和 Kahn 的論文已經為 TCP 奠定了理論基礎。NCP 與 TCP 的根本差異在於：

- NCP 依賴於 IMP 子網路的可靠性，TCP 則假設下層網路可能不可靠
- NCP 只設計用於 ARPANET，TCP 則設計用於任意網路的互連
- NCP 沒有明確的資料報介面，TCP 則建立在資料報之上

## CYCLADES 網路的影響

值得一提的是法國的 CYCLADES 網路，由 Louis Pouzin 在 1973 年發起。CYCLADES 是世界上第一個以資料報（datagram）為核心設計的分組交換網路。Pouzin 提出的「資料報」概念直接影響了 TCP 的設計——Cerf 和 Kahn 在論文中明確感謝了 Pouzin 的貢獻。

CYCLADES 的設計哲學——讓網路層保持簡單，可靠性和控制功能留在傳輸層和端點——後來成為網際網路架構的基本原則。

## 延伸閱讀

- [NCP - Wikipedia](https://en.wikipedia.org/wiki/Network_Control_Protocol)
- [CYCLADES - Wikipedia](https://en.wikipedia.org/wiki/CYCLADES)
- [RFC 675 - Internet Transmission Control Program](https://www.rfc-editor.org/rfc/rfc675)
