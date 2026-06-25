# VAX/VMS V1.0：32 位元作業系統

## 軟硬體同步開發

VAX/VMS 的開發與 VAX-11/780 硬體同步進行。作業系統代號「Starlet」，與硬體的代號「Star」相呼應。DEC 投入了超過 300 人年的開發力量。

VMS V0.5（Beta 版本）在 1977 年隨硬體測試版送交給早期客戶。正式的 V1.0 版本於 1978 年出貨。

## 核心功能

VAX/VMS V1.0 包含了現代作業系統的多項關鍵功能：

**虛擬記憶體管理**：硬體支援的分頁式虛擬記憶體，讓程式可以使用比實體記憶體更大的位址空間。

**優先級排程**：使用事件驅動的優先級排程器，支援即時應用的高優先級任務。

**Record Management Services (RMS)**：提供順序檔案、相對檔案和多重鍵索引檔案的統一存取介面。

**DECnet 整合**：從第一天起就內建了 DECnet 網路支援和遠端檔案存取。

**DCL 命令列**：DIGITAL Command Language 提供了 Unix shell 風格的命令列環境。

## 可靠性傳承

VMS 以其卓越的穩定性著稱。它支援容錯叢集和滾動升級——某些 VMS 系統連續運行數年不需要重開機。這種對可靠性的極致追求後來影響了 Windows NT 和許多即時作業系統的設計。

## 延伸閱讀

- [OpenVMS - Wikipedia](https://en.wikipedia.org/wiki/OpenVMS)
- [VMS 歷史 - VSI](https://wiki.vmssoftware.com/)
