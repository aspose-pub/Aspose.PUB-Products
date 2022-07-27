---
translation: true
template: /_templates/metadata-java.md
title: Uitgever bewerken | PUB-metagegevens | Java
description: Lees Publisher Metadata met behulp van PUB Java API Solution. Native Java API geeft u toegang tot de eigenschappen SummaryInfo en DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: bewerk pub metadata java, pub bestand metadata java, uitgever metadata editor java, lees pub bestand metadata java, lees pub metadata java
family: pub
platformtag: java
feature: metadata
aliases: /java/metagegevens/
---

{{<section banner>}}
---
h1: PUB-metagegevens bewerken
h2: Lees MS Publisher-bestand. PUB Metatada-editor-API voor Java
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher-documentbestandsindeling wordt gebruikt voor het maken van verschillende publicatietypen, zoals nieuwsbrieven, brochures, flyers en ansichtkaarten, en wordt gebruikt in e-mails en websites. Pub-bestanden bevatten zowel tekst als bitmap- en vectorafbeeldingsgegevens.
p2: Publisher Metadata zijn eigenschappen (informatie) die PUB-documenten beschrijven. Het zijn standaardeigenschappen zoals uitgever, titel, laatste auteur, organisatie, URL, taal en andere soortgelijke informatie. Er zijn ook gegevens die automatisch worden gegenereerd na het werken met een bestand, zoals de grootte of de laatste bewerkingstijd. Deze nuttige informatie wordt samen met het document opgeslagen.
p3: Naast de conversie- en leesfunctionaliteit, kunt u met deze PUB API-oplossing voor Java standaardmetadata bewerken door middel van de klassen DocSummaryInfo en SummaryInfo, zoals weergegeven in het volgende codevoorbeeld. U kunt de API ook gebruiken om uw eigen Metadata Editor-toepassing te maken.
p4: Voordat u Metadata codeert, moet u de Java PUB Metadata API integreren. In het volgende voorbeeld ziet u hoe u de eigenschap "Taal" kunt bewerken.
---

{{<section widget>}}
---
title: Hoe PUB-metadata te bewerken met Java
item1: "Om PUB-metadata te bewerken, gebruiken we [Aspose.PUB for Java API](https://products.aspose.com/pub/java), een functierijke, krachtige en gebruiksvriendelijke conversie API voor het Java-platform. U kunt de nieuwste versie rechtstreeks downloaden van [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pub) en installeren in uw Maven -gebaseerd project door de volgende configuraties toe te voegen aan de pom.xml."
---

{{<section feature1>}}
---
title: Bekijk en bewerk PUB-metadata op Java
item1: "Het leesproces van de uitgever Metadata bestaat uit de volgende stappen:"
item2: Upload uw PUB-bestand met behulp van [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) Methode van [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) klasse.
item3: Bestand ontleden via [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) methode van [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser)-interface.
item4: Bewerk metadata, bijv. Taal door middel van [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Methode van [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) klasse.
---

{{<section feature2>}}
---
title: systeem vereisten
item1: Aspose.PUB voor Java wordt ondersteund op alle belangrijke besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.
item2: J2SE 8.0 (1.8) of hoger.
---

{{<section codeexample>}}
---
title: Java-code om PUB-metagegevens bij te werken
---