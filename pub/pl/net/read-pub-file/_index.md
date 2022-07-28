---
translation: true
template: /_templates/reader-net.md
title: Czytaj pliki PUB | .NET
description: Programowo otwieraj pliki programu Publisher. Rozwiązanie C# .NET API do odczytywania właściwości PUB. Użyj go, aby zintegrować się ze swoim projektem.
url: /net/read-pub-file/
metakeywords: otwórz plik publikacji .net, wyświetl pliki wydawcy c#, odczytaj pliki wydawcy, przeglądarka wydawcy dla c#, czytnik formatu pub, narzędzie do otwierania plików publikacji
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: Otwieracz plików PUB
h2: Czytaj pliki PUB. Open Publisher z API dla .NET
---

{{<section overview>}}
---
p1: Format pliku dokumentu Microsoft<sup>®</sup> Publisher jest używany do tworzenia różnego rodzaju publikacji, takich jak biuletyny, broszury, ulotki i pocztówki, a także jest używany w wiadomościach e-mail i witrynach internetowych. Pliki publikacji zawierają tekst, tabele oraz dane bitmapowe i grafiki wektorowej.
p2: Mimo, że format jest dość popularny, nie jest tak popularny jak formaty PDF czy DOCX. Aplikacja MS Publisher sama w sobie nie jest darmowa.
p3: Dlatego czasami wymagane jest otwieranie plików PUB bez tego programu. Jest to potrzebne, gdy chcesz pokazać zawartość dokumentu bez edytowania lub manipulowania nim w inny sposób, na przykład podczas prezentacji lub recenzji. W tym celu możesz skorzystać z wieloplatformowej aplikacji PUB Viewer.
p4: Tutaj otrzymasz rozwiązanie .NET API, które pozwala przeglądać właściwości dokumentu MS Publisher, takie jak rozmiar, szerokość, wysokość, nazwy używanych czcionek, liczba pól i kolory.
---

{{<section feature1>}}
---
title: Czytaj pliki Publishera w .NET
item1: "Aby wyświetlić właściwości plików .pub, musisz wykonać następujące czynności:"
item2: Zintegruj interfejs API .NET PUB, który działa nie tylko z dokumentami jednostronicowymi, ale także obsługuje wielostronicowe pliki .pub.
item3: Prześlij plik PUB za pomocą [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) metody [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Klasa.
item4: Przeanalizuj dokument za pomocą metody [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) metody [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Interfejs.
item5: Wydrukuj dokument [*właściwości*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties).
---

{{<section feature2>}}
---
title: Pierwsze kroki z .NET PUB API
item1: "Produkt można zainstalować na dwa sposoby:"
item2: Zainstaluj z wiersza polecenia jako ```nuget install Aspose.PUB``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.PUB```.
item3: Możesz też pobrać instalator MSI offline lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: Kod .NET do odczytu właściwości plików PUB
---

{{<section summary>}}
---
item1: Aby zobaczyć pełny przykład kodu ReadPubDocument.cs, przejdź do rozwiązania Aspose.PUB.Examples.sln, w przykładach sieciowych dokumentacji Aspose.PUB, gdzie można również znaleźć inne przykłady korzystania z biblioteki.
---