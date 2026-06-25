# BERT 全面影響 NLP 領域：Google 的預訓練革命

## BERT 的誕生

2018 年 10 月，Google 發表了 BERT（Bidirectional Encoder Representations from Transformers），但它在 2019 年才真正展現出對 NLP 領域的全面衝擊。BERT 的核心創新在於其雙向預訓練方式——不同於以往從左到右或從右到左的單向語言模型，BERT 同時考慮了上下文中的左右兩側資訊。

BERT 使用 Transformer 編碼器架構，透過「遮蔽語言模型」（Masked Language Model，MLM）和「下句預測」（Next Sentence Prediction，NSP）兩個任務進行預訓練。

## 席捲排行榜

2019 年，BERT 橫掃了 11 項 NLP 基準測試，包括 GLUE、SQuAD 問答和 SWAG 推論等。它在 SQuAD 1.1 上的 F1 分數達到了 93.2，超越了人類基準的 91.2——這是 NLP 領域的一個重要里程碑。

Google 於 2019 年將 BERT 整合到搜尋引擎中，改善了約 10% 的查詢理解——這意味著每天數億次搜尋體驗的提升。

## BERT 生態系統

BERT 的開源釋出引發了一系列後續研究：
- RoBERTa（Facebook，更優化的訓練策略）
- ALBERT（Google，參數共享減少記憶體）
- DistilBERT（Hugging Face，知識蒸餾加速）
- TinyBERT（華為，輕量化部署）

BERT 的影響超越了學術圈——Hugging Face 的 Transformers 函式庫因 BERT 而成為 NLP 開發者不可或缺的工具。BERT 也標誌著「預訓練-微調」（pre-train then fine-tune）範式在 NLP 領域的全面確立。
