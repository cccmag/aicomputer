# Go 語言 1.0 穩定版

## Google 的系統程式語言

2012 年 3 月，Google 正式發布 Go 語言 1.0 版本。Go 由 Robert Griesemer、Rob Pike 和 Ken Thompson 在 2007 年開始設計，目標是創造一種同時具有 C++ 的執行效率和 Python 的開發效率的系統程式語言。

Go 1.0 的發布是一個承諾——Google 保證向後兼容性，所有 Go 1.0 時代的程式碼都可以在未來的 Go 版本中正常編譯。

## Go 的核心設計

Go 語言的設計反映了其創造者對軟體工程長期的觀察和思考：

- **簡潔的語法**：沒有類別繼承、沒有泛型（2012 年版本）、沒有異常處理。Go 故意省略了這些被認為會導致複雜性的特性。
- **內建並發支援**：goroutine（輕量級執行緒）和 channel（通訊機制）是 Go 最著名的特性。goroutine 的堆疊初始僅 4KB，可以輕鬆建立數十萬個 goroutine。
- **快速編譯**：Go 的編譯器非常快速——大型專案的編譯通常在數秒內完成。
- **靜態連結**：Go 將所有依賴編譯為單一的靜態二進位檔案，解決了動態連結的依賴地獄問題。

## 雲端時代的語言

Go 1.0 發布後，首先在 Google 內部獲得採用。Docker（2013 年開源）就是用 Go 語言編寫的，這成為 Go 語言最重要的殺手級應用。其他用 Go 編寫的重要基礎設施項目包括 Kubernetes、Prometheus、Consul、etcd、Terraform 等。

Go 語言在 2013 年後成為雲端基礎設施開發的事實標準。它的成功證明了「簡潔」和「務實」經過精心設計，可以戰勝「特性豐富」的競爭哲學。

## 延伸閱讀

- [Go 語言 - Wikipedia](https://en.wikipedia.org/wiki/Go_(programming_language))
- [Go 官方網站](https://go.dev/)
