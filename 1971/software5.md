# 結構化程式設計的理論基礎

## 對抗戈多

1968 年，Edsger Dijkstra 發表了著名的信件「Go To Statement Considered Harmful」，引發了程式設計方法論的革命。到 1971 年，這個運動已經發展成為一個完整的理論體系。

結構化程式設計的核心主張是：**任何程式都可以僅用三種控制結構來撰寫**：
1. **順序**（sequence）：程式碼依序執行
2. **選擇**（selection）：if-then-else
3. **重複**（iteration）：while-do

這個命題由 Böhm 和 Jacopini 在 1966 年證明，稱為「結構化定理」。

## 逐步求精方法論

1971 年，Niklaus Wirth 在《Communications of the ACM》上發表了「Program Development by Stepwise Refinement」。這篇論文闡述了從高層規格到具體實現的系統化過程：

```
步驟 1: 解決方案用自然語言描述
步驟 2: 分解為子問題
步驟 3: 用虛擬碼表達
步驟 4: 轉換為可執行程式碼
```

## Floyd 的證明的正確性

Robert Floyd 在 1967 年的論文「Assigning Meanings to Programs」中提出了程式正確性的邏輯證明方法。他的方法使用前置條件和後置條件的概念：

```
{ x = a, y = b }
temp := x;
x := y;
y := temp;
{ x = b, y = a }
```

這為軟體驗證建立了理論基礎。

## 對軟體工業的影響

1971 年，結構化程式設計不僅是學術討論，也開始影響實務。IBM 在開發 OS/360 的過程中遭遇了大量問題（Fred Brooks 的《人月神話》就在這一年出版），結構化方法被視為解決軟體危機的關鍵。

## 延伸閱讀

- [Edsger Dijkstra - Go To Statement Considered Harmful](https://homepages.cwi.nl/~storm/teaching/reader/Dijkstra68.pdf)
- [Niklaus Wirth - Program Development by Stepwise Refinement](https://dl.acm.org/doi/10.1145/361175.361184)
