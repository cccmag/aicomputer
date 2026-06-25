# USB 標準的萌芽：通用序列匯流排

## 連接埠的混亂

1995 年，個人電腦的背面是一場連接埠的噩夢：序列埠（RS-232）、並列埠（LPT）、PS/2（鍵盤和滑鼠分開）、SCSI（需終端器和 ID 設定）、MIDI/遊戲埠——每一種周邊需要不同規格的連接器，驅動程式安裝更是令人頭痛。

Intel、Microsoft、IBM、Compaq 等七家公司組成了 USB 推動小組，目標是開發一個真正的通用連接標準。

## 目標與設計

USB 的設計目標包括：
- **真正的隨插即用（Plug and Play）**：不需要關機安裝裝置
- **單一連接器統一所有周邊**
- **可擴展性**：透過集線器（hub）連接多達 127 個裝置
- **供電能力**：透過匯流排為低功耗裝置供電，不需外部電源

USB 1.0 規格在 1996 年 1 月正式發布，支援兩種速度模式：低速 1.5 Mbps（鍵盤、滑鼠）和全速 12 Mbps（印表機、掃描器、數據機）。

## 實際上市的延遲

雖然 USB 1.0 規格在 1996 年完成，但真正讓 USB 進入主流的產品是：

- **iMac (1998)**：Apple 的 iMac 是第一款完全依賴 USB、捨棄序列埠和 ADB 的消費產品
- **Windows 98 (1998)**：提供了完善的 USB 驅動支援

從規格制定到真正普及花了三年——這是科技產業常見的「規格早，生態晚」現象。

## 延伸閱讀

- [USB 歷史 - Wikipedia](https://en.wikipedia.org/wiki/USB)
- [USB 規格 - USB-IF](https://www.usb.org/)
- [USB 推動小組 - Intel](https://www.intel.com/content/www/us/en/io/universal-serial-bus/usb.html)
