---
title: View and Edit PUB Metadata with CPP 
description: View and Edit PUB Metadata using C++ API on Windows
url: /cpp/metadata/pub/
family: pub
platformtag: cpp
feature: metadata
informat: PUB
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="View & Edit PUB Metadata via C++ API" h2="C++ API to View & Edit PUB Metadata on 32-bit and 64-bit Windows OS">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="View & Edit PUB Metadata on C++" %}}
1. Load PUB file using [CreateParser](https://apireference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) method of [PubFactory](https://apireference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) class
2. Parse file using [Parse](https://apireference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) method of [IPubParser](https://apireference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) interface
3. Edit metadata e.g Category using [SetCategory](https://apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) method of [DocSummaryInfo](https://apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) class
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with CPP PUB API" %}}
Install from command line as ```nuget install Aspose.PUB.cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.PUB.cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/pub/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C++ Code for PUB to PDF Conversion" gistPath="" %}}
```cs
// Load PUB file
System::SharedPtr<IPubParser> parser = PubFactory::CreateParser("input.pub");
// Parse file 
System::SharedPtr<Document> document = parser->Parse();
// Eidt Category metadata
document->get_DocumentSummaryInfo()->SetCategory(u"category");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}