# 結構化程式設計運動的開端

## 程式設計的危機

1960 年代末，電腦科學面臨一場「軟體危機」。硬體的效能快速成長，但軟體的開發能力遠遠跟不上。大型專案經常延遲、超出預算、充滿錯誤。作業系統 OS/360 的開發經理 Fred Brooks 在 1975 年的《人月神話》中描述了這種困境：「大型軟體專案的開發進度就像一隻巨獸在泥濘中掙扎。」

在這種背景下，結構化程式設計（Structured Programming）應運而生。它不僅是一套程式碼寫作規則，更是一種思維方式——用系統化的方法來管理程式的複雜性。

## 核心原則

結構化程式設計建立在幾個簡單但強大的原則之上：

**自上而下的設計（Top-Down Design）**：從最抽象的功能描述開始，逐步細化為具體的程式碼。每一步都建立在上一步的抽象層之上。

**模組化（Modularity）**：將程式分解為獨立、可測試的模組，每個模組負責一個明確定義的功能。

**單一入口單一出口（Single Entry, Single Exit）**：每個控制結構只有一個入口和一個出口，避免混亂的跳躍。

**三種基本控制結構**：順序、選擇（if-then-else）、重複（while-do），足以表達任何程式邏輯。

## 程式碼範例：結構化 vs 非結構化

非結構化的流程控制：

```
100 READ X
    IF X < 0 GO TO 200
    SUM = SUM + X
    COUNT = COUNT + 1
    GO TO 100
200 IF COUNT = 0 GO TO 300
    AVG = SUM / COUNT
    PRINT AVG
    STOP
300 PRINT "NO DATA"
    STOP
```

結構化的版本：

```
COUNT = 0
SUM = 0
READ X
WHILE X >= 0 DO
    SUM = SUM + X
    COUNT = COUNT + 1
    READ X
END WHILE
IF COUNT > 0 THEN
    AVG = SUM / COUNT
    PRINT AVG
ELSE
    PRINT "NO DATA"
END IF
```

## 歷史脈絡中的重要著作

1968 年，Dijkstra、Hoare 與 Dahl 合著了《Structured Programming》一書。書中不僅討論了控制結構，還探討了程式驗證（program verification）和抽象資料型態（abstract data type）的概念。

同年，ACM 出版了課程建議書「Curriculum 68」，將程式設計方法學納入了電腦科學教育的核心課程。這標誌著程式設計從職業訓練轉變為學術學科。

## 結構化程式的遺產

結構化程式設計運動的影響遠遠超出了 1960 年代。它為後續的軟體工程方法論——如物件導向程式設計、設計模式、敏捷開發——奠定了基礎。更重要的是，它改變了人們對程式的看法：程式不再只是給機器執行的指令，而是一種人類可以閱讀、理解、推理的結構化文字。

## 延伸閱讀

- [結構化程式設計 - Wikipedia](https://zh.wikipedia.org/wiki/%E7%BB%93%E6%9E%84%E5%8C%96%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1)
- [Dijkstra, Dahl, Hoare 《Structured Programming》](https://www.google.com/search?q=Structured+Programming+Dijkstra+Dahl+Hoare)
- [Brooks 《The Mythical Man-Month》](https://www.google.com/search?q=The+Mythical+Man-Month+Fred+Brooks)
