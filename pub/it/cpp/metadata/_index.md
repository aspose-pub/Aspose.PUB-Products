---
translation: true
template: /_templates/metadata-cpp.md
title: Modifica editore | Metadati PUB | C++
description: Leggi i metadati dell'editore utilizzando la soluzione API C++ PUB. L'API C++ nativa ti dà accesso alle proprietà SummaryInfo e DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: modifica metadati pub, metadati file pub, editor metadati editore, leggi metadati file pub, leggi metadati pub
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadati/
---

{{<section banner>}}
---
h1: Modifica metadati PUB
h2: Leggi il file MS Publisher. PUB Editor di metadati API per C++
---

{{<section overview>}}
---
p1: Il formato di file del documento Microsoft<sup>®</sup> Publisher viene utilizzato per creare vari tipi di pubblicazioni come newsletter, brochure, volantini e cartoline e viene utilizzato in e-mail e siti Web. I file Pub contengono testo, bitmap e dati di grafica vettoriale.
p2: I metadati dell'editore sono proprietà (informazioni) che descrivono i documenti PUB. Sono proprietà standard come editore, titolo, ultimo autore, organizzazione, URL, lingua e altre informazioni simili. Ci sono anche dati che vengono generati automaticamente dopo aver lavorato con un file, come le sue dimensioni o l'ultima modifica. Queste informazioni utili vengono memorizzate insieme al documento.
p3: Oltre alla funzionalità di conversione e lettura, questa soluzione API PUB per C++ consente di modificare i metadati standard tramite le classi DocSummaryInfo e SummaryInfo, come illustrato nell'esempio di codice seguente. Puoi anche utilizzare l'API per creare la tua applicazione Editor di metadati.
p4: Prima di codificare i metadati, è necessario integrare l'API dei metadati PUB C++. L'esempio seguente mostra come modificare la proprietà "Categoria".
---

{{<section feature1>}}
---
title: Visualizza e modifica i metadati PUB su C++
item1: "Il processo di lettura dei metadati dell'editore consiste nei seguenti passaggi:"
item2: Carica il tuo file PUB utilizzando [*CreateParser*()](https://apiference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Metodo di [*PubFactory*](https://apireference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Classe.
item3: Analizza il file tramite [*Parse*()](https://apiference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Metodo di [*IPubParser*](https://apiference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) interfaccia.
item4: Modifica i metadati, ad es. Categoria mediante [*SetCategory*()](https://apiference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Metodo di [*DocSummaryInfo*](https://apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Classe.
---

{{<section feature2>}}
---
title: Inizia con l'API PUB CPP
item1: Installa dalla riga di comando come ```nuget install Aspose.PUB.cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.PUB.cpp```.
item2: In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/pub/cpp).
---

{{<section codeexample>}}
---
title: Codice C++ per modificare i metadati PUB
---
