---
translation: true
template: /_templates/metadata-cpp.md
title: Editar editor | Metadatos PUB | C++
description: Lea los metadatos del editor mediante la solución API PUB C++. La API nativa de C++ le brinda acceso a las propiedades SummaryInfo y DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: editar metadatos de pub, metadatos de archivos de pub, editor de metadatos de editores, leer metadatos de archivos de pub, leer metadatos de pub
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadatos/
---

{{<section banner>}}
---
h1: Editar metadatos de PUB
h2: Lea el archivo de MS Publisher. API del editor de Metatada PUB para C++
---

{{<section overview>}}
---
p1: El formato de archivo de documento de Microsoft<sup>®</sup> Publisher se usa para crear varios tipos de publicaciones, como boletines, folletos, volantes y postales, y se usa en correos electrónicos y sitios web. Los archivos Pub contienen texto, así como datos de mapas de bits y gráficos vectoriales.
p2: Los metadatos del editor son propiedades (información) que describen documentos PUB. Son propiedades estándar como editor, título, último autor, organización, URL, idioma y otra información similar. También hay datos que se generan automáticamente después de trabajar con un archivo como su tamaño o la última hora de edición. Esta información útil se almacena junto con el documento.
p3: Junto con la funcionalidad de lectura y conversión, esta solución API de PUB para C++ le permite editar metadatos estándar mediante las clases DocSummaryInfo y SummaryInfo, como se muestra en el siguiente ejemplo de código. También puede utilizar la API para crear su propia aplicación Editor de metadatos.
p4: Antes de codificar los metadatos, debe integrar la API de metadatos de C++ PUB. El siguiente ejemplo le mostrará cómo editar la propiedad "Categoría".
---

{{<section feature1>}}
---
title: Ver y editar metadatos PUB en C++
item1: "El proceso de lectura de metadatos del editor consta de los siguientes pasos:"
item2: Cargue su archivo PUB usando [*CreateParser*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Método de [*PubFactory*](https://apireference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Clase.
item3: Analizar el archivo mediante [*Parse*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Método de [*IPubParser*](https://apireference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Interfaz.
item4: Edite metadatos, por ejemplo, Categoría mediante [*SetCategory*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Método de [*DocSummaryInfo*](https://apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Clase.
---

{{<section feature2>}}
---
title: Introducción a la API de CPP PUB
item1: Instale desde la línea de comandos como ```nuget install Aspose.PUB.cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.PUB.cpp```.
item2: Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/pub/cpp).
---

{{<section codeexample>}}
---
title: Código C++ para modificar metadatos PUB
---
