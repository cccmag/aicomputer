# GPT-1：生成式預訓練的起點

## 從 Transformer Decoder 開始

2018 年 6 月 11 日，OpenAI 發表了題為「Improving Language Understanding by Generative Pre-Training」的論文——這是 Generative Pre-trained Transformer（GPT）系列的第一代模型。

與 BERT 使用 Transformer Encoder 不同，GPT-1 使用 Transformer Decoder 進行訓練。它採用標準的語言模型目標——從左到右預測下一個詞彙。這種設計讓 GPT-1 天生適合文本生成任務。

GPT-1 包含 12 層 Transformer Decoder，1.17 億個參數——以當時的標準來說只是一個中型模型。

## 兩階段訓練

GPT-1 引入了後來成為標準的兩階段訓練流程：

1. **無監督預訓練**：在大規模未標記文字資料集（BookCorpus）上學習語言知識
2. **有監督微調**：在特定任務的小量標記資料上適應目標任務

這個範式的重要貢獻在於：預訓練模型只需少量任務特定資料即可達到優異的效能。這解決了 NLP 領域標記資料稀缺的關鍵問題。

## 與 BERT 的對比

2018 年出現了兩條通往更好語言理解的路徑：

| | BERT | GPT-1 |
|---|---|---|
| 架構 | Encoder-only | Decoder-only |
| 注意力 | 雙向 | 左到右 |
| 訓練目標 | Masked LM | 標準 LM |
| 擅長 | 理解/分類 | 生成 |
| 參數 | 3.4 億 | 1.17 億 |

兩條路線後來都展現了巨大的潛力——BERT 路線進化為 RoBERTa、ALBERT，GPT 路線進化為 GPT-2、GPT-3、GPT-4。

## 延伸閱讀

- [GPT-1 論文](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)
- [OpenAI Blog - GPT](https://openai.com/blog/language-unsupervised/)
