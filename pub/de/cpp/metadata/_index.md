---
translation: true
template: /_templates/metadata-cpp.md
title: Herausgeber bearbeiten | PUB-Metadaten | C++
description: Lies Publisher-Metadaten mit der PUB C++ API-Lösung. Die lokale C++-API ermöglicht Ihnen den Zugriff auf die SummaryInfo- und DocSummaryInfo-Eigenschaften.
url: /cpp/metadata/pub/
metakeywords: Pub-Metadaten bearbeiten, Pub-Datei-Metadaten, Herausgeber-Metadaten-Editor, Pub-Datei-Metadaten lesen, Pub-Metadaten lesen
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadaten/
---

{{<section banner>}}
---
h1: PUB-Metadaten bearbeiten
h2: Lesen Sie die MS Publisher-Datei. PUB Metatada-Editor-API für C++
---

{{<section overview>}}
---
p1: Das Dokumentdateiformat von Microsoft<sup>®</sup> Publisher wird zum Erstellen verschiedener Veröffentlichungstypen wie Newsletter, Broschüren, Flyer und Postkarten sowie in E-Mails und Websites verwendet. Pub-Dateien enthalten sowohl Text als auch Bitmap- und Vektorgrafiken.
p2: Publisher-Metadaten sind Eigenschaften (Informationen), die PUB-Dokumente beschreiben. Dies sind Standardeigenschaften wie Herausgeber, Titel, letzter Autor, Organisation, URL, Sprache und andere ähnliche Informationen. Es gibt auch Daten, die nach der Arbeit mit einer Datei automatisch generiert werden, wie etwa deren Größe oder der Zeitpunkt der letzten Bearbeitung. Diese nützlichen Informationen werden zusammen mit dem Dokument gespeichert.
p3: Neben der Konvertierungs- und Lesefunktionalität können Sie mit dieser PUB-API-Lösung für C++ Standardmetadaten mithilfe der Klassen DocSummaryInfo und SummaryInfo bearbeiten, wie im folgenden Codebeispiel gezeigt. Sie können die API auch verwenden, um Ihre eigene Metadaten-Editor-Anwendung zu erstellen.
p4: Vor dem Codieren von Metadaten müssen Sie die C++ PUB-Metadaten-API integrieren. Das folgende Beispiel zeigt Ihnen, wie Sie die Eigenschaft "Kategorie" bearbeiten.
---

{{<section feature1>}}
---
title: Anzeigen und Bearbeiten von PUB-Metadaten in C++
item1: "Der Leseprozess für Publisher-Metadaten besteht aus den nächsten Schritten:"
item2: Laden Sie Ihre PUB-Datei mit [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Methode von [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Klasse.
item3: Analysieren Sie die Datei über [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Methode von [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Schnittstelle.
item4: Metadaten bearbeiten z.B. Kategorie mittels [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Methode von [*DocSummaryInfo*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Klasse.
---

{{<section feature2>}}
---
title: Erste Schritte mit der CPP PUB-API
item1: Installieren Sie von der Befehlszeile als ```nuget install Aspose.PUB.cpp``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.PUB.cpp```.
item2: Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/pub/cpp/) herunterladen.
---

{{<section codeexample>}}
---
title: C++-Code zum Ändern von PUB-Metadaten
---
