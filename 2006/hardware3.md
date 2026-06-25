# PlayStation 3：Cell 處理器的豪賭

## 複雜的野心

2006 年 11 月 11 日（日本）和 11 月 17 日（北美），Sony 推出了 PlayStation 3。PS3 的開發代號為「Cell」——這不僅是一個處理器名稱，更代表了 Sony 對運算未來的願景。

Cell 處理器由 IBM、Toshiba、Sony 三家公司聯合開發，於 2001 年啟動。Cell 的架構極其特殊：
- **1 個 PowerPC PPE（Power Processing Element）**：通用核心，負責作業系統和任務調度
- **8 個 SPE（Synergistic Processing Elements）**：專用向量處理核心（實際使用 7 個，1 個作為備援）
- **彈性匯流排**（EIB）：SPE 之間與 SPE-PPE 之間的高速互連
- **XDR 記憶體**：由 Rambus 開發的高頻寬記憶體技術

Cell 在理論上的浮點運算能力達到 230 GFLOPS——遠超過當時的任何桌上型處理器。理論上，Cell 非常適合物理模擬、AI、圖形處理等需要密集平行運算的任務。

## 現實的挑戰

Cell 的開發難度遠超預期：
- **SPE 的程式設計極為困難**：SPE 不是標準的 CPU 核心，開發者必須手動管理本機儲存（256KB Local Store）和 DMA 傳輸
- **統一著色器架構的缺失**：RSX Reality Synthesizer GPU（NVIDIA RSX）沒有採用統一著色器架構（這個 Xbox 360 已經使用了）
- **高成本**：Cell 的晶片面積龐大，良率低，導致 PS3 初版售價高達 599 美元
- **熱量問題**：PS3 早期型號產生的熱量相當可觀，導致了後來的 YLOD（黃燈故障）問題

## 延遲上市的代價

PS3 比 Xbox 360 晚了一年上市。這個差距讓 Sony 付出了高昂代價——到 2006 年底，Xbox 360 已銷售超過 1,000 萬台。PS3 最終在第七代主機競爭中排名第三（約 8700 萬台），低於 Wii 和 Xbox 360。但 PS3 的 Cell 處理器在科學運算領域找到了一個意想不到的應用——多所大學和研究機構將多台 PS3 串聯成叢集，用於蛋白質折疊模擬和天文資料處理。
