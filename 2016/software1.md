# AlphaGo 擊敗李世乭：AI 的歷史時刻

## 世紀對決

2016 年 3 月 9 日至 15 日，在韓國首爾，Google DeepMind 開發的 AlphaGo 與圍棋傳奇棋手李世乭進行了五局對戰。結果 AlphaGo 以 4:1 獲勝——這是電腦首次在圍棋這項被視為人類智慧最後堡壘的比賽中擊敗世界頂尖棋手。

賽前大多數專家預測 AlphaGo 至少需要十年才能達到這個水準。圍棋的棋盤有 19×19 格，可能局面數量（10^170）遠大於西洋棋（10^50），傳統的暴力搜尋方法在圍棋中完全不可行。

## 技術突破

AlphaGo 的核心技術是深度神經網路與蒙地卡羅樹搜尋（MCTS）的結合：

- **策略網路（Policy Network）**：預測下一步的最佳落子位置
- **價值網路（Value Network）**：評估給定盤面的勝率
- **蒙地卡羅樹搜尋**：結合兩個網路進行高效搜尋

AlphaGo 首先透過監督學習從人類棋譜中學習，再透過強化學習自我對弈數百萬局來不斷改進。

## 第四局的「神之一手」

李世乭在第四局下出了第 78 手——後來被稱為「神之一手」——這步棋的出現機率被 AlphaGo 評估為萬分之一。這步棋讓 AlphaGo 陷入了混亂，最終李世乭贏得了唯一的一場勝利。DeepMind CEO Demis Hassabis 表示，這步棋讓 AlphaGo「對自己的計算產生了懷疑」。

## 社會影響

AlphaGo 的勝利引發了全球對人工智慧的廣泛關注。超過兩億人觀看了比賽直播或報導。這場比賽改變了公眾對 AI 能力的認知——不再只是工具性的計算，而是能夠在需要直覺和創造力的領域挑戰人類。

## 延伸閱讀

- [AlphaGo - DeepMind](https://deepmind.google/research/alphago/)
- [AlphaGo 對李世乭 - Wikipedia](https://en.wikipedia.org/wiki/AlphaGo_versus_Lee_Sedol)
