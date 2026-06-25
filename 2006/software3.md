# .NET Framework 3.0：微軟的整合平台

## 從 WinFX 到 .NET 3.0

2006 年 11 月 6 日，微軟發布了 Windows Vista——伴隨 Vista 一同推出的是 .NET Framework 3.0。.NET 3.0 最初被稱為 WinFX——Windows 的新開發平台。它包含四個全新的技術棧，全部建構在 .NET Framework 2.0 之上：

## 四大支柱

**WPF（Windows Presentation Foundation）**：代號 Avalon。WPF 重新定義了 Windows 應用程式的使用者介面模型——使用 XAML（可擴充應用程式標記語言）宣告式地定義 UI，支援向量圖形、硬體加速、動畫、資料繫結。WPF 將 Windows 的 UI 開發從 GDI/GDI+ 時代推進到 DirectX 時代。

**WCF（Windows Communication Foundation）**：代號 Indigo。WCF 統合了微軟分散式應用開發的各種技術（ASMX Web Services、.NET Remoting、Enterprise Services、System.Messaging），提供一個統一的程式設計模型。WCF 支援多種通訊協定（HTTP、TCP、Named Pipes、MSMQ）和安全模型。

**WF（Windows Workflow Foundation）**：代號 WinOE。WF 提供了建構工作流程應用程式的框架——包括順序工作流程（sequential workflow）和狀態機工作流程（state machine workflow）。

**WCS（Windows CardSpace）**：代號 InfoCard。WCS 試圖解決數位身分的問題——一個使用者可以在不同網站使用不同的虛擬「卡片」來登入。這個技術後來影響不大，但反映了微軟對身分管理的早期思考。

## 技術影響

.NET Framework 3.0 代表微軟在 2000 年代中期最雄心勃勃的平台整合嘗試。WPF 對後來的 Windows UI 發展產生了深遠影響——Windows 8 和 Windows 10 的 Metro/Modern UI 設計語言可以追溯到 WPF 的向量圖形和資料驅動理念。WCF 為 SOA（服務導向架構）提供了強大的基礎設施。

但 .NET 3.0 也面臨挑戰：Windows Vista 的市場接受度不佳，影響了 .NET 3.0 的採用；WPF 的效能在早期版本中表現不足；而 Web 開發正迅速從桌面應用轉向 Web 應用——Silverlight（2007 年推出）試圖填補這個缺口，但最終也沒能成功。
