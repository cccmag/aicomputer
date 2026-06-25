# ALGOL 58：國際代數語言的誕生

1958 年 1 月，在瑞士蘇黎世聯邦理工學院（ETH Zurich）召開的一場歷史性會議中，來自美國和歐洲的頂尖電腦科學家共同完成了一份程式語言設計方案，這份方案後來被稱為 ALGOL 58（ALGOrithmic Language 1958）。這是計算機科學史上第一次真正的國際合作程式語言設計嘗試。

會議的參與者包括美國的 John Backus（IBM，FORTRAN 開發團隊領導人）、Alan Perlis（卡內基理工學院）、歐洲的 Peter Naur（丹麥哥本哈根大學）、Friedrich Bauer（德國美因茨大學）和 Heinz Rutishauser（瑞士 ETH Zurich）等人。他們共同組成了一支名為「國際代數語言委員會」（International Algebraic Language Committee）的團隊。

ALGOL 58 的設計目標是建立一種適合描述數值計算演算法的通用程式語言。與 FORTRAN 偏向 IBM 特定平台的設計不同，ALGOL 58 從一開始就追求跨平台的可移植性。這個語言引入了許多重要的概念，包括區塊結構（block structure）——程式由嵌套的區塊構成，每個區塊可以有自己的區域變數宣告，變數的作用域被嚴格限制在所屬的區塊內。

ALGOL 58 還引入了條件語句的標準化結構（if-then-else）、陣列的動態宣告、迴圈的標準化寫法（for 語句）和遞迴呼叫的可能性（雖然實作尚未完整支援）。更重要的是，這份語言規範首次使用了形式語法（formal syntax）來描述程式的結構——這項工作後來發展為著名的 BNF（Backus-Naur Form）範式，成為程式語言設計和文件撰寫的標準工具。

ALGOL 58 雖然沒有被廣泛實作，但它為 ALGOL 60（1960 年正式發布）奠定了基礎。ALGOL 60 對整個計算機科學領域產生了巨大的影響——它的語法設計影響了 Pascal、Simula、C 語言，進而影響了 Java、C++ 和 C# 等現代語言。ALGOL 系列語言所建立的結構化程式設計概念至今仍然是現代軟體開發的基石。1958 年的蘇黎世會議，可以說是現代程式語言設計的起點。
