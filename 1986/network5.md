# Brain 病毒：MS-DOS 惡意程式的開端

## 來自巴基斯坦的驚喜

1986 年 1 月，Brain 病毒被發現——這是第一個針對 IBM PC 相容電腦的電腦病毒，也是第一個在 MS-DOS 平台上大規模傳播的惡意軟體。

Brain 由巴基斯坦 Lahore 的兩兄弟 Basit Farooq Alvi 和 Amjad Farooq Alvi 編寫。他們經營一家名為 Brain Computer Services 的電腦商店，開發這個病毒的初衷是追蹤盜版軟體——病毒會顯示被盜版軟體的用戶的電話號碼，誘使他們打電話來「尋求協助」。

## 技術特徵

Brain 是一個開機磁區病毒，透過軟碟傳播。它使用了一些當時相當先進的技術：

**隱身（stealth）技術**：當系統嘗試讀取被感染的開機磁區時，病毒會攔截讀取請求並返回原始的、未感染的開機磁區內容。

**卷標（volume label）**：受感染磁碟的卷標會被改為「©Brain」。

**感染檢測**：病毒會檢查磁碟上是否已經有感染標記，避免重複感染。

## 影響與遺產

Brain 病毒造成的實際損害很小——它不會刪除檔案或破壞資料——但它的心理影響極大。Brain 讓數百萬 PC 使用者第一次意識到：軟體可以自我複製、可以在使用者不知情的情況下在機器之間傳播。

Brain 的出現引發了第一波防毒軟體市場的成長。1980 年代末期，McAfee、Norton 和 Dr. Solomon 等防毒產品相繼出現。

## 延伸閱讀

- [Brain 病毒 - Wikipedia](https://en.wikipedia.org/wiki/Brain_(computer_virus))
- [電腦病毒歷史 - Wikipedia](https://en.wikipedia.org/wiki/Timeline_of_computer_viruses_and_worms)
