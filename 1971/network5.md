# 終端介面處理器：網路存取的民主化

## 終端機的問題

在 ARPANET 發展的早期，要加入網路需要一台完整的主機電腦。終端機使用者只能透過主機來間接存取網路——這是一個昂貴的限制。許多組織有終端機和操作員，卻沒有自己的主機。

為了解決這個問題，BBN 開發了 TIP（Terminal Interface Processor，終端介面處理器）。TIP 是一台 Honeywell 316 迷你電腦（使用更輕的非加固版本），可以同時支援最多 63 台 ASCII 序列終端機。

## TIP 的架構

TIP 在一個設備中結合了兩項功能：
- **IMP 功能**：處理 ARPANET 的分組交換
- **終端伺服器功能**：將終端機的序列連線轉換為 ARPANET 上的 TELNET 連線

TIP 配備了一個多線控制器（Multi-Line Controller），可以同時處理多個終端連線。使用者只需將終端機連接到 TIP，就可以直接登入 ARPANET 上的任何主機。

## 歷史意義

TIP 是現代網路存取點和終端伺服器的直接前身。它讓更多使用者可以加入 ARPANET，而不需要擁有或操作自己的主機電腦。這不僅降低了加入網路的成本，也促進了 ARPANET 從研究工具向通訊基礎設施的轉變。

到 1971 年底，TIP 已經在多個站點部署，大大擴展了網路的可及性。

## 延伸閱讀

- [Interface Message Processor - Wikipedia](https://en.wikipedia.org/wiki/Interface_Message_Processor)
- [BBN Report 1822](https://www.rfc-editor.org/)
