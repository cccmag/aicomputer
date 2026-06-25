# Android 宣布：Google 的行動作業系統

## Open Handset Alliance

2007 年 11 月 5 日，Google 宣布成立 Open Handset Alliance（開放手機聯盟）——一個由 34 家公司組成的產業聯盟，包括 Google、HTC、Samsung、Motorola、Intel、Qualcomm、Texas Instruments、T-Mobile、NTT DoCoMo 等。同日，聯盟公布了 Android——一個基於 Linux 的開放原始碼行動作業系統。

Android 的誕生背景是 Google 對行動網際網路的戰略判斷：Google 認為封閉的行動生態系統（如當時的 Symbian、Windows Mobile、以及即將問世的 iPhone）會阻礙行動網際網路的發展。一個開放的平台可以確保 Google 的服務不會被任何單一廠商封鎖。

## 技術架構

Android 的技術架構分為多個層次：

**Linux 核心**：提供底層的硬體抽象、記憶體管理、行程管理和驅動程式模型。Google 選擇 Linux 核心而非從頭開發，大幅加快了 Android 的開發進度。

**Dalvik 虛擬機器**：Android 不直接執行標準 Java 位元組碼，而是使用自行設計的 Dalvik VM。Dalvik 基於暫存器架構（相對於 JVM 的堆疊架構），針對行動裝置的低記憶體與低功耗需求進行了最佳化。

**應用程式框架**：Android 提供了一套完整的應用程式 API，包括 Activity Manager、Content Providers、Resource Manager、Notification Manager 等。

## 開源策略

Android 採用 Apache 2.0 授權發布原始碼，這與 Linux 核心的 GPL 授權不同。Apache 授權允許製造商在 Android 上添加私有元件而無需釋出原始碼——這是 Google 為了吸引硬體廠商的策略性選擇。

## 延伸閱讀

- [Android 歷史 - Wikipedia](https://zh.wikipedia.org/wiki/Android)
- [Open Handset Alliance 宣布](https://www.openhandsetalliance.com/press_110507.html)
- [Android 開源專案](https://source.android.com/)
