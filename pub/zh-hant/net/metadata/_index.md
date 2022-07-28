---
translation: true
template: /_templates/metadata-net.md
title: 編輯出版商 | PUB 元數據 | .NET
description: 使用跨平台 PUB .NET API 解決方案讀取發布者文件元數據。本地 .NET API 使您可以訪問 SummaryInfo 和 DocSummaryInfo 屬性。
url: /net/metadata/pub/
metakeywords: 編輯 pub 元數據網絡，pub 文件元數據 C#，發布者元數據編輯器 .net，讀取 pub 文件元數據 C#，讀取 pub 元數據 .net
family: pub
platformtag: net
feature: metadata
aliases: /net/元數據/
---

{{<section banner>}}
---
h1: 編輯 PUB 元數據
h2: 閱讀 MS Publisher 文件。用於 .NET 的 PUB Metatada 編輯器 API
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 文檔文件格式用於創建各種出版物類型，例如新聞稿、小冊子、傳單和明信片，並用於電子郵件和網站。 Pub 文件包含文本以及位圖和矢量圖形數據。
p2: 發布者元數據是描述 PUB 文檔的屬性（信息）。它們是標準屬性，如發布者、標題、最後作者、組織、URL、語言和其他類似信息。還有一些數據是在處理文件後自動生成的，例如文件大小或上次編輯時間。此有用信息與文檔一起存儲。
p3: 除了轉換和讀取功能外，此 .NET 的 PUB API 解決方案還允許您通過 DocSummaryInfo 和 SummaryInfo 類編輯標準元數據，如以下代碼示例所示。您也可以使用 API 創建您自己的元數據編輯器應用程序。
p4: 在編碼元數據之前，您需要集成 C# .NET PUB 元數據 API。以下示例將向您展示如何編輯“公司”屬性。
---

{{<section feature1>}}
---
title: 在 .NET 上編輯 PUB 文件的元數據
item1: "發布者元數據讀取過程包括以下步驟："
item2: 使用 [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) 上傳您的 PUB 文件 [*PubFactory*](https:///reference.aspose.com/pub/net/aspose.pub/pubfactory) 類。
item3: 通過[*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse)方法解析文檔[*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) 接口。
item4: 通過 [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) 方法編輯元數​​據，例如公司 [*DocSummaryInfo*](https:///reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) 類。
---

{{<section feature2>}}
---
title: .NET PUB API 入門
item1: 從命令行安裝為 ```nuget install Aspose.PUB``` 或通過 Visual Studio 的 Package Manager Console 使用 ```Install-Package Aspose.PUB``` 安裝。
item2: 或者，從 [下載](https://releases.aspose.com/pub/net/) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
---

{{<section codeexample>}}
---
title: .NET 代碼編輯 PUB 元數據
---