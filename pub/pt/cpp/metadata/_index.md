---
translation: true
template: /_templates/metadata-cpp.md
title: Editar editor | Metadados do PUB | C++
description: Leia metadados de arquivos do Publisher usando a solução de API PUB C++. A API C++ local fornece acesso às propriedades SummaryInfo e DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: editar metadados do pub, metadados do arquivo pub, editor de metadados do editor, ler metadados do arquivo pub, ler metadados do pub
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadados/
---

{{<section banner>}}
---
h1: Editar metadados do PUB
h2: Leia o arquivo MS Publisher. API do editor PUB Metatada para C++
---

{{<section overview>}}
---
p1: O formato de arquivo de documento do Microsoft<sup>®</sup> Publisher é usado para criar vários tipos de publicação, como boletins informativos, brochuras, folhetos e cartões postais, e é usado em e-mails e sites. Os arquivos Pub contêm texto, bem como dados de bitmap e gráficos vetoriais.
p2: Os metadados do editor são propriedades (informações) que descrevem documentos PUB. São propriedades padrão, como editor, título, último autor, organização, URL, idioma e outras informações semelhantes. Há também dados que são gerados automaticamente após trabalhar com um arquivo como seu tamanho ou a última hora de edição. Essas informações úteis são armazenadas junto com o documento.
p3: Juntamente com a funcionalidade de conversão e leitura, esta solução de API PUB para C++ permite editar metadados padrão por meio das classes DocSummaryInfo e SummaryInfo, conforme mostrado no exemplo de código a seguir. Você também pode usar a API para criar seu próprio aplicativo Editor de Metadados.
p4: Antes de codificar metadados, você precisa integrar a API de metadados C++ PUB. O exemplo a seguir mostrará como editar a propriedade "Category".
---

{{<section feature1>}}
---
title: Visualizar e editar metadados de PUB em C++
item1: "O processo de leitura de metadados do editor consiste nas próximas etapas:"
item2: Carregue seu arquivo PUB usando [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Método de [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Class.
item3: Analisar arquivo via [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Método de [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Interface.
item4: Edite metadados, por exemplo, Categoria por meio de [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Método de [*DocSummaryInfo*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Classe.
---

{{<section feature2>}}
---
title: Introdução à API CPP PUB
item1: Instale a partir da linha de comando como ```nuget install Aspose.PUB.cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.PUB.cpp```.
item2: Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/pub/cpp).
---

{{<section codeexample>}}
---
title: Código C++ para modificar metadados de PUB
---
