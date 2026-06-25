# X Window System：MIT 的視窗系統

## 分散式視窗的設計

1985 年，MIT 的 Project Athena 發表了 X Window System（版本 9）——一個為 Unix 工作站設計的視窗化系統。X 的設計哲學與 Microsoft Windows 或 Macintosh 截然不同：它不是一個作業系統內建的 GUI，而是一個網路透明的顯示協定。

在 X 的模型中，應用程式（client）和顯示器（server）可以位於不同的機器上。使用者可以在工作站 A 上執行程式，但將視窗顯示在工作站 B 的螢幕上——只需要網路連線。這種「網路透明性」在區域網路普及的大學校園中極為有用。

## 從 MIT 到產業標準

X Window System 的開發由 Bob Scheifler 和 Jim Gettys 領導。他們從史丹佛大學的 W 視窗系統獲得了靈感（因此命名為 X——比 W 更進一步）。

X 的設計保持「機制而非政策」的原則——X 只負責底層的繪圖和事件處理，不規定視窗外觀和操作方式。上層的視窗管理器和工具包可以自由實現不同的介面風格（Motif、OpenLook、CDE 等）。

到 1986 年，X 已經被 Hewlett-Packard、DEC、IBM 等主要工作站製造商採用，成為 Unix 圖形環境的事實標準。

## 延伸閱讀

- [X Window System - Wikipedia](https://en.wikipedia.org/wiki/X_Window_System)
- [Project Athena - Wikipedia](https://en.wikipedia.org/wiki/Project_Athena)
