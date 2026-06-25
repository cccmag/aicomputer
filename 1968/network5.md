# Roberts 的「資源共享電腦網路」提案

## 關鍵文獻

1968 年 6 月 3 日，Larry Roberts 向 ARPA 提交了一份題為「Resource Sharing Computer Networks」的計畫書。這份文件不僅是 ARPANET 的正式建設計畫，也是分散式網路願景最完整的早期表述。

Roberts 在文件中明確提出了 ARPANET 的主要目標：「讓一台電腦的使用者能夠呼叫遠端系統來執行程式，從而共享稀有的計算資源。」在當時，運算能力是一種稀缺且昂貴的資源——一台大型主機的造價可達數百萬美元。Roberts 認為，如果不同機構的電腦可以互相連接，就能大幅提高整個國家的運算資源利用率。

## 計畫的具體內容

Roberts 的計畫書詳細描述了：

**網路架構**：採用分散式分組交換網路，由 IMP 負責路由和轉發。沒有中央控制節點——任何一個 IMP 失效都不會影響整體網路的運作。

**節點選擇**：最初四個站點（UCLA、SRI、UCSB、猶他大學）的選擇基於其在電腦科學研究領域的領先地位，以及每站點擁有的獨特運算資源。

**通訊線路**：使用 AT&T 的 50 kbps 租用電話線路連接各站點。50 kbps 是當時可以取得的最經濟的高速數據傳輸服務。

**時間表**：第一台 IMP 在 1969 年 9 月交付，四個節點在 1969 年 12 月前完成連線。

## 從提案到批准

Bob Taylor 在收到計畫書後給予了全力支持。他僅用 18 天——6 月 21 日——就批准了這項計畫。這種快速決策反映了 ARPA 對網路研究的緊迫感。

Taylor 後來解釋了他的支持理由：「所有我們資助的研究機構都在買大型電腦。如果我們可以用網路把這些電腦連接起來，那麼每個機構都可以共享所有機構的資源。這樣我們就不需要為每個機構都買最先進的電腦了。」

## 提案的歷史地位

Roberts 的提案是 ARPANET 從概念走向現實的關鍵文件。它明確說明了網路的願景、技術方案、實施計畫和預算。更重要的是，它將前兩年所有研究工作——Baran 的分散式網路、Davies 的分組交換、Clark 的 IMP 概念、Roberts 的 SOSP 論文——整合成了一個可執行的計畫。

從這個意義上說，「Resource Sharing Computer Networks」是網際網路的出生證明。

## 延伸閱讀

- [Larry Roberts 傳記 - Britannica](https://www.britannica.com/biography/Lawrence-Roberts)
- [IPTO 歷史 - Internet History](https://www.livinginternet.com/i/ii_roberts.htm)
- [Resource Sharing Computer Networks - 原始文檔](https://www.computerhistory.org/collections/catalog/102739067)
