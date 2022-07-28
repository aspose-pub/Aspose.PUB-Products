---
translation: true
template: /_templates/reader-net.md
title: Läs PUB-filer | .NET
description: Öppna utgivarfiler programmatiskt. On-premise .NET C# API-lösning för att läsa PUB-egenskaper. Använd den för att integrera i ditt projekt.
url: /net/read-pub-file/
metakeywords: öppna pubfilen .net, visa förlagsfiler c#, läs förlagsfiler, förlagsvisare för c#, pubformatläsare, pubfilöppnare
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: PUB-filöppnare
h2: Läs PUB-filer. Öppna Publisher med API för .NET
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher-dokumentfilformat används för att skapa olika publikationstyper som nyhetsbrev, broschyrer, flygblad och vykort och används i e-postmeddelanden och webbplatser. Pubfiler innehåller text, tabeller samt bitmapps- och vektorgrafikdata.
p2: Även om formatet är ganska populärt är det inte lika populärt som format som PDF eller DOCX. MS Publisher-applikationen är inte gratis själv.
p3: Så ibland krävs det att öppna PUB-filer utan detta program. Detta behövs när du vill visa dokumentets innehåll, utan att redigera eller manipulera det på något annat sätt, som när du har en presentation eller recension. För sådana ändamål kan du använda en plattformsoberoende PUB Viewer-applikation.
p4: Här får du .NET API-lösningen som låter dig se MS Publisher-dokumentets egenskaper som storlek, bredd, höjd, namn på de använda typsnitten, antal fält och färger.
---

{{<section feature1>}}
---
title: Läs utgivarfiler på .NET
item1: "För att se egenskaper för .pub-filer måste du ta följande steg:"
item2: Integrera .NET PUB API, som inte bara fungerar med ensidiga dokument utan också stöder flersidiga .pub-filer.
item3: Ladda upp din PUB-fil med [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Metoden [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Klass.
item4: Analysera dokumentet via [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Metoden för [*IPubParser*](https://referens.aspose.com/pub/net/aspose.pub/ipubparser) Gränssnitt.
item5: Skriv ut dokument [*properties*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties).
---

{{<section feature2>}}
---
title: Kom igång med .NET PUB API
item1: "Det finns två sätt att få produkten installerad:"
item2: Installera från kommandoraden som ```nuget install Aspose.PUB``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.PUB```.
item3: Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: .NET-kod för att läsa PUB-filers egenskaper
---

{{<section summary>}}
---
item1: För att se det fullständiga exemplet på ReadPubDocument.cs, gå till lösningen Aspose.PUB.Examples.sln, i nätexemplen i Aspose.PUB-dokumentationen där du också kan hitta andra exempel på hur du använder biblioteket.
---