# Android 1.0 SDK：開發者的新舞台

## SDK 的發布

2008 年 9 月 23 日，Google 發布了 Android 1.0 SDK（Software Development Kit）的第一個穩定版本（API Level 1）。開發者下載後可以建立、測試和發布 Android 應用程式。SDK 包含了模擬器（emulator）、除錯工具（DDMS）、效能分析器、以及完整的 API 文件和範例程式。

Android 1.0 SDK 的核心 API 包括了：

**Activity Manager**：管理應用程式的生命週期和導航棧。Android 的 Activity 概念與 iOS 的「視圖控制器」相似但更靈活——每個 Activity 可以獨立啟動和管理。

**Content Providers**：允許應用程式之間共享資料。通訊錄、媒體庫、行事曆等系統資料都是透過 Content Provider 對外開放的。

**Service 與 BroadcastReceiver**：讓應用程式可以在背景執行任務或響應系統事件——這是 Android 與當時 iPhone OS 最關鍵的差異之一。

**Intent 系統**：Android 最與眾不同的設計——應用程式不是透過顯式呼叫來互動，而是發送 Intent 請求，系統會匹配適合的應用程式來處理。例如，發送一個「查看地圖」的 Intent，系統會自動打開 Google Maps 或使用者選擇的其他地圖應用。

## Java 與 Eclipse

Android 應用程式使用 Java 語言編寫（雖然不是標準 Java ME）。Google 提供了 Android Development Tools（ADT）Eclipse 外掛程式，讓開發者可以在 Eclipse IDE 中完成編碼、除錯和部署的完整工作流程。

## 延伸閱讀

- [Android SDK 歷史](https://developer.android.com/about/versions/android-1.0)
- [Android 1.0 發布公告](https://android-developers.googleblog.com/2008/09/announcing-android-10-sdk-release-1.html)
