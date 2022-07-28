---
translation: true
template: /_templates/metadata-java.md
title: 編輯出版商 | PUB 元數據 |爪哇
description: 使用跨平台 PUB Java API 解決方案讀取發布者文件元數據。本地 Java API 使您可以訪問 SummaryInfo 和 DocSummaryInfo 屬性。
url: /java/metadata/pub/
metakeywords: 編輯 pub 元數據 java, pub 文件元數據 java, 發布者元數據編輯器 java, 讀取 pub 文件元數據 java, 讀取 pub 元數據 java
family: pub
platformtag: java
feature: metadata
aliases: /java/元數據/
---

{{<section banner>}}
---
h1: 編輯 PUB 元數據
h2: 閱讀 MS Publisher 文件。 PUB Metatada 編輯器 API for Java
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 文檔文件格式用於創建各種出版物類型，例如新聞稿、小冊子、傳單和明信片，並用於電子郵件和網站。 Pub 文件包含文本以及位圖和矢量圖形數據。
p2: 發布者元數據是描述 PUB 文檔的屬性（信息）。它們是標準屬性，如發布者、標題、最後作者、組織、URL、語言和其他類似信息。還有一些數據是在處理文件後自動生成的，例如文件大小或上次編輯時間。此有用信息與文檔一起存儲。
p3: 除了轉換和讀取功能外，此 Java PUB API 解決方案還允許您通過 DocSummaryInfo 和 SummaryInfo 類編輯標準元數據，如以下代碼示例所示。您還可以使用 API 創建您自己的元數據編輯器應用程序。
p4: 在編碼元數據之前，您需要集成 Java PUB 元數據 API。以下示例將向您展示如何編輯“語言”屬性。
---

{{<section widget>}}
---
title: 如何使用 Java 編輯 PUB 元數據
item1: "為了編輯 PUB 元數據，我們將使用 [Aspose.PUB for Java API](https://products.aspose.com/pub/java/) 這是一個功能豐富、強大且易於使用的轉換Java 平台的 API。您可以直接從 [Maven](https://repository.aspose.com/pub/) 下載其最新版本並將其安裝在您的 Maven 中通過將以下配置添加到 pom.xml 中的基於項目的項目。"
---

{{<section feature1>}}
---
title: 在 Java 上查看和編輯 PUB 元數據
item1: "發布者元數據讀取過程包括以下步驟："
item2: 使用 [*createParser()*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) 的  方法加載 PUB 文件 [*PubFactory*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) 類。
item3: 通過 [*IPdfConverter*](https://apireference) 的 [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) 方法解析文件.aspose.com/pub/java/com.aspose.pub/IPubParser) 接口。
item4: 通過 [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) 方法編輯元數​​據，例如語言 [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) 類。
---

{{<section feature2>}}
---
title: 系統要求
item1: 所有主要操作系統都支持 Aspose.PUB for Java。只需確保您具有以下先決條件。
item2: J2SE 8.0 (1.8) 或更高版本。
---

{{<section codeexample>}}
---
title: 更新 PUB 元數據的 Java 代碼
---