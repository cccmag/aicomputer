# TensorFlow 2.0 開發方向與 Keras 整合

## 從 1.x 到 2.0

2017 年，雖然 TensorFlow 1.x 系列已經成為最受歡迎的深度學習框架，但開發者對其 API 的抱怨也日益增加。TensorFlow 1.x 的靜態圖設計雖然有利於部署和優化，但對研究者來說既繁瑣又難以除錯。

2017 年，Google 開始規劃 TensorFlow 2.0——一次對 API 的重大重新設計。最重要的決定是將 Keras 作為 TensorFlow 的高階 API，並讓 Eager Execution（動態執行）成為預設模式。這項轉變意味著 TensorFlow 開始接受 PyTorch 式「執行即可見」的理念。

## Keras 的收編

Keras 由 François Chollet 在 2015 年創建，最初是作為一個獨立於底層框架的高階 API，支援 TensorFlow、Theano、CNTK 等多種後端。2017 年，Google 宣布 Keras 將被深度整合到 TensorFlow 中，成為其官方高階 API。

這個決策的影響：

- Keras 的簡單性與 TensorFlow 的強大能力結合
- 開發者可以用數行程式碼完成常見的深度學習任務
- TensorFlow 的生態變得對初學者更友好

## 生態震盪

TensorFlow 2.0 的設計方向在 2017 年引發了社群討論。雖然大多數人歡迎 Keras 整合和 Eager Execution，但 1.x 到 2.x 的不相容變更意味著大量現有程式碼需要重寫。這個轉型過程一直持續到 2019 年 9 月 TensorFlow 2.0 正式發布。

## 延伸閱讀

- [TensorFlow 2.0 開發方向](https://blog.tensorflow.org/2019/01/whats-coming-in-tensorflow-2-0.html)
- [Keras 官方網站](https://keras.io/)
