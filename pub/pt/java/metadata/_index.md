---
translation: true
template: /_templates/metadata-java.md
title: Editar editor | Metadados do PUB | Java
description: Leia metadados de arquivos do Publisher usando a solução de API Java PUB multiplataforma. A API Java no local fornece acesso às propriedades SummaryInfo e DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: editar metadados pub java, metadados do arquivo pub java, editor de metadados do editor java, ler metadados do arquivo pub java, ler metadados do pub java
family: pub
platformtag: java
feature: metadata
aliases: /java/metadados/
---

{{<section banner>}}
---
h1: Editar metadados do PUB
h2: Leia o arquivo MS Publisher. API do editor PUB Metatada para Java
---

{{<section overview>}}
---
p1: O formato de arquivo de documento do Microsoft<sup>®</sup> Publisher é usado para criar vários tipos de publicação, como boletins informativos, brochuras, folhetos e cartões postais, e é usado em e-mails e sites. Os arquivos Pub contêm texto, bem como dados de bitmap e gráficos vetoriais.
p2: Os metadados do editor são propriedades (informações) que descrevem documentos PUB. São propriedades padrão, como editor, título, último autor, organização, URL, idioma e outras informações semelhantes. Há também dados que são gerados automaticamente após trabalhar com um arquivo como seu tamanho ou a última hora de edição. Essas informações úteis são armazenadas junto com o documento.
p3: Juntamente com a funcionalidade de conversão e leitura, esta solução de API PUB para Java permite editar metadados padrão por meio das classes DocSummaryInfo e SummaryInfo, conforme mostrado no exemplo de código a seguir. Você também pode usar a API para criar seu próprio aplicativo Editor de Metadados.
p4: Antes de codificar metadados, você precisa integrar a API de metadados Java PUB. O exemplo a seguir mostrará como editar a propriedade "Language".
---

{{<section widget>}}
---
title: Como editar metadados de PUB usando Java
item1: "Para editar metadados de PUB, usaremos [Aspose.PUB for Java API](https://products.aspose.com/pub/java/), que é uma conversão rica em recursos, poderosa e fácil de usar API para a plataforma Java. Você pode baixar a versão mais recente diretamente do [Maven](https://repository.aspose.com/pub/) e instalá-lo no seu Maven baseado em projeto adicionando as seguintes configurações ao pom.xml."
---

{{<section feature1>}}
---
title: Visualizar e editar metadados de PUB em Java
item1: "O processo de leitura de metadados do editor consiste nas próximas etapas:"
item2: Carregue seu arquivo PUB usando [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) Método de [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Classe.
item3: Analisar arquivo por meio do método [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) do método [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser).
item4: Edite metadados, por exemplo, Idioma por meio de [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Método de [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Class.
---

{{<section feature2>}}
---
title: Requisitos de sistema
item1: Aspose.PUB para Java é suportado em todos os principais sistemas operacionais. Apenas certifique-se de ter os seguintes pré-requisitos.
item2: J2SE 8.0 (1.8) ou superior.
---

{{<section codeexample>}}
---
title: Código Java para atualizar metadados de PUB
---