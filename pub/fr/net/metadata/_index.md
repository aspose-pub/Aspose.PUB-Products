---
translation: true
template: /_templates/metadata-net.md
title: Modifier l'éditeur | Métadonnées PUB | .NET
description: Lisez les métadonnées de l'éditeur à l'aide de la solution d'API PUB C#. L'API .NET native vous donne accès aux propriétés SummaryInfo et DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: "modifier le réseau de métadonnées de publication, les métadonnées de fichier de publication C #, l'éditeur de métadonnées de l'éditeur .net, lire les métadonnées de fichier de publication C #, lire les métadonnées de publication .net"
family: pub
platformtag: net
feature: metadata
aliases: /net/métadonnées/
---

{{<section banner>}}
---
h1: Modifier les métadonnées PUB
h2: Lire le fichier MS Publisher. API de l'éditeur PUB Metatada pour .NET
---

{{<section overview>}}
---
p1: Le format de fichier de document Microsoft<sup>®</sup> Publisher est utilisé pour créer divers types de publication tels que des bulletins d'information, des brochures, des dépliants et des cartes postales et est utilisé dans les e-mails et les sites Web. Les fichiers Pub contiennent du texte ainsi que des données graphiques bitmap et vectorielles.
p2: Les métadonnées de l'éditeur sont des propriétés (informations) qui décrivent les documents PUB. Ce sont des propriétés standard telles que l'éditeur, le titre, le dernier auteur, l'organisation, l'URL, la langue et d'autres informations similaires. Il y a aussi des données qui sont générées automatiquement après avoir travaillé avec un fichier comme sa taille ou l'heure de la dernière édition. Ces informations utiles sont stockées avec le document.
p3: Outre les fonctionnalités de conversion et de lecture, cette solution d'API PUB pour .NET vous permet de modifier les métadonnées standard au moyen des classes DocSummaryInfo et SummaryInfo, comme illustré dans l'exemple de code suivant. Vous pouvez également utiliser l'API pour créer votre propre application Metadata Editor.
p4: Avant de coder les métadonnées, vous devez intégrer l'API de métadonnées C# .NET PUB. L'exemple suivant vous montrera comment modifier la propriété "Société".
---

{{<section feature1>}}
---
title: Modifier les métadonnées des fichiers PUB sur .NET
item1: "Le processus de lecture des métadonnées de l'éditeur comprend les étapes suivantes :"
item2: Téléchargez votre fichier PUB en utilisant [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Méthode de [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory) Classe.
item3: Analysez le document via [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Méthode de [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser).
item4: Modifier les métadonnées, par exemple la société au moyen de [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Méthode de [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Classe.
---

{{<section feature2>}}
---
title: Premiers pas avec l'API .NET PUB
item1: Installez à partir de la ligne de commande en tant que ```nuget install Aspose.PUB``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.PUB```.
item2: Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/pub/net).
---

{{<section codeexample>}}
---
title: Code .NET pour modifier les métadonnées PUB
---