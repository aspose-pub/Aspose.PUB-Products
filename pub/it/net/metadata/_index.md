---
translation: true
template: /_templates/metadata-net.md
title: Modifica editore | Metadati PUB | .NET
description: Leggi i metadati dell'editore utilizzando la soluzione API C# .NET PUB. L'API .NET nativa ti dà accesso alle proprietà SummaryInfo e DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: modifica pub metadata net, pub file metadata C#, editor metadata editor .net, leggi pub file metadata C#, leggi pub metadata .net
family: pub
platformtag: net
feature: metadata
aliases: /net/metadati/
---

{{<section banner>}}
---
h1: Modifica metadati PUB
h2: Leggi il file MS Publisher. PUB Editor di metadati API per .NET
---

{{<section overview>}}
---
p1: Il formato di file del documento Microsoft<sup>®</sup> Publisher viene utilizzato per creare vari tipi di pubblicazioni come newsletter, brochure, volantini e cartoline e viene utilizzato in e-mail e siti Web. I file Pub contengono testo, bitmap e dati di grafica vettoriale.
p2: I metadati dell'editore sono proprietà (informazioni) che descrivono i documenti PUB. Sono proprietà standard come editore, titolo, ultimo autore, organizzazione, URL, lingua e altre informazioni simili. Ci sono anche dati che vengono generati automaticamente dopo aver lavorato con un file, come le sue dimensioni o l'ultima modifica. Queste informazioni utili vengono memorizzate insieme al documento.
p3: Oltre alla funzionalità di conversione e lettura, questa soluzione API PUB per .NET consente di modificare i metadati standard tramite le classi DocSummaryInfo e SummaryInfo, come illustrato nell'esempio di codice seguente. Puoi anche utilizzare l'API per creare la tua applicazione Editor di metadati.
p4: Prima di codificare i metadati, è necessario integrare l'API dei metadati C# .NET PUB. L'esempio seguente mostra come modificare la proprietà "Azienda".
---

{{<section feature1>}}
---
title: Modifica i metadati dei file PUB su .NET
item1: "Il processo di lettura dei metadati dell'editore consiste nei seguenti passaggi:"
item2: Carica il tuo file PUB utilizzando [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) Metodo di [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Classe.
item3: Analizza il documento tramite [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse) Metodo di [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) interfaccia.
item4: Modifica i metadati, ad es. Società tramite [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Metodo di [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Classe.
---

{{<section feature2>}}
---
title: Inizia con l'API .NET PUB
item1: Installa dalla riga di comando come ```nuget install Aspose.PUB``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.PUB```.
item2: In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: Codice .NET per modificare i metadati PUB
---