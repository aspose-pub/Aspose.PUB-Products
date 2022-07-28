---
translation: true
template: /_templates/metadata-java.md
title: Edit Publisher | PUB Metadata | Java
description: Read Publisher files Metadata using cross-platform PUB Java API Solution. On-premise Java API gives you access to SummaryInfo and DocSummaryInfo properties.
url: /java/metadata/pub/
metakeywords: edit pub metadata java, pub file metadata java, publisher metadata editor java, read pub file metadata java, read pub metadata java
family: pub
platformtag: java
feature: metadata
aliases: /java/metadata/
---

{{<section banner>}}
---
h1: Edit PUB Metadata
h2: Read MS Publisher file. PUB Metatada editor API for Java
---

{{<section overview>}}
---
p1: Microsoft<sup>&reg;</sup> Publisher document file format is used for creating various publication types such as newsletters, brochures, flyers, and postcards and is used in Emails and Websites. Pub files contain text as well as bitmap and vector graphics data.
p2: Publisher Metadata is properties(information) that describe PUB documents. They are standard properties like publisher, title, last author, organization, URL, language, and other similar information. There is also data that is generated automatically after working with a file like its size or the last editing time. This useful information is stored along with the document. 
p3: Along with Conversion and Reading functionality, this PUB API solution for Java lets you edit standard metadata by means of the DocSummaryInfo and SummaryInfo classes as shown in the following code sample. You may also use the API to create your own Metadata Editor application.
p4: Before coding Metadata, you need to integrate Java PUB Metadata API. The following example will show you how to edit the "Language" property.
---

{{<section widget>}}
---
title: How to Edit PUB Metadata Using Java
item1: "In order to Edit PUB Metadata, we’ll use [Aspose.PUB for Java API](https://products.aspose.com/pub/java/) which is a feature-rich, powerful, and easy-to-use conversion API for the Java platform. You can download its latest version directly from [Maven](https://repository.aspose.com/pub/) and install it within your Maven-based project by adding the following configurations to the pom.xml."
---

{{<section feature1>}}
---
title: View and Edit PUB Metadata on Java
item1: "The publisher Metadata reading process consists of the next steps:"
item2: Upload your PUB file using [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) Method of [*PubFactory*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Class.
item3: Parse file via [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) method of [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) Interface.
item4: Edit metadata e.g Language by means of [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Method of [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Class. 
---

{{<section feature2>}}
---
title: System Requirements
item1: Aspose.PUB for Java is supported on all major operating systems. Just make sure that you have the following prerequisites.
item2: J2SE 8.0 (1.8) or above.
---

{{<section codeexample>}}
---
title: Java Code to Update PUB Metadata
---