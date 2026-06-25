# Intel 8086：x86 架構的起點

## 一個臨時替代品的傳奇

1978 年 6 月 8 日，Intel 發表了 8086 微處理器。但這個後來成為個人電腦之心的晶片，最初在公司內部只被視為一個臨時替代品——一個「代用品」（stopgap）。

Intel 真正的野心是 iAPX 432——一個革命性的 32 位元處理器，內建記憶體管理和多工支援。但 432 的開發一再延遲。與此同時，Motorola 正在開發 68000，Zilog 已經推出了 Z80，National Semiconductor 也虎視眈眈。Intel 需要一個能立即出貨的 16 位元產品來防止客戶流失。

## 設計團隊與限制

8086 的專案始於 1976 年 5 月。Intel 管理層給了軟體工程師 Stephen Morse 極大的自由——因為沒人預期這個設計會存活很久。唯一的限制是：必須與 8080 的組合語言相容，讓現有客戶的程式碼可以經由重新編譯來移植。

Morse 的設計包含了四個 16 位元通用暫存器（AX、BX、CX、DX）、分段記憶體模型（segmented memory）、字串處理指令和十進制算術指令。Jim McKevitt 將架構實現為邏輯電路——據專案經理 Bill Pohlman 所說，McKevitt 的第一次設計就完全正確，沒有任何錯誤。

## 一個帝國的誕生

8086 在三年內推出了降低成本版的 8088（外部 8 位元資料匯流排）。1981 年，IBM 選擇了 8088 作為 IBM PC 的處理器——這個決定讓 x86 架構成為個人電腦的標準，直到今天。

## 延伸閱讀

- [Intel 8086 - Wikipedia](https://en.wikipedia.org/wiki/Intel_8086)
- [x86 架構歷史 - Google 搜尋](https://www.google.com/search?q=x86+architecture+history+8086)
