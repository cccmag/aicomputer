# 2004 年圖靈獎：Vint Cerf & Bob Kahn

## 網際網路的建造者

Vint Cerf 和 Bob Kahn 是 2004 年 ACM 圖靈獎的共同得主，授獎理由是「為網際網路的通訊協定做出開創性貢獻，包括 TCP/IP 協定的設計與實作」。他們的工作為全球網際網路奠定了技術基礎。

故事始於 1973 年——Kahn 在 DARPA 提出了一個「開放式架構網路」的構想，目標是讓不同類型的網路（分組無線電網、衛星網路、ARPANET）可以互相通訊。他邀請了史丹佛大學的 Cerf 加入這個專案。

## TCP/IP 的誕生

Cerf 和 Kahn 在 1974 年 5 月發表了經典論文「A Protocol for Packet Network Intercommunication」，提出了 TCP（傳輸控制協定）的概念。這篇論文奠定了網際網路架構的三個核心原則：

- **網路層的不可靠性**：網路本身不保證封包送達，可靠性由端點負責
- **黑盒子設計**：不需要了解中間網路的內部細節
- **全球定址**：每個節點有唯一的 IP 位址

最初的 TCP 同時處理資料傳輸和封包路由功能。1978 年，Cerf 和團隊將 TCP 拆分為 TCP（負責端到端可靠性）和 IP（負責封包路由），形成了現代 TCP/IP 協定棧。

## 從學術網路到全球基礎設施

1983 年 1 月 1 日，ARPANET 正式從 NCP 協定切換到 TCP/IP——這一天被稱為網際網路的誕生日。Cerf 和 Kahn 最偉大的決策之一，是堅持將 TCP/IP 的規範公開發布，而非申請專利或商業化。這個開放決策讓任何人、任何組織都可以自由實作 TCP/IP 協定。

如果沒有這個決策，今天的網際網路可能像當年的封閉網路（CompuServe、AOL、Prodigy）一樣，由少數商業公司控制通訊協定和存取權。

## 圖靈獎演講

Cerf 在圖靈獎演講中回顧了網際網路的發展歷程，並將功勞歸於整個社群。Kahn 在演講中探討了網際網路的演化與未來挑戰。他們共同強調的一件事是：網際網路的成功來自於它的開放架構和最低限度的中央控制。

## 延伸閱讀

- [Vint Cerf - ACM Turing Award](https://amturing.acm.org/award_winners/cerf_1083211.cfm)
- [Bob Kahn - ACM Turing Award](https://amturing.acm.org/award_winners/kahn_4598637.cfm)
- [TCP/IP 歷史 - Wikipedia](https://zh.wikipedia.org/wiki/TCP/IP)
- [A Protocol for Packet Network Intercommunication (1974)](https://www.cs.princeton.edu/courses/archive/fall06/cos561/papers/cerf74.pdf)
