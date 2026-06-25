# MINIX：教學用的 Unix 系統

## 為了教作業系統而寫的系統

1987 年，荷蘭阿姆斯特丹自由大學的 Andrew Tanenbaum 教授發表了 MINIX（Mini-Unix）作業系統。Tanenbaum 寫 MINIX 只有一個目的：為他的教科書《作業系統：設計與實作》提供一個可以實際運行的範例系統。

MINIX 是一個類 Unix 作業系統，完全從頭編寫（不包含任何 AT&T 的原始碼），可以在 IBM PC 相容機上運行。它的原始碼完整收錄在教科書的附錄中——沒錯，紙本印刷的原始碼，約 12,000 行。

## 微核心架構

MINIX 使用微核心（Microkernel）架構：核心只提供最基本的服務（行程間通訊、中斷處理），而檔案系統、記憶體管理、裝置驅動程式則作為使用者空間的行程執行。這與 Linux 的單核心（Monolithic Kernel）架構形成鮮明對比。

教學目的決定了 MINIX 的設計選擇：微核心更容易理解，也更適合學生修改和實驗。

## 對 Linux 的影響

MINIX 的出現對後來的 Linux 產生了直接的影響。1991 年，芬蘭赫爾辛基大學的學生 Linus Torvalds 在 MINIX 的啟發下開始開發 Linux。Torvalds 最初在 comp.os.minix 新聞群組中發布了他的專案，並表示「我正在製作一個（免費的）作業系統，只是一個業餘愛好，不會像 GNU 那樣龐大專業。」

MINIX 的存在證明了：一個完整的作業系統可以被一個人從頭寫出來，並且可以被用於教學——這激勵了整個開放原始碼作業系統的發展運動。

## 延伸閱讀

- [MINIX - Wikipedia](https://zh.wikipedia.org/wiki/MINIX)
- [Andrew Tanenbaum - Wikipedia](https://en.wikipedia.org/wiki/Andrew_S._Tanenbaum)
- [MINIX 對 Linux 的影響 - Google 搜尋](https://www.google.com/search?q=MINIX+Linux+history)
