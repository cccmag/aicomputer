# 資料加密標準 DES 的審查與爭議

## 從 IBM 到 NBS

1976 年是 DES（Data Encryption Standard）準備正式成為美國聯邦標準的關鍵年。美國國家標準局（NBS）在 1973 年和 1974 年兩次公開徵求加密演算法後，最終選擇了 IBM 開發的 Lucifer 演算法作為基礎。IBM 在 Walt Tuchman 的領導下，根據 NBS 和國家安全局（NSA）的建議進行了修改。

## 公聽會與爭議

1976 年，NBS 舉辦了兩場公開研討會來審查 DES。會中最大的爭議在於密鑰長度：IBM 最初的設計使用 112 位元密鑰，但最終 DES 只採用了 56 位元——縮短了一半。許多人懷疑 NSA 故意削弱了演算法，以便自己能夠破解。

Diffie 和 Hellman 在 1977 年發表了題為「Exhaustive Cryptanalysis of the NBS Data Encryption Standard」的論文，指出 56 位元密鑰在不久後將可以被暴力破解。他們估算，一台造價 2000 萬美元的事用機器可以在一天內窮舉搜尋所有密鑰。歷史證明他們是對的——1998 年，EFF 的 Deep Crack 機器在 56 小時內破解了一個 DES 密鑰。

## 正式標準

DES 最終在 1977 年 1 月 15 日正式發布為 FIPS 46，並於 1977 年 7 月生效。儘管存在爭議，DES 成為歷史上最重要的加密標準之一，服務了超過二十年。

## 延伸閱讀

- [資料加密標準 - Wikipedia](https://en.wikipedia.org/wiki/Data_Encryption_Standard)
- [DES 歷史 - NIST](https://csrc.nist.gov/publications/detail/fips/46/archive/1977-01-31)
