# Shakey 機器人與 STRIPS 規劃系統

## 第一台 AI 機器人

1970 年，SRI International（史丹佛國際研究院）展示了 Shakey——第一台由人工智慧控制的移動式機器人。Shakey 裝備了一台電視攝影機、雷射測距儀和碰撞感測器，透過無線電鏈路與一台 DEC PDP-10 和 PDP-15 通訊。它的移動速度約為每小時 2 公尺（比烏龜還慢），因而得名「Shakey」（搖晃者）。

## STRIPS 規劃系統

Shakey 的「大腦」是一個稱為 STRIPS（Stanford Research Institute Problem Solver）的規劃程式。STRIPS 由 Richard Fikes 和 Nils Nilsson 開發，是第一個成功的自動規劃系統。

STRIPS 使用一種稱為「手段-目的分析」（means-ends analysis）的技術。它將世界狀態表示為一階邏輯的斷言集合，動作則被描述為前置條件和效果的組合。例如，推動一個方塊到門口的前置條件是機器人在方塊旁邊，效果是方塊到了門口。

## 實際運作方式

Shakey 的典型任務是：從房間 A 移動一個箱子到房間 B。STRIPS 會：
1. 分析當前狀態與目標狀態的差異
2. 找出能消除差異的動作
3. 遞迴地規劃子目標
4. 生成一系列動作指令

如果執行過程中出現錯誤，Shakey 能夠重新規劃。

## 對 AI 的影響

Shakey 和 STRIPS 對人工智慧的發展產生了深遠影響：
- STRIPS 成為自動規劃系統的典範，影響了後來的所有規劃演算法
- Shakey 展示了感測、規劃、執行循環的完整鏈路
- 這些工作直接促成了 NASA 在太空探測器中的自主規劃系統

## 延伸閱讀

- [Shakey the Robot - SRI](https://www.sri.com/research-development/shakey-the-robot/)
- [STRIPS - Wikipedia](https://en.wikipedia.org/wiki/Stanford_Research_Institute_Problem_Solver)
