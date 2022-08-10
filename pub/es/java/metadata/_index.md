---
translation: true
template: /_templates/metadata-java.md
title: Editar editor | Metadatos PUB | Java
description: Lea los metadatos del editor mediante la solución API PUB Java. La API nativa de Java le brinda acceso a las propiedades SummaryInfo y DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: editar metadatos java de publicación, metadatos de archivo de publicación java, editor de metadatos de editor java, leer metadatos de archivo de publicación java, leer metadatos de publicación java
family: pub
platformtag: java
feature: metadata
aliases: /java/metadatos/
---

{{<section banner>}}
---
h1: Editar metadatos de PUB
h2: Lea el archivo de MS Publisher. API del editor de Metatada PUB para Java
---

{{<section overview>}}
---
p1: El formato de archivo de documento de Microsoft<sup>®</sup> Publisher se usa para crear varios tipos de publicaciones, como boletines, folletos, volantes y postales, y se usa en correos electrónicos y sitios web. Los archivos Pub contienen texto, así como datos de mapas de bits y gráficos vectoriales.
p2: Los metadatos del editor son propiedades (información) que describen documentos PUB. Son propiedades estándar como editor, título, último autor, organización, URL, idioma y otra información similar. También hay datos que se generan automáticamente después de trabajar con un archivo como su tamaño o la última hora de edición. Esta información útil se almacena junto con el documento.
p3: Junto con la funcionalidad de lectura y conversión, esta solución API de PUB para Java le permite editar metadatos estándar por medio de las clases DocSummaryInfo y SummaryInfo como se muestra en el siguiente ejemplo de código. También puede utilizar la API para crear su propia aplicación Editor de metadatos.
p4: Antes de codificar metadatos, debe integrar la API de metadatos Java PUB. El siguiente ejemplo le mostrará cómo editar la propiedad "Idioma".
---

{{<section widget>}}
---
title: Cómo editar metadatos PUB usando Java
item1: "Para editar metadatos de PUB, usaremos [Aspose.PUB para la API de Java](https://products.aspose.com/pub/java/), que es una conversión rica en funciones, potente y fácil de usar. API para la plataforma Java. Puede descargar su última versión directamente desde [Maven](https://repository.aspose.com/pub/) e instalarlo dentro de su Maven -proyecto basado agregando las siguientes configuraciones al pom.xml."
---

{{<section feature1>}}
---
title: Ver y editar metadatos PUB en Java
item1: "El proceso de lectura de metadatos del editor consta de los siguientes pasos:"
item2: Cargue su archivo PUB usando [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) Método de [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Clase.
item3: Analizar el archivo a través del método [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) de [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) Interfaz.
item4: Edite metadatos, por ejemplo, idioma mediante [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Método de [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Clase.
---

{{<section feature2>}}
---
title: Requisitos del sistema
item1: Aspose.PUB para Java es compatible con todos los principales sistemas operativos. Solo asegúrese de tener los siguientes requisitos previos.
item2: J2SE 8.0 (1.8) o superior.
---

{{<section codeexample>}}
---
title: Código Java para actualizar metadatos PUB
---