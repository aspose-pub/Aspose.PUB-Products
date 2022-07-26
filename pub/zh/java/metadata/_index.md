---
translation: true
template: /_templates/metadata-java.md
title: 编辑出版商 | PUB 元数据 |爪哇
description: 使用跨平台 PUB Java API 解决方案读取发布者文件元数据。本地 Java API 使您可以访问 SummaryInfo 和 DocSummaryInfo 属性。
url: /java/metadata/pub/
metakeywords: 编辑 pub 元数据 java, pub 文件元数据 java, 发布者元数据编辑器 java, 读取 pub 文件元数据 java, 读取 pub 元数据 java
family: pub
platformtag: java
feature: metadata
aliases: /java/元数据/
---

{{<section banner>}}
---
h1: 编辑 PUB 元数据
h2: 阅读 MS Publisher 文件。 PUB Metatada 编辑器 API for Java
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 文档文件格式用于创建各种出版物类型，例如新闻稿、小册子、传单和明信片，并用于电子邮件和网站。 Pub 文件包含文本以及位图和矢量图形数据。
p2: 发布者元数据是描述 PUB 文档的属性（信息）。它们是标准属性，如发布者、标题、最后作者、组织、URL、语言和其他类似信息。还有一些数据是在处理文件后自动生成的，例如文件大小或上次编辑时间。此有用信息与文档一起存储。
p3: 除了转换和读取功能外，此 Java PUB API 解决方案还允许您通过 DocSummaryInfo 和 SummaryInfo 类编辑标准元数据，如以下代码示例所示。您也可以使用 API 创建您自己的元数据编辑器应用程序。
p4: 在编码 Metadata 之前，您需要集成 Java PUB Metadata API。以下示例将向您展示如何编辑“语言”属性。
---

{{<section widget>}}
---
title: 如何使用 Java 编辑 PUB 元数据
item1: "为了编辑 PUB 元数据，我们将使用 [Aspose.PUB for Java API](https://products.aspose.com/pub/java) 这是一个功能丰富、强大且易于使用的转换Java 平台的 API。您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pub) 下载其最新版本并将其安装在您的 Maven 中通过将以下配置添加到 pom.xml 中的基于项目的项目。"
---

{{<section feature1>}}
---
title: 在 Java 上查看和编辑 PUB 元数据
item1: "发布者元数据读取过程包括以下步骤："
item2: 使用 [*createParser*()](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-)的方法上传您的 [*PubFactory*](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory) 类。
item3: 通过 [*IPdfConverter*](https://apireference) 的 [*parse*()](https://apireference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) 方法解析文件.aspose.com/pub/java/com.aspose.pub/IPubParser) 接口。
item4: 通过 [*setLanguage*()](https://apireference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) 方法编辑元数据，例如语言 [*DocSummaryInfo*](https://apireference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) 类。
---

{{<section feature2>}}
---
title: 系统要求
item1: 所有主要操作系统都支持 Aspose.PUB for Java。只需确保您具有以下先决条件。
item2: J2SE 8.0 (1.8) 或更高版本。
---

{{<section codeexample>}}
---
title: 更新 PUB 元数据的 Java 代码
---