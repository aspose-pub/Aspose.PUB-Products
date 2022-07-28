---
translation: true
template: /_templates/reader-net.md
title: 阅读 PUB 文件 | .NET
description: 以编程方式打开 Publisher 文件。 用于读取 PUB 属性的 C# .NET API 解决方案。 使用它来集成到您的项目中。
url: /net/read-pub-file/
metakeywords: 打开 pub 文件 .net, 查看发布者文件 c#, 读取发布者文件, c# 发布者查看器, pub 格式阅读器, pub 文件打开器
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: PUB文件打开器
h2: 阅读 PUB 文件。使用 .NET 的 API 打开 Publisher
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 文档文件格式用于创建各种出版物类型，例如新闻稿、小册子、传单和明信片，并用于电子邮件和网站。 Pub 文件包含文本、表格以及位图和矢量图形数据。
p2: 尽管该格式非常流行，但它不如 PDF 或 DOCX 等格式流行。 MS Publisher 应用程序本身不是免费的。
p3: 所以有时需要在没有这个程序的情况下打开 PUB 文件。当您想要显示文档的内容而不以任何其他方式编辑或操作它时(例如在进行演示或审阅时)，这是需要的。为此，您可以使用跨平台的 PUB Viewer 应用程序。
p4: 在这里，您将获得 .NET API 解决方案，可让您查看 MS Publisher 文档的属性，例如大小、宽度、高度、所用字体的名称、字段数和颜色。
---

{{<section feature1>}}
---
title: 阅读 .NET 上的 Publisher 文件
item1: "要查看 .pub 文件属性，您需要执行以下步骤:"
item2: 集成 .NET PUB API，它不仅适用于单页文档，还支持多页 .pub 文件。
item3: 使用 [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) 上传您的 PUB 文件 [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) 类。
item4: 通过 [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse) 方法解析文档[*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) 接口。
item5: 打印文档 [*properties*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties)。
---

{{<section feature2>}}
---
title: .NET PUB API 入门
item1: "有两种方法可以安装产品:"
item2: 从命令行安装为 ```nuget install Aspose.PUB``` 或通过 Visual Studio 的 Package Manager Console 使用 ```Install-Package Aspose.PUB``` 安装。
item3: 或者，从 [下载](https://releases.aspose.com/pub/net/) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
---

{{<section codeexample>}}
---
title: .NET 代码读取 PUB 文件属性
---

{{<section summary>}}
---
item1: 要查看完整代码 ReadPubDocument.cs 示例，请转到 Aspose.PUB.Examples.sln 解决方案，在 Aspose.PUB 文档的网络示例中，您还可以在其中找到有关如何使用该库的其他示例。
---