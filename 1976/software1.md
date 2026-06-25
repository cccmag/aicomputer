# Diffie-Hellman 密鑰交換：公鑰密碼學的誕生

## 一個革命性的想法

1976 年 11 月，IEEE Transactions on Information Theory 發表了一篇題為「New Directions in Cryptography」的邀請論文。作者 Whitfield Diffie 和 Martin Hellman 在論文中提出了兩個革命性的概念：**公鑰密碼系統**（public key cryptosystem）和**公鑰分發系統**（public key distribution system）。後者後來被稱為 Diffie-Hellman 密鑰交換。

在此之前，加密通訊需要雙方事先共享一把密鑰——這通常要透過私人信差或掛號郵件來傳遞，成本高昂且不適合大規模網路。Diffie 和 Hellman 的想法是：雙方可以在一個完全公開的通道上交換資訊，最終推導出一把相同的密鑰，而竊聽者即使掌握了所有交換內容也無法計算出這把密鑰。

## 背後的數學

Diffie-Hellman 密鑰交換利用了**離散對數問題**的困難性。給定一個質數 p 和一個原根 g，Alice 選擇一個秘密數字 a，計算 A = g^a mod p 送到公開通道；Bob 選擇 b，計算 B = g^b mod p 送回。雙方分別計算 K = B^a mod p = A^b mod p = g^(ab) mod p。第三方面對 g、p、A、B，要計算出 K 是計算上不可行的。

## 密碼學的分水嶺

這篇論文標誌著現代密碼學的開始。Ralph Merkle 在同一時期獨立提出了類似概念。1977 年，Ron Rivest、Adi Shamir 和 Len Adleman 基於這些概念發明了 RSA 演算法——第一個完整的公鑰密碼系統。如果沒有 1976 年的這篇論文，今天的網路安全——從 HTTPS 到電子商務——都將不復存在。

## 延伸閱讀

- [Diffie-Hellman 密鑰交換 - Wikipedia](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange)
- [New Directions in Cryptography - IEEE](https://ieeexplore.ieee.org/document/1055638)
