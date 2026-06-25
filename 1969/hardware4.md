# GE-645：Multics 的硬體平台

## 為分時系統而生的電腦

1964 年，MIT 的 Project MAC 開始規劃一個全新的作業系統——Multics。為了支援這個系統的硬體需求，MIT 需要一款具備虛擬記憶體、分段（segmentation）和保護環（protection rings）能力的電腦。

1965 年初，MIT 向多家電腦製造商發出了招標。IBM 提案的 System/360 型號不能滿足 MIT 對分頁（paging）和分段的需求——IBM 認為這些功能不重要。Joe Weizenbaum 教授——因開發 ELIZA 聊天機器人而聞名——引薦了他以前在 GE 的同事。GE Schenectady 實驗室的團隊對這個挑戰非常感興趣。

1965 年 8 月，GE 獲得了合約，開始在 GE 635 的基礎上開發一款特製型號——GE-645。

## GE-645 的技術創新

GE-645 是 GE 635 的重大改良版，新增了以下關鍵功能：

**分段與分頁**：GE-645 的記憶體管理單元（MMU）支援分段——每個程式可以擁有多個獨立的位址空間——以及在分段內的分頁機制。每個分段被劃分為 1024 字（36 位元）的頁面。

**保護環**：硬體支援 8 層保護環（protection rings），這是 Multics 安全模型的基礎。內環（數字小）有更高的特權，作業系統核心運行在最內層的環 0 中。這是現代作業系統特權級別概念的起源。

**關聯記憶體（Associative Memory）**：GE-645 配備了一個小型的、以硬體實現的位址轉換緩衝區——相當於現代的 TLB（Translation Lookaside Buffer）——用於加速虛擬位址到實體位址的轉換。

**多處理器支援**：GE-645 可以配置多個 CPU，共享同一記憶體。Multics 是早期支援對稱多處理（SMP）的作業系統之一。

## 第一台 GE-645 的交付

第一台 GE-645 在 1967 年 1 月交付給 MIT。但它需要大量的硬體和軟體調校才能正常運作。Multics 的開發過程充滿了挫折——作業系統的各種組件直到 1968 年底才開始協調運作。

1969 年，Multics 開始為 MIT 的用戶提供服務。雖然效能仍然不理想，但它已經能夠支援數十個同時連線的分時用戶。同年 10 月，MIT 的資訊處理中心正式接管了 GE-645 的運作。

## 商業命運

1970 年，GE 將整個電腦部門出售給了 Honeywell。Honeywell 繼續銷售 Multics——主要面向政府和大型企業客戶——直到 1985 年終止支援。雖然 GE-645/Multics 在商業上從未獲得巨大成功，但它在作業系統設計、虛擬記憶體和安全模型方面的創新，深刻地影響了 Unix、Linux、Windows 等後來的系統。

## 延伸閱讀

- [Multics 歷史 - MIT](https://web.mit.edu/multics-history/)
- [GE-645 架構 - Wikipedia](https://en.wikipedia.org/wiki/GE-645)
- [Multics 虛擬記憶體](https://multicians.org/f7y.html)
