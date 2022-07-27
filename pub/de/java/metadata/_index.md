---
translation: true
template: /_templates/metadata-java.md
title: Herausgeber bearbeiten | PUB-Metadaten | Java
description: Lies Publisher-Metadaten mit der PUB Java API-Lösung. Die lokale Java-API ermöglicht Ihnen den Zugriff auf die SummaryInfo- und DocSummaryInfo-Eigenschaften.
url: /java/metadata/pub/
metakeywords: Pub-Metadaten Java bearbeiten, Pub-Datei-Metadaten Java, Herausgeber-Metadaten-Editor Java, Pub-Datei-Metadaten Java lesen, Pub-Metadaten Java lesen
family: pub
platformtag: java
feature: metadata
aliases: /java/metadaten/
---

{{<section banner>}}
---
h1: PUB-Metadaten bearbeiten
h2: Lesen Sie die MS Publisher-Datei. PUB Metatada-Editor-API für Java
---

{{<section overview>}}
---
p1: Das Dokumentdateiformat von Microsoft<sup>®</sup> Publisher wird zum Erstellen verschiedener Veröffentlichungstypen wie Newsletter, Broschüren, Flyer und Postkarten sowie in E-Mails und Websites verwendet. Pub-Dateien enthalten sowohl Text als auch Bitmap- und Vektorgrafiken.
p2: Publisher-Metadaten sind Eigenschaften (Informationen), die PUB-Dokumente beschreiben. Dies sind Standardeigenschaften wie Herausgeber, Titel, letzter Autor, Organisation, URL, Sprache und andere ähnliche Informationen. Es gibt auch Daten, die nach der Arbeit mit einer Datei automatisch generiert werden, wie etwa deren Größe oder der Zeitpunkt der letzten Bearbeitung. Diese nützlichen Informationen werden zusammen mit dem Dokument gespeichert.
p3: Neben der Konvertierungs- und Lesefunktionalität können Sie mit dieser PUB-API-Lösung für Java Standardmetadaten mithilfe der Klassen DocSummaryInfo und SummaryInfo bearbeiten, wie im folgenden Codebeispiel gezeigt. Sie können die API auch verwenden, um Ihre eigene Metadaten-Editor-Anwendung zu erstellen.
p4: Vor dem Codieren von Metadaten müssen Sie die Java PUB Metadata API integrieren. Das folgende Beispiel zeigt Ihnen, wie Sie die Eigenschaft "Sprache" bearbeiten.
---

{{<section widget>}}
---
title: So bearbeiten Sie PUB-Metadaten mit Java
item1: "Um PUB-Metadaten zu bearbeiten, verwenden wir [Aspose.PUB for Java API](https://products.aspose.com/pub/java), eine funktionsreiche, leistungsstarke und benutzerfreundliche Konvertierung API für die Java-Plattform. Sie können die neueste Version direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pub) herunterladen und in Ihrem Maven installieren -basiertes Projekt, indem Sie der pom.xml die folgenden Konfigurationen hinzufügen."
---

{{<section feature1>}}
---
title: Anzeigen und Bearbeiten von PUB-Metadaten in Java
item1: "Der Leseprozess für Publisher-Metadaten besteht aus den nächsten Schritten:"
item2: Laden Sie Ihre PUB-Datei mit [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) Methode von [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Klasse.
item3: Analysieren Sie die Datei über die Methode [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) von [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) Schnittstelle.
item4: Bearbeiten Sie Metadaten, z. B. Sprache, mittels [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Methode von [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Klasse.
---

{{<section feature2>}}
---
title: System Anforderungen
item1: Aspose.PUB für Java wird auf allen wichtigen Betriebssystemen unterstützt. Stellen Sie einfach sicher, dass Sie die folgenden Voraussetzungen erfüllen.
item2: J2SE 8.0 (1.8) oder höher.
---

{{<section codeexample>}}
---
title: Java-Code zum Aktualisieren von PUB-Metadaten
---