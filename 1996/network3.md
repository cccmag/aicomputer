# USB 1.0 規格制定：周邊連接的統一

## 七家公司的聯盟

1996 年 1 月，USB 1.0 規格正式發布。推動者是由 Intel、Microsoft、IBM、Compaq、NEC、DEC 和 Nortel 七家公司組成的 USB 推動小組（USB Implementers Forum, USB-IF）。

這個聯盟的形成本身就說明了問題的嚴重性：每家公司都認識到，PC 周邊連接的混亂狀態正在阻礙產業的進一步成長。

## 兩種速度模式

USB 1.0 定義了兩種傳輸速度：

| 模式 | 速度 | 應用 |
|---|---|---|
| 低速 | 1.5 Mbps | 鍵盤、滑鼠、搖桿 |
| 全速 | 12 Mbps | 印表機、掃描器、數據機、儲存裝置 |

12 Mbps 在 1996 年是相當不錯的速度——比當時的序列埠（115 Kbps）快了 100 倍，比並列埠（2 Mbps）快了 6 倍。

## 主要的設計決策

USB 的設計中有幾項關鍵決策：
- **主從架構**：由主機控制器（Host Controller）管理所有通訊，周邊裝置不能主動發起通訊
- **輪詢機制**：主機定期輪詢每個裝置是否有資料要傳送
- **四種傳輸類型**：控制傳輸、批量傳輸、中斷傳輸、同步傳輸
- **隨插即用**：裝置可以在不關機的情況下連接和斷開
- **匯流排供電**：低功耗裝置可以透過 USB 纜線直接取電

## 普及的障礙

USB 1.0 規格雖然在 1996 年制定，但真正的普及要等到 1998 年：
- Windows 95 對 USB 的支援不完整
- USB 裝置的驅動程式開發複雜
- 主機板製造商花了時間才加入 USB 連接埠

直到 Windows 98（1998 年）和 iMac（1998 年）的推出，USB 才真正進入主流。

## 延伸閱讀

- [USB 規格 - USB-IF](https://www.usb.org/)
- [USB 歷史 - Wikipedia](https://en.wikipedia.org/wiki/USB)
- [USB 1.0 文件 - Intel](https://www.intel.com/content/www/us/en/io/universal-serial-bus/usb.html)
