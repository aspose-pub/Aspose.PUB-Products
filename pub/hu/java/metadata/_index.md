---
translation: true
template: /_templates/metadata-java.md
title: Kiadó szerkesztése | PUB metaadatok | Jáva
description: Olvassa el a megjelenítői metaadatokat a PUB Java API-megoldással. A natív Java API hozzáférést biztosít a SummaryInfo és DocSummaryInfo tulajdonságokhoz.
url: /java/metadata/pub/
metakeywords: pub metaadatok szerkesztése java, publikációs fájl metaadatok java, kiadói metaadat szerkesztő java, publikációs fájl olvasása metaadatok java, publikációs metaadatok olvasása java
family: pub
platformtag: java
feature: metadata
aliases: /java/metadata/
---

{{<section banner>}}
---
h1: PUB-metaadatok szerkesztése
h2: Olvassa el az MS Publisher fájlt. PUB Metatada szerkesztő API Java-hoz
---

{{<section overview>}}
---
p1: A Microsoft<sup>®</sup> Publisher dokumentumfájl-formátuma különféle kiadványtípusok, például hírlevelek, brosúrák, szórólapok és képeslapok létrehozására szolgál, valamint e-mailekben és webhelyeken használatos. A publikációs fájlok szöveget, valamint bittérképes és vektorgrafikus adatokat tartalmaznak.
p2: A kiadói metaadatok olyan tulajdonságok (információk), amelyek a PUB-dokumentumokat írják le. Ezek olyan szabványos tulajdonságok, mint a kiadó, cím, utolsó szerző, szervezet, URL, nyelv és más hasonló adatok. Vannak olyan adatok is, amelyek automatikusan generálódnak egy fájllal végzett munka után, például a mérete vagy az utolsó szerkesztési idő. Ezeket a hasznos információkat a dokumentummal együtt tároljuk.
p3: A konvertálási és olvasási funkciókkal együtt ez a Java PUB API-megoldás lehetővé teszi a szabványos metaadatok szerkesztését a DocSummaryInfo és SummaryInfo osztályok segítségével, ahogy az a következő kódmintában látható. Az API-t saját metaadatszerkesztő alkalmazás létrehozására is használhatja.
p4: A metaadatok kódolása előtt integrálnia kell a Java PUB Metadata API-t. A következő példa bemutatja, hogyan szerkesztheti a „Language” tulajdonságot.
---

{{<section widget>}}
---
title: A PUB-metaadatok szerkesztése Java használatával
item1: "A PUB-metaadatok szerkesztéséhez az [Aspose.PUB for Java API](https://products.aspose.com/pub/java/) fájlt használjuk, amely funkciókban gazdag, hatékony és könnyen használható konverzió. API a Java platformhoz. Legfrissebb verzióját közvetlenül a webhelyről töltheti le [Maven](https://repository.aspose.com/pub/), és telepítheti a Mavenbe. -alapú projektet a következő konfigurációk hozzáadásával a pom.xml fájlhoz."
---

{{<section feature1>}}
---
title: PUB-metaadatok megtekintése és szerkesztése Java-on
item1: "A kiadói metaadatok olvasási folyamata a következő lépésekből áll:"
item2: Töltse fel PUB-fájlját a [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) módszerével [*PubFactory*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Osztály.
item3: A fájl elemzése a [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) metódusával [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) Interfész.
item4: Szerkessze a metaadatokat, például a nyelvet a [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) módszerrel a [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Osztály.
---

{{<section feature2>}}
---
title: rendszerkövetelmények
item1: Az Aspose.PUB for Java minden nagyobb operációs rendszeren támogatott. Csak győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.
item2: J2SE 8.0 (1.8) vagy újabb.
---

{{<section codeexample>}}
---
title: Java kód a PUB metaadatok frissítéséhez
---