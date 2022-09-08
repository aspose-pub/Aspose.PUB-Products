---
translation: true
template: /_templates/metadata-java.md
title: Upravit vydavatele | Metadata PUB | Jáva
description: Číst metadata souborů vydavatele pomocí řešení PUB Java API pro různé platformy. On-premise Java API vám poskytuje přístup k vlastnostem SummaryInfo a DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: upravit metadata pub java, metadata pub file java, editor metadat vydavatele java, read pub file metadata java, read pub metadata java
family: pub
platformtag: java
feature: metadata
aliases: /java/metadata/
---

{{<section banner>}}
---
h1: Upravit metadata PUB
h2: Přečtěte si soubor MS Publisher. PUB Metatada editor API pro Javu
---

{{<section overview>}}
---
p1: Formát souboru dokumentu Microsoft<sup>®</sup> Publisher se používá k vytváření různých typů publikací, jako jsou informační bulletiny, brožury, letáky a pohlednice, a používá se v e-mailech a na webových stránkách. Pub soubory obsahují text i bitmapová a vektorová grafická data.
p2: Metadata vydavatele jsou vlastnosti (informace), které popisují dokumenty PUB. Jsou to standardní vlastnosti, jako je vydavatel, název, poslední autor, organizace, adresa URL, jazyk a další podobné informace. Existují také data, která se generují automaticky po práci se souborem, jako je jeho velikost nebo čas poslední úpravy. Tyto užitečné informace jsou uloženy spolu s dokumentem.
p3: Spolu s funkcemi konverze a čtení vám toto řešení PUB API pro Java umožňuje upravovat standardní metadata pomocí tříd DocSummaryInfo a SummaryInfo, jak je znázorněno v následující ukázce kódu. Můžete také použít API k vytvoření vlastní aplikace Metadata Editor.
p4: Před kódováním metadat musíte integrovat Java PUB Metadata API. Následující příklad vám ukáže, jak upravit vlastnost "Language".
---

{{<section widget>}}
---
title: Jak upravit metadata PUB pomocí Javy
item1: "Abychom mohli upravit metadata PUB, použijeme [Aspose.PUB for Java API](https://products.aspose.com/pub/java/), což je funkčně bohatý, výkonný a snadno použitelný převod. API pro platformu Java. Jeho nejnovější verzi si můžete stáhnout přímo z [Aspose Maven Repository](https://repository.aspose.com/pub/) a nainstalovat do svého Maven -založený projekt přidáním následujících konfigurací do souboru pom.xml."
---

{{<section feature1>}}
---
title: Zobrazení a úprava metadat PUB v Javě
item1: "Proces čtení metadat vydavatele se skládá z následujících kroků:"
item2: Nahrajte svůj soubor PUB pomocí metody [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) metody [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Třída.
item3: Analyzujte soubor pomocí [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) metody [*IPdfConverter*](https://apireferenceRozhraní.aspose.com/pub/java/com.aspose.pub/IPubParser).
item4: Upravte metadata, např. jazyk, pomocí [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Metoda [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Třída.
---

{{<section feature2>}}
---
title: Požadavky na systém
item1: Aspose.PUB for Java je podporován na všech hlavních operačních systémech. Jen se ujistěte, že máte následující předpoklady.
item2: J2SE 8.0 (1.8) nebo vyšší.
---

{{<section codeexample>}}
---
title: Java kód pro aktualizaci metadat PUB
---