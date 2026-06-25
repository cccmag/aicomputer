# Multics 上線：分時系統的里程碑

## 從計畫到實現

Multics（Multiplexed Information and Computing Service）是 1960 年代最具野心的軟體專案。它的目標是建立一個「計算機公用事業」——讓使用者可以像用電一樣，隨時隨地透過終端機取得運算服務。

這個專案由 MIT 的 Fernando Corbató 教授領導，在 1965 年啟動時得到了 GE 和貝爾實驗室的合作。但開發過程遠比預期艱難：GE-645 硬體在 1967 年 1 月才交付；作業系統本身到 1968 年底才達到可以自我編譯的狀態。

## 1969 年的里程碑

1969 年是 Multics 從開發期轉向運作期的關鍵一年：

- **3 月**：貝爾實驗室退出合作，認為 Multics 無法在短期內交付可用系統
- **7 月**：Multics 開始對 MIT Project MAC 的非開發者用戶提供服務
- **10 月**：MIT 資訊處理中心正式接管 GE-645 的運作，開始提供商用分時服務

Multics 的第一個正式版本使用 EPL（Early PL/I）撰寫——這是後來標準 PL/I 語言的前身。1969 年底，Multics 開發團隊用 native 編譯器重新編譯了整個系統，效能顯著提升。

## 技術創新

Multics 引入了一系列即使在今天看來仍然先進的概念：

**單層儲存（Single-Level Store）**：記憶體和磁碟儲存在作業系統層面被統一管理。程式設計師不需要手動管理資料在哪一層儲存中——作業系統自動處理頁面的換入換出。這個概念直到 20 年後的作業系統中才被普遍實現。

**動態連結（Dynamic Linking）**：程式可以在執行時才連結共享的程式庫，不需要在編譯時靜態連結。這大大減少了記憶體的使用量。

**階層式檔案系統**：Multics 的檔案系統支援多層次的目錄結構——這是現代檔案系統的標準。它的路徑名稱格式（如 `/usr/doc/paper.txt`）直接影響了 Unix 的設計。

**保護環**：硬體支援 8 層保護環，實現了嚴格的存取控制。這是現代作業系統強制存取控制（MAC）的早期實現。

## 商業命運

Multics 的商業化並不算成功——在 1985 年終止時，全球僅有約 80 套系統。但它對電腦科學的貢獻遠超過它的商業成就。Unix 直接繼承了 Multics 的許多設計概念——檔案系統層次結構、Shell、I/O 重定向——但用更簡潔的方式實現。Linux 和 Windows 又繼承了 Unix 的許多概念。

Corbató 在 1990 年獲得了圖靈獎，表彰他在 Multics 和 CTSS 上的開創性工作。

## 延伸閱讀

- [Multics 歷史 - Multicians.org](https://multicians.org/history.html)
- [Fernando Corbató - Wikipedia](https://en.wikipedia.org/wiki/Fernando_J._Corbató)
- [Multics 文件](https://web.mit.edu/multics-history/)
