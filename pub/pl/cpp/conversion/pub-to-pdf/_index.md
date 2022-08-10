---
translation: true
template: /_templates/conversion-child.md
title: Konwertuj PUB na PDF | C++
description: Konwertuj PUB na PDF za pomocą interfejsu API C++ w systemach Windows, Linux i Mac OS X. Funkcja konwersji programu Publisher, którą można łatwo zintegrować z własnym rozwiązaniem.
url: /cpp/conversion/pub-to-pdf/
metakeywords: pub na pdf c++, konwersja pub na pdf cpp, c++ pub na pdf, wydawca na pdf c++
family: pub
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Konwertuj PUB na PDF
h2: Wydawca do konwertera PDF. Funkcjonalność konwersji API С++.
---

{{<section overview>}}
---
p1: Format pliku dokumentu Microsoft<sup>®</sup> Publisher jest używany do tworzenia różnych typów publikacji, takich jak biuletyny, broszury, ulotki i pocztówki, a także jest używany w wiadomościach e-mail i witrynach internetowych. Pliki Pub zawierają dane tekstowe, bitmapowe i grafiki wektorowej.
p2: Jak wszystkie inne produkty Microsoft<sup>®</sup>, aplikacja Publisher sama w sobie nie jest bezpłatna. A ponieważ plik tego formatu może zostać otwarty tylko przez ten program, aby udostępnić wyniki swojej pracy, czasami będziesz musiał przekonwertować plik PUB na bardziej rozpowszechniony format. Najpopularniejszą ze wszystkich jest konwersja PUB do PDF. Obecnie ten format jest obsługiwany przez wszystkie nowoczesne urządzenia i można go nawet otworzyć w przeglądarce bez instalowania dodatkowego oprogramowania. Oto funkcja konwersji PUB do PDF dla C++. Ta biblioteka może być również wykorzystana do stworzenia własnego projektu.
p3: Przed uruchomieniem konwersji musisz zintegrować C++ PUB z PDF Converter API, który działa nie tylko z dokumentami jednostronicowymi, ale także obsługuje wielostronicowe pliki .pub.
---

{{<section feature1>}}
---
title: Konwersja PUB do PDF w C++
item1: Załaduj plik PUB za pomocą [*CreateParser()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) metody [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Klasa.
item2: Przeanalizuj plik za pomocą [*Parse()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) metody [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Interfejs.
item3: Uruchom konwersję za pomocą [*ConvertToPdf()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter#acdea381bc8f2a2799e73a039b09ecdb5) metody [*IPdfConverter*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter) Interfejs.
---

{{<section feature2>}}
---
title: Zacznij korzystać z C++ PUB API
item1: Zainstaluj z wiersza polecenia jako ```nuget install Aspose.PUB.cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio z ```Install-Package Aspose.PUB.cpp```.
item2: Możesz też pobrać instalator MSI offline lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.com/pub/cpp/).
---

{{<section codeexample>}}
---
title: Kod C++ do konwersji PUB na PDF
---

{{<section summary>}}
---
p1: Konwersja PUB do PDF jest wymaganym krokiem w PUB do konwersji dowolnego innego formatu. Następnie przekształcony plik można przekonwertować do potrzebnego formatu.
p2: Możesz także wypróbować wieloplatformową aplikację PUB do PDF. Ma bardzo prosty interfejs, a proces zajmie tylko kilka sekund.
p3: "Rozwiązanie umożliwia: Przekształcanie wielu plików programu Publisher, konwersję PUB do formatu PDF i zapisywanie przekonwertowanych dokumentów na urządzeniu."
---