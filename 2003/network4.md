# Skype 的 VoIP 技術與 P2P 網路架構

## 語音封包的旅程

Skype 的技術核心在於如何將語音訊號透過網際網路即時傳送。這個過程涉及訊號編碼、封包化、路由、解碼等多個步驟——每一環都需要精心設計才能在不可靠的網路上實現可接受的通話品質。

Skype 採用的 iSAC（Internet Speech Audio Codec）編解碼器專為語音通話設計，能夠在低位元率（10-32 kbps）下保持良好的音質。它支援自適應位元率——當網路狀況不佳時自動降低品質以維持通話連續性。

## 全球索引技術

Skype 最獨特的技術是「全球索引」（Global Index）。這是 P2P 架構中運作的分散式目錄系統：每個用戶端登入時，會將其存在通知給一組超級節點。這些超級節點互相交換資訊，形成一個覆蓋整個 Skype 網絡的分散式資料庫。

當用戶 A 要呼叫用戶 B 時，Skype 用戶端不需要向中央伺服器查詢——它透過附近的超級節點就可以找到 B 的目前 IP 位址和連線狀態。這個設計讓 Skype 極具擴展性，同時沒有中央化的故障單點。

## 穿越防火牆

Skype 的穿透 NAT 和防火牆能力是它的關鍵競爭優勢。它使用了多種技術的組合：UPnP、STUN、TURN、以及中繼路由——如果兩個用戶都無法直接連線，通話可以透過第三方超級節點轉發。這讓 Skype 在幾乎所有的網路環境中都能運作。

## 延伸閱讀

- [Skype 協定 - Wikipedia](https://en.wikipedia.org/wiki/Skype_protocol)
- [VoIP 技術 - Google 搜尋](https://www.google.com/search?q=VoIP+Skype+%E6%8A%80%E8%A1%93%E5%8E%9F%E7%90%86)
- [P2P 語音通訊 - Google 搜尋](https://www.google.com/search?q=Skype+P2P+VoIP+architecture)
