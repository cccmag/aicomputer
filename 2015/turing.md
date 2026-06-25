# 2015 年圖靈獎：Whitfield Diffie & Martin Hellman

## 公鑰密碼學的奠基者

2015 年 ACM 圖靈獎頒給了 Whitfield Diffie 和 Martin Hellman，表彰他們在現代密碼學上的開創性貢獻——特別是在 1976 年發表的開創性論文「New Directions in Cryptography」中提出的公鑰密碼學概念。

這篇論文被認為是密碼學史上最重要的文獻之一。它首次提出了無需預先共享密鑰即可進行安全通訊的數學框架——這個概念徹底改變了資訊安全的面貌。

## Diffie-Hellman 密鑰交換

Diffie 和 Hellman 最著名的貢獻是 Diffie-Hellman 密鑰交換協定。這個協定讓兩方可以在不安全的通道上共同建立一個共享的密鑰，即使第三者能夠監聽所有通訊也無法推導出該密鑰。

這個看似違反直覺的成就依賴於離散對數問題的數學難度——給定一個大質數 p 和一個生成元 g，計算 g^a mod p 很容易，但從結果反推出 a 則被認為在計算上不可行。

## 深遠的影響

Diffie 和 Hellman 的工作為整個現代密碼學奠定了基礎：

- RSA 加密系統（1977 年）直接建立在公鑰概念的基礎上
- SSL/TLS 協定使用 Diffie-Hellman 來保護網路通訊
- 電子商務、網上銀行、手機通訊的安全都依賴於他們的思想

有趣的是，英國情報機構 GCHQ 的 James Ellis 和 Clifford Cocks 在 1973-1974 年就獨立發現了公鑰密碼學的概念，但因為機密等級而無法發表。Diffie 和 Hellman 的公開研究成果確保了這項技術能夠造福全世界。

## 圖靈獎演講

Diffie 在獲獎演講中回顧了 1970 年代中期密碼學研究的環境——當時這幾乎是政府機構的禁臠，民間研究受到極大限制。他與 Hellman 突破這些限制，將密碼學從軍工領域帶入公共學術領域。

## 延伸閱讀

- [Whitfield Diffie - ACM Turing Award](https://amturing.acm.org/award_winners/diffie_8277003.cfm)
- [Martin Hellman - ACM Turing Award](https://amturing.acm.org/award_winners/hellman_9919792.cfm)
- [New Directions in Cryptography (1976)](https://ieeexplore.ieee.org/document/1055638)
