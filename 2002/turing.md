# 2002 年圖靈獎：Ron Rivest、Adi Shamir、Len Adleman

## RSA 的誕生

2002 年的 ACM 圖靈獎頒給了 Ron Rivest、Adi Shamir 和 Leonard Adleman——三位麻省理工學院的教授，表彰他們在 1977 年共同發明了 RSA 公開金鑰密碼系統。這是現代網路安全的基石。

RSA 的故事始於 1976 年——Whitfield Diffie 和 Martin Hellman 發表了公開金鑰密碼學的概念。但他們沒有找到一個實用的單向函數（one-way function）來實現這個概念。

1977 年春天，Rivest、Shamir 和 Adleman 在 MIT 開始了公開金鑰系統的研究。經過多次失敗後，Rivest 在 1977 年 4 月的一個晚上——在大量飲用瑪格麗特雞尾酒後——無法入睡，於是在筆記本上寫下了基於大質數因數分解困難性的數學方案。次日早上，他將這個方案交給 Shamir 和 Adleman——他們確認這個方案是安全的。

RSA 的名字來自三位發明者的姓氏：Rivest、Shamir、Adleman。

## 核心原理

RSA 的安全性建立在一個簡單的數學事實上：將兩個大質數相乘非常容易，但將它們的乘積分解回原來的質數則極為困難。

RSA 的操作過程：

1. **金鑰生成**：選擇兩個大質數 p 和 q，計算 N = p × q。選擇一個與 φ(N) 互質的 e，計算 d 使 e × d ≡ 1 (mod φ(N))

2. **公開金鑰**：(N, e) 可以公開給任何人

3. **私密金鑰**：(N, d) 必須保密

4. **加密**：將訊息 m 轉換為密文 c = m^e mod N

5. **解密**：從密文 c 還原訊息 m = c^d mod N

這個優雅的數學方案實現了一個強大的功能：任何人都可以用你的公開金鑰加密訊息，但只有持有私密金鑰的你才能解密。

## 對網路安全的貢獻

RSA 是 SSL/TLS、數位簽章、安全電子郵件（PGP）、電子商務和網路銀行安全的基礎。每一筆線上交易、每一次安全瀏覽（HTTPS）、每一封加密的電子郵件，都間接使用了 RSA 或在其啟發下發展的密碼學技術。

## 圖靈獎演講

2002 年圖靈獎的三位獲獎者分別發表了演講，回顧了 RSA 的發明歷程，並討論了密碼學在資訊社會中的重要性——特別是在隱私和安全日益受到關注的 21 世紀初。

## 延伸閱讀

- [Ron Rivest, Adi Shamir, Len Adleman - ACM Turing Award](https://amturing.acm.org/award_winners/rivest_1403005.cfm)
- [RSA - Wikipedia](https://zh.wikipedia.org/wiki/RSA%E5%8A%A0%E5%AF%86%E6%BC%94%E7%AE%97%E6%B3%95)
- [公開金鑰密碼學 - Wikipedia](https://zh.wikipedia.org/wiki/%E5%85%AC%E5%BC%80%E9%92%A5%E5%AF%86%E7%A0%81%E5%AD%A6)
