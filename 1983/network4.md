# Elk Cloner：第一個在野外傳播的電腦病毒

## 15 歲高中生的惡作劇

1983 年（實際散布始於 1982 年初），匹茲堡 Mt. Lebanon 高中的 15 歲學生 Rich Skrenta 編寫了 Elk Cloner——歷史上第一個在「野外」（in the wild）大規模傳播的個人電腦病毒。

Skrenta 是 Apple II 程式高手，以在朋友之間惡作劇聞名。他經常修改遊戲磁片，讓朋友執行時出現搞怪的訊息。當朋友們開始拒絕收他的磁片時，Skrenta 決定想一個不需要實體接觸就能整人的方法：讓程式自己複製自己。

## 技術原理

Elk Cloner 是一個開機磁區病毒（boot sector virus）。當使用感染的磁片開機時，病毒會複製到電腦記憶體中。之後每次使用者插入新的磁片，病毒就會將自己寫入那張磁片的開機磁區。

每隔 50 次開機，病毒會顯示一首詩：
```
Elk Cloner: The program with a personality
It will get on all your disks
It will infiltrate your chips
Yes, it's Cloner!
```

## 歷史意義

Elk Cloner 本身沒有破壞性，但它開啟了資訊安全的新紀元。1983 年稍晚，南加州大學的 Fred Cohen 在他的博士論文中正式定義了「電腦病毒」這個術語。Elk Cloner 的出現比 IBM PC 上的 Brain 病毒早了四年，為所有後來的惡意軟體鋪平了道路。

## 延伸閱讀

- [Elk Cloner - Wikipedia](https://en.wikipedia.org/wiki/Elk_Cloner)
- [Rich Skrenta - Wikipedia](https://en.wikipedia.org/wiki/Rich_Skrenta)
