---
title: Read PUB file Metadata | Java 
description: Read Publisher files Metadata using cross-platform PUB Java API Solution.  On-premise Java API gives you access to SummaryInfo and DocSummaryInfo properties.
url: /java/metadata/pub/
family: pub
platformtag: java
feature: metadata
informat: PUB
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="View & Edit PUB Metadata via Java" h2="Native Java Library to View & Edit PUB Metadata on Windows, Linux and Mac OS X">}}
{{< blocks/products/pf/main-container >}}
{{% blocks/products/pf/agp/content h2="How to Edit PUB Metadata Using Java" %}}

In order to Edit PUB Metadata, we’ll use <a href="https://products.aspose.com/pub/java">Aspose.PUB for Java</a> API which is a feature-rich, powerful and easy to use conversion API for Java platform. You can download its latest version directly from <a href="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pub">Maven</a> and install it within your Maven-based project by adding the following configurations to the pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs
<repository>
    <id>snapshots</id>
    <name>repo</name>
    <url>http://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

```cs
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-pub</artifactId>
    <version>20.8</version>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="PUB to PDF Conversion on Java" %}}
1. Load PUB file using [createParser](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) method of [PubFactory](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory) class
2. Parse file using [parse](https://apireference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) method of [IPdfConverter](https://apireference.aspose.com/pub/java/com.aspose.pub/IPubParser) interface
3. Edit metadata e.g Language using [setLanguage](https://apireference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) method of [DocSummaryInfo](https://apireference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) class 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}
{{% blocks/products/pf/agp/text %}}
Aspose.PUB for Java is supported on all major operating systems. Just make sure that you have the following prerequisites.
{{% /blocks/products/pf/agp/text %}}
- J2SE 8.0 (1.8) or above.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Code to Update PUB Metadata" gistPath="" %}}

{{< gist "aspose-com-gists" "01150f8eb789a1413f4eb8b1c9484eb7" "update-pub-metadata.java" >}}

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}