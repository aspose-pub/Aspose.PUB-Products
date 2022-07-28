---
translation: true
template: /_templates/metadata-net.md
title: Redigera utgivare | PUB Metadata | .NET
description: Läs utgivarens metadata med PUB .NET API-lösning. Native C# .NET API ger dig tillgång till egenskaperna SummaryInfo och DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: redigera pub metadata net, pub fil metadata C#, publisher metadata editor .net, läs pub fil metadata C#, läs pub metadata .net
family: pub
platformtag: net
feature: metadata
aliases: /net/metadata/
---

{{<section banner>}}
---
h1: Redigera PUB-metadata
h2: Läs MS Publisher-filen. PUB Metatada editor API för .NET
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher-dokumentfilformat används för att skapa olika publikationstyper som nyhetsbrev, broschyrer, flygblad och vykort och används i e-postmeddelanden och webbplatser. Pub-filer innehåller text samt bitmapps- och vektorgrafikdata.
p2: Publisher Metadata är egenskaper(information) som beskriver PUB-dokument. De är standardegenskaper som utgivare, titel, senaste författare, organisation, URL, språk och annan liknande information. Det finns också data som genereras automatiskt efter att ha arbetat med en fil som dess storlek eller senaste redigeringstiden. Denna användbara information lagras tillsammans med dokumentet.
p3: Tillsammans med konverterings- och läsfunktionalitet låter denna PUB API-lösning för .NET dig redigera standardmetadata med hjälp av klasserna DocSummaryInfo och SummaryInfo som visas i följande kodexempel. Du kan också använda API:et för att skapa din egen Metadata Editor-applikation.
p4: Innan du kodar Metadata måste du integrera C# .NET PUB Metadata API. Följande exempel visar hur du redigerar egenskapen "Företag".
---

{{<section feature1>}}
---
title: Redigera metadata för PUB-filer på .NET
item1: "Läsprocessen för utgivarens metadata består av följande steg:"
item2: Ladda upp din PUB-fil med [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) Metoden [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Klass.
item3: Analysera dokumentet via [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse) Metoden för [*IPubParser*](https://referens.aspose.com/pub/net/aspose.pub/ipubparser) Gränssnitt.
item4: Redigera metadata t.ex. företag med hjälp av [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Metoden [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Klass.
---

{{<section feature2>}}
---
title: Kom igång med .NET PUB API
item1: Installera från kommandoraden som ```nuget install Aspose.PUB``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.PUB```.
item2: Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: .NET-kod för att redigera PUB-metadata
---