---
translation: true
template: /_templates/reader-net.md
title: 打开 PUB 文档 | .NET
description: 以編程方式打開 Publisher 文件。用於讀取 PUB 屬性的本地 .NET C# API 解決方案。使用它來集成到您的項目中。
url: /net/read-pub-file/
metakeywords: 閱讀 PUB 文件, PUB文件打開器
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: PUB文件打開器
h2: 閱讀 PUB 文件。使用 .NET 的 API 打開 Publisher
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 文檔文件格式用於創建各種出版物類型，例如新聞稿、小冊子、傳單和明信片，並用於電子郵件和網站。 Pub 文件包含文本、表格以及位圖和矢量圖形數據。
p2: 儘管該格式非常流行，但它不如 PDF 或 DOCX 等格式流行。 MS Publisher 應用程序本身不是免費的。
p3: 所以有時需要在沒有這個程序的情況下打開 PUB 文件。當您想要顯示文檔的內容而不以任何其他方式編輯或操作它時(例如在進行演示或審閱時)，這是需要的。為此，您可以使用跨平台的 PUB Viewer 應用程序。
p4: 在這裡，您將獲得 .NET API 解決方案，可讓您查看 MS Publisher 文檔的屬性，例如大小、寬度、高度、所用字體的名稱、字段數和顏色。
---

{{<section feature1>}}
---
title: 閱讀 .NET 上的 Publisher 文件
item1: "要查看 .pub 文件屬性，您需要執行以下步驟:"
item2: 集成 .NET PUB API，它不僅適用於單頁文檔，還支持多頁 .pub 文件。
item3: 使用 [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) 上傳您的 PUB 文件 [*PubFactory*](https:///reference.aspose.com/pub/net/aspose.pub/pubfactory) 類。
item4: 通過[*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse)方法解析文檔[*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) 接口。
item5: 打印文檔 [*properties*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties)。
---

{{<section feature2>}}
---
title: .NET PUB API 入門
item1: "有兩種方法可以安裝產品:"
item2: 從命令行安裝為 ```nuget install Aspose.PUB``` 或通過 Visual Studio 的 Package Manager Console 使用 ```Install-Package Aspose.PUB``` 安裝。
item3: 或者，從 [下載](https://releases.aspose.com/pub/net/) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
---

{{<section codeexample>}}
---
title: .NET 代碼讀取 PUB 文件屬性
---

{{<section summary>}}
---
item1: 要查看完整代碼 ReadPubDocument.cs 示例，請轉到 Aspose.PUB.Examples.sln 解決方案，在 Aspose.PUB 文檔的網絡示例中，您還可以在其中找到有關如何使用該庫的其他示例。
---