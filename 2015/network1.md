# TensorFlow 開源：Google 的深度學習引擎

## 從 DistBelief 到 TensorFlow

2015 年 11 月 9 日，Google 宣布開源 TensorFlow——其第二世代的機器學習系統。在此之前，Google 內部使用的是 2011 年開發的 DistBelief 系統，用於訓練大規模神經網路。DistBelief 雖然成功——它訓練了辨識 YouTube 貓咪的神經網路、提升了 Google 語音辨識 25% 的準確率——但其架構存在限制：它專門針對神經網路、難以配置、與 Google 內部基礎設施深度耦合。

TensorFlow 從頭開始重新設計，解決了這些問題。它的名稱來自於神經網路中的運算方式——多維陣列（張量，tensor）在資料流圖中流動（flow）。

## 資料流圖架構

TensorFlow 的核心概念是資料流圖（data flow graph）。節點（nodes）代表數學運算，邊（edges）代表多維資料陣列（張量）在節點之間傳遞。這種架構讓 TensorFlow 具有極大的靈活性：

- 可以在 CPU、GPU、行動裝置上執行相同的程式碼
- 支援分散式訓練
- 適合研究和生產部署

## 對 AI 產業的衝擊

TensorFlow 的開源對機器學習產業產生了深遠的影響。它讓 Google 內部的 AI 技術成為公開資源，世界各地的研究者和開發者都可以使用與 Google 相同的工具來建立 AI 模型。

TensorFlow 迅速成為最受歡迎的深度學習框架，其社群在幾個月內就累積了數萬的 GitHub 星星。2015 年的開源決定被視為深度學習民主化的關鍵時刻之一。

## 延伸閱讀

- [TensorFlow 開源公告](https://research.google/blog/tensorflow-googles-latest-machine-learning-system-open-sourced-for-everyone/)
- [TensorFlow 白皮書 2015](https://www.tensorflow.org/extras/tensorflow-whitepaper2015.pdf)
