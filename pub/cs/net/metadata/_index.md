---
translation: true
template: /_templates/metadata-net.md
title: Upravit vydavatele | Metadata PUB | .NET
description: Čtěte metadata vydavatele pomocí řešení PUB .NET API. Nativní rozhraní C# .NET API vám poskytuje přístup k vlastnostem SummaryInfo a DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: editovat pub metadata net, pub file metadata C#, vydavatel metadat editor .net, read pub file metadata C#, read pub metadata .net
family: pub
platformtag: net
feature: metadata
aliases: /net/metadata/
---

{{<section banner>}}
---
h1: Upravit metadata PUB
h2: Přečtěte si soubor MS Publisher. PUB Metatada editor API pro .NET
---

{{<section overview>}}
---
p1: Formát souboru dokumentu Microsoft<sup>®</sup> Publisher se používá k vytváření různých typů publikací, jako jsou informační bulletiny, brožury, letáky a pohlednice, a používá se v e-mailech a na webových stránkách. Pub soubory obsahují text i bitmapová a vektorová grafická data.
p2: Metadata vydavatele jsou vlastnosti (informace), které popisují dokumenty PUB. Jsou to standardní vlastnosti, jako je vydavatel, název, poslední autor, organizace, adresa URL, jazyk a další podobné informace. Existují také data, která se generují automaticky po práci se souborem, jako je jeho velikost nebo čas poslední úpravy. Tyto užitečné informace jsou uloženy spolu s dokumentem.
p3: Spolu s funkcemi konverze a čtení vám toto řešení PUB API pro .NET umožňuje upravovat standardní metadata pomocí tříd DocSummaryInfo a SummaryInfo, jak je znázorněno v následující ukázce kódu. Můžete také použít API k vytvoření vlastní aplikace Metadata Editor.
p4: Před kódováním metadat musíte integrovat C# .NET PUB Metadata API. Následující příklad vám ukáže, jak upravit vlastnost "Společnost".
---

{{<section feature1>}}
---
title: Upravte metadata souborů PUB na .NET
item1: "Proces čtení metadat vydavatele se skládá z následujících kroků:"
item2: Nahrajte svůj soubor PUB pomocí metody [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/createparser/) metody [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Třída.
item3: Analyzujte dokument pomocí metody [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/parse/) metody [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Rozhraní.
item4: Upravte metadata, např. společnost, pomocí [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/setcompany/) Metoda [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/) Třída.
---

{{<section feature2>}}
---
title: Začněte s .NET PUB API
item1: Instalujte z příkazového řádku jako ```nuget install Aspose.PUB``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.PUB```.
item2: Případně stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: Kód .NET pro úpravu metadat PUB
---