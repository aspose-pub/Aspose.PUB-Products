---
translation: true
template: /_templates/metadata-net.md
title: Edit Publisher | PUB Metadata | .NET
description: Read Publisher files Metadata using cross-platform PUB .NET API Solution.  On-premise .NET API gives you access to SummaryInfo and DocSummaryInfo properties.
url: /net/metadata/pub/
metakeywords: edit pub metadata net, pub file metadata C#, publisher metadata editor .net, read pub file metadata C#, read pub metadata .net
family: pub
platformtag: net
feature: metadata
aliases: /net/metadata/
---

{{<section banner>}}
---
h1: Edit PUB Metadata
h2: Read MS Publisher file. PUB Metatada editor API for .NET
---

{{<section overview>}}
---
p1: Microsoft<sup>&reg;</sup> Publisher document file format is used for creating various publication types such as newsletters, brochures, flyers, and postcards and is used in Emails and Websites. Pub files contain text as well as bitmap and vector graphics data.
p2: Publisher Metadata is properties(information) that describe PUB documents. They are standard properties like publisher, title, last author, organization, URL, language, and other similar information. There is also data that is generated automatically after working with a file like its size or the last editing time. This useful information is stored along with the document. 
p3: Along with Conversion and Reading functionality, this PUB API solution for .NET lets you edit standard metadata by means of the DocSummaryInfo and SummaryInfo classes as shown in the following code sample. You may also use the API to create your own Metadata Editor application.
p4: Before coding Metadata, you need to integrate C# .NET PUB Metadata API. The following example will show you how to edit the "Company" property.
---

{{<section feature1>}}
---
title: Edit Metadata of PUB Files on .NET
item1: "The publisher Metadata reading process consists of the next steps:"
item2: Upload your PUB file using [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Method of [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory) Class.
item3: Parse the document via [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Method of [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser) Interface.
item4: Edit metadata e.g Company by means of [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Method of [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Class.
---

{{<section feature2>}}
---
title: Get Started with .NET PUB API
item1: Install from command line as ```nuget install Aspose.PUB``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.PUB```.
item2: Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/pub/net).
---

{{<section codeexample>}}
---
title: .NET Code to Edit PUB Metadata
---