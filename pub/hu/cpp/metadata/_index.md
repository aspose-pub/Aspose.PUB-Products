---
translation: true
template: /_templates/metadata-cpp.md
title: Kiadó szerkesztése | PUB metaadatok | C++
description: Olvassa el a megjelenítői metaadatokat a PUB C++ API-megoldással. A natív C++ API hozzáférést biztosít a SummaryInfo és DocSummaryInfo tulajdonságokhoz.
url: /cpp/metadata/pub/
metakeywords: publikációs metaadatok szerkesztése, közzétételi fájl metaadatai, kiadói metaadat-szerkesztő, publikációs fájl metaadatainak olvasása, publikációs metaadatok olvasása
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadata/
---

{{<section banner>}}
---
h1: PUB-metaadatok szerkesztése
h2: Olvassa el az MS Publisher fájlt. PUB Metatada szerkesztő API C++-hoz
---

{{<section overview>}}
---
p1: A Microsoft<sup>®</sup> Publisher dokumentumfájl-formátuma különféle kiadványtípusok, például hírlevelek, brosúrák, szórólapok és képeslapok létrehozására szolgál, valamint e-mailekben és webhelyeken használatos. A publikációs fájlok szöveget, valamint bittérképes és vektorgrafikus adatokat tartalmaznak.
p2: A kiadói metaadatok olyan tulajdonságok (információk), amelyek a PUB-dokumentumokat írják le. Ezek olyan szabványos tulajdonságok, mint a kiadó, cím, utolsó szerző, szervezet, URL, nyelv és más hasonló adatok. Vannak olyan adatok is, amelyek automatikusan generálódnak egy fájllal végzett munka után, például a mérete vagy az utolsó szerkesztési idő. Ezeket a hasznos információkat a dokumentummal együtt tároljuk.
p3: A konvertálási és olvasási funkciókkal együtt ez a C++-hoz készült PUB API-megoldás lehetővé teszi a szabványos metaadatok szerkesztését a DocSummaryInfo és SummaryInfo osztályok segítségével, ahogy az a következő kódmintában látható. Az API-t saját metaadatszerkesztő alkalmazás létrehozására is használhatja.
p4: A metaadatok kódolása előtt integrálnia kell a C++ PUB Metadata API-t. A következő példa bemutatja, hogyan szerkesztheti a „Kategória” tulajdonságot.
---

{{<section feature1>}}
---
title: PUB-metaadatok megtekintése és szerkesztése C++-on
item1: "A kiadói metaadatok olvasási folyamata a következő lépésekből áll:"
item2: 'Töltsd fel PUB-fájlodat a [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) módszerrel: [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Osztály.'
item3: 'Fájl elemzése a következővel: [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Az [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Interfész.'
item4: Szerkessze a metaadatokat, például a kategóriát a  segítségével [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) a Metódusa [*DocSummaryInfo*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Osztály.
---

{{<section feature2>}}
---
title: Ismerkedjen meg a CPP PUB API-val
item1: Telepítés parancssorból ```nuget install Aspose.PUB.cpp```ként, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.PUB.cpp``` paranccsal.
item2: Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a  webhelyről [downloads](https://releases.aspose.com/pub/cpp).
---

{{<section codeexample>}}
---
title: C++ kód a PUB metaadatok módosításához
---
