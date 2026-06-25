# 1993 年圖靈獎：Juris Hartmanis & Richard Stearns

## 計算複雜度理論的奠基者

Juris Hartmanis 和 Richard E. Stearns 共同獲得了 1993 年的 ACM 圖靈獎，表彰他們在 1965 年發表的開創性論文〈On the Computational Complexity of Algorithms〉——這篇論文建立了計算複雜度理論的基礎。

他們的貢獻可以歸納為一個核心成就：證明了「困難的問題可以量化比較」——不同的演算法之間存在著固有的難度等級，而這些等級可以透過嚴格的數學方法來分類和比較。

## 複雜度類別的發明

在 Hartmanis 和 Stearns 之前，計算機科學主要關注的是「可計算性」問題——哪些問題可以被電腦解決。他們轉而問了一個更細緻的問題：「解決一個問題需要多少時間和記憶體？」

他們定義了複雜度類別（complexity class）的概念：一組可以用某個時間界限內解決的問題。例如：
- **線性時間**（n）：問題大小加倍時，所需時間也加倍
- **多項式時間**（n²）：問題大小加倍時，所需時間變為四倍
- **指數時間**（2ⁿ）：問題大小稍微增加，所需時間急遽成長

他們的關鍵定理是：存在無限多個不同的複雜度類別組成的層級結構——從最簡單到最困難的問題，形成了一個無限的階梯。

## 圖靈機作為分析工具

Hartmanis 和 Stearns 選擇了 Alan Turing 的圖靈機作為複雜度分析的基礎模型。他們證明了對圖靈機進行的各種修改（如增加磁帶數量）最多只會對時間複雜度造成平方級的變化——這建立了複雜度分析的穩健基礎。

這個選擇是極具遠見的。圖靈機雖然簡陋，但其精確的數學定義使得複雜度證明可以嚴格進行。時至今日，圖靈機仍然是複雜度理論的核心模型。

## Hartmanis 與 Stearns 的背景

Juris Hartmanis 出生於拉脫維亞，在第二次世界大戰期間輾轉流亡，最終在美國接受教育並在通用電氣（GE）研究實驗室工作。Richard Stearns 在新澤西州出生，在普林斯頓大學獲得數學博士學位，也加入了 GE 研究實驗室。兩人在 GE 相遇並開始了他們的合作。

他們的合作始於順序機的分解理論，然後延伸到計算複雜度——他們自己創造了「計算複雜度」（computational complexity）這個術語。

## 影響與遺產

Hartmanis 和 Stearns 的工作直接啟發了：
- Stephen Cook 的 NP 完備性理論（1971 年）
- Richard Karp 的 21 個 NP 完全問題（1972 年）
- 整個密碼學的安全性基礎——許多密碼系統的安全性依賴於「某些問題本質上難以解決」的假設

如果沒有共複雜度理論，現代計算機科學——從演算法設計到密碼學到人工智慧——都將失去其理論基礎。

## 延伸閱讀

- [Juris Hartmanis - ACM Turing Award](https://amturing.acm.org/award_winners/hartmanis_1059260.cfm)
- [Richard Stearns - ACM Turing Award](https://amturing.acm.org/award_winners/stearns_1081900.cfm)
- [計算複雜度理論 - Wikipedia](https://zh.wikipedia.org/wiki/%E8%AE%A1%E7%AE%97%E5%A4%8D%E6%9D%82%E6%80%A7%E7%90%86%E8%AE%BA)
