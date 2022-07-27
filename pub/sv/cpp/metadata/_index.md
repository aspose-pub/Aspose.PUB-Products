---
translation: true
template: /_templates/metadata-cpp.md
title: Redigera utgivare | PUB Metadata | C++
description: Läs metadata för utgivarfiler med PUB C++ API-lösning. Lokalt C++ API ger dig tillgång till egenskaperna SummaryInfo och DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: redigera pub metadata, pub fil metadata, utgivare metadata editor, läs pub fil metadata, läs pub metadata
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadata/
---

{{<section banner>}}
---
h1: Redigera PUB-metadata
h2: Läs MS Publisher-filen. PUB Metatada editor API för C++
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher-dokumentfilformat används för att skapa olika publikationstyper som nyhetsbrev, broschyrer, flygblad och vykort och används i e-postmeddelanden och webbplatser. Pub-filer innehåller text samt bitmapps- och vektorgrafikdata.
p2: Publisher Metadata är egenskaper(information) som beskriver PUB-dokument. De är standardegenskaper som utgivare, titel, senaste författare, organisation, URL, språk och annan liknande information. Det finns också data som genereras automatiskt efter att ha arbetat med en fil som dess storlek eller den senaste redigeringstiden. Denna användbara information lagras tillsammans med dokumentet.
p3: Tillsammans med konverterings- och läsfunktionalitet låter denna PUB API-lösning för C++ dig redigera standardmetadata med hjälp av klasserna DocSummaryInfo och SummaryInfo som visas i följande kodexempel. Du kan också använda API:et för att skapa din egen Metadata Editor-applikation.
p4: Innan du kodar metadata måste du integrera C++ PUB Metadata API. Följande exempel visar hur du redigerar egenskapen "Kategori".
---

{{<section feature1>}}
---
title: Visa och redigera PUB-metadata på C++
item1: "Läsprocessen för utgivarens metadata består av följande steg:"
item2: Ladda upp din PUB-fil med [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Metoden [*PubFactory*](https://apireference*](.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Klass.
item3: Analysera fil via [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Metod för [*IPubParserpire*].https://poseapire*]. .com/pub/cpp/class/aspose.pub.i_pub_parser) Gränssnitt.
item4: Redigera metadata, t.ex. Kategori med hjälp av [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Metod för [*Info*](Sammanfattning:https:info*) /apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Klass.
---

{{<section feature2>}}
---
title: Kom igång med CPP PUB API
item1: Installera från kommandoraden som ```nuget install Aspose.PUB.cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.PUB.cpp```.
item2: Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.com/pub/cpp).
---

{{<section codeexample>}}
---
title: C++-kod för att ändra PUB-metadata
---
