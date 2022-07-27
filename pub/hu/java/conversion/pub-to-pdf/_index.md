---
translation: true
template: /_templates/conversion-child-java.md
title: PUB konvertálása PDF-be | Jáva
description: Konvertálja a PUB-t PDF-be a Java API használatával bármilyen platformon. Kiadói konverziós funkció, amely könnyen integrálható saját megoldásába.
url: /java/conversion/pub-to-pdf/
metakeywords: pub pdf java formátumba, pub konvertálása pdf java formátumba, java pub pdf formátumba, kiadó pdf java formátumba
family: pub
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: PUB konvertálása PDF-be
h2: Publisher to PDF Converter. Java API konverziós funkció.
---

{{<section overview>}}
---
p1: A Microsoft<sup>®</sup> Publisher dokumentumfájl-formátuma különféle kiadványtípusok, például hírlevelek, brosúrák, szórólapok és képeslapok létrehozására szolgál, valamint e-mailekben és webhelyeken használatos. A publikációs fájlok szöveget, valamint bittérképes és vektorgrafikus adatokat tartalmaznak.
p2: A többi Microsoft<sup>®</sup> termékhez hasonlóan a kiadói alkalmazás sem ingyenes. És mivel a formátum fájlját csak ez a program tudja megnyitni, hogy megosszák a munkája eredményét, néha át kell konvertálnia egy PUB fájlt egy jobban elterjedt formátumba. A legnépszerűbb a PUB-ból PDF-be konvertálás. Mára ezt a formátumot minden modern eszköz támogatja, és akár böngészőben is megnyitható további szoftver telepítése nélkül. Itt található a Java PUB-ból PDF-be konvertáló funkciója. Ez a könyvtár saját projekt létrehozására is használható.
p3: Az átalakítás futtatása előtt integrálnia kell a Java PUB to PDF Converter API-t, amely nem csak egyoldalas dokumentumokkal működik, hanem támogatja a többoldalas .pub fájlokat is.
---

{{<section widget>}}
---
title: Hogyan lehet PUB-t PDF-be konvertálni Java segítségével
item1: "A PUB PDF-be konvertálásához az Aspose.PUB for Java API fájlt használjuk, amely egy funkciókban gazdag, hatékony és könnyen használható konverziós API Java platform. Legfrissebb verzióját közvetlenül a  webhelyről töltheti le [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pub), és telepítheti a Mavenbe. -alapú projektet a következő konfigurációk hozzáadásával a pom.xml fájlhoz."
---

{{<section feature1>}}
---
title: PUB-ból PDF-be konvertálás Java-on
item1: A PUB-fájl betöltése a [*createParser()*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) módszerével [*PubFactory*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Osztály.
item2: Fájl elemzése a [*parse()*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) [*IPdfConverter*] módszerrel (https://apireference .aspose.com/pub/java/com.aspose.pub/IPubParser) Interfész.
item3: PUB konvertálása PDF-be a [*convertToPdf()*](https://reference.aspose.com/pub/java/com.aspose.pub/IPdfConverter#convertToPdf-com.aspose.pub.Document-java.lang.String segítségével -) Az [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPdfConverter) interfész módszere.
---

{{<section feature2>}}
---
title: rendszerkövetelmények
item1: Az Aspose.PUB for Java minden nagyobb operációs rendszeren támogatott. Csak győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.
item2: "J2SE 8.0 (1.8) vagy újabb."
---

{{<section codeexample>}}
---
title: Java kód a PUB-ból PDF-be konvertálásához
---

{{<section summary>}}
---
p1: A PUB-ból PDF-be konvertálás egy kötelező lépés a PUB-ból bármely más formátumba való konvertálás során. Ezt követően az átalakított fájl a kívánt formátumra konvertálható.
p2: Kipróbálhatja a PUB–PDF többplatformos alkalmazást is. Nagyon egyszerű felülettel rendelkezik, és a folyamat csak néhány másodpercet vesz igénybe.
p3: "A megoldás lehetővé teszi a következőket: Több Publisher-fájl átalakítása, PUB-fájl konvertálása PDF-be, és konvertált dokumentumok mentése eszközére."
---