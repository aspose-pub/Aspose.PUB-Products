---
translation: true
template: /_templates/metadata-cpp.md
title: Edytuj wydawcę | Metadane PUB | C++
description: Czytaj metadane wydawcy za pomocą rozwiązania API PUB C++. Natywny interfejs API C++ zapewnia dostęp do właściwości SummaryInfo i DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: edytuj metadane publikacji, metadane pliku publikacji, edytor metadanych wydawcy, odczyt metadanych pliku publikacji, odczyt metadanych publikacji
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadane/
---

{{<section banner>}}
---
h1: Edytuj metadane PUB
h2: Przeczytaj plik MS Publisher. API edytora PUB Metatada dla C++
---

{{<section overview>}}
---
p1: Format pliku dokumentu Microsoft<sup>®</sup> Publisher jest używany do tworzenia różnego rodzaju publikacji, takich jak biuletyny, broszury, ulotki i pocztówki, a także jest używany w wiadomościach e-mail i witrynach internetowych. Pliki Pub zawierają dane tekstowe, bitmapowe i grafiki wektorowej.
p2: Metadane wydawcy to właściwości (informacje) opisujące dokumenty PUB. Są to standardowe właściwości, takie jak wydawca, tytuł, ostatni autor, organizacja, adres URL, język i inne podobne informacje. Są też dane, które są generowane automatycznie po pracy z plikiem, takie jak jego rozmiar czy czas ostatniej edycji. Te przydatne informacje są przechowywane wraz z dokumentem.
p3: Wraz z funkcjami konwersji i odczytu to rozwiązanie interfejsu API PUB dla języka C++ umożliwia edytowanie standardowych metadanych za pomocą klas DocSummaryInfo i SummaryInfo, jak pokazano w poniższym przykładzie kodu. Możesz również użyć interfejsu API do stworzenia własnej aplikacji Edytora metadanych.
p4: Przed kodowaniem metadanych musisz zintegrować C++ PUB Metadata API. Poniższy przykład pokazuje, jak edytować właściwość „Kategoria”.
---

{{<section feature1>}}
---
title: Przeglądaj i edytuj metadane PUB w C++
item1: "Proces odczytywania metadanych wydawcy składa się z następujących kroków:"
item2: Prześlij plik PUB za pomocą [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) metody [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Klasa.
item3: Przeanalizuj plik za pomocą [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Metoda [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Interfejs.
item4: Edytuj metadane, np. Kategorię za pomocą [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Metodę [*DocSummary/Info*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) /apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Klasa.
---

{{<section feature2>}}
---
title: Zacznij korzystać z CPP PUB API
item1: Zainstaluj z wiersza poleceń jako ```nuget install Aspose.PUB.cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio z ```Install-Package Aspose.PUB.cpp```.
item2: Możesz też pobrać instalator MSI offline lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.com/pub/cpp/).
---

{{<section codeexample>}}
---
title: Kod C++ do modyfikacji metadanych PUB
---
