---
translation: true
template: /_templates/reader-net.md
title: Leia arquivos PUB | .NET
description: Abra os arquivos do Publisher programaticamente. Solução C# .NET API para ler as propriedades do PUB. Use-o para integrar em seu projeto.
url: /net/read-pub-file/
metakeywords: abrir arquivo pub .net, visualizar arquivos do editor c#, ler arquivos do editor, visualizador do editor para c#, leitor de formato pub, abridor de arquivos pub
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: Abridor de arquivos PUB
h2: Leia arquivos PUB. Open Publisher com API para .NET
---

{{<section overview>}}
---
p1: O formato de arquivo de documento do Microsoft<sup>®</sup> Publisher é usado para criar vários tipos de publicação, como boletins informativos, brochuras, folhetos e cartões postais, e é usado em e-mails e sites. Os arquivos pub contêm texto, tabelas, bem como dados de bitmap e gráficos vetoriais.
p2: Embora o formato seja bastante popular, não é tão popular quanto formatos como PDF ou DOCX. O aplicativo MS Publisher não é gratuito.
p3: Portanto, às vezes é necessário abrir arquivos PUB sem este programa. Isso é necessário quando você deseja mostrar o conteúdo do documento, sem editá-lo ou manipulá-lo de outra forma, como quando você faz uma apresentação ou revisão. Para tais fins, você pode usar um aplicativo PUB Viewer multiplataforma.
p4: Aqui você obterá a solução .NET API que permite visualizar as propriedades do documento do MS Publisher, como tamanho, largura, altura, nomes das fontes usadas, número de campos e cores.
---

{{<section feature1>}}
---
title: Ler arquivos do Publisher no .NET
item1: "Para visualizar as propriedades dos arquivos .pub, você precisará executar as próximas etapas:"
item2: Integre a API .NET PUB, que funciona não apenas com documentos de página única, mas também suporta arquivos .pub de várias páginas.
item3: Carregue seu arquivo PUB usando [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/createparser/) Método de [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Class.
item4: Analise o documento via [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/parse/) Método de [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Interface.
item5: Imprimir documento [*properties*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties).
---

{{<section feature2>}}
---
title: Introdução à API do .NET PUB
item1: "Existem duas maneiras de instalar o produto:"
item2: Instale a partir da linha de comando como ```nuget install Aspose.PUB``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.PUB```.
item3: Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: Código .NET para ler propriedades de arquivos PUB
---

{{<section summary>}}
---
item1: Para ver o código completo do exemplo ReadPubDocument.cs acesse a solução Aspose.PUB.Examples.sln, na net-examples da Documentação Aspose.PUB onde você também pode encontrar outros exemplos de como usar a biblioteca.
---