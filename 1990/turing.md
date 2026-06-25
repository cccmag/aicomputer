# 1990 年圖靈獎：Fernando Corbató

## 分時系統之父

Fernando José Corbató（1926-2019）是 1990 年 ACM 圖靈獎得主，授獎理由是「在組織通用大規模分時及資源共享計算系統的概念方面做出先驅性工作」。Corbató 被稱為「分時系統之父」。

Corbató 在加州奧克蘭出生，在加州理工學院獲得物理學士學位，在 MIT 獲得物理學博士學位。他從 1956 年起一直在 MIT 的計算中心工作，直到退休。

## CTSS：第一個分時系統

1960 年代初期，Corbató 領導開發了 CTSS（Compatible Time-Sharing System，相容分時系統）。CTSS 於 1961 年首次展示，是第一個讓多個使用者同時使用一台計算機的系統。

在 CTSS 之前，計算機的操作方式是「批次處理」——使用者將程式和資料（通常以打孔卡片的形式）提交給操作員，等到程式執行完畢後再來取結果。這種方式可能讓使用者等上好幾個小時甚至好幾天。

CTSS 改變了一切：多個使用者透過終端機同時連接到一台主機，每個人都感覺自己獨占了整台機器。使用者可以在幾秒鐘內得到回應，極大地提高了生產力。

CTSS 還引入了第一個電腦密碼系統——雖然 Corbató 後來承認，密碼管理已經變成了一場噩夢。

## Multics：分時系統的巔峰

CTSS 的成功導致了一個更大的專案——Multics（MULTiplexed Information and Computing Service）。Multics 由 MIT、貝爾實驗室和通用電氣（GE）合作開發，後來由 Honeywell 商業化。

Multics 引入的創新概念包括：

- **階層式檔案系統**：目錄和子目錄的結構（被 Unix 採用）
- **環形安全保護（Ring Protection）**：分級的安全訪問機制
- **存取控制清單（ACL）**：精細的權限控制
- **動態連結（Dynamic Linking）**：程式在執行時動態載入共享程式庫
- **單層儲存（Single-Level Store）**：統一的記憶體和檔案存取模型

Multics 雖然商業上不算成功，但它對後來的作業系統產生了深遠的影響。特別是，Ken Thompson 和 Dennis Ritchie 在參與 Multics 開發後，開發了 Unix 作為一個更簡潔的分時系統。

## Corbató 定律

Corbató 有一條著名的「Corbató 定律」：「一個程式設計師在固定時間內能寫出的程式碼行數，與使用的語言無關。」這意味著用高階語言寫一行程式碼比用組合語言寫一行程式碼更有生產力，但每天能寫出的行數大致相同。

## 圖靈獎演講

Corbató 在 1990 年的圖靈獎演講題為「論建造將會失敗的系統」（On Building Systems That Will Fail）。他在演講中反思了大規模軟體系統開發的挑戰，指出：「任何大規模的系統都會在某處失敗，而且往往以你從未預期的方式失敗。」

## 延伸閱讀

- [Fernando Corbató - ACM Turing Award](https://amturing.acm.org/award_winners/corbato_1009471.cfm)
- [CTSS - Wikipedia](https://zh.wikipedia.org/wiki/%E5%85%BC%E5%AE%B9%E5%88%86%E6%99%82%E7%B3%BB%E7%B5%B1)
- [Multics - Wikipedia](https://zh.wikipedia.org/wiki/Multics)
