# Meltdown 與 Spectre：CPU 安全漏洞

## 近二十年最嚴重的 CPU 漏洞

2018 年 1 月 3 日，來自 Google Project Zero、多所大學和產業研究機構的安全研究人員公開披露了兩個嚴重的 CPU 安全漏洞——Meltdown 和 Spectre。這兩個漏洞影響了過去二十年生產的幾乎所有處理器——包括 Intel、AMD、ARM 和 IBM。

Meltdown（CVE-2017-5754）利用處理器在推測執行期間的特權分離漏洞，讓攻擊者可以讀取作業系統核心記憶體中的資料。它主要影響 Intel 處理器。

Spectre（CVE-2017-5753 和 CVE-2017-5715）利用推測執行的副作用來誘導受害者存取記憶體，可以打破進程間隔離。它影響幾乎所有現代處理器。

## 技術原理

漏洞的根本原因是 CPU 效能優化技術——推測執行（speculative execution）和分支預測（branch prediction）的副作用。

當 CPU 遇到條件分支時，它會猜測結果並提前執行指令。如果猜測錯誤，CPU 會捨棄結果，但執行期間的副作用（快取狀態的變化）不會被還原。Meltdown 和 Spectre 利用這個微觀的時間差來推斷被隔離的記憶體內容。

## 影響與修復

Meltdown 和 Spectre 的修復面臨巨大挑戰：

- 作業系統修補（KPTI）可以解決 Meltdown，但會導致 5-30% 的效能下降
- Spectre 的修復需要微碼更新和編譯器層級的工作
- 某些修復無法徹底解決問題
- 此後數年不斷有 Spectre 變種被發現（Spectre v2、v3、v4、L1TF、MDS）

這兩個漏洞的曝光徹底改變了處理器設計與安全社群的關係——硬體安全從假定安全轉變為需要形式化驗證。

## 延伸閱讀

- [Meltdown 攻擊論文](https://meltdownattack.com/)
- [Spectre 攻擊論文](https://spectreattack.com/)
- [Google Project Zero 分析](https://googleprojectzero.blogspot.com/2018/01/reading-privileged-memory-with-side.html)
