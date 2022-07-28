---
translation: true
template: /_templates/metadata-cpp.md
title: Edit Publisher | PUB Metadata | C++
description: Read Publisher files Metadata using PUB C++ API Solution.  On-premise C++ API gives you access to SummaryInfo and DocSummaryInfo properties.
url: /cpp/metadata/pub/
metakeywords: edit pub metadata, pub file metadata, publisher metadata editor, read pub file metadata, read pub metadata
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadata/
---

{{<section banner>}}
---
h1: Edit PUB Metadata
h2: Read MS Publisher file. PUB Metatada editor API for C++
---

{{<section overview>}}
---
p1: Microsoft<sup>&reg;</sup> Publisher document file format is used for creating various publication types such as newsletters, brochures, flyers, and postcards and is used in Emails and Websites. Pub files contain text as well as bitmap and vector graphics data.
p2: Publisher Metadata is properties(information) that describe PUB documents. They are standard properties like publisher, title, last author, organization, URL, language, and other similar information. There is also data that is generated automatically after working with a file like its size or the last editing time. This useful information is stored along with the document. 
p3: Along with Conversion and Reading functionality, this PUB API solution for C++ lets you edit standard metadata by means of the DocSummaryInfo and SummaryInfo classes as shown in the following code sample. You may also use the API to create your own Metadata Editor application.
p4: Before coding Metadata, you need to integrate C++ PUB Metadata API. The following example will show you how to edit the "Category" property.
---

{{<section feature1>}}
---
title: View & Edit PUB Metadata on C++
item1: "The publisher Metadata reading process consists of the next steps:"
item2: Upload your PUB file using [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Method of [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Class.
item3: Parse file via [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Method of [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Interface.
item4: Edit metadata e.g Category by means of [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Method of [*DocSummaryInfo*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Class.
---

{{<section feature2>}}
---
title: Get Started with CPP PUB API
item1: Install from command line as ```nuget install Aspose.PUB.cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.PUB.cpp```.
item2: Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/pub/cpp/).
---

{{<section codeexample>}}
---
title: C++ Code to Modify PUB Metadata
---
