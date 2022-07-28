---
translation: true
template: /_templates/metadata-cpp.md
title: 编辑出版商 | PUB 元数据 | C++
description: 使用 PUB C++ API 解决方案读取发布者文件元数据。本地 C++ API 使您可以访问 SummaryInfo 和 DocSummaryInfo 属性。
url: /cpp/metadata/pub/
metakeywords: 编辑 pub 元数据、pub 文件元数据、发布者元数据编辑器、读取 pub 文件元数据、读取 pub 元数据
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/元数据/
---

{{<section banner>}}
---
h1: 编辑 PUB 元数据
h2: 阅读 MS Publisher 文件。用于 C++ 的 PUB Metatada 编辑器 API
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 文档文件格式用于创建各种出版物类型，例如新闻稿、小册子、传单和明信片，并用于电子邮件和网站。 Pub 文件包含文本以及位图和矢量图形数据。
p2: 发布者元数据是描述 PUB 文档的属性（信息）。它们是标准属性，如发布者、标题、最后作者、组织、URL、语言和其他类似信息。还有一些数据是在处理文件后自动生成的，例如文件大小或上次编辑时间。此有用信息与文档一起存储。
p3: 除了转换和读取功能外，此 C++ PUB API 解决方案还允许您通过 DocSummaryInfo 和 SummaryInfo 类编辑标准元数据，如以下代码示例所示。您也可以使用 API 创建您自己的元数据编辑器应用程序。
p4: 在编码元数据之前，您需要集成 C++ PUB 元数据 API。以下示例将向您展示如何编辑“类别”属性。
---

{{<section feature1>}}
---
title: 在 C++ 上查看和编辑 PUB 元数据
item1: "发布者元数据读取过程包括以下步骤："
item2: 使用 [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) 方法 上传您的 [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) 类。
item3: 通过 [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) 方法解析文件 [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) 接口。
item4: 通过 [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) 方法编辑元数据，例如类别 [*DocSummaryInfo*](https:///apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) 类。
---

{{<section feature2>}}
---
title: 开始使用 CPP PUB API
item1: 从命令行安装为 ```nuget install Aspose.PUB.cpp``` 或通过 Visual Studio 的包管理器控制台使用 ``Install-Package Aspose.PUB.cpp``。
item2: 或者，从 [下载](https://releases.aspose.com/pub/cpp/) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
---

{{<section codeexample>}}
---
title: 修改 PUB 元数据的 C++ 代码
---
