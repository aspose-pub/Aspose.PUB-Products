---
translation: true
template: /_templates/metadata-net.md
title: Herausgeber bearbeiten | PUB-Metadaten | .NET
description: Lesen Sie Publisher-Metadaten mit der PUB .NET API-Lösung. Die native C#-API bietet Ihnen Zugriff auf die SummaryInfo- und DocSummaryInfo-Eigenschaften.
url: /net/metadata/pub/
metakeywords: Pub-Metadaten net bearbeiten, Pub-Datei-Metadaten C#, Herausgeber-Metadaten-Editor .net, Pub-Datei-Metadaten C# lesen, Pub-Metadaten .net lesen
family: pub
platformtag: net
feature: metadata
aliases: /net/metadaten/
---

{{<section banner>}}
---
h1: PUB-Metadaten bearbeiten
h2: Lesen Sie die MS Publisher-Datei. PUB Metatada-Editor-API für .NET
---

{{<section overview>}}
---
p1: Das Dokumentdateiformat von Microsoft<sup>®</sup> Publisher wird zum Erstellen verschiedener Veröffentlichungstypen wie Newsletter, Broschüren, Flyer und Postkarten sowie in E-Mails und Websites verwendet. Pub-Dateien enthalten sowohl Text als auch Bitmap- und Vektorgrafiken.
p2: Publisher-Metadaten sind Eigenschaften (Informationen), die PUB-Dokumente beschreiben. Dies sind Standardeigenschaften wie Herausgeber, Titel, letzter Autor, Organisation, URL, Sprache und andere ähnliche Informationen. Es gibt auch Daten, die nach der Arbeit mit einer Datei automatisch generiert werden, wie etwa deren Größe oder der Zeitpunkt der letzten Bearbeitung. Diese nützlichen Informationen werden zusammen mit dem Dokument gespeichert.
p3: Neben der Konvertierungs- und Lesefunktionalität können Sie mit dieser PUB-API-Lösung für .NET Standardmetadaten mithilfe der Klassen DocSummaryInfo und SummaryInfo bearbeiten, wie im folgenden Codebeispiel gezeigt. Sie können die API auch verwenden, um Ihre eigene Metadaten-Editor-Anwendung zu erstellen.
p4: Vor dem Codieren von Metadaten müssen Sie die C# .NET PUB-Metadaten-API integrieren. Das folgende Beispiel zeigt Ihnen, wie Sie die Eigenschaft "Firma" bearbeiten.
---

{{<section feature1>}}
---
title: Bearbeiten Sie Metadaten von PUB-Dateien in .NET
item1: "Der Leseprozess für Publisher-Metadaten besteht aus den nächsten Schritten:"
item2: Laden Sie Ihre PUB-Datei mit [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Methode von [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Klasse.
item3: Analysieren Sie das Dokument über [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Methode von [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Schnittstelle.
item4: Bearbeiten Sie Metadaten, z. B. Unternehmen, mithilfe von [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Methode von [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Klasse.
---

{{<section feature2>}}
---
title: Erste Schritte mit der .NET PUB-API
item1: Installieren Sie von der Befehlszeile als ```nuget install Aspose.PUB``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.PUB```.
item2: Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [Downloads](https://releases.aspose.com/pub/net/) herunterladen.
---

{{<section codeexample>}}
---
title: .NET-Code zum Bearbeiten von PUB-Metadaten
---