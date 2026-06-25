# LISP 1.0：符號運算的起點

1960 年，John McCarthy 在麻省理工學院（MIT）發表了 LISP 1.0——這是一門以符號表達式（Symbolic Expression，簡稱 S-expression）為基礎的列表處理語言，後來成為人工智慧研究領域最重要的程式語言。LISP 的設計哲學——程式碼即資料、遞迴作為基本控制結構、垃圾回收——在 1960 年代是革命性的。

McCarthy 開發 LISP 的動機來自於他在人工智慧研究中的需求。1958 年，McCarthy 發表了〈Programs with Common Sense〉論文，提出了一個名為「Advice Taker」的程式概念——一個能夠使用邏輯推理來解決問題的通用智慧系統。為了實現這個系統，McCarthy 需要一種能夠靈活地操作符號表達式與列表數據的程式語言——FORTRAN 與 ALGOL 在設計上以數值計算為中心，無法滿足這個需求。

LISP 1.0 的核心資料結構是 S-expression。S-expression 可以是原子（atom）——如數字、符號、字串——或是由點對（dotted pair）構成的列表。列表以括號表示，例如 (A B C) 表示包含三個元素的列表。列表可以嵌套，可以包含任意類型的元素。S-expression 的結構可以自然地表示樹狀資料、語法樹、邏輯表達式等——這些都是 AI 程式中常見的資料結構。

LISP 提供了兩個基本的列表操作原語：car 取出列表的第一個元素，cdr 取出剩餘的列表（即去掉第一個元素後的列表）。這兩個原語的名稱來自於 IBM 704 硬體暫存器的位址欄位——car 代表 Contents of the Address part of Register，cdr 代表 Contents of the Decrement part of Register。LISP 也提供了 cons 函數來構造新的列表。

LISP 1.0 使用條件表達式（conditional expression）而非 FORTRAN 的 IF 陳述式。McCarthy 的條件表達式以 (cond (p1 e1) (p2 e2) ...) 的形式書寫——依次檢查每個條件 p1、p2……，當條件為真時傳回對應的 e1、e2……。條件表達式可以傳回值，這與 ALGOL 60 的條件表達式概念類似。遞迴則取代了 FORTRAN 的 DO 循環——程式員定義一個函數，讓它反覆呼叫自身來處理列表中的每個元素。

LISP 1.0 的另一個革命性特點是將程式碼表示為資料。LISP 程式本身就是 S-expression——(lambda (x) (* x x)) 這是一個定義平方函數的 LISP 程式，同時也是一個合法的列表資料結構。這意味著 LISP 程式可以像資料一樣被建立、修改、解析與求值。McCarthy 在 LISP 中提供了一個被稱為 eval 的特殊函數，它可以接受一個 S-expression 作為參數，將其解釋為 LISP 程式碼並執行。eval 的實作使得 LISP 可以輕鬆地實現腳本化、動態程式碼生成與元程式設計——這些功能在當時的程式語言中是極為罕見的。

LISP 1.0 也引入了垃圾回收（garbage collection）的概念。由於 LISP 大量使用動態分配的列表結構，手動管理記憶體變得極其困難。McCarthy 設計了一個標記-清除（mark-and-sweep）的垃圾回收演算法：當系統的可用記憶體不足時，回收器從全域變數與堆疊中的根物件開始，標記所有可達的列表單元，然後清除（回收）所有未被標記的單元。

LISP 1.0 的發表對電腦科學產生了深遠的影響。它不僅是 AI 領域的標準語言——1970 年代的 MacLISP、Interlisp，1980 年代的 Common Lisp、Scheme——更重要的是，它引入了許多在當時極為前衛的概念：動態型別、頭等函數、閉包、垃圾回收、元循環求值器。這些概念在 1990 年代開始大量進入主流語言——Python、JavaScript、Ruby、Java 等都借鑑了 LISP 的思想。
