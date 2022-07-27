---
translation: true
template: /_templates/metadata-net.md
title: Editar editor | Metadatos PUB | .NET
description: Lea los metadatos del editor mediante la solución API PUB .NET. La API nativa de C# le brinda acceso a las propiedades SummaryInfo y DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: editar red de metadatos de publicación, metadatos de archivo de publicación C#, editor de metadatos de publicación .net, lectura de metadatos de archivo de publicación C#, lectura de metadatos de publicación .net
family: pub
platformtag: net
feature: metadata
aliases: /red/metadatos/
---

{{<section banner>}}
---
h1: Editar metadatos de PUB
h2: Lea el archivo de MS Publisher. API del editor de Metatada PUB para .NET
---

{{<section overview>}}
---
p1: El formato de archivo de documento de Microsoft<sup>®</sup> Publisher se usa para crear varios tipos de publicaciones, como boletines, folletos, volantes y postales, y se usa en correos electrónicos y sitios web. Los archivos Pub contienen texto, así como datos de mapas de bits y gráficos vectoriales.
p2: Los metadatos del editor son propiedades (información) que describen documentos PUB. Son propiedades estándar como editor, título, último autor, organización, URL, idioma y otra información similar. También hay datos que se generan automáticamente después de trabajar con un archivo como su tamaño o la última hora de edición. Esta información útil se almacena junto con el documento.
p3: Junto con la funcionalidad de lectura y conversión, esta solución API de PUB para .NET le permite editar metadatos estándar por medio de las clases DocSummaryInfo y SummaryInfo como se muestra en el siguiente ejemplo de código. También puede utilizar la API para crear su propia aplicación Editor de metadatos.
p4: Antes de codificar metadatos, debe integrar la API de metadatos C# .NET PUB. El siguiente ejemplo le mostrará cómo editar la propiedad "Empresa".
---

{{<section feature1>}}
---
title: Editar metadatos de archivos PUB en .NET
item1: "El proceso de lectura de metadatos del editor consta de los siguientes pasos:"
item2: Cargue su archivo PUB usando [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Método de [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory) Clase.
item3: Analice el documento a través de [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Método de [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser) Interfaz.
item4: Edite metadatos, por ejemplo, Empresa mediante [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Método de [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Clase.
---

{{<section feature2>}}
---
title: Introducción a la API de .NET PUB
item1: Instale desde la línea de comandos como ```nuget install Aspose.PUB``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.PUB```.
item2: Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/pub/net).
---

{{<section codeexample>}}
---
title: Código .NET para editar metadatos PUB
---