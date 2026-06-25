# DES 加密標準正式上路

## 從提案到標準

1977 年 1 月 15 日，美國國家標準局（NBS）正式發布了聯邦資訊處理標準 FIPS 46——資料加密標準（DES）。這項標準在 1976 年 11 月 23 日已獲美國商務部批准，經過六個月緩衝期後於 1977 年 7 月正式生效。

DES 的演算法源自 IBM 的 Lucifer 密碼，由 Horst Feistel 在 1970 年代初期設計。IBM 團隊在 Walt Tuchman 的領導下，與 NBS 和 NSA 合作，將 Lucifer 修改為最終的 DES 規格。

## 演算法概要

DES 使用 56 位元密鑰對 64 位元資料區塊進行加密。它採用 Feistel 網路結構，包含 16 輪的置換和替代操作。雖然現在看來 56 位元密鑰太短，但在 1977 年，對絕大多數應用來說已經足夠安全。

## 爭議的遺產

DES 的 56 位元密鑰長度始終是爭議焦點。Diffie 和 Hellman 在 1977 年發表的分析中指出，DES 的密鑰長度可能無法長期抵禦暴力破解。然而 NBS 的回應是：該標準在預期的 15 年壽命內足夠安全，並將每五年檢討一次。

歷史證明 DES 的壽命遠超過 15 年——它服務了超過二十年，直到 1999 年被 AES 取代。

## 延伸閱讀

- [資料加密標準 - Wikipedia](https://en.wikipedia.org/wiki/Data_Encryption_Standard)
- [FIPS 46 原始文件 - NIST](https://csrc.nist.gov/publications/detail/fips/46/archive/1977-01-31)
