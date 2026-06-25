# BERT：雙向語言理解的突破

## 預訓練語言模型的進化

2018 年 10 月 11 日，Google AI 的 Jacob Devlin 和他的團隊發表了 BERT（Bidirectional Encoder Representations from Transformers）。BERT 建立在 Transformer 架構之上，但引入了兩項關鍵創新：**雙向訓練**和**遮蓋語言模型（Masked Language Model）**。

BERT 的核心概念是：傳統語言模型是從左到右（或從右到左）單向閱讀文字，但 BERT 在預訓練時隨機遮蓋輸入中的部分詞彙，然後要求模型根據雙向上下文來預測被遮蓋的詞。這個設計讓 BERT 能夠捕捉更豐富的語境資訊。

## 技術創新

BERT 的關鍵技術包括：

- **Masked LM**：隨機遮蓋 15% 的輸入詞彙進行預測
- **Next Sentence Prediction**：預測兩個句子是否連續
- **雙向注意力**：Transformer Encoder 的自我注意力機制可以同時看到左右兩側的上下文
- **微調**：只需在預訓練模型上添加一個輸出層，即可適應各種下游任務

## 驚人的結果

BERT 在 GLUE 基準測試的 11 項 NLP 任務中全部達到當時最佳結果——包括情感分類、問答系統、文本蘊含、命名實體識別等。SQuAD 1.1 問答基準的 F1 分數從 91.2 提升到 93.2。這讓整個 NLP 社群為之震驚。

隨著 BERT 的開源（Apache 2.0 授權），全球的研究者和工程師可以立即在自己的領域應用這個強大的模型。

## 延伸閱讀

- [BERT: Pre-training of Deep Bidirectional Transformers](https://arxiv.org/abs/1810.04805)
- [Google AI Blog - BERT](https://research.google/blog/open-sourcing-bert-state-of-the-art-pre-training-for-natural-language-processing/)
