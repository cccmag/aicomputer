# Minsky 與 Papert 的《Perceptrons》：神經網路的寒冬

## 感知機的熱潮

1958 年，Frank Rosenblatt 在 Cornell Aeronautical Laboratory 發明了感知機（Perceptron）——一種模仿生物神經元的人工神經網路。感知機可以透過訓練自動調整權重來分類圖案，例如區分三角形和圓形。這項成果引發了極大的興奮——媒體甚至報導說「能夠思考和學習的機器」即將問世。

在接下來的十年中，感知機的研究蓬勃發展。研究者建立了多層感知機（雖然訓練方法有限）、開發了各種學習演算法、並將其應用於字元識別和模式辨識。

## Minsky 與 Papert 的分析

1969 年，MIT 的 Marvin Minsky 和 Seymour Papert 出版了《Perceptrons》一書。這本書從數學上嚴謹地分析了感知機的能力與限制。

最重要的結論是：**單層感知機無法解決線性不可分的問題**。最經典的例子是 XOR（互斥或）函數——感知機無法學習這個簡單的邏輯運算，因為兩類輸出在特徵空間中無法用一條直線分開。

Minsky 和 Papert 也論證了：雖然多層感知機理論上可以解決這個問題，但當時沒有人知道如何有效地訓練多層網路。他們對「將感知機擴展到多層」的可行性持悲觀態度。

## 爭議與影響

《Perceptrons》的出版對類神經網路研究造成了災難性的影響。許多研究者將書中的結論解讀為「神經網路根本不可行」，導致：

- 研究經費被大幅削減
- 學術期刊不再接受相關論文
- 研究者紛紛轉向其他領域（如符號式 AI）

1980 年代的「AI 寒冬」在很大程度上可以追溯到《Perceptrons》的影響。直到 1986 年反向傳播演算法（Backpropagation）被重新發現和推廣後，神經網路才迎來復興。

## 一個重要的誤解

值得注意的是，Minsky 和 Papert 的結論在後來被廣泛誤解。他們的證明只適用於**單層**感知機，且只針對**硬限制**（無連續啟發函數）的網路。書中實際上提到了多層網路可能具有更強的能力，但這個細節被大多數讀者忽略了。

Minsky 本人後來對這個誤解感到困擾。他在 1988 年《Perceptrons》擴充版的前言中寫道：「許多教科書錯誤地聲稱我們的結論只適用於一兩層的網路……事實上，我們的大部分結論同樣適用於任何深度的前饋網路。」

## 延伸閱讀

- [Perceptrons - MIT Press](https://mitpress.mit.edu/books/perceptrons)
- [Marvin Minsky - Wikipedia](https://zh.wikipedia.org/wiki/%E9%A6%AC%E7%88%BE%E6%96%87%C2%B7%E6%98%8E%E6%96%AF%E5%9F%BA)
- [感知機 - Wikipedia](https://zh.wikipedia.org/wiki/%E6%84%9F%E7%9F%A5%E6%9C%BA)
