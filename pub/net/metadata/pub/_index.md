---
title: Edit Metadata of PUB file with .NET 
description: Eid PUB files Metadata .NET API on Windows
url: /net/metadata/pub/
family: pub
platformtag: net
feature: metadata
informat: PUB
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Edit PUB Metadata via C#" h2="Edit PUB Metadata using .NET Framework, .NET Core and Mono">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Edit Metadata of PUB Files on .NET" %}}
1. Load PUB file using [CreateParser](https://apireference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) method of [PubFactory](https://apireference.aspose.com/pub/net/aspose.pub/pubfactory) class
2. Parse file using [Parse](https://apireference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) method of [IPubParser](https://apireference.aspose.com/pub/net/aspose.pub/ipubparser) interface
3. Edit metadata e.g Company using [SetCompany](https://apireference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) method of [DocSummaryInfo ](https://apireference.aspose.com/pub/net/aspose.pub/docsummaryinfo) class 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET PUB API" %}}
Install from command line as ```nuget install Aspose.PUB``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.PUB```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/pub/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code to Edit PUB Metadata" gistPath="" %}}
```cs
// Load PUB file
var parser = PubFactory.CreateParser("sample.pub");
// Parse file 
var doc = parser.Parse();
// Edit company metadata
document.DocumentSummaryInfo.SetCompany("company");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}