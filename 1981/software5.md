# 組合語言與編譯器工具的成熟

## 8086/8088 組合語言的崛起

隨著 IBM PC 使用 Intel 8088 處理器，x86 組合語言成為個人電腦上最重要的底層開發工具。Intel 提供了 MASM（Macro Assembler）作為官方組譯器。此外，Microsoft 也推出了自己的組譯器和連結器。

x86 架構的 segmented 記憶體模型——使用 CS、DS、SS、ES 等區段暫存器加上偏移位址來定址——對程式設計師來說是個挑戰。但組合語言的掌控力是無可比擬的：直接操作硬體、最佳化執行速度、最小化程式大小。

## 高階語言的成熟

1981 年，個人電腦上的高階語言編譯器也在快速成熟：
- **Microsoft BASIC**：直譯器版本是 IBM PC 內建語言
- **Microsoft FORTRAN-80**：科學計算領域的重要工具
- **Microsoft COBOL**：商業應用開發
- **Pascal**：特別是 UCSD Pascal，因其可攜性好而在教育領域受歡迎

這些語言工具與 MS-DOS 的組合，形成了一套完整的軟體開發環境——編輯器、編譯器、連結器、除錯器。1981 年的開發者已經可以使用現代軟體工程的基本工具鏈。

## 延伸閱讀

- [x86 組合語言 - Wikipedia](https://en.wikipedia.org/wiki/X86_assembly_language)
- [Microsoft MASM - Wikipedia](https://en.wikipedia.org/wiki/Microsoft_Macro_Assembler)
