# PL/M 正式釋出

## 從 PDP-10 到 Intel 8008

1973 年，Intel 正式釋出了 PL/M（Programming Language for Microcomputers）——第一個專為微處理器設計的高階程式語言。這套系統由 Gary Kildall 在 1972 年開始開發，最初在 PDP-10 大型主機上進行交叉編譯。

Kildall 當時在 Naval Postgraduate School 工作，同時以顧問身份與 Intel 合作。他的 PL/M 編譯器包含兩個部分：`PLM1` 和 `PLM2`（Fortran 寫的編譯器程式），以及 `Interp/8`（8008 的指令集模擬器）。開發者在 PDP-10 上編譯程式後，透過打孔紙帶將機器碼載入到 Intellec 8 開發系統上執行。

## 為什麼需要高階語言

在 1973 年，微處理器的程式幾乎全部用組合語言撰寫。這有兩個問題：

1. **生產力極低**：組合語言每行程式碼只能做一件非常簡單的操作，一個複雜的計畫可能需要數萬行程式碼
2. **無法移植**：換一顆微處理器，所有程式碼都要重寫

PL/M 解決了這兩個問題。它提供了 if-then-else、do-while、case 等高階控制結構，以及有意義的變數名稱和結構化資料型別。Kildall 曾經在演示中證明：用 PL/M 寫一個程式，需要約十分之一的時間，卻能產生與組合語言相近的機器碼大小和效能。

## 對 CP/M 的催化作用

PL/M 最重要的貢獻或許是促成了 CP/M 的誕生。當 Intel 提供了一台使用 8080 的 Intellec 8/80 開發系統後，Kildall 面臨一個問題：這台機器沒有磁碟儲存。他需要一個軟碟控制器和一個磁碟作業系統，才能讓開發環境正常運作。

Kildall 用 PL/M 寫了一個簡單的磁碟作業系統來管理 Shugart 800 軟碟機——這就是 CP/M 的前身。1974 年，他將這個系統完善並命名為 CP/M（Control Program for Microcomputers），成立了 Digital Research 公司。

如果沒有 PL/M，Kildall 可能不會有勇氣用高階語言來寫作業系統——而如果沒有 CP/M，1980 年代的個人電腦革命將會完全不同。

## 延伸閱讀

- [PL/M - Wikipedia](https://en.wikipedia.org/wiki/PL/M)
- [Gary Kildall 生平 - Computer History Museum](https://computerhistory.org/blog/in-his-own-words-gary-kildall/)
- [PL/M 歷史 - Google 搜尋](https://www.google.com/search?q=PL/M+Intel+1973+Gary+Kildall)
