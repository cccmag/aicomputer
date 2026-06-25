# Hadoop 概念雛形：分散式運算

## 搜尋引擎的挑戰

2002 年，Doug Cutting（Lucene 搜尋引擎的作者）和 Mike Cafarella（華盛頓大學研究生）啟動了 Nutch 專案——一個開放原始碼的 Web 搜尋引擎。他們的目標是建立一個可以與商用搜尋引擎競爭的開源替代方案。

Nutch 在初期成功地在單台機器上索引了約 100 萬個頁面——但他們遇到了規模化的瓶頸。當時的網際網路已經有大約 170 萬個網站，而且 Google 已經在索引數十億個頁面。Nutch 的架構無法擴展到這個規模。

## 從 Google 論文中找到答案

2002 到 2003 年間，Cutting 和 Cafarella 讀到了 Google 在 2001 年發表的分散式資料儲存論文——Google File System。這篇論文描述了 Google 如何在大量廉價的消費級硬體上建立可靠的分散式檔案系統。

他們意識到，這個架構正是解決 Nutch 規模化問題的關鍵。如果 Nutch 的索引可以分散在數百台機器上處理，那麼理論上它可以擴展到任何規模。

## 奠基概念

Nutch 專案在 2002 年開始建立的概念，後來演化為 Hadoop：

**分散式儲存**：將資料分割成區塊並複製到多台機器上，以實現容錯和高可用性

**資料本地化計算**：將計算任務移動到資料所在的位置，而不是將資料移動到計算節點——這是大規模資料處理的關鍵原則

**批次處理模型**：專為大規模資料的批次處理（而非即時處理）設計的架構

**開放原始碼**：與 Google 的專有實作不同，Nutch/Hadoop 的目標是建立一個任何人都可以使用和改進的開源方案

## 歷史意義

2002 年的 Nutch 專案是 Hadoop 的起點。雖然「Hadoop」這個名字要到 2006 年才出現（Doug Cutting 以他兒子的黃色大象填充玩具命名），但分散式儲存和運算的核心概念已經在 2002 年的 Nutch 設計中確立。

Hadoop 後來成為大數據時代的關鍵基礎設施，被 Yahoo、Facebook、Twitter 等公司廣泛採用。

## 延伸閱讀

- [Hadoop 歷史 - HPCWire](https://www.hpcwire.com/2015/04/15/from-spiders-to-elephants-the-history-of-hadoop/)
- [Nutch - Wikipedia](https://en.wikipedia.org/wiki/Nutch)
