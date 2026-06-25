# LISP 在 MIT 開始開發：John McCarthy 與人工智慧

1958 年秋天，John McCarthy 從達特茅斯學院來到麻省理工學院（MIT）並開始著手開發一種全新的程式語言。到了 1959 年，這項工作已經取得了顯著進展，一種以符號表達式和列表處理為核心的語言逐漸成形——這就是 LISP（LISt Processing language）。

「人工智慧」這個術語正是在 1956 年由 McCarthy 與 Marvin Minsky、Claude Shannon 等人在達特茅斯會議上共同提出的。McCarthy 深信，要實現真正的人工智慧，需要一種能夠靈活處理符號資訊而非僅限於數值計算的程式語言。當時的 FORTRAN 和組合語言在符號處理方面力不從心，這促使他從零開始設計 LISP。

LISP 的核心創新在於將程式碼和資料統一的表示方式——符號表達式（symbolic expression，簡稱 S-expression）。在 LISP 中，程式本身也是由列表構成的資料結構，這意味著程式可以在執行時對自身進行修改和生成，這一特性稱為「同像性」（homoiconicity）。LISP 還引入了自動記憶體管理（垃圾回收）、高階函數、遞迴作為基本控制結構等革命性概念。

McCarthy 的第一個 LISP 實作是在 IBM 704 電腦上進行的。他借鑒了 IPL（Information Processing Language，由 Allen Newell 和 Herbert Simon 開發）中的列表處理概念，但將其提升到一個更具形式化基礎的高度。McCarthy 在 1959 年撰寫的備忘錄中詳細描述了 LISP 的設計原理和實作方法，這份備忘錄後來成為人工智慧研究的重要文獻。

LISP 的誕生對計算機科學產生了不可估量的影響。它不僅成為人工智慧研究的首選語言長達數十年，還啟發了許多程式語言設計中的重要概念，包括函數式程式設計、垃圾回收和元程式設計等。LISP 的後繼者如 Common Lisp、Scheme 和 Clojure 至今仍然被廣泛使用，而它的許多設計理念已經融入了 Python、JavaScript、Ruby 等主流語言的血液之中。
