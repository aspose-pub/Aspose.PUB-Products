---
translation: true
template: /_templates/metadata-net.md
title: Kiadó szerkesztése | PUB metaadatok | .NET
description: Olvassa el a megjelenítői metaadatokat a PUB C# API-megoldással. A natív .NET API hozzáférést biztosít a SummaryInfo és DocSummaryInfo tulajdonságokhoz.
url: /net/metadata/pub/
metakeywords: publikációs metaadatok szerkesztése net, közzétételi fájl metaadatai C#, kiadói metaadatszerkesztő .net, publikációs fájl metaadatainak olvasása C#, publikációs metaadatok olvasása .net
family: pub
platformtag: net
feature: metadata
aliases: /net/metadata/
---

{{<section banner>}}
---
h1: PUB-metaadatok szerkesztése
h2: Olvassa el az MS Publisher fájlt. PUB Metatada szerkesztő API .NET-hez
---

{{<section overview>}}
---
p1: A Microsoft<sup>®</sup> Publisher dokumentumfájl-formátuma különféle kiadványtípusok, például hírlevelek, brosúrák, szórólapok és képeslapok létrehozására szolgál, valamint e-mailekben és webhelyeken használatos. A publikációs fájlok szöveget, valamint bittérképes és vektorgrafikus adatokat tartalmaznak.
p2: A kiadói metaadatok olyan tulajdonságok (információk), amelyek a PUB-dokumentumokat írják le. Ezek olyan szabványos tulajdonságok, mint a kiadó, cím, utolsó szerző, szervezet, URL, nyelv és más hasonló adatok. Vannak olyan adatok is, amelyek automatikusan generálódnak egy fájllal végzett munka után, például a mérete vagy az utolsó szerkesztési idő. Ezeket a hasznos információkat a dokumentummal együtt tároljuk.
p3: A konvertálási és olvasási funkciókkal együtt ez a .NET-hez készült PUB API-megoldás lehetővé teszi a szabványos metaadatok szerkesztését a DocSummaryInfo és SummaryInfo osztályok segítségével, ahogy az a következő kódmintában látható. Az API-t saját metaadatszerkesztő alkalmazás létrehozására is használhatja.
p4: A metaadatok kódolása előtt integrálnia kell a C# .NET PUB Metadata API-t. A következő példa bemutatja, hogyan szerkesztheti a „Cég” tulajdonságot.
---

{{<section feature1>}}
---
title: PUB-fájlok metaadatainak szerkesztése a .NET-en
item1: "A kiadói metaadatok olvasási folyamata a következő lépésekből áll:"
item2: Töltse fel PUB-fájlját a [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) módszerével [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Osztály.
item3: Elemezze a dokumentumot a  metódusával [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse) [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Interfész.
item4: Szerkessze a metaadatokat, például a vállalatot a [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) segítségével [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Osztály.
---

{{<section feature2>}}
---
title: Ismerkedjen meg a .NET PUB API-val
item1: Telepítés parancssorból ```nuget install Aspose.PUB``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.PUB``` segítségével.
item2: Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a webhelyről [letöltések](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: .NET kód a PUB metaadatok szerkesztéséhez
---