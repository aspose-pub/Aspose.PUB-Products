---
translation: true
template: /_templates/metadata-cpp.md
title: Modifier l'éditeur | Métadonnées PUB | C++
description: Lisez les métadonnées de l'éditeur à l'aide de la solution d'API PUB C++. L'API C++ native vous donne accès aux propriétés SummaryInfo et DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: modifier les métadonnées de la publication, les métadonnées du fichier de publication, l'éditeur de métadonnées de l'éditeur, lire les métadonnées du fichier de publication, lire les métadonnées de la publication
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadata/
---

{{<section banner>}}
---
h1: Modifier les métadonnées PUB
h2: Lire le fichier MS Publisher. API de l'éditeur PUB Metatada pour C++
---

{{<section overview>}}
---
p1: Le format de fichier de document Microsoft<sup>®</sup> Publisher est utilisé pour créer divers types de publication tels que des bulletins d'information, des brochures, des dépliants et des cartes postales et est utilisé dans les e-mails et les sites Web. Les fichiers Pub contiennent du texte ainsi que des données graphiques bitmap et vectorielles.
p2: Les métadonnées de l'éditeur sont des propriétés (informations) qui décrivent les documents PUB. Ce sont des propriétés standard telles que l'éditeur, le titre, le dernier auteur, l'organisation, l'URL, la langue et d'autres informations similaires. Il y a aussi des données qui sont générées automatiquement après avoir travaillé avec un fichier comme sa taille ou l'heure de la dernière édition. Ces informations utiles sont stockées avec le document.
p3: Outre les fonctionnalités de conversion et de lecture, cette solution d'API PUB pour C++ vous permet de modifier les métadonnées standard au moyen des classes DocSummaryInfo et SummaryInfo, comme illustré dans l'exemple de code suivant. Vous pouvez également utiliser l'API pour créer votre propre application Metadata Editor.
p4: Avant de coder les métadonnées, vous devez intégrer l'API de métadonnées C++ PUB. L'exemple suivant vous montrera comment modifier la propriété "Catégorie".
---

{{<section feature1>}}
---
title: Afficher et modifier les métadonnées PUB sur C++
item1: "Le processus de lecture des métadonnées de l'éditeur comprend les étapes suivantes :"
item2: Téléchargez votre fichier PUB en utilisant [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Méthode de [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Classe.
item3: Analyser le fichier via [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Méthode de [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser).
item4: Modifier les métadonnées, par exemple la catégorie au moyen de [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Méthode de [*DocSummaryInfo*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Classe.
---

{{<section feature2>}}
---
title: Premiers pas avec l'API CPP PUB
item1: Installez à partir de la ligne de commande en tant que ```nuget install Aspose.PUB.cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.PUB.cpp```.
item2: Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/pub/cpp/).
---

{{<section codeexample>}}
---
title: Code C++ pour modifier les métadonnées PUB
---
