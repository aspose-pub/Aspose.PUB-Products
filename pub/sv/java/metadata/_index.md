---
translation: true
template: /_templates/metadata-java.md
title: Redigera utgivare | PUB Metadata | Java
description: Läs metadata för utgivarfiler med PUB Java API-lösning för flera plattformar. Lokalt Java API ger dig tillgång till egenskaperna SummaryInfo och DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: redigera pub metadata java, pub fil metadata java, publisher metadata editor java, läs pub fil metadata java, läs pub metadata java
family: pub
platformtag: java
feature: metadata
aliases: /java/metadata/
---

{{<section banner>}}
---
h1: Redigera PUB-metadata
h2: Läs MS Publisher-filen. PUB Metatada editor API för Java
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher-dokumentfilformat används för att skapa olika publikationstyper som nyhetsbrev, broschyrer, flygblad och vykort och används i e-postmeddelanden och webbplatser. Pub-filer innehåller text samt bitmapps- och vektorgrafikdata.
p2: Publisher Metadata är egenskaper(information) som beskriver PUB-dokument. De är standardegenskaper som utgivare, titel, senaste författare, organisation, URL, språk och annan liknande information. Det finns också data som genereras automatiskt efter att ha arbetat med en fil som dess storlek eller den senaste redigeringstiden. Denna användbara information lagras tillsammans med dokumentet.
p3: Tillsammans med konverterings- och läsningsfunktionalitet låter denna PUB API-lösning för Java dig redigera standardmetadata med hjälp av klasserna DocSummaryInfo och SummaryInfo som visas i följande kodexempel. Du kan också använda API:et för att skapa din egen Metadata Editor-applikation.
p4: Innan du kodar metadata måste du integrera Java PUB Metadata API. Följande exempel visar hur du redigerar egenskapen "Language".
---

{{<section widget>}}
---
title: Hur man redigerar PUB-metadata med Java
item1: "För att redigera PUB-metadata använder vi [Aspose.PUB för Java API](https://products.aspose.com/pub/java/) som är en funktionsrik, kraftfull och lättanvänd konvertering API för Java-plattformen. Du kan ladda ner den senaste versionen direkt från [Aspose Maven Repository](https://repository.aspose.com/pub/) och installera den i din Maven -baserat projekt genom att lägga till följande konfigurationer till pom.xml."
---

{{<section feature1>}}
---
title: Visa och redigera PUB-metadata på Java
item1: "Läsprocessen för utgivarens metadata består av följande steg:"
item2: Ladda upp din PUB-fil med [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) Metoden [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Klass.
item3: Analysera fil med metoden [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) enligt [*IFFConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) Gränssnitt.
item4: Redigera metadata, t.ex. språk med hjälp av [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Metoden [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Klass.
---

{{<section feature2>}}
---
title: Systemkrav
item1: Aspose.PUB för Java stöds på alla större operativsystem. Se bara till att du har följande förutsättningar.
item2: J2SE 8.0 (1.8) eller högre.
---

{{<section codeexample>}}
---
title: Java-kod för att uppdatera PUB-metadata
---