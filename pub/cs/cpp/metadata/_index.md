---
translation: true
template: /_templates/metadata-cpp.md
title: Upravit vydavatele | Metadata PUB | C++
description: Číst metadata souborů Publisher pomocí řešení PUB C++ API. On-premise C++ API vám poskytuje přístup k vlastnostem SummaryInfo a DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: editovat metadata pubu, metadata pub souboru, editor metadat vydavatele, číst metadata pub souboru, číst metadata pubu
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadata/
---

{{<section banner>}}
---
h1: Upravit metadata PUB
h2: Přečtěte si soubor MS Publisher. PUB Metatada editor API pro C++
---

{{<section overview>}}
---
p1: Formát souboru dokumentu Microsoft<sup>®</sup> Publisher se používá k vytváření různých typů publikací, jako jsou informační bulletiny, brožury, letáky a pohlednice, a používá se v e-mailech a na webových stránkách. Pub soubory obsahují text i bitmapová a vektorová grafická data.
p2: Metadata vydavatele jsou vlastnosti (informace), které popisují dokumenty PUB. Jsou to standardní vlastnosti, jako je vydavatel, název, poslední autor, organizace, adresa URL, jazyk a další podobné informace. Existují také data, která se generují automaticky po práci se souborem, jako je jeho velikost nebo čas poslední úpravy. Tyto užitečné informace jsou uloženy spolu s dokumentem.
p3: Spolu s funkcemi konverze a čtení vám toto řešení PUB API pro C++ umožňuje upravovat standardní metadata pomocí tříd DocSummaryInfo a SummaryInfo, jak je znázorněno v následující ukázce kódu. Můžete také použít API k vytvoření vlastní aplikace Metadata Editor.
p4: Před kódováním metadat musíte integrovat C++ PUB Metadata API. Následující příklad vám ukáže, jak upravit vlastnost "Category".
---

{{<section feature1>}}
---
title: Zobrazit a upravit metadata PUB v C++
item1: "Proces čtení metadat vydavatele se skládá z následujících kroků:"
item2: Nahrajte svůj soubor PUB pomocí metody [*CreateParser*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) metody [*PubFactory*](https://reference*].aspose.com/pub/cpp/class/aspose.pub.pub_factory) Třída.
item3: Analyzujte soubor pomocí [*Parse*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Metoda [*IPubParser*].asposeapireference .com/pub/cpp/class/aspose.pub.i_pub_parser) Rozhraní.
item4: Upravte metadata, např. kategorii, pomocí [*SetCategory*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec]Metoda[*Info/Summary]z[*Doc/Doc/apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Třída.
---

{{<section feature2>}}
---
title: Začněte s CPP PUB API
item1: Instalujte z příkazového řádku jako ```nuget install Aspose.PUB.cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.PUB.cpp```.
item2: Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/pub/cpp).
---

{{<section codeexample>}}
---
title: C++ kód pro úpravu metadat PUB
---
