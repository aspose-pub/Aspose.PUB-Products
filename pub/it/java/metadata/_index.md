---
translation: true
template: /_templates/metadata-java.md
title: Modifica editore | Metadati PUB | Giava
description: Leggi i metadati dell'editore utilizzando la soluzione API Java PUB. L'API Java nativa ti dà accesso alle proprietà SummaryInfo e DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: modifica metadati pub java, pub file metadata java, editor metadata editor java, leggi pub file metadata java, leggi pub metadata java
family: pub
platformtag: java
feature: metadata
aliases: /java/metadati/
---

{{<section banner>}}
---
h1: Modifica metadati PUB
h2: Leggi il file MS Publisher. PUB Editor di metadati API per Java
---

{{<section overview>}}
---
p1: Il formato di file del documento Microsoft<sup>®</sup> Publisher viene utilizzato per creare vari tipi di pubblicazioni come newsletter, brochure, volantini e cartoline e viene utilizzato in e-mail e siti Web. I file Pub contengono testo, bitmap e dati di grafica vettoriale.
p2: I metadati dell'editore sono proprietà (informazioni) che descrivono i documenti PUB. Sono proprietà standard come editore, titolo, ultimo autore, organizzazione, URL, lingua e altre informazioni simili. Ci sono anche dati che vengono generati automaticamente dopo aver lavorato con un file, come le sue dimensioni o l'ultima modifica. Queste informazioni utili vengono memorizzate insieme al documento.
p3: Oltre alla funzionalità di conversione e lettura, questa soluzione API PUB per Java consente di modificare i metadati standard tramite le classi DocSummaryInfo e SummaryInfo, come illustrato nell'esempio di codice seguente. Puoi anche utilizzare l'API per creare la tua applicazione Editor di metadati.
p4: Prima di codificare i metadati, è necessario integrare l'API dei metadati PUB Java. L'esempio seguente mostra come modificare la proprietà "Lingua".
---

{{<section widget>}}
---
title: Come modificare i metadati PUB utilizzando Java
item1: "Per modificare i metadati PUB, utilizzeremo [Aspose.PUB for Java API](https://products.aspose.com/pub/java) che è una conversione ricca di funzionalità, potente e facile da usare API per la piattaforma Java. Puoi scaricare la sua ultima versione direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pub) e installarla all'interno del tuo Maven basato sul progetto aggiungendo le seguenti configurazioni al file pom.xml."
---

{{<section feature1>}}
---
title: Visualizza e modifica i metadati PUB su Java
item1: "Il processo di lettura dei metadati dell'editore consiste nei seguenti passaggi:"
item2: Carica il tuo file PUB utilizzando [*createParser*()](https://apiference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) Metodo di [*PubFactory* ](https://apiference.aspose.com/pub/java/com.aspose.pub/PubFactory) Classe.
item3: Analizza il file tramite il metodo [*parse*()](https://apiference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) di [*IPdfConverter*](https://afireference.aspose.com/pub/java/com.aspose.pub/IPubParser) interfaccia.
item4: Modifica i metadati, ad es. Lingua per mezzo di [*setLanguage*()](https://apiference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Metodo di [* DocSummaryInfo*](https://apiference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Classe.
---

{{<section feature2>}}
---
title: Requisiti di sistema
item1: Aspose.PUB per Java è supportato su tutti i principali sistemi operativi. Assicurati solo di avere i seguenti prerequisiti.
item2: J2SE 8.0 (1.8) o superiore.
---

{{<section codeexample>}}
---
title: Codice Java per aggiornare i metadati PUB
---