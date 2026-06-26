# 數學之鏈：資訊科技背後的數學基礎

**資訊科技年鑑　1950-2025**

編輯：[陳鍾誠](https://csie.nqu.edu.tw/p/404-1038-2377.php?Lang=zh-tw)

---

每一項改變世界的技術，背後都站著一條數學定理。從你口袋裡的手機到雲端的大型語言模型，從網路搜尋到 GPS 導航——若抽離了數學，整座科技大廈將轟然倒塌。這份文件揭示那些隱藏在資訊科技背後的數學力量。

## 1. 從布林代數到數位世界

沒有布林，就沒有電腦——這句話毫不誇張。

$$
\text{布林代數} \xrightarrow{\text{1854}} \text{邏輯閘} \xrightarrow{\text{1938}} \text{數位電路} \xrightarrow{\text{1945}} \text{儲存程式電腦}
$$

```
布林代數 (Boole, 1854)
  └→ 邏輯閘理論 (Shannon, 1938)
       ├→ 數位電路設計
       │    ├→ 算術邏輯單元 (ALU)
       │    ├→ 記憶體位址解碼
       │    └→ 處理器控制單元
       │         └→ 馮紐曼架構 (1945)
       │              ├→ ENIAC (1946) → SEAC (1950)
       │              ├→ IBM System/360 (1964)
       │              │    └→ 相容性概念 → 產業標準
       │              ├→ 微處理器 (1971)
       │              │    ├→ Intel 4004 → 8080 → x86 架構
       │              │    └→ ARM 架構 (1985) → Apple M1 (2020)
       │              └→ GPU 運算 (2007)
       │                   └→ 深度學習革命
       └→ 布林運算最佳化
            ├→ 邏輯合成 → EDA 工具
            └→ 硬體描述語言 (Verilog/VHDL)
```

核心公式：**任何邏輯函數都可以用 AND、OR、NOT 三種運算來表達**

$$
F(x, y, z) = (x \land y) \lor (\lnot y \land z)
$$

**推論**：沒有 1854 年布林的邏輯代數，香農就無法在 1938 年用繼電器實現邏輯閘，也就沒有數位電路。沒有數位電路，就沒有電腦—從 1950 年的 SEAC 到 2025 年的 Apple M5，每一顆晶片本質上都是布林運算的組合。

- [維基百科：布林代數](https://zh.wikipedia.org/wiki/布爾代數)
- [維基百科：邏輯閘](https://zh.wikipedia.org/wiki/邏輯閘)
- [資訊科技年鑑 1950：SEAC 首部儲存程式計算機](https://github.com/cccmag/aicomputer/blob/master/1950/hardware1.md)

---

## 2. 從傅立葉分析到數位媒體

你聽的 MP3、看的 JPEG、打的電話—全都靠傅立葉變換。

$$
f(t) = \sum_{n=-\infty}^{\infty} c_n e^{i n \omega t}
$$

```
傅立葉級數 (Fourier, 1822)
  └→ 傅立葉變換
       ├→ 離散傅立葉變換 (DFT)
       │    ├→ 快速傅立葉變換 (FFT, Cooley-Tukey, 1965)
       │    │    ├→ JPEG 壓縮 (1992)
       │    │    │    └→ DCT (離散餘弦變換)
       │    │    │         └→ 數位照片、網路圖片
       │    │    ├→ MP3 壓縮 (1993)
       │    │    │    └→ MDCT (改進離散餘弦變換)
       │    │    │         └→ 數位音樂革命
       │    │    └→ 數位通信 (OFDM)
       │    │         ├→ Wi-Fi (1997)
       │    │         ├→ 4G/LTE (2009)
       │    │         └→ 5G (2019)
       │    └→ 頻譜分析
       │         ├→ 數據機 (1950s) → 撥接上網
       │         └→ 語音辨識
       └→ 拉普拉斯變換
            └→ 控制理論
                 └→ 自動駕駛 PID 控制
```

從時域到頻域，傅立葉變換讓我們用全新的視角看世界。

$$
X_k = \sum_{n=0}^{N-1} x_n \cdot e^{-2\pi i k n / N}
$$

**推論**：沒有傅立葉分析，就沒有 JPEG 和 MP3——你的手機將無法儲存照片或音樂，YouTube 和 Spotify 根本不可能存在。沒有 OFDM，就沒有 Wi-Fi 和 4G/5G——行動網路也將不復存在。

- [維基百科：傅立葉變換](https://zh.wikipedia.org/wiki/傅里叶变换)
- [維基百科：JPEG](https://zh.wikipedia.org/wiki/JPEG)
- [維基百科：MP3](https://zh.wikipedia.org/wiki/MP3)
- [資訊科技年鑑 1992：JPEG 標準化](https://github.com/cccmag/aicomputer/blob/master/1992/network2.md)

---

## 3. 從線性代數到人工智慧

深度學習的本質，就是一連串的矩陣乘法。

$$
\mathbf{y} = \sigma(\mathbf{W}\mathbf{x} + \mathbf{b})
$$

```
線性代數
  ├→ 矩陣運算
  │    ├→ 圖形處理 (GPU)
  │    │    ├→ 3D 渲染 → 電玩遊戲
  │    │    ├→ CUDA (2007) → GPU 通用運算
  │    │    │    └→ 深度學習訓練
  │    │    └→ 電腦視覺 (卷積)
  │    ├→ 神經網路
  │    │    ├→ 感知機 (Rosenblatt, 1957)
  │    │    │    └→ 多層感知機 (MLP)
  │    │    │         └→ 反向傳播 (Rumelhart, 1986)
  │    │    │              └→ 深度學習 (Hinton, 2006)
  │    │    │                   ├→ 卷積神經網路 (CNN)
  │    │    │                   │    ├→ 影像分類 → ImageNet (2012)
  │    │    │                   │    └→ 自動駕駛
  │    │    │                   ├→ Transformer (Vaswani, 2017)
  │    │    │                   │    ├→ BERT (2018)
  │    │    │                   │    └→ GPT 系列 (2018-2025)
  │    │    │                   │         └→ ChatGPT (2022)
  │    │    │                   │              └→ AI 代理 (2025)
  │    │    │                   └→ AlphaFold (2021)
  │    │    └→ 嵌入 (Embedding)
  │    │         └→ Word2Vec (2013)
  │    │              └→ 語義搜尋
  │    └→ 奇異值分解 (SVD)
  │         ├→ 推薦系統 → Netflix / YouTube
  │         └→ 搜尋引擎 → PageRank 變體
  └→ 特徵值與特徵向量
       ├→ 主成分分析 (PCA)
       │    └→ 維度縮減 → 數據科學
       └→ PageRank (Google, 1998)
            └→ 搜尋引擎霸權
```

$$
\mathbf{W}^{(l+1)} = \mathbf{W}^{(l)} - \eta \frac{\partial \mathcal{L}}{\partial \mathbf{W}^{(l)}}
$$

**推論**：沒有線性代數的神經網路，本質上就是一連串的矩陣乘法加上非線性激活函數。沒有 GPU 的大規模矩陣運算，深度學習就無法訓練。沒有 Transformer 中的注意力機制（本質是查詢-鍵-值的線性變換），就沒有 ChatGPT。2025 年的 AI 代理革命，源頭可追溯到 1957 年感知機的矩陣運算。

- [維基百科：線性代數](https://zh.wikipedia.org/wiki/线性代数)
- [維基百科：神經網路](https://zh.wikipedia.org/wiki/人工神经网络)
- [維基百科：Transformer](https://zh.wikipedia.org/wiki/Transformer_(模型))
- [資訊科技年鑑 2017：Attention Is All You Need](https://github.com/cccmag/aicomputer/blob/master/2017/software2.md)

---

## 4. 從機率論到機器學習

機器學習的每一個環節——從貝氏分類器到大型語言模型——都建構在機率論之上。

$$
P(A|B) = \frac{P(B|A)P(A)}{P(B)}
$$

```
機率論
  ├→ 貝氏統計
  │    ├→ 貝氏分類器 (Naive Bayes)
  │    │    └→ 垃圾郵件過濾
  │    ├→ 馬可夫鏈
  │    │    ├→ 馬可夫決策過程 (MDP)
  │    │    │    └→ 強化學習
  │    │    │         ├→ AlphaGo (2016)
  │    │    │         └→ 機器人控制
  │    │    └→ 隱馬可夫模型 (HMM)
  │    │         └→ 語音辨識 → Siri (2011)
  │    └→ 貝氏網路
  │         └→ 專家系統 → 醫療診斷
  ├→ 最大似然估計 (MLE)
  │    ├→ 迴歸分析
  │    └→ 深度學習損失函數
  │         └→ 交叉熵 → 分類訓練
  ├→ 蒙地卡羅方法
  │    ├→ 粒子濾波 → GPS、機器人定位
  │    └→ MCMC → 貝氏統計計算
  └→ 中央極限定理
       └→ 統計推論 → A/B 測試 → 產品決策
```

**大型語言模型的本質**：下一個詞的條件機率預測

$$
P(w_t | w_{1}, w_{2}, \ldots, w_{t-1})
$$

**推論**：沒有機率論的貝氏定理，就沒有垃圾郵件過濾器。沒有馬可夫鏈，就沒有強化學習和 AlphaGo。沒有最大似然估計，就沒有訓練神經網路的數學框架。ChatGPT 和 2025 年的 AI 代理，「智慧」的外衣下只是一連串精巧的條件機率計算。

- [維基百科：貝氏定理](https://zh.wikipedia.org/wiki/贝叶斯定理)
- [維基百科：馬可夫鏈](https://zh.wikipedia.org/wiki/马尔可夫链)
- [維基百科：強化學習](https://zh.wikipedia.org/wiki/強化学习)
- [資訊科技年鑑 2016：AlphaGo 擊敗李世乭](https://github.com/cccmag/aicomputer/blob/master/2016/software1.md)

---

## 5. 從數論到密碼學

每一筆網路交易、每一則加密訊息、每一枚加密貨幣——都依賴數論。

$$
c \equiv m^e \pmod{n}
$$

```
數論
  ├→ 質數理論
  │    ├→ RSA 加密 (Rivest-Shamir-Adleman, 1977)
  │    │    ├→ HTTPS / SSL/TLS
  │    │    │    └→ 電子商務 → Amazon (1994)
  │    │    └→ 數位簽章
  │    │         └→ 軟體信任 → 作業系統更新
  │    └→ 離散對數問題
  │         └→ Diffie-Hellman 金鑰交換 (1976)
  │              └→ 安全通信 → SSH, VPN
  ├→ 橢圓曲線理論
  │    └→ 橢圓曲線密碼學 (ECC, 1985)
  │         ├→ 比特幣 (2009)
  │         │    └→ 區塊鏈
  │         │         ├→ 加密貨幣 → 金融革命
  │         │         └→ 智能合約 → Ethereum (2015)
  │         └→ 現代 HTTPS → 更高效的金鑰交換
  └→ 哈希函數
       ├→ SHA 系列 → 密碼儲存
       └→ 工作量證明 (PoW)
            └→ 比特幣挖礦
```

**RSA 的安全性**：因數分解一個大整數 $n = p \times q$ 在計算上不可行。

$$
n = p \times q \quad p, q \text{ 為大質數} \quad \phi(n) = (p-1)(q-1)
$$

**推論**：沒有數論的質數理論，就沒有 RSA 加密。沒有 RSA 和 ECC，就沒有 HTTPS——你現在看的每一個網站都將不安全。沒有區塊鏈的密碼學基礎，就沒有 2009 年比特幣的誕生。Diffie 與 Hellman 在 2015 年獲得圖靈獎，表彰他們對公鑰密碼學的貢獻——數論在資訊科技中的地位由此可見。

- [維基百科：數論](https://zh.wikipedia.org/wiki/数论)
- [維基百科：RSA 加密演算法](https://zh.wikipedia.org/wiki/RSA加密算法)
- [維基百科：橢圓曲線密碼學](https://zh.wikipedia.org/wiki/椭圆曲线密码学)
- [資訊科技年鑑 2009：Bitcoin 創世區塊](https://github.com/cccmag/aicomputer/blob/master/2009/software1.md)

---

## 6. 從密碼學到數位信任

每一筆網路交易、每一則加密訊息、每一枚加密貨幣——都建立在密碼學之上。

$$
c \equiv m^e \pmod{n}
$$

```
密碼學
  ├→ 古典密碼 → 凱薩密碼 → Enigma → 破譯 → 電腦誕生
  ├→ 對稱式加密 → DES (1977) → AES (2001) → 檔案加密、磁碟加密
  ├→ 非對稱式加密 (公鑰密碼學)
  │    ├→ Diffie-Hellman 金鑰交換 (1976) → SSH, VPN, TLS 交握
  │    ├→ RSA (Rivest-Shamir-Adleman, 1977) → HTTPS → 電子商務
  │    │    └→ 數位簽章 → 程式碼簽署 → 軟體信任鏈
  │    └→ 橢圓曲線密碼學 ECC (1985)
  │         ├→ 比特幣 (2009) → 區塊鏈 → 加密貨幣革命
  │         │    └→ 智能合約 → Ethereum (2015) → DeFi → NFT
  │         └→ 現代 HTTPS → TLS 1.3 (2018) → 更高效的金鑰交換
  ├→ 哈希函數 → MD5 → SHA-1 → SHA-256/SHA-3
  │    ├→ 密碼儲存 → bcrypt → 身分驗證
  │    ├→ 數位指紋 → 檔案完整性 → 軟體更新驗證
  │    └→ 工作量證明 (PoW) → 比特幣挖礦 → 區塊鏈共識機制
  └→ 零知識證明 → zk-SNARKs → 隱私保護 → 區塊鏈擴容

RSA 安全性：因數分解 n = p × q 在計算上不可行。
區塊鏈：哈希鏈結 + 共識機制 = 去中心化信任。
```

**推論**：沒有 1976 年 Diffie 與 Hellman 的公鑰密碼學構想，就沒有 RSA。沒有 RSA 和 ECC，就沒有 HTTPS——網路電子商務將無法安全運作。沒有密碼學的哈希函數與數位簽章，就沒有 2009 年的比特幣和後續的區塊鏈革命。2015 年 Diffie 與 Hellman 獲得圖靈獎——這項技術從軍事機密變成了每個人每天使用的基礎設施。

- [維基百科：密碼學](https://zh.wikipedia.org/wiki/密码学)
- [維基百科：RSA 加密演算法](https://zh.wikipedia.org/wiki/RSA加密算法)
- [維基百科：區塊鏈](https://zh.wikipedia.org/wiki/区块链)
- [資訊科技年鑑 2009：Bitcoin 創世區塊](https://github.com/cccmag/aicomputer/blob/master/2009/software1.md)

---

## 7. 從圖論到網路時代

從 Google 搜尋、GPS 導航、到社群媒體的推薦——圖論無所不在。

$$
\text{PageRank}(u) = \sum_{v \in B_u} \frac{\text{PageRank}(v)}{L(v)}
$$

```
圖論 (Euler, 1736)
  ├→ 最短路徑
  │    ├→ Dijkstra 演算法 (1956)
  │    │    ├→ GPS 導航 → Google Maps
  │    │    └→ 網路路由 → OSPF 協定
  │    └→ A* 搜尋
  │         └→ 遊戲 AI → 自動尋路
  ├→ 最小生成樹
  │    └→ 網路設計 → 電路佈線
  ├→ 圖著色
  │    ├→ 頻率分配 → 無線通信
  │    └→ 暫存器分配 → 編譯器
  ├→ 網路流
  │    ├→ 最大流量 → 網路頻寬管理
  │    └→ 匹配理論 → 配對系統 (Uber)
  └→ 社群網路分析
       ├→ PageRank (Google, 1998)
       │    └→ 搜尋引擎 → 資訊檢索革命
       │         └→ Google 搜尋霸權 (2000-)
       ├→ 社群偵測 → Facebook 好友推薦 (2004)
       └→ 知識圖譜
            └→ Google Knowledge Graph (2012)
                 └→ 語意搜尋
```

**推論**：沒有圖論的 Dijkstra 最短路徑演算法，就沒有 GPS 導航。沒有 PageRank，就沒有 Google——1998 年的這項發明改變了人類獲取資訊的方式。沒有圖著色理論，無線通信的頻譜分配將陷入混亂。圖論是網路時代的隱藏語言。

- [維基百科：圖論](https://zh.wikipedia.org/wiki/图论)
- [維基百科：PageRank](https://zh.wikipedia.org/wiki/PageRank)
- [維基百科：Dijkstra 演算法](https://zh.wikipedia.org/wiki/戴克斯特拉算法)
- [資訊科技年鑑 1998：Google 公司成立](https://github.com/cccmag/aicomputer/blob/master/1998/software1.md)

---

## 8. 從資訊理論到數位通信

克勞德·香農在 1948 年發表的《通信的數學理論》開創了資訊時代。

$$
C = B \log_2(1 + \frac{S}{N})
$$

```
香農資訊理論 (Shannon, 1948)
  ├→ 資訊熵 H = -∑ p_i log₂ p_i
  │    ├→ 資料壓縮極限
  │    │    ├→ 霍夫曼編碼
  │    │    ├→ 算術編碼 → JPEG、影片壓縮
  │    │    └→ LZW 演算法 → GIF (1987)
  │    ├→ 交叉熵
  │    │    └→ 深度學習損失函數
  │    └→ 互信息
  │         └→ 特徵選擇 → 機器學習
  ├→ 通道容量 C = B log₂(1 + SNR)
  │    ├→ 數位通信理論
  │    │    ├→ 數據機 (1950s)
  │    │    └→ 寬頻技術 → ADSL、光纖
  │    └→ 無線通道
  │         ├→ Wi-Fi (1997)
  │         ├→ 3G (2001) → 4G/LTE (2009) → 5G (2019)
  │         └→ 藍牙 (2000)
  └→ 糾錯碼
       ├→ 漢明碼 (Hamming, 1950)
       │    └→ ECC 記憶體 → 伺服器可靠性
       ├→ 里德-所羅門碼 (Reed-Solomon, 1960)
       │    ├→ CD/DVD → 刮傷可讀
       │    └→ QR Code → 手機掃碼
       └→ LDPC 碼
            ├→ Wi-Fi (802.11n)
            └→ 5G NR
```

**推論**：沒有香農的資訊理論，就沒有資料壓縮——你的手機將無法儲存任何照片或音樂。沒有通道容量公式，我們不知道通信的極限在哪裡。沒有糾錯碼，CD 會因為刮傷而無法播放，衛星傳輸的信號會被雜訊淹沒。香農的理論是整個數位通信時代的基石。

- [維基百科：資訊理論](https://zh.wikipedia.org/wiki/信息论)
- [維基百科：香農](https://zh.wikipedia.org/wiki/克劳德·香农)
- [維基百科：糾錯碼](https://zh.wikipedia.org/wiki/纠错码)
- [資訊科技年鑑 1997：Wi-Fi 802.11 標準](https://github.com/cccmag/aicomputer/blob/master/1999/network2.md)

---

## 9. 從計算理論到電腦科學

圖靈機是電腦科學的起點——它定義了「什麼是可計算的」。

$$
\text{圖靈機} \equiv \text{通用計算模型}
$$

```
計算理論
  ├→ 圖靈機 (Turing, 1936)
  │    ├→ 圖靈完備概念
  │    │    ├→ 通用電腦 (Von Neumann, 1945)
  │    │    │    ├→ ENIAC (1946) → 現代計算機
  │    │    │    └→ 軟體概念誕生
  │    │    │         ├→ 作業系統 (1960s)
  │    │    │         ├→ 編譯器 → FORTRAN (1957)
  │    │    │         └→ 程式語言演化
  │    │    └→ 可計算性理論
  │    │         └→ 停機問題 → 程式驗證
  │    └→ 圖靈測試 (1950)
  │         └→ 人工智慧 (1956)
  │              └→ 深度學習 (2012)
  │                   └→ ChatGPT (2022)
  ├→ 計算複雜性理論
  │    ├→ P vs NP 問題
  │    │    ├→ 密碼學安全性基礎
  │    │    └→ 最佳化演算法
  │    ├→ Cook-Levin 定理 (1971)
  │    │    └→ NP-Complete 問題
  │    │         └→ Stephen Cook 獲得圖靈獎 (1982)
  │    └→ 非決定性計算
  │         └→ Michael Rabin 獲得圖靈獎 (1976)
  ├→ 形式語言與自動機
  │    ├→ 喬姆斯基階層 (Chomsky, 1956)
  │    │    ├→ 正規語言 → 正規表達式
  │    │    ├→ 上下文無關語言 → 程式語言語法
  │    │    └→ 編譯器設計基礎
  │    └→ 有限狀態機
  │         └→ 數位電路設計 → 所有硬體
  └→ λ 演算 (Church, 1930s)
       └→ 函數式程式設計
            ├→ LISP (1958) → John McCarthy 圖靈獎 (1971)
            └→ Haskell / Scala / 現代函數式語言
```

$$
\text{NP-Complete: 若任意一個 NP-Complete 問題可在多項式時間內解決，則所有 NP 問題皆可在多項式時間內解決}
$$

**推論**：沒有 1936 年圖靈的通用機概念，就沒有電腦科學。沒有計算複雜性理論，我們無法理解哪些問題可以高效解決、哪些問題本質上就是困難的。P vs NP 問題是電腦科學最大的未解之謎，它的答案將深刻影響密碼學與 AI 的未來。

- [維基百科：圖靈機](https://zh.wikipedia.org/wiki/图灵机)
- [維基百科：計算複雜性理論](https://zh.wikipedia.org/wiki/计算复杂性理论)
- [維基百科：P vs NP](https://zh.wikipedia.org/wiki/P/NP问题)
- [資訊科技年鑑 1950：圖靈測試](https://github.com/cccmag/aicomputer/blob/master/1950/software1.md)

---

## 10. 從微積分到 AI 訓練

微積分是工程與 AI 的語言——從梯度下降到反向傳播，深度學習的每一步都是微積分。

$$
\frac{d}{dx} \left( \frac{1}{2}mv^2 \right) = m \cdot \frac{dv}{dt} \cdot v = F \cdot v
$$

```
微積分
  ├→ 微分
  │    ├→ 變化率 → 物理學
  │    │    └→ 梯度 → 梯度下降法
  │    │         ├→ 線性迴歸 → 最小平方法
  │    │         ├→ 神經網路 → 反向傳播
  │    │         │    └→ 鏈鎖律 (Chain Rule)
  │    │         │         └→ 多層網路訓練
  │    │         └→ 深度學習 → 模型最佳化
  │    │              └→ GPT-3 (2020) → ChatGPT (2022)
  │    └→ 邊際分析
  │         └→ 工程最佳化 → 晶片設計
  ├→ 積分
  │    ├→ 面積、體積 → 工程設計
  │    └→ 數值積分
  │         └→ 電腦模擬 → 氣候模型
  └→ 變分法
       ├→ 最小作用量原理 → 物理學基礎
       └→ 最佳控制 → 火箭軌道
```

**梯度下降——機器學習的核心引擎**：

$$
\theta_{t+1} = \theta_t - \eta \nabla_{\theta} \mathcal{L}(\theta_t)
$$

**推論**：沒有微積分的梯度概念，就無法訓練神經網路——反向傳播演算法本質上就是鏈鎖律的應用。每一次大型語言模型的訓練，背後都是數十億次的梯度計算。從 1986 年反向傳播的重新發現，到 2025 年 AI 代理的崛起，微積分始終是 AI 進步的數學引擎。

- [維基百科：微積分](https://zh.wikipedia.org/wiki/微积分学)
- [維基百科：梯度下降法](https://zh.wikipedia.org/wiki/梯度下降法)
- [維基百科：反向傳播演算法](https://zh.wikipedia.org/wiki/反向传播算法)
- [資訊科技年鑑 1986：反向傳播演算法](https://github.com/cccmag/aicomputer/blob/master/1986/software2.md)

---

## 11. 從統計學到數據科學

統計學是數據時代的語言——從 A/B 測試到搜尋引擎評估，沒有統計就無法從數據中提取結論。

$$
\text{相關係數} \quad r = \frac{\sum{(x_i - \bar{x})(y_i - \bar{y})}}{\sqrt{\sum{(x_i - \bar{x})^2}\sum{(y_i - \bar{y})^2}}}
$$

```
統計學
  ├→ 描述統計
  │    ├→ 平均數、標準差
  │    │    └→ 品質管制 → Six Sigma → 製造業
  │    └→ 數據可視化
  │         └→ 儀表板 → 商業智慧
  ├→ 推論統計
  │    ├→ 假設檢定
  │    │    ├→ A/B 測試 → 產品設計 → Google、Facebook
  │    │    └→ 臨床試驗 → 藥物批准
  │    ├→ 信賴區間
  │    │    └→ 民調 → 政治決策
  │    └→ 迴歸分析
  │         ├→ 線性迴歸 → 預測模型
  │         └→ 邏輯迴歸 → 風險評估
  ├→ 實驗設計
  │    ├→ 隨機對照試驗 (RCT)
  │    │    └→ 醫學實證 → 實證醫學
  │    └→ 變異數分析 (ANOVA)
  │         └→ 農業實驗 → 綠色革命
  └→ 多變量分析
       ├→ 因子分析 → 心理測量
       └→ 聚類分析 → 市場區隔
```

**推論**：沒有統計學的假設檢定，就無法判斷藥物是否有效。沒有 A/B 測試，Google 和 Facebook 無法科學地優化產品。沒有迴歸分析，就無法建立預測模型。在資訊時代，統計學是數據科學的基礎語言。

- [維基百科：統計學](https://zh.wikipedia.org/wiki/统计学)
- [維基百科：假設檢定](https://zh.wikipedia.org/wiki/假设检验)
- [維基百科：迴歸分析](https://zh.wikipedia.org/wiki/回归分析)
- [資訊科技年鑑 2004：Web 2.0 時代的數據驅動產品](https://github.com/cccmag/aicomputer/blob/master/2004/software1.md)

---

## 12. 從幾何學到時空與影像

從 GPS 的相對論校正到 3D 渲染，從電腦視覺到晶片佈局——幾何學無所不在。

$$
ds^2 = -c^2 dt^2 + dx^2 + dy^2 + dz^2
$$

```
幾何學
  ├→ 歐幾里得幾何
  │    ├→ 計算機圖學
  │    │    ├→ 3D 渲染 → Pixar 電影、電玩
  │    │    │    ├→ 圖靈獎 2019: Catmull & Hanrahan
  │    │    │    └→ GPU → CUDA → AI 訓練
  │    │    └→ CAD/CAM → 產品設計
  │    │         └→ 積體電路佈局 → 晶片設計
  │    ├→ 光學設計
  │    │    └→ 鏡頭設計 → 手機攝影
  │    └→ 大地測量
  │         └→ 地圖投影 → Google Maps
  ├→ 非歐幾何
  │    └→ 黎曼幾何
  │         └→ 廣義相對論 (Einstein, 1915)
  │              └→ GPS 相對論校正
  │                   └→ 衛星導航 → Google Maps
  └→ 微分幾何
       └→ 電腦視覺
            ├→ 3D 重建 → Photogrammetry
            └→ 物體辨識
```

**GPS 的相對論校正**：沒有廣義相對論的時空彎曲公式，GPS 的每日數百公尺誤差將無法校正。

$$
\Delta t_{\text{GPS}} \approx \frac{GM}{c^2 R} \times t
$$

**推論**：沒有黎曼幾何，愛因斯坦就無法寫出廣義相對論。沒有廣義相對論，GPS 導航每日將累積數百公尺誤差。沒有計算機圖學的幾何基礎，就沒有 3D 電影和電玩遊戲。2019 年圖靈獎頒給了 Edwin Catmull 與 Pat Hanrahan——表彰他們對 3D 圖學和 GPU 運算的貢獻。

- [維基百科：非歐幾何](https://zh.wikipedia.org/wiki/非欧几里得几何)
- [維基百科：計算機圖學](https://zh.wikipedia.org/wiki/计算机图形学)
- [維基百科：廣義相對論](https://zh.wikipedia.org/wiki/广义相对论)
- [資訊科技年鑑 2019：Catmull & Hanrahan 圖靈獎](https://github.com/cccmag/aicomputer/blob/master/2019/turing.md)

---

## 13. 從群論到晶片與物理

群論是研究對稱性的數學——從半導體晶體結構到量子運算，對稱性決定了物理定律的形式。

$$
[G_{\mu}, G_{\nu}] = i f_{\mu\nu\rho} G_{\rho}
$$

```
群論 (Galois, 1832)
  ├→ 晶體群
  │    ├→ 晶體學 → X 射線繞射
  │    ├→ 半導體晶體結構
  │    │    └→ 能帶理論 → 電晶體 (1947)
  │    │         └→ 積體電路 (1958)
  │    │              └→ 摩爾定律 → 現代晶片
  │    └→ 晶體工程 → 材料科學
  ├→ 李群與李代數
  │    └→ 標準模型 (SU(3) × SU(2) × U(1))
  │         └→ 粒子物理 → 高能計算
  └→ 表示論
       └→ 量子化學
            └→ 分子軌道理論 → 藥物設計
```

**推論**：沒有群論的晶體學，就無法理解半導體晶體結構。沒有對半導體能帶理論的理解，就沒有 1947 年的電晶體和 1958 年的積體電路。群論看似是純數學的最抽象分支，卻決定了從你手機晶片到量子電腦的物理基礎。

- [維基百科：群論](https://zh.wikipedia.org/wiki/群论)
- [維基百科：晶體學](https://zh.wikipedia.org/wiki/晶体学)
- [資訊科技年鑑 1947：電晶體的發明](https://github.com/cccmag/aicomputer/blob/master/1947/hardware1.md)

---

## 總結：數學是資訊科技的隱藏語言

下表總結了數學分支與其催生的資訊科技之間的對應關係：

| 數學分支 | 關鍵概念 | 催生技術 | 影響領域 |
|---------|---------|---------|---------|
| 布林代數 | 邏輯運算 | 數位電路、CPU、GPU | 整個數位世界 |
| 傅立葉分析 | 頻域變換 | JPEG、MP3、OFDM、Wi-Fi | 數位媒體、通信 |
| 線性代數 | 矩陣運算 | 神經網路、GPU、3D 渲染 | AI、遊戲、影像 |
| 機率論 | 不確定性量化 | 機器學習、強化學習、LLM | AI、安全、預測 |
| 數論 | 質數、同餘 | 因數分解、同餘運算 | 密碼學基礎 |
| 密碼學 | 公鑰加密、哈希 | RSA、ECC、區塊鏈、比特幣 | 網路安全、加密貨幣 |
| 圖論 | 網路結構 | PageRank、GPS 導航 | 搜尋、交通 |
| 資訊理論 | 熵與通道容量 | 壓縮、糾錯碼、5G | 通信、儲存 |
| 計算理論 | 可計算性、複雜性 | 電腦科學基礎、密碼學 | 整個電腦科學 |
| 微積分 | 梯度、變化率 | 反向傳播、梯度下降 | AI 訓練、工程 |
| 統計學 | 推論與顯著性 | A/B 測試、數據科學 | 產品、科學 |
| 幾何學 | 空間與形狀 | GPS、3D 渲染、CAD | 導航、娛樂、製造 |
| 群論 | 對稱性 | 半導體、晶體學 | 晶片、材料 |

---

### 最後的推論

**沒有數學，就沒有電腦科學。沒有電腦科學，就沒有資訊科技。沒有資訊科技，就沒有現代數位文明。**

當你拿起手機時，你握著的不是一部裝置——而是一團凝固的數學：

- 運算靠 **布林代數**
- 通訊靠 **傅立葉分析** 和 **資訊理論**
- AI 靠 **線性代數**、**微積分**、**機率論**
- 定位靠 **幾何學** 和 **相對論**
- 加密靠 **密碼學**（數論 + RSA + 區塊鏈）
- 照片和音樂靠 **傅立葉分析**
- 搜尋靠 **圖論**
- 晶片靠 **群論** 和 **晶體學**
- 整個電腦科學的基礎靠 **計算理論**

數學不是一門在教室裡考試用的科目——**它是這個世界運作的原始碼**。

---

**延伸閱讀：**

- [維基百科：數學史](https://zh.wikipedia.org/wiki/数学史)
- [維基百科：應用數學](https://zh.wikipedia.org/wiki/应用数学)
- [資訊科技年鑑（1950-2025）](https://github.com/cccmag/aicomputer)
- [知識圖譜（中文）](https://cccmag.github.io/aicomputer/graphify-out-tw/graph.html)
- [Google 搜尋：mathematics computer science connection](https://www.google.com/search?q=mathematics+computer+science+foundation+Boolean+algebra+information+theory)
- [Google 搜尋：math behind everyday technology](https://www.google.com/search?q=math+behind+everyday+technology+smartphone+GPS+AI)
