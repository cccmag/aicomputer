# Attention Is All You Need：Transformer 革命

## 一篇論文改變一切

2017 年 6 月 12 日，Google Brain 團隊的八位研究者在 arXiv 上發表了一篇題為「Attention Is All You Need」的論文。這篇論文的動機看似簡單：他們想找到一個比遞迴神經網路（RNN）更高效、更可並行化的序列轉換模型。

他們的答案是——完全放棄遞迴和卷積，僅使用注意力機制來建立全局依賴關係。這個架構被命名為 Transformer。

## Transformer 的設計

Transformer 的核心創新包括：

- **多頭注意力（Multi-Head Attention）**：將多個注意力頭並行運算，捕捉不同位置的子空間資訊
- **位置編碼（Positional Encoding）**：用正弦波產生位置向量，取代遞迴的位置感知
- **自我注意力（Self-Attention）**：每個位置都可以直接關注任何其他位置，解決長距離依賴問題
- **編碼器-解碼器架構**：堆疊的編碼器和解碼器層

## 深遠的影響

Transformer 在機器翻譯任務上取得了當時最佳的成果：WMT 2014 英德翻譯 BLEU 28.4，英法翻譯 BLEU 41.0。訓練時間僅需 3.5 天（8 個 GPU），遠低於當時最佳模型的訓練成本。

但這篇論文的重要性遠超機器翻譯。Transformer 架構後來成為所有大型語言模型（BERT、GPT-2/3/4、T5）的基礎。自 2017 年以後，NLP 領域的幾乎所有重大突破都建立在 Transformer 之上。有人說這篇論文開啟了「注意力經濟時代」。

## 延伸閱讀

- [Attention Is All You Need - arXiv](https://arxiv.org/abs/1706.03762)
- [Transformer 解說 - Google Research](https://research.google/blog/transformer-a-novel-neural-network-architecture-for-language-understanding/)
