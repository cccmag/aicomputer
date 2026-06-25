# LISP 開發啟動：McCarthy 的備忘錄

1958 年秋天，John McCarthy 離開達特茅斯學院，轉往麻省理工學院（MIT）擔任助理教授。在 MIT 任職期間，他撰寫了一份重要的備忘錄，詳細描述了一種以符號表達式（symbolic expression）和列表處理（list processing）為核心的全新程式語言設計方案。這份備忘錄標誌著 LISP 語言的正式起點。

McCarthy 對當時既有的程式語言並不滿意。FORTRAN 雖然適合數值計算，但在符號處理方面力有未逮。IPL（Information Processing Language）是 Newell 和 Simon 開發的一種列表處理語言，但其語法過於底層，使用起來相當不便。McCarthy 希望設計一種既具備強大的符號處理能力，又擁有清晰的數學基礎的語言。

McCarthy 的關鍵洞察在於：列表（list）是一種通用的資料結構，可以用來表示任何複雜的符號表達式。更進一步，他提出程式碼本身也可以表示為列表結構——這就是「同像性」（homoiconicity）的概念。這意味著 LISP 程式可以在執行時生成、修改和執行其他 LISP 程式，這對於人工智慧研究中的自適應系統和學習演算法特別有用。

在 IBM 704 電腦上，McCarthy 開始實作第一個 LISP 直譯器。由於 704 的硬體限制，他設計了以 S-expression（符號表達式）作為程式的書寫形式，並使用 CAR（取頭元素）和 CDR（取尾列表）等名稱來操作列表結構——這些名稱源自 704 的機器指令助記碼。LISP 還引入了一個後來被廣泛採用的核心機制：垃圾回收（garbage collection），自動管理不再使用的記憶體空間。

LISP 的誕生對人工智慧研究和計算機科學發展產生了不可估量的影響。在 1960 到 1980 年代，LISP 是人工智慧研究的主要程式語言，廣泛應用於專家系統、自然語言處理和機器人學等領域。LISP 所引入的函數式程式設計（functional programming）理念——以純函數和不可變資料為核心——在 21 世紀迎來了復興，深刻影響了 Haskell、Scala、Clojure 和 JavaScript 等語言的設計。
