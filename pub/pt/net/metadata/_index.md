---
translation: true
template: /_templates/metadata-net.md
title: Editar editor | Metadados do PUB | .NET
description: Leia metadados do editor usando a solução de API PUB .NET. A API C# .NET nativa fornece acesso às propriedades SummaryInfo e DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: editar metadados do pub net, metadados do arquivo pub C#, editor de metadados do editor .net, ler metadados do arquivo pub C#, ler metadados do pub .net
family: pub
platformtag: net
feature: metadata
aliases: /net/metadados/
---

{{<section banner>}}
---
h1: Editar metadados do PUB
h2: Leia o arquivo MS Publisher. API do editor PUB Metatada para .NET
---

{{<section overview>}}
---
p1: O formato de arquivo de documento do Microsoft<sup>®</sup> Publisher é usado para criar vários tipos de publicação, como boletins informativos, brochuras, folhetos e cartões postais, e é usado em e-mails e sites. Os arquivos Pub contêm texto, bem como dados de bitmap e gráficos vetoriais.
p2: Os metadados do editor são propriedades (informações) que descrevem documentos PUB. São propriedades padrão, como editor, título, último autor, organização, URL, idioma e outras informações semelhantes. Há também dados que são gerados automaticamente após trabalhar com um arquivo como seu tamanho ou a última hora de edição. Essas informações úteis são armazenadas junto com o documento.
p3: Juntamente com a funcionalidade de conversão e leitura, esta solução de API PUB para .NET permite editar metadados padrão por meio das classes DocSummaryInfo e SummaryInfo, conforme mostrado no exemplo de código a seguir. Você também pode usar a API para criar seu próprio aplicativo Editor de Metadados.
p4: Antes de codificar metadados, você precisa integrar a API de metadados C# .NET PUB. O exemplo a seguir mostrará como editar a propriedade "Empresa".
---

{{<section feature1>}}
---
title: Editar metadados de arquivos PUB no .NET
item1: "O processo de leitura de metadados do editor consiste nas próximas etapas:"
item2: Carregue seu arquivo PUB usando [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) Método de [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Class.
item3: Analise o documento via [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse) Método de [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Interface.
item4: Edite metadados, por exemplo, Empresa por meio de [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Método de [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Classe.
---

{{<section feature2>}}
---
title: Introdução à API do .NET PUB
item1: Instale a partir da linha de comando como ```nuget install Aspose.PUB``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.PUB```.
item2: Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: Código .NET para editar metadados de PUB
---