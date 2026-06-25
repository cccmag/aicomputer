# IBM Watson 在 Jeopardy 擊敗人類冠軍

## 從學術研究到電視直播

2011 年 2 月 14 日至 16 日，IBM 的人工智慧系統 Watson 在美國電視益智問答節目 Jeopardy! 上，與兩位人類冠軍 Ken Jennings 和 Brad Rutter 進行對決。Watson 最終獲得 77,147 美元，遠超過 Jennings（24,000 美元）和 Rutter（21,600 美元），贏得冠軍頭銜。

Watson 的核心技術是 IBM 的 DeepQA 架構——一個大規模平行化的自然語言處理和機器學習系統。Watson 不需要連接網路，它只依靠內部載入的 2 億頁結構化和非結構化資料，涵蓋維基百科、字典、百科全書、新聞報導等。

## 技術架構

Watson 由 90 台 IBM Power 750 伺服器組成，搭載 2,880 個 POWER7 處理器核心，總記憶體超過 15 TB。系統執行約 3,000 個並行的軟體模組，包括語言解析、知識檢索、假設生成、證據評估和融合決策等環節。

當 Watson 收到一個問題時，它會：
1. 解析問題的語法和語意
2. 生成數百個候選答案（假設）
3. 針對每個候選答案搜尋證據
4. 使用數百種演算法評估證據的強度
5. 根據信心分數決定是否作答

## 里程碑意義

Watson 在 Jeopardy! 的勝利象徵著人工智慧在自然語言理解領域的重大突破。不同於 Deep Blue 在 1997 年擊敗 Kasparov 時使用的暴力搜尋，Watson 需要理解雙關語、反諷、隱喻等人類語言的複雜特性。Watson 的成功證明了基於統計和機器學習的自然語言處理方法在實際應用中的可行性。

## 延伸閱讀

- [IBM Watson - Wikipedia](https://en.wikipedia.org/wiki/IBM_Watson)
- [Watson Jeopardy 技術報告](https://ieeexplore.ieee.org/document/6177724)
