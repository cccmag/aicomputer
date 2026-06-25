# Pascal 語言的誕生：結構化程式設計的典範

## 從 ALGOL 到 Pascal

Niklaus Wirth 在 1968 年從史丹佛回到蘇黎世聯邦理工學院（ETH Zurich）後，開始設計一種新的程式語言。他的目標是創造一種適用於商業和科學應用、同時能教導學生結構化程式設計的語言。這個語言以 17 世紀法國數學家 Blaise Pascal 命名。

1970 年，Wirth 完成了第一個 Pascal 編譯器，並發表了語言定義文件。Pascal 的設計基於 ALGOL 60，但做了重要的簡化和擴充。

## 語言設計原則

Pascal 的核心設計理念是「簡潔即力量」。它引入了清晰的資料結構定義：

```
type
  Person = record
    name: string[50];
    age: integer;
    salary: real;
  end;
```

Pascal 強調強型別檢查，幾乎不允許隱含型別轉換。它提供了列舉型別、子界型別、記錄（record）、陣列、集合、檔案等豐富的資料結構，所有這些都在嚴格的型別系統下運作。

## 程式設計方法的革命

Pascal 成為結構化程式設計（structured programming）運動的主要載具。Wirth 在 1971 年發表了經典論文「Program Development by Stepwise Refinement」（逐步求精的程式開發），闡述了如何從頂層規格逐步分解為具體程式碼的方法。

```
program HelloWorld;
begin
  writeln('Hello, World!');
end.
```

這段簡潔的程式碼展示了 Pascal 清晰易讀的語法。

## 深遠影響

Pascal 在 1970 和 1980 年代成為大學程式設計課程的首選語言。它的影響無遠弗屆：Apple 的 Lisa 和早期 Macintosh 的開發環境大量使用 Pascal；Borland 的 Turbo Pascal（1983）讓 PC 上的程式開發變得快速且負擔得起。Wirth 後來開發的 Modula-2 和 Oberon 延續了同樣的設計哲學。他於 1984 年獲得圖靈獎。

## 延伸閱讀

- [Pascal 程式語言 - Wikipedia](https://en.wikipedia.org/wiki/Pascal_(programming_language))
- [Niklaus Wirth - Wikipedia](https://en.wikipedia.org/wiki/Niklaus_Wirth)
