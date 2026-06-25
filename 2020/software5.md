# Windows 10 on ARM 與 x64 模擬

## ARM 版 Windows 的演進

隨著 Apple M1 的問世和 ARM 伺服器處理器的成熟，ARM 版 Windows 在 2020 年變得更加重要。Microsoft 在 2017 年就已經推出了 Windows 10 on ARM，但僅支援 32 位元 x86 應用的模擬，這極大限制了它的實用性。

## x64 模擬的重大突破

2020 年 12 月，Microsoft 宣布 Windows 10 on ARM 將支援 x64 應用的模擬——這是一項長久以來被使用者期待的關鍵功能。x64 模擬讓大量現有的 64 位元 Windows 應用可以在 ARM 裝置上執行。

這項技術類似於 Apple 的 Rosetta 2——在指令層面進行動態二進位轉譯，將 x86-64 指令轉換為 ARM64 指令。雖然轉譯會帶來一定的性能損耗（通常在 70-85% 的原生性能之間），但它極大地擴展了 ARM 版 Windows 的軟體生態系統。

## 硬體合作夥伴

2020 年，ARM 版 Windows 裝置的生態也在擴展：

- **Microsoft Surface Pro X**：搭載 Microsoft SQ1/SQ2 處理器（與 Qualcomm 合作開發）
- **Lenovo ThinkPad X13s**：搭載 Qualcomm Snapdragon 8cx Gen 3
- **Samsung Galaxy Book S**：配備 Snapdragon 8cx

然而，這些裝置面臨的挑戰仍然存在：性能與同價位的 x86 競爭對手還有差距，且部分驅動程式和應用仍然無法正常工作。

## 未來展望

Windows on ARM 的發展在 2020 年獲得了新的動力——Apple M1 的成功證明了 ARM PC 的巨大潛力。Microsoft 持續改進 x64 模擬的性能，而 Qualcomm 則在 2020 年收購了 Nuvia（由 Apple 前晶片設計師創立的公司），為下一代 Windows on ARM 處理器做準備。
