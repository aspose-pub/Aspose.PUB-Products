---
title: Convert PUB to PDF with .NET 
description: Convert PUB files using .NET API on Windows
url: /net/conversion/pub-to-pdf/
family: pub
platformtag: net
feature: conversion
informat: PUB
outformat: PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert PUB to PDF via C#" h2="Export PUB to PDF using .NET Framework, .NET Core and Mono">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="PUB to PDF Conversion on .NET" %}}
1. Load PUB file using [CreateParser](https://apireference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) method of [PubFactory](https://apireference.aspose.com/pub/net/aspose.pub/pubfactory) class
2. Parse file using [Parse](https://apireference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) method of [IPubParser](https://apireference.aspose.com/pub/net/aspose.pub/ipubparser) interface
3. Convert PUB to PDF using [ConvertToPdf](https://apireference.aspose.com/pub/net/aspose.pub/ipdfconverter/methods/converttopdf) method of [IPdfConverter](https://apireference.aspose.com/pub/net/aspose.pub/ipdfconverter) interface 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET PUB API" %}}
Install from command line as ```nuget install Aspose.PUB``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.PUB```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/pub/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for PUB to PDF Conversion" gistPath="" %}}
```cs
// Load PUB file
var parser = PubFactory.CreateParser("sample.pub");
// Parse file 
var doc = parser.Parse();
// Convert PUB to PDF
Aspose.Pub.PubFactory.CreatePdfConverter().ConvertToPdf(doc, "output.pdf");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}