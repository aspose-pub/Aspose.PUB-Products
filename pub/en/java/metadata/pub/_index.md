---
title: Edit Publisher | PUB Metadata | Java
description: Read Publisher files Metadata using cross-platform PUB Java API Solution.  On-premise Java API gives you access to SummaryInfo and DocSummaryInfo properties.
url: /java/metadata/pub/
metakeywords: edit pub metadata java, pub file metadata java, publisher metadata editor java, read pub file metadata java, read pub metadata java
family: pub
platformtag: java
feature: metadata
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Edit PUB Metadata" h2="Read MS Publisher file. PUB Metatada editor API for Java">}}

{{% blocks/products/pf/feature-page-summary %}}
<p>
Microsoft<sup>&reg;</sup> Publisher document file format is used for creating various publication types such as newsletters, brochures, flyers, and postcards and is used in Emails and Websites. Pub files contain text as well as bitmap and vector graphics data.
</p>
<p>
Publisher Metadata is properties(information) that describe PUB documents. They are standard properties like publisher, title, last author, organization, URL, language, and other similar information. There is also data that is generated automatically after working with a file like its size or the last editing time. This useful information is stored along with the document. 
</p>
<p>
Along with Conversion and Reading functionality, this PUB API solution for Java lets you edit standard metadata by means of the DocSummaryInfo and SummaryInfo classes as shown in the following code sample. You may also use the API to create your own Metadata Editor application.
</p>

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/main-container >}}
{{% blocks/products/pf/agp/content h2="How to Edit PUB Metadata Using Java" %}}

Before coding Metadata, you need to integrate Java PUB Metadata API. The following example will show you how to edit the "Language" property.

In order to Edit PUB Metadata, we’ll use <a href="https://products.aspose.com/pub/java">Aspose.PUB for Java</a> API which is a feature-rich, powerful, and easy-to-use conversion API for the Java platform. You can download its latest version directly from <a href="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pub">Maven</a> and install it within your Maven-based project by adding the following configurations to the pom.xml.

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
1. Upload your PUB file using [*createParser*](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) Method of [*PubFactory*](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory) Class.
2. Parse file via [*parse*](https://apireference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) method of [*IPdfConverter*](https://apireference.aspose.com/pub/java/com.aspose.pub/IPubParser) interface
3. Edit metadata e.g Language by means of [*setLanguage*](https://apireference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Method of [*DocSummaryInfo*](https://apireference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Class. 
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

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/pub/java/" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-pub/Aspose.PUB-for-Java" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.com/java/pub" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/pub" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/pub/" >}}
{{< blocks/products/pf/slr-element name="Release Notes" href="https://docs.aspose.com/pub/java/release-notes/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.PUB for Java?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
{{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://downloads.aspose.com/pub/java" pricingInformationLink="https://purchase.aspose.com/pricing/pub/java" >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}