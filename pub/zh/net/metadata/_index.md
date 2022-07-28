---
translation: true
template: /_templates/metadata-net.md
title: 编辑出版商 | PUB 元数据 | .NET
description: 使用跨平台 PUB .NET API 解决方案读取发布者文件元数据。本地 .NET API 使您可以访问 SummaryInfo 和 DocSummaryInfo 属性。
url: /net/metadata/pub/
metakeywords: 编辑 pub 元数据网络，pub 文件元数据 C#，发布者元数据编辑器 .net，读取 pub 文件元数据 C#，读取 pub 元数据 .net
family: pub
platformtag: net
feature: metadata
aliases: /net/元数据/
---

{{<section banner>}}
---
h1: 编辑 PUB 元数据
h2: 阅读 MS Publisher 文件。用于 .NET 的 PUB Metatada 编辑器 API
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 文档文件格式用于创建各种出版物类型，例如新闻稿、小册子、传单和明信片，并用于电子邮件和网站。 Pub 文件包含文本以及位图和矢量图形数据。
p2: 发布者元数据是描述 PUB 文档的属性（信息）。它们是标准属性，如发布者、标题、最后作者、组织、URL、语言和其他类似信息。还有一些数据是在处理文件后自动生成的，例如文件大小或上次编辑时间。此有用信息与文档一起存储。
p3: 除了转换和读取功能外，此 .NET 的 PUB API 解决方案还允许您通过 DocSummaryInfo 和 SummaryInfo 类编辑标准元数据，如以下代码示例所示。您也可以使用 API 创建您自己的元数据编辑器应用程序。
p4: 在编码元数据之前，您需要集成 C# .NET PUB 元数据 API。以下示例将向您展示如何编辑“公司”属性。
---

{{<section feature1>}}
---
title: 在 .NET 上编辑 PUB 文件的元数据
item1: "发布者元数据读取过程包括以下步骤："
item2: 使用 [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) [*PubFactory*](https:///reference.aspose.com/pub/net/aspose.pub/pubfactory) 类。
item3: 通过[*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse)方法解析文档[*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) 接口。
item4: 通过 [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) 方法编辑元数据，例如公司 [*DocSummaryInfo*](https:///reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) 类。
---

{{<section feature2>}}
---
title: .NET PUB API 入门
item1: 从命令行安装为 ```nuget install Aspose.PUB``` 或通过 Visual Studio 的 Package Manager Console 使用 ```Install-Package Aspose.PUB``` 安装。
item2: 或者，从 [下载](https://releases.aspose.com/pub/net/) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
---

{{<section codeexample>}}
---
title: .NET 代码编辑 PUB 元数据
---