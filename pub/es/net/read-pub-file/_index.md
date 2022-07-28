---
translation: true
template: /_templates/reader-net.md
title: Leer archivos PUB | .NET
description: Abra los archivos de Publisher mediante programación. Solución de API .NET C# local para leer propiedades PUB. Úselo para integrarlo en su proyecto.
url: /net/read-pub-file/
metakeywords: abrir archivo pub .net, ver archivos de publicación c#, leer archivos de publicación, visor de publicación para c#, lector de formato de publicación, abridor de archivos de publicación
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: abridor de archivos PUB
h2: Leer archivos PUB. Open Publisher con API para .NET
---

{{<section overview>}}
---
p1: El formato de archivo de documento de Microsoft<sup>®</sup> Publisher se usa para crear varios tipos de publicaciones, como boletines, folletos, volantes y postales, y se usa en correos electrónicos y sitios web. Los archivos Pub contienen texto, tablas, mapas de bits y datos de gráficos vectoriales.
p2: Aunque el formato es bastante popular, no es tan popular como formatos como PDF o DOCX. La aplicación MS Publisher no es gratuita en sí misma.
p3: Entonces, a veces se requiere abrir archivos PUB sin este programa. Esto es necesario cuando desea mostrar el contenido del documento, sin editarlo ni manipularlo de ninguna otra manera, como cuando tiene una presentación o revisión. Para tales fines, puede utilizar una aplicación PUB Viewer multiplataforma.
p4: Aquí obtendrá la solución API de .NET que le permite ver las propiedades del documento de MS Publisher, como el tamaño, el ancho, la altura, los nombres de las fuentes utilizadas, la cantidad de campos y los colores.
---

{{<section feature1>}}
---
title: Leer archivos de Publisher en .NET
item1: "Para ver las propiedades de los archivos .pub, deberá seguir los siguientes pasos:"
item2: Integre la API .NET PUB, que no solo funciona con documentos de una sola página, sino que también admite archivos .pub de varias páginas.
item3: Cargue su archivo PUB usando [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) Método de [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Clase.
item4: Analice el documento a través de [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse) Método de [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Interfaz.
item5: Imprimir documento [*propiedades*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties).
---

{{<section feature2>}}
---
title: Introducción a la API de .NET PUB
item1: "Hay dos formas de instalar el producto:"
item2: Instale desde la línea de comandos como ```nuget install Aspose.PUB``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.PUB```.
item3: Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: Código .NET para leer propiedades de archivos PUB
---

{{<section summary>}}
---
item1: Para ver el código completo del ejemplo ReadPubDocument.cs, vaya a la solución Aspose.PUB.Examples.sln, en los ejemplos de red de la documentación de Aspose.PUB, donde también puede encontrar otros ejemplos sobre cómo usar la biblioteca.
---