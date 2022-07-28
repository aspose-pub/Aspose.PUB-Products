---
translation: true
template: /_templates/metadata-net.md
title: Edytuj wydawcę | Metadane PUB | .NET
description: Czytaj metadane wydawcy za pomocą rozwiązania API PUB .NET. Natywny interfejs API C# .NET zapewnia dostęp do właściwości SummaryInfo i DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: edytowanie sieci metadanych pub, C# metadanych pliku pub, edytor metadanych wydawcy .net, odczyt metadanych pliku pub C#, odczyt metadanych pliku pub .net
family: pub
platformtag: net
feature: metadata
aliases: /sieć/metadane/
---

{{<section banner>}}
---
h1: Edytuj metadane PUB
h2: Przeczytaj plik MS Publisher. API edytora PUB Metatada dla platformy .NET
---

{{<section overview>}}
---
p1: Format pliku dokumentu Microsoft<sup>®</sup> Publisher jest używany do tworzenia różnych typów publikacji, takich jak biuletyny, broszury, ulotki i pocztówki, a także jest używany w wiadomościach e-mail i witrynach internetowych. Pliki Pub zawierają dane tekstowe, bitmapowe i grafiki wektorowej.
p2: Metadane wydawcy to właściwości (informacje) opisujące dokumenty PUB. Są to standardowe właściwości, takie jak wydawca, tytuł, ostatni autor, organizacja, adres URL, język i inne podobne informacje. Są też dane, które są generowane automatycznie po pracy z plikiem, takie jak jego rozmiar czy czas ostatniej edycji. Te przydatne informacje są przechowywane wraz z dokumentem.
p3: Wraz z funkcjami konwersji i odczytu to rozwiązanie interfejsu API PUB dla platformy .NET umożliwia edytowanie standardowych metadanych za pomocą klas DocSummaryInfo i SummaryInfo, jak pokazano w poniższym przykładzie kodu. Możesz również użyć interfejsu API do stworzenia własnej aplikacji Edytora metadanych.
p4: Przed kodowaniem metadanych należy zintegrować interfejs API metadanych C# .NET PUB. Poniższy przykład pokazuje, jak edytować właściwość „Firma”.
---

{{<section feature1>}}
---
title: Edytuj metadane plików PUB w .NET
item1: "Proces odczytywania metadanych wydawcy składa się z następujących kroków:"
item2: Prześlij plik PUB za pomocą [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) metody [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Klasa.
item3: Przeanalizuj dokument za pomocą metody [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) metody [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Interfejs.
item4: Edytuj metadane, np. Firma za pomocą metody [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) metody [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Klasa.
---

{{<section feature2>}}
---
title: Pierwsze kroki z .NET PUB API
item1: Zainstaluj z wiersza poleceń jako ```nuget install Aspose.PUB``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.PUB```.
item2: Możesz też pobrać instalator MSI offline lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: Kod .NET do edycji metadanych PUB
---