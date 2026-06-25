# Java 的企業化：從 applet 到平台

## Applet 夢想的破滅

1995-1996 年，Java 被定位為「Web 程式語言」，核心應用是 applet——在瀏覽器中執行的小程式。但 applet 從未真正成功：

- **啟動速度慢**：JVM 啟動需要數秒，在 56K 數據機上下載類別庫更久
- **版本不相容**：不同瀏覽器內建不同版本的 JVM
- **安全限制嚴格**：applet 在沙箱中執行，功能受限
- **Netscape 與 Sun 的衝突**：兩家公司關於 Java 內建支援的關係惡化

## 轉向伺服器端

到 1997 年，Sun 和 Java 社群開始認識到 Java 的真正價值在伺服器端。關鍵的技術發展包括：

- **Servlet API**：Java 的伺服器端 Web 元件，取代 CGI 腳本
- **JDBC**：Java Database Connectivity，統一的資料庫存取 API
- **EJB 規範**（開始設計）：Enterprise JavaBeans，企業級元件模型
- **Java Beans**：可重複使用的軟體元件模型

## 企業生態的萌芽

1997 年，多家公司開始圍繞 Java 建立產品：

- **IBM**：VisualAge for Java 和 WebSphere 應用伺服器
- **BEA**：WebLogic 應用伺服器
- **Oracle**：JDeveloper 和 Oracle Application Server
- **Sun**：Java Web Server

這些產品預示了 Java 在企業級市場的主導地位——雖然這個地位要到 1999 年 Java 2 Enterprise Edition 發布後才真正確立。

## 延伸閱讀

- [Java 歷史 - Oracle](https://www.oracle.com/java/)
- [Java Servlet - Wikipedia](https://en.wikipedia.org/wiki/Java_Servlet)
- [Java Enterprise Edition 歷史 - Wikipedia](https://en.wikipedia.org/wiki/Jakarta_EE)
