---
translation: true
template: /_templates/metadata-net.md
title: Uitgever bewerken | PUB-metagegevens | .NET
description: Lees Publisher Metadata met behulp van PUB .NET API Solution. Native C# .NET API geeft u toegang tot de eigenschappen SummaryInfo en DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: bewerk pub metadata net, pub bestand metadata C#, uitgever metadata editor .net, lees pub bestand metadata C#, lees pub metadata .net
family: pub
platformtag: net
feature: metadata
aliases: /net/metagegevens/
---

{{<section banner>}}
---
h1: PUB-metagegevens bewerken
h2: Lees MS Publisher-bestand. PUB Metatada-editor-API voor .NET
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher-documentbestandsindeling wordt gebruikt voor het maken van verschillende publicatietypen, zoals nieuwsbrieven, brochures, flyers en ansichtkaarten, en wordt gebruikt in e-mails en websites. Pub-bestanden bevatten zowel tekst als bitmap- en vectorafbeeldingsgegevens.
p2: Publisher Metadata zijn eigenschappen (informatie) die PUB-documenten beschrijven. Het zijn standaardeigenschappen zoals uitgever, titel, laatste auteur, organisatie, URL, taal en andere soortgelijke informatie. Er zijn ook gegevens die automatisch worden gegenereerd na het werken met een bestand, zoals de grootte of de laatste bewerkingstijd. Deze nuttige informatie wordt samen met het document opgeslagen.
p3: Naast de conversie- en leesfunctionaliteit, kunt u met deze PUB API-oplossing voor .NET standaardmetadata bewerken door middel van de klassen DocSummaryInfo en SummaryInfo, zoals weergegeven in het volgende codevoorbeeld. U kunt de API ook gebruiken om uw eigen Metadata Editor-toepassing te maken.
p4: Voordat u Metadata codeert, moet u C# .NET PUB Metadata API integreren. In het volgende voorbeeld ziet u hoe u de eigenschap "Bedrijf" kunt bewerken.
---

{{<section feature1>}}
---
title: Bewerk metadata van PUB-bestanden op .NET
item1: "Het leesproces van de uitgever Metadata bestaat uit de volgende stappen:"
item2: Upload uw PUB-bestand met [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) Methode van [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) klasse.
item3: Parseer het document via [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse) Methode van [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) interface.
item4: Bewerk metadata bijv. Bedrijf door middel van [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Methode van [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) klasse.
---

{{<section feature2>}}
---
title: Aan de slag met .NET PUB API
item1: Installeer vanaf de opdrachtregel als ```nuget install Aspose.PUB``` of via de Package Manager Console van Visual Studio met ```Install-Package Aspose.PUB```.
item2: U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: .NET-code om PUB-metagegevens te bewerken
---