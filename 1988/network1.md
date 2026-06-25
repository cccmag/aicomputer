# Morris Worm：第一個網際網路蠕蟲

## 一個研究生的實驗

1988 年 11 月 2 日晚上 8:30，康乃爾大學的研究生 Robert Tappan Morris 從麻省理工學院（MIT）的網路釋出了一個程式。這個程式只有 99 行程式碼，但它在短短 24 小時內感染了當時網際網路上約 60,000 台主機中的 6,000 台。

Morris 聲稱他的目的是估計網際網路的大小——透過讓程式自我複製並向一台遠端伺服器回報感染次數。但他的程式碼中有一個致命的錯誤：無論伺服器是否回報感染成功，程式都會繼續感染同一台機器。這導致被感染的機器被數百甚至數千個蠕蟲行程淹沒，最終完全癱瘓。

## 技術細節

Morris Worm 利用了三種不同的攻擊手法：

1. **Sendmail 除錯模式漏洞**：利用 sendmail 郵件伺服器的一個後門
2. **Finger 服務緩衝區溢位**：利用 finger 程式中一個未檢查緩衝區長度的漏洞
3. **rexec/rsh 信任關係**：嘗試利用主機之間的信任登入關係

此外，它還帶著一個簡單的密碼破解器，嘗試用 432 個常見密碼來猜測使用者的帳號密碼。

## 深遠的影響

Morris Worm 是網際網路安全史上的轉捩點：

- 它是第一個引起主流媒體關注的網路攻擊事件
- 促成了 CERT（Computer Emergency Response Team）的成立
- Morris 成為美國《電腦詐欺與濫用法》（1986 年）定罪的第一人
- 它讓整個網路社群意識到安全不是可以事後考慮的事情

Morris 後來對自己的行為表示道歉，並在 2008 年說他只是想估計網際網路的規模，無意造成傷害。

## 延伸閱讀

- [Morris Worm - Wikipedia](https://zh.wikipedia.org/wiki/%E8%8E%AB%E9%87%8C%E6%96%AF%E8%9B%86%E8%99%AB)
- [Robert Tappan Morris - Wikipedia](https://en.wikipedia.org/wiki/Robert_Tappan_Morris)
- [CERT - Wikipedia](https://en.wikipedia.org/wiki/CERT_Coordination_Center)
