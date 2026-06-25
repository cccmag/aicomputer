# Google Chrome 與瀏覽器大戰

## 瀏覽器市場的變革

Chrome 在 9 月發布時，瀏覽器市場由 Internet Explorer 主導（約 72%），Firefox 是最大的挑戰者（約 20%），Safari 約 6%，Opera 約 1%。

Chrome 的第一個測試版雖然只佔有極小的市場比例，但它的技術優勢——特別是 V8 引擎的速度——迅速在開發者社群中建立了口碑。開發者開始注意到 Chrome 的 JavaScript 效能比其他瀏覽器快了數倍。

## 瀏覽器引擎的多樣化

Chrome 的出現也加劇了瀏覽器引擎的多樣化趨勢。雖然 Chrome 使用 WebKit 渲染引擎，但它的 JavaScript 引擎 V8 是完全獨立的。這意味著網頁開發者需要測試的瀏覽器組合增加了：

- **Internet Explorer**：Trident 渲染引擎 + JScript
- **Firefox**：Gecko 渲染引擎 + SpiderMonkey
- **Safari**：WebKit 渲染引擎 + JavaScriptCore
- **Chrome**：WebKit 渲染引擎 + V8

這個組合最終導致了後續數年的瀏覽器效能戰爭——每家都在 JavaScript 執行速度和網頁渲染方面不斷優化。

## 延伸閱讀

- [Chrome 發布 - Google Blog](https://googleblog.blogspot.com/2008/09/google-chrome-beta.html)
- [瀏覽器大戰歷史](https://en.wikipedia.org/wiki/Browser_wars)
