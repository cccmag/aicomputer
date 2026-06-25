# CAD 工具：用電腦設計電腦

## 積體電路的設計危機

1966 年，積體電路已經從少數幾個電晶體發展到數百個邏輯閘的規模。當工程師可以將越來越多的電晶體塞進一顆晶片時，一個新的問題出現了——人工設計變得越來越困難且容易出錯。

IBM 的 James Koford 和他的同事們在 IBM 菲什基爾工廠率先開發了解決方案：電腦輔助設計（CAD）工具。他們的系統能夠在圖形顯示器上捕捉 SLT 混合電路模組的設計、自動檢查錯誤，並將設計資訊轉換為遮罩圖案——這是電子設計自動化（EDA）的濫觴。

## FAIRSIM 與後續發展

Koford 後來加入 Fairchild R&D，與 Hugh Mays、Ed Jones 等人合作，將這套方法應用到單石積體電路的設計中。他們的努力創造了一系列重要的 EDA 工具：

- **FAIRSIM**：邏輯模擬器，能夠在製造之前驗證電路的正確性
- **測試程式產生器**：自動產生用於測試晶片製造缺陷的測試向量
- **佈局與繞線軟體**：自動化閘陣列和標準單元的擺放與連線

這些工具奠定了接下來數十年 EDA 產業的基礎。

## 1966 年 FJCC 論文

1966 年秋季，Koford、Sporzynski 和 Strickland 在 Fall Joint Computer Conference 上發表了題為「Using a Graphic Data Processing System to Design Artwork for Manufacturing Hybrid Integrated Circuits」的論文（pp. 229-246），詳細描述了他們在 IBM 菲什基爾的圖形資料處理系統。這篇論文成為 EDA 領域的重要里程碑。

## SPICE 的前奏

在同一時期，加州大學柏克萊分校的 Larry Nagel 和 Donald Pederson 正在開發 SPICE（Simulation Program with IC Emphasis）電路模擬程式的前身。雖然 SPICE 要到 1973 年才正式發表，但 1966 年的 CAD 工具開發為 SPICE 的誕生鋪平了道路。

## 從 CAD 到 EDA 產業

1966 年的 CAD 工具最終演變為數百億美元的 EDA 產業：

- **Cadence** 和 **Synopsys** 等公司的商業邏輯合成套件
- 設計規則檢查（DRC）和佈局與繞線（P&R）工具
- 時序分析、功耗分析、訊號完整性分析等先進功能

如果沒有 1966 年這些先驅者的工作，摩爾定律的持續推進將因設計生產力的瓶頸而停滯。

## 延伸閱讀

- [1966: Computer Aided Design Tools Developed for ICs - CHM](https://www.computerhistory.org/siliconengine/computer-aided-design-tools-developed-for-ics/)
- [EDA 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Electronic_design_automation)
- [SPICE - Wikipedia](https://en.wikipedia.org/wiki/SPICE)
