# B 語言：UNIX 的系統程式語言前身

## 從 BCPL 到 B

在 UNIX 開發的初期，Ken Thompson 和 Dennis Ritchie 發現組合語言編寫作業系統的效率太低。他們需要一種高階語言來加速開發。

Thompson 在 1970 年設計了 B 語言，它的前身是 Martin Richards 在 1967 年開發的 BCPL（Basic Combined Programming Language）。Thompson 簡化了 BCPL 的語法，去掉了許多複雜的特性，創造了一種輕量級的系統程式語言。

## B 語言的特徵

B 語言非常簡潔——核心語法只有幾十個關鍵字。它的型別系統非常薄弱，基本上只有一種資料型別：機器字（word）。所有變數都視為機器的「儲存單元」，型別轉換幾乎完全由程式設計師負責。

一個典型的 B 程式片段：

```
main() {
  auto a, b, c;
  a = 1;
  b = 2;
  c = a + b;
  printf("%d*n", c);
}
```

B 語言支援自動變數（auto）、全域變數、指標運算和基本的控制流程結構。它沒有型別檢查，所有算術都是機器位元運算。

## 語言設計的折衷

B 語言的簡潔來自於對 PDP-7 和 PDP-11 硬體的直接映射。它的指標可以直接操作記憶體位址，陣列和指標幾乎沒有區別——這些特性後來全部繼承到了 C 語言中。

但 B 語言缺乏對浮點數的支援，型別檢查幾乎不存在，這在開發複雜系統時成為重大障礙。

## 通往 C 語言的橋樑

B 語言直接啟發了 Dennis Ritchie 在 1972 年設計的 C 語言。C 語言在 B 的基礎上增加了型別系統、結構體、union 等特性，同時保持了直接操作記憶體的能力。UNIX 內核在 1973 年用 C 重寫，這是第一個用高階語言實現的作業系統。

## 延伸閱讀

- [B 程式語言 - Wikipedia](https://en.wikipedia.org/wiki/B_(programming_language))
- [Ken Thompson - Wikipedia](https://en.wikipedia.org/wiki/Ken_Thompson)
