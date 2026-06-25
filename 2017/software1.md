# PyTorch 開源：研究者的深度學習框架

## 從 Torch 到 PyTorch

2017 年 1 月 18 日，Facebook AI Research（FAIR）正式開源了 PyTorch——一個基於 Python 的深度學習框架。PyTorch 源自 LuaTorch（用 Lua 語言編寫的 Torch 框架），但與其說它是移植，不如說是重新設計。

PyTorch 由 Soumith Chintala、Adam Paszke 和 Sam Gross 等人在 FAIR 主導開發，其目標很明確：為研究者提供一個靈活、直觀、易於除錯的深度學習框架。

## 動態計算圖

PyTorch 最核心的設計選擇是動態計算圖（Dynamic Computation Graph）。與 TensorFlow 的靜態圖不同，PyTorch 的計算圖是在執行過程中即時建立的——這意味著開發者可以使用標準的 Python 控制流程（if、for、while）來建構網路結構。

這個設計帶來了巨大的除錯優勢：研究者在 PyTorch 中可以使用標準的 Python 除錯工具（pdb、print）來檢查網路的中間狀態，而無需像 TensorFlow 那樣通過 tf.Session.run() 來間接檢查。

## 社群反應

PyTorch 在發布後迅速受到學術社群的歡迎。到 2017 年底，越來越多的研究論文選擇 PyTorch 作為實作框架。研究者在社交媒體上表達了對 PyTorch 的熱情——「Pythonic」的 API 設計和動態圖的靈活性正是他們長期以來渴望的。

## 延伸閱讀

- [PyTorch 發布](https://pytorch.org/blog/pytorch-0-1-6-beta-is-here/)
- [PyTorch GitHub](https://github.com/pytorch/pytorch)
