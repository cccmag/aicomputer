# 3dfx Voodoo：3D 繪圖加速卡元年

## 從軟體到硬體渲染

1995 年 11 月 6 日，3dfx Interactive 發表了 Voodoo Graphics——第一款消費級 3D 繪圖加速卡。在此之前，3D 遊戲完全依賴 CPU 進行軟體渲染，效能和畫質都極其有限。

Voodoo 不是完整的顯示卡，而是需要與現有的 2D 顯示卡協同運作的子卡（add-on card）。使用者需要將顯示器的訊號先送入 Voodoo，再送到 2D 顯示卡——Voodoo 只處理 3D 運算，2D 則交給原有的顯示卡。

## 技術規格

Voodoo 由兩顆核心晶片組成：

- **FBI (Frame Buffer Interface)**：負責幀緩衝區管理
- **TMU (Texture Mapping Unit)**：負責紋理映射，每個晶片支援一條管線

主要規格：
- 支援 640x480 和 800x600 解析度
- 每秒可處理 45-50 MB 紋理資料
- 支援雙線性濾波（bilinear filtering）
- 支援 alpha 混合（透明度）
- 支援抗鋸齒（anti-aliasing）

## 遊戲產業的催化劑

Voodoo 的殺手級應用是 GLQuake——id Software 的 John Carmack 為 Quake 開發的 OpenGL 移植版本。GLQuake 在 Voodoo 上的表現遠超軟體渲染的 Quake，紋理更清晰、幀率更穩定。

之後的 Tomb Raider（蘿拉·卡芙特）也使用了 Voodoo 加速。3D 遊戲從此不再是軟體渲染的天下。

## 延伸閱讀

- [3dfx Voodoo - Wikipedia](https://en.wikipedia.org/wiki/3dfx_Interactive)
- [Voodoo Graphics - Wikipedia](https://en.wikipedia.org/wiki/Voodoo_Graphics)
- [3Dfx Voodoo 歷史 - FilFreak](https://www.filfre.net/)
