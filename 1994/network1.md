# SSL 加密協定：安全網路的開端

## 電子商務的關鍵技術

1994 年，Netscape Communications 開發了 SSL（Secure Sockets Layer）協定——第一個用於在網際網路上建立加密通訊通道的標準協定。SSL 的開發由 Taher Elgamal（被稱為「SSL 之父」）領導，基於 RSA 公開金鑰加密技術。

SSL 解決了電子商務面臨的核心問題：如何在不安全的網際網路上安全地傳輸信用卡號碼和個人資訊。

## SSL 的工作原理

SSL 協定在傳輸層（TCP）和應用層（HTTP）之間建立了一個安全層。其運作流程包括：

- **交握階段**（Handshake）：客戶端和伺服器交換公開金鑰，協商加密演算法
- **伺服器身分驗證**：客戶端驗證伺服器的數位憑證，確保連線到正確的伺服器
- **會話金鑰生成**：雙方共同生成一個對稱金鑰，用於後續的通訊加密
- **加密通訊**：所有資料使用會話金鑰加密傳輸

SSL 的關鍵創新是「混合加密」——使用非對稱加密（RSA）來安全交換金鑰，然後使用對稱加密（RC4、DES 等）來加密實際資料。這樣的設計兼顧了安全性與效能。

## Netscape Commerce Server

1994 年 12 月 15 日，Netscape 推出了 Netsite Commerce Server——第一個支援 SSL 的商業 Web 伺服器。售價為 5,000 美元。它與 Navigator 1.0 配合使用，提供了完整的客戶端-伺服器安全通訊方案。

第一個使用 SSL 的安全交易發生在 1994 年 8 月——NetMarket 的一個客戶 Phil Brandenberger 用信用卡購買了 Sting 的音樂 CD《Ten Summoner's Tales》，金額為 12.48 美元。當時使用的是早期版本的 SSL 實作。

## SSL 的遺產

SSL 後來演變為 TLS（Transport Layer Security），至今仍是網際網路安全的基礎。從線上購物、網路銀行到電子郵件，幾乎所有安全的網際網路通訊都依賴於 SSL/TLS 協定。1994 年的這項發明，讓電子商務從夢想變成了現實。

## 延伸閱讀

- [SSL 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Transport_Layer_Security)
- [Taher Elgamal - SSL 的發明](https://en.wikipedia.org/wiki/Taher_Elgamal)
