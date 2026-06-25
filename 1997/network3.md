# 六度分隔理論：社群網路的科學基礎

## Milgram 的經典實驗

1967 年，美國社會心理學家 Stanley Milgram 進行了著名的「小世界實驗」。他要求參與者將一封信透過人際網絡轉寄給一個目標人物——參與者只能將信寄給他們認識的人，再由收信人繼續轉寄。

實驗的驚人結果是：平均只需要六個中間人，信就可以從任何一個隨機選取的人手中到達目標人物。這就是「六度分隔」（Six Degrees of Separation）概念的由來。

## 1997 年的重新發現

1997 年，物理學家 Duncan Watts 和 Steven Strogatz 在《Nature》上發表了里程碑論文「Collective Dynamics of 'Small-World' Networks」。他們提出了小世界網路的數學模型，解釋了為什麼真實世界的網路（從人際關係到電力網路到神經元網路）都表現出「六度」的特性。

Watts-Strogatz 模型的關鍵發現是：

- **高集群係數**：我的朋友之間也很可能是朋友（社群結構）
- **短路徑長度**：透過少數「長程連結」，整個網路的平均路徑長度非常短

這兩個特性看起來矛盾——既緊密又有捷徑——但正是它們定義了小世界網路。

## 對計算機科學的影響

小世界理論對計算機科學和網際網路的影響深遠：

- **社群網路**：Facebook、LinkedIn 的「朋友的朋友」推薦演算法
- **資訊傳播**：病毒式行銷背後的網路動力學
- **搜尋演算法**：利用小世界特性的點對點搜尋
- **網路拓撲**：網際網路骨幹和路由最佳化

## 延伸閱讀

- [六度分隔 - Wikipedia](https://en.wikipedia.org/wiki/Six_degrees_of_separation)
- [小世界網路 - Wikipedia](https://en.wikipedia.org/wiki/Small-world_network)
- [Watts-Strogatz 模型 - Nature](https://www.nature.com/articles/30918)
