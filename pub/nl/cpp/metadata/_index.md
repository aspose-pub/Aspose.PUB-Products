---
translation: true
template: /_templates/metadata-cpp.md
title: Uitgever bewerken | PUB-metagegevens | C++
description: Lees Publisher Metadata met behulp van PUB C++ API Solution. Native C++ API geeft u toegang tot de eigenschappen SummaryInfo en DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: bewerk pub-metadata, pub-bestand metadata, uitgever metadata-editor, lees pub-metadata, lees pub-metadata
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metagegevens/
---

{{<section banner>}}
---
h1: PUB-metagegevens bewerken
h2: Lees MS Publisher-bestand. PUB Metatada-editor-API voor C++
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher-documentbestandsindeling wordt gebruikt voor het maken van verschillende publicatietypen, zoals nieuwsbrieven, brochures, flyers en ansichtkaarten, en wordt gebruikt in e-mails en websites. Pub-bestanden bevatten zowel tekst als bitmap- en vectorafbeeldingsgegevens.
p2: Publisher Metadata zijn eigenschappen (informatie) die PUB-documenten beschrijven. Het zijn standaardeigenschappen zoals uitgever, titel, laatste auteur, organisatie, URL, taal en andere soortgelijke informatie. Er zijn ook gegevens die automatisch worden gegenereerd na het werken met een bestand, zoals de grootte of de laatste bewerkingstijd. Deze nuttige informatie wordt samen met het document opgeslagen.
p3: Samen met de conversie- en leesfunctionaliteit, kunt u met deze PUB API-oplossing voor C++ standaardmetadata bewerken door middel van de klassen DocSummaryInfo en SummaryInfo, zoals weergegeven in het volgende codevoorbeeld. U kunt de API ook gebruiken om uw eigen Metadata Editor-toepassing te maken.
p4: Voordat u Metadata codeert, moet u de C++ PUB Metadata API integreren. In het volgende voorbeeld ziet u hoe u de eigenschap "Categorie" kunt bewerken.
---

{{<section feature1>}}
---
title: Bekijk en bewerk PUB-metadata op C++
item1: "Het leesproces van de uitgever Metadata bestaat uit de volgende stappen:"
item2: Upload uw PUB-bestand met [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Methode van [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) klasse.
item3: Bestand ontleden via [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Methode van [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) interface.
item4: Bewerk metadata, bijv. Categorie door middel van [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Methode van [*DocSummaryInfo*](https:/apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) klasse.
---

{{<section feature2>}}
---
title: Aan de slag met CPP PUB API
item1: Installeer vanaf de opdrachtregel als ```nuget install Aspose.PUB.cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.PUB.cpp```.
item2: U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/pub/cpp).
---

{{<section codeexample>}}
---
title: C++-code om PUB-metadata te wijzigen
---
