# JavaScript/TypeScript 崛起與 Deno 1.0 開發

## TypeScript 的加速普及

2019 年，TypeScript 迎來了爆發式成長。根據 JetBrains 的開發者調查，TypeScript 的使用率從 2017 年的 12% 成長到 2019 年的 27%。TypeScript 3.x 系列引入了多項重要功能：Project References（3.0，改善大型專案編譯速度）、optional chaining（3.7）和 nullish coalescing（3.7）。

TypeScript 的成功在於它在 JavaScript 的靈活性與靜態型別的可靠性之間取得了平衡。大型專案（如 VS Code、Angular、Deno）全面採用 TypeScript，提升了程式碼品質和開發效率。

## deno 的開發與 1.0 發布

Ryan Dahl——Node.js 的原始創造者——在 2018 年開始了 Deno 專案，並於 2019 年積極開發。Deno 旨在解決 Node.js 設計中的多項遺留問題：

- **安全性**：Deno 預設在沙盒中執行，需要明確授予檔案、網路、環境變數等存取權限
- **現代 JavaScript**：原生支援 TypeScript 和 ES Modules
- **去中心化套件管理**：不再有 npm 中心和 node_modules，透過 URL 直接導入模組
- **標準函式庫**：提供經過審查的標準函式庫，減少對第三方套件的依賴

## 影響與爭議

Deno 的出現引發了 JavaScript 社群對 Node.js 未來方向的討論。雖然 Deno 在技術上更現代化，但 Node.js 的生態系統規模和 npm 的龐大套件庫使得遷移成本極高。截至 2019 年底，Deno 尚未達到 1.0，但其設計理念已開始影響 Node.js 本身的發展（如 Node.js 對 ES Modules 的支援）。
