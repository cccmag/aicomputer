# ARPANET 的第一次呼吸：1969 年 10 月 29 日

## 那個晚上的事件

1969 年 10 月 29 日，晚上 10 點 30 分。加州大學洛杉磯分校（UCLA）Boelter Hall 3420 室。21 歲的研究生 Charley Kline 坐在 SDS Sigma 7 主機的控制台前。

在 350 英里外的 Menlo Park，Stanford Research Institute（SRI）的 Bill Duvall 正守著 SDS 940 主機。這是 ARPANET 的第一次實際測試——從 UCLA 的主機登入 SRI 的主機。

Kline 敲入了第一個字母：「L」。電話裡 Duvall 說：「收到 L 了。」Kline 敲入第二個字母：「O」。Duval 確認：「收到 O 了。」

Kline 敲入第三個字母「G」——系統立刻崩潰了。

## LO——史上最簡短的訊息

ARPANET 的第一條訊息是「LO」——原本應該發送的是「LOGIN」。但系統因為一個緩衝區溢位問題而當機。

問題的原因很簡單：SRI 的接收程式原本設計用於 10 cps（字元/秒）的電傳打字機線路，但 ARPANET 可以以 5,000 cps 的速度傳輸資料。UCLA 發送的資料太快了，SRI 的緩衝區來不及處理。Duvall 立即修改了程式——將緩衝區變大——大約一小時後，完整的「LOGIN」訊息終於成功地傳輸完成。

Leonard Kleinrock——UCLA 的教授、研究團隊的領導者——後來幽默地評論說：「這條訊息 'LO' 就像是網際網路嬰兒的第一次呼吸——不完整，但充滿了驚奇。」

## 技術架構

首次連線的技術設置如下：

- **主機**：UCLA 使用 SDS Sigma 7（科學資料系統公司的主機），SRI 使用 SDS 940
- **IMP**：BBN 在兩地各安裝了一台 Honeywell DDP-516 作為 IMP
- **數據機**：使用 AT&T 的 50 kbps 租用電話線路
- **協定**：IMP 間使用 1822 協議（以 BBN 技術報告編號命名）
- **介面**：主機通過特殊的平行介面與 IMP 連接

## 即時記錄

Kleinrock 保存了一份珍貴的歷史文件——UCLA IMP LOG 中的手寫記錄。這份記錄準確地記載了 1969 年 10 月 29 日 22:30 的連線事件。淡黃色的紙張上，有人用鉛筆寫下了日期、時間和簡短的描述。

這份文件現在被收藏在 UCLA 的圖書館中，是網際網路時代的出生證明。

## 延伸閱讀

- [Kleinrock 教授的回憶](https://www.lk.cs.ucla.edu/internet_first_words.html)
- [完整故事 - BBC Future](https://www.bbc.com/future/article/20241028-the-failure-that-started-the-internet)
- [ARPANET 歷史 - DARPA](https://www.darpa.mil/news/features/arpanet)
