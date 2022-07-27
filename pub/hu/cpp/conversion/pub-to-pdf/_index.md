---
translation: true
template: /_templates/conversion-child.md
title: PUB konvertálása PDF-be | C++
description: Konvertálja a PUB-t PDF-be a C++ API-val Windows, Linux és Mac OS X rendszeren. Kiadói konverziós funkció, amely könnyen integrálható saját megoldásába.
url: /cpp/conversion/pub-to-pdf/
metakeywords: pub pdf c++ formátumba, pub konvertálása pdf cpp formátumba, c++ pub pdf formátumba, kiadó pdf c++ formátumba
family: pub
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: PUB konvertálása PDF-be
h2: Publisher to PDF Converter. С++ API konverziós funkció.
---

{{<section overview>}}
---
p1: A Microsoft<sup>®</sup> Publisher dokumentumfájl-formátuma különféle kiadványtípusok, például hírlevelek, brosúrák, szórólapok és képeslapok létrehozására szolgál, valamint e-mailekben és webhelyeken használatos. A publikációs fájlok szöveget, valamint bittérképes és vektorgrafikus adatokat tartalmaznak.
p2: A többi Microsoft<sup>®</sup> termékhez hasonlóan a kiadói alkalmazás sem ingyenes. És mivel a formátum fájlját csak ez a program tudja megnyitni, hogy megosszák a munkája eredményét, néha át kell konvertálnia egy PUB fájlt egy jobban elterjedt formátumba. A legnépszerűbb a PUB-ból PDF-be konvertálás. Mára ezt a formátumot minden modern eszköz támogatja, és akár böngészőben is megnyitható további szoftver telepítése nélkül. Itt található a C++ PUB-ból PDF-be konvertáló funkciója. Ez a könyvtár saját projekt létrehozására is használható.
p3: Az átalakítás futtatása előtt integrálnia kell a C++ PUB to PDF Converter API-t, amely nem csak egyoldalas dokumentumokkal működik, hanem támogatja a többoldalas .pub fájlokat is.
---

{{<section feature1>}}
---
title: Konverzió PUB-ból PDF-be C++-on
item1: 'A PUB-fájl betöltése a [*CreateParser()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) módszerrel: [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Osztály.'
item2: 'A fájl elemzése a [*Parse()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) módszerrel: [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Interfész.'
item3: 'Futtassa a konverziót a [*ConvertToPdf()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter#acdea381bc8f2a2799e73a039b09ecdb5) módszerrel: [*IPdfConverter*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter) Interfész.'
---

{{<section feature2>}}
---
title: Kezdje el a C++ PUB API-t
item1: Telepítés parancssorból ```nuget install Aspose.PUB.cpp```ként, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.PUB.cpp``` paranccsal.
item2: Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a  webhelyről [downloads](https://releases.aspose.com/pub/cpp).
---

{{<section codeexample>}}
---
title: C++ kód a PUB-ból PDF-be konvertáláshoz
---

{{<section summary>}}
---
p1: A PUB-ból PDF-be konvertálás egy kötelező lépés a PUB-ból bármely más formátumba való konvertálás során. Ezt követően az átalakított fájl a kívánt formátumra konvertálható.
p2: Kipróbálhatja a PUB–PDF többplatformos alkalmazást is. Nagyon egyszerű felülettel rendelkezik, és a folyamat csak néhány másodpercet vesz igénybe.
p3: "A megoldás lehetővé teszi: Több Publisher-fájl átalakítása, PUB-fájl konvertálása PDF-be, és konvertált dokumentumok mentése az eszközre."
---