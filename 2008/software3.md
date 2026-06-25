# Dropbox 發布：雲端儲存的普及

## 一個遺忘 USB 隨身碟的故事

2008 年，MIT 畢業生 Drew Houston 和 Arash Ferdowsi 正式發布了 Dropbox——一個雲端檔案同步與共享服務。Houston 的故事是矽谷經典：「我在從波士頓到紐約的巴士上忘記帶 USB 隨身碟，無法繼續工作。為什麼我不能直接從雲端存取我的文件？」

Dropbox 的概念看似簡單：一個資料夾，任何檔案放在裡面都會被自動同步到雲端伺服器和所有其他裝置。但這個「簡單」的背後是複雜的技術設計。

## 同步引擎的核心技術

Dropbox 的同步引擎建立在幾個關鍵技術決策之上：

**差異同步**：當一個檔案被修改時，Dropbox 只上傳被修改的部分（稱為 block-level sync），而不是整個檔案。這大幅減少了頻寬消耗和同步時間。

**衝突解決**：當同一個檔案在多個裝置上同時被修改時，Dropbox 會保留所有版本。伺服器會選出一個版本作為主要版本，並將衝突的版本重新命名為「衝突的副本」（conflicted copy）。

**區域網路同步**：在同一區域網路中的多台電腦可以直接同步檔案，不需通過雲端伺服器——這稱為 LAN Sync，大幅加快了同步速度。

## 破壞性定價

Dropbox 的商業模式基於 freemium 策略：2 GB 免費，付費方案提供 50 GB 到 100 GB 的儲存空間。免費使用者的推薦獎勵計畫（每推薦一人獲得 500 MB 空間）成為了 Dropbox 病毒式成長的關鍵驅動力。

到 2008 年底，Dropbox 已經獲得了數十萬使用者——雖然與後來的百萬用戶相比只是個開端。它證明了一件事：雲端儲存不是一個功能，而是一個平台。

## 延伸閱讀

- [Dropbox - Wikipedia](https://zh.wikipedia.org/wiki/Dropbox)
- [Drew Houston 的 Y Combinator 演講](https://www.ycombinator.com/library/4C-how-dropbox-started)
