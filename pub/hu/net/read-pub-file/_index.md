---
translation: true
template: /_templates/reader-net.md
title: PUB-fájlok olvasása | .NET
description: Nyissa meg a Publisher fájlokat programozottan. Helyszíni .NET C# API megoldás a PUB-tulajdonságok olvasásához. Használja a projektbe való integráláshoz.
url: /net/read-pub-file/
metakeywords: pub fájl megnyitása .net, kiadói fájlok megtekintése c#, kiadói fájlok olvasása, kiadói megjelenítő c#-hoz, pub formátum olvasó, publikációs fájl megnyitó
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: PUB fájl megnyitó
h2: Olvassa el a PUB fájlokat. Nyissa meg a Publisher with API for .NET alkalmazást
---

{{<section overview>}}
---
p1: A Microsoft<sup>®</sup> Publisher dokumentumfájl-formátuma különféle kiadványtípusok, például hírlevelek, brosúrák, szórólapok és képeslapok létrehozására szolgál, valamint e-mailekben és webhelyeken használatos. A publikációs fájlok szöveget, táblázatokat, valamint bittérképes és vektorgrafikus adatokat tartalmaznak.
p2: Annak ellenére, hogy a formátum meglehetősen népszerű, nem olyan népszerű, mint az olyan formátumok, mint a PDF vagy a DOCX. Az MS Publisher alkalmazás önmagában nem ingyenes.
p3: Tehát néha meg kell nyitni a PUB fájlokat a program nélkül. Erre akkor van szükség, ha meg szeretné jeleníteni a dokumentum tartalmát anélkül, hogy szerkesztené vagy bármilyen más módon manipulálná, például prezentáció vagy ismertető esetén. Ilyen célokra használhat többplatformos PUB Viewer alkalmazást.
p4: Itt kapja meg a .NET API megoldást, amellyel megtekintheti az MS Publisher dokumentum tulajdonságait, mint például a méret, szélesség, magasság, a használt betűtípusok nevei, a mezők száma és színei.
---

{{<section feature1>}}
---
title: Olvassa el a Publisher fájlokat a .NET-en
item1: "A .pub fájlok tulajdonságainak megtekintéséhez a következő lépéseket kell végrehajtania:"
item2: Integrálja a .NET PUB API-t, amely nem csak egyoldalas dokumentumokkal működik, hanem támogatja a többoldalas .pub fájlokat is.
item3: Töltse fel PUB-fájlját a [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) módszerével [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Osztály.
item4: Elemezze a dokumentumot a [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse)   metódusával [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Interfész.
item5: Nyomtassa ki a dokumentumot [*properties*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties).
---

{{<section feature2>}}
---
title: Ismerkedjen meg a .NET PUB API-val
item1: "A termék telepítésének két módja van:"
item2: Telepítse a parancssorból ```nuget install Aspose.PUB``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.PUB``` paranccsal.
item3: Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a webhelyről [letöltések](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: .NET-kód a PUB-fájlok tulajdonságainak olvasásához
---

{{<section summary>}}
---
item1: A ReadPubDocument.cs teljes kódú példájának megtekintéséhez keresse fel az Aspose.PUB.Examples.sln megoldást az Aspose.PUB dokumentáció net-példáiban, ahol további példákat is találhat a könyvtár használatára vonatkozóan.
---