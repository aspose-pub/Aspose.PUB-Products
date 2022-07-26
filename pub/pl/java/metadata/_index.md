---
translation: true
template: /_templates/metadata-java.md
title: Edytuj wydawcę | Metadane PUB | Jawa
description: Czytaj metadane wydawcy za pomocą rozwiązania API PUB Java. Natywny interfejs API Java zapewnia dostęp do właściwości SummaryInfo i DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: edytuj java metadanych pubu, java metadanych pliku pubu, java edytora metadanych wydawcy, czytaj java metadanych pliku publikacji, czytaj java metadanych pubu
family: pub
platformtag: java
feature: metadata
aliases: /java/metadane/
---

{{<section banner>}}
---
h1: Edytuj metadane PUB
h2: Przeczytaj plik MS Publisher. API edytora PUB Metatada dla Java
---

{{<section overview>}}
---
p1: Format pliku dokumentu Microsoft<sup>®</sup> Publisher jest używany do tworzenia różnego rodzaju publikacji, takich jak biuletyny, broszury, ulotki i pocztówki, a także jest używany w wiadomościach e-mail i witrynach internetowych. Pliki Pub zawierają dane tekstowe, bitmapowe i grafiki wektorowej.
p2: Metadane wydawcy to właściwości (informacje) opisujące dokumenty PUB. Są to standardowe właściwości, takie jak wydawca, tytuł, ostatni autor, organizacja, adres URL, język i inne podobne informacje. Są też dane, które są generowane automatycznie po pracy z plikiem, takie jak jego rozmiar czy czas ostatniej edycji. Te przydatne informacje są przechowywane wraz z dokumentem.
p3: Wraz z funkcjami konwersji i odczytu to rozwiązanie interfejsu API PUB dla języka Java umożliwia edycję standardowych metadanych za pomocą klas DocSummaryInfo i SummaryInfo, jak pokazano w poniższym przykładzie kodu. Możesz również użyć interfejsu API do stworzenia własnej aplikacji Edytora metadanych.
p4: Przed przystąpieniem do kodowania metadanych należy zintegrować interfejs API metadanych Java PUB. Poniższy przykład pokazuje, jak edytować właściwość „Język”.
---

{{<section widget>}}
---
title: Jak edytować metadane PUB za pomocą Javy
item1: "Aby edytować metadane PUB, użyjemy [Aspose.PUB for Java API](https://products.aspose.com/pub/java), który jest bogatą w funkcje, wydajną i łatwą w użyciu konwersją API dla platformy Java. Możesz pobrać jego najnowszą wersję bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pub) i zainstalować ją w swoim Maven oparty na projekcie poprzez dodanie następujących konfiguracji do pliku pom.xml."
---

{{<section feature1>}}
---
title: Przeglądaj i edytuj metadane PUB w Javie
item1: "Proces odczytywania metadanych wydawcy składa się z następujących kroków:"
item2: Prześlij swój plik PUB za pomocą [*createParser*()](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) metody [*PubFactory* ](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory) Klasa.
item3: Przeanalizuj plik za pomocą metody [*parse*()](https://apireference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) [*IPdfConverter*](https://apireference.aspose.com/pub/java/com.aspose.pub/IPubParser).
item4: Edytuj metadane np. Język za pomocą [*setLanguage*()](https://apireference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Metoda [* DocSummaryInfo*](https://apireference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo).
---

{{<section feature2>}}
---
title: wymagania systemowe
item1: Aspose.PUB for Java jest obsługiwany we wszystkich głównych systemach operacyjnych. Tylko upewnij się, że masz następujące wymagania wstępne.
item2: J2SE 8.0 (1.8) lub nowszy.
---

{{<section codeexample>}}
---
title: Kod Java do aktualizacji metadanych PUB
---