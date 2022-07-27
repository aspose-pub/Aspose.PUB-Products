---
translation: true
template: /_templates/metadata-cpp.md
title: 編輯出版商 | PUB 元數據 | C++
description: 使用 PUB C++ API 解決方案讀取發布者文件元數據。本地 C++ API 使您可以訪問 SummaryInfo 和 DocSummaryInfo 屬性。
url: /cpp/metadata/pub/
metakeywords: 編輯 pub 元數據、pub 文件元數據、發布者元數據編輯器、讀取 pub 文件元數據、讀取 pub 元數據
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/元數據/
---

{{<section banner>}}
---
h1: 編輯 PUB 元數據
h2: 閱讀 MS Publisher 文件。用於 C++ 的 PUB Metatada 編輯器 API
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 文檔文件格式用於創建各種出版物類型，例如新聞稿、小冊子、傳單和明信片，並用於電子郵件和網站。 Pub 文件包含文本以及位圖和矢量圖形數據。
p2: 發布者元數據是描述 PUB 文檔的屬性（信息）。它們是標準屬性，如發布者、標題、最後作者、組織、URL、語言和其他類似信息。還有一些數據是在處理文件後自動生成的，例如文件大小或上次編輯時間。此有用信息與文檔一起存儲。
p3: 除了轉換和讀取功能外，此 C++ PUB API 解決方案還允許您通過 DocSummaryInfo 和 SummaryInfo 類編輯標準元數據，如以下代碼示例所示。您還可以使用 API 創建您自己的元數據編輯器應用程序。
p4: 在編碼元數據之前，您需要集成 C++ PUB 元數據 API。以下示例將向您展示如何編輯“類別”屬性。
---

{{<section feature1>}}
---
title: 在 C++ 上查看和編輯 PUB 元數據
item1: "發布者元數據讀取過程包括以下步驟："
item2: 使用 [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) 方法 [*PubFactory*](https://apireference) 上傳您的 PUB 文件.aspose.com/pub/cpp/class/aspose.pub.pub_factory) 類。
item3: 通過[*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915)方法解析文件[*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) 接口。
item4: 通過 [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) 方法編輯元數​​據，例如類別 [*DocSummaryInfo*](https:///apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) 類。
---

{{<section feature2>}}
---
title: 開始使用 CPP PUB API
item1: 從命令行安裝為 ```nuget install Aspose.PUB.cpp``` 或通過 Visual Studio 的包管理器控制台使用 ``Install-Package Aspose.PUB.cpp``。
item2: 或者，從 [下載](https://releases.aspose.com/pub/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
---

{{<section codeexample>}}
---
title: 修改 PUB 元數據的 C++ 代碼
---
