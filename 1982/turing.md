# 1982 年圖靈獎：Stephen Cook

## NP-completeness 的奠基者

Stephen A. Cook 是 1982 年 ACM 圖靈獎得主，授獎理由是「對計算複雜度的理解做出了重大而深遠的貢獻」。具體來說，他的 1971 年論文「The Complexity of Theorem Proving Procedures」被認為是 NP-completeness 理論的奠基之作。

Cook 1939 年出生於美國紐約州水牛城。他在哈佛大學獲得數學博士學位後，在加州大學柏克萊分校任教，但由於數學系未能給他終身職（這後來被 Richard Karp 稱為「永遠的羞恥」），1970 年轉往多倫多大學。他在多倫多大學獲得了最佳的學術環境，成為傑出的教授和導師。

## Cook-Levin 定理

Cook 最重要的貢獻是證明了 SAT（Boolean Satisfiability Problem，布林公式滿足問題）是 NP-complete 的。這個定理——由 Cook 和蘇聯數學家 Leonid Levin 獨立發現——建立了 NP-completeness 的嚴格數學基礎。

Cook 論文的核心洞見是：
1. 定義了 NP 類別（非確定性多項式時間可解的問題）
2. 定義了多項式時間歸約（polynomial-time reduction）
3. 證明了 SAT 可以歸約到任何 NP 問題——因此如果 SAT 可以在多項式時間內被解決，那麼所有 NP 問題都可以
4. 將 「P vs. NP」問題正式化——這個問題至今仍是 Clay 數學研究所的七個千禧年大獎難題之一

## 對電腦科學的影響

Cook 的工作創立了計算複雜度理論這個領域。在接下來的數十年中，數千個問題被證明是 NP-complete 的——從排程、佈局到背包問題。NP-completeness 已成為電腦科學中最實用的工具之一：當面對一個新問題時，如果它被證明是 NP-complete 的，研究人員就知道不太可能存在有效演算法，應轉而尋找近似解或啟發式演算法。

Cook 也對命題證明複雜度（propositional proof complexity）做出了開創性貢獻，並指導了 30 多位博士生——其中許多人已成為理論電腦科學的領軍人物。

## 延伸閱讀

- [Stephen Cook - ACM Turing Award](https://amturing.acm.org/award_winners/cook_n991950.cfm)
- [Stephen Cook - Wikipedia](https://en.wikipedia.org/wiki/Stephen_Cook)
- [Cook-Levin Theorem - Wikipedia](https://en.wikipedia.org/wiki/Cook%E2%80%93Levin_theorem)
