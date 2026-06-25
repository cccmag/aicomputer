# VAX-11/780：32 位元超級迷你電腦

## Star 專案

1977 年 10 月 25 日，DEC 在年度股東大會上發表了 VAX-11/780（代號「Star」）。這是 DEC 的第一台 32 位元電腦，也是 VAX 架構的第一個實作。它的作業系統代號「Starlet」（後來稱為 VAX/VMS）。

## 32 位元的意義

VAX 代表「Virtual Address eXtension」。PDP-11 的 16 位元架構只能定址 64 KB 記憶體，到 1970 年代中期已成為嚴重瓶頸。VAX-11/780 將位址空間擴充到 32 位元（4 GB），並提供了硬體虛擬記憶體管理。它還可以在「相容模式」下執行 PDP-11 的使用者模式程式碼，保護了客戶的軟體投資。

## 硬體架構

VAX-11/780 使用 Schottky TTL 邏輯電路，時脈 5 MHz（200 ns 週期），內建 2 KB 快取。它的微程式碼不是存在 ROM 中，而是從 8 吋軟碟載入到可寫入控制儲存器（WCS）——這讓 DEC 可以事後發布微碼更新來最佳化指令集。

## 深遠影響

VAX/VMS 在可靠性方面建立了極高的聲譽——有些系統連續運行數年不需要重開機。VMS 對 Microsoft 的 Windows NT 產生了直接影響（David Cutler 主導了兩個作業系統的開發）。BSD Unix 也是在 VAX 平台上發展起來的。

## 延伸閱讀

- [VAX-11 - Wikipedia](https://en.wikipedia.org/wiki/VAX-11)
- [VAX/VMS - Wikipedia](https://en.wikipedia.org/wiki/OpenVMS)
