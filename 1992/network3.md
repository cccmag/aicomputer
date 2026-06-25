# TWAIN 標準：掃描器與電腦的橋樑

## 影像擷取的共同語言

1992 年，一個由 Aldus（後來被 Adobe 收購）、Eastman Kodak、Hewlett-Packard 和 Logitech 組成的產業聯盟推出了 TWAIN 標準——一套用於掃描器和數位影像擷取設備的軟體通訊協定和 API。

TWAIN——這個名稱是一個文字遊戲，取自「從來不會給出兩個東西」（And never the twain shall meet）——反映了它要解決的問題：掃描器硬體和影像軟體之間的溝通障礙。

## 技術架構

TWAIN 標準定義了三層架構：
- **應用程式層**：影像編輯或文字辨識軟體
- **來源管理器層**（Source Manager）：管理安裝的掃描器驅動程式
- **來源層**（Source）：掃描器製造商提供的驅動程式

在 TWAIN 出現之前，每個掃描器廠商使用自己專屬的驅動程式，軟體開發者需要為每台掃描器編寫特定的支援程式碼。TWAIN 將「掃描」這個動作標準化——任何支援 TWAIN 的軟體都可以使用任何支援 TWAIN 的掃描器。

## 多媒體生態系統的關鍵

1992 年 TWAIN 的發布是多媒體生態系統擴張的重要一步。隨著個人電腦開始內建 CD-ROM 和音效卡，「影像輸入」成為下一個需要標準化的領域。

TWAIN 讓掃描器從專業出版工具變為大眾消費產品。家庭使用者可以掃描照片、文件和手繪圖稿，然後在 Word 或 Photoshop 中編輯。TWAIN 的「一鍵掃描」概念簡化了操作，降低了數位影像入門門檻。

TWAIN 標準至今仍在使用，儘管面臨 WIA（Windows Image Acquisition）和 SANE（Scanner Access Now Easy）等替代方案的競爭。
