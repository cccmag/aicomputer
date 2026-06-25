# troff 排版系統：電子出版的起源

## 文書處理的實際需求

UNIX 從 PDP-7 移植到 PDP-11 後，貝爾實驗室為它找到了一個實際的應用場景：支援專利部門的文件處理。三位專利部門的打字員需要一個高效的文字編輯和排版系統。

在這背景下，Joe Ossanna 於 1971 年為 UNIX 開發了 **roff**——一種文字排版工具。它的名字來自「run off」（快速產出）這個動詞。roff 的輸入是純文字檔案，內嵌格式指令，輸出是準備好列印的格式化文字。

## roff 的工作原理

使用者撰寫一個包含排版指令的文字檔案：

```
.de PP
.sp 1
.ti 3
..
.PP
This is a paragraph with indentation.
```

roff 處理器解析這些指令，產生格式化的輸出。它支援段落縮排、對齊、分頁、行距調整等功能。

## 通往 troff 的路徑

Ossanna 的 roff 很快演化為 **nroff**（new roff），用於終端機和行式印表機。隨後 Ossanna 開發了 **troff**（typesetter roff），專為 Graphic Systems 公司的照相排版機設計。troff 支援多種字型、字體大小變化、上標/下標等排版功能。

troff 後來由 Brian Kernighan 接手維護，並加入了對 PostScript 的支援。

## 深遠影響

troff 是「文件即程式碼」理念的早期實踐。在圖形使用者介面出現之前，這是一種極有效率的工作方式。troff 的 man page 格式至今仍是 UNIX 和 Linux 系統中文件的標準格式。

## 延伸閱讀

- [Troff - Wikipedia](https://en.wikipedia.org/wiki/Troff)
- [UNIX 文書處理歷史](https://www.bell-labs.com/usr/dmr/www/1stEdman.html)
