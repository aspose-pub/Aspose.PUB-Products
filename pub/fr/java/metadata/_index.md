---
translation: true
template: /_templates/metadata-java.md
title: Modifier l'éditeur | Métadonnées PUB | Java
description: Lisez les métadonnées de l'éditeur à l'aide de la solution d'API PUB Java. L'API Java native vous donne accès aux propriétés SummaryInfo et DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: modifier les métadonnées de pub java, les métadonnées de fichier pub java, l'éditeur de métadonnées java, lire les métadonnées de fichier pub java, lire les métadonnées de pub java
family: pub
platformtag: java
feature: metadata
aliases: /java/metadata/
---

{{<section banner>}}
---
h1: Modifier les métadonnées PUB
h2: Lire le fichier MS Publisher. API de l'éditeur PUB Metatada pour Java
---

{{<section overview>}}
---
p1: Le format de fichier de document Microsoft<sup>®</sup> Publisher est utilisé pour créer divers types de publication tels que des bulletins d'information, des brochures, des dépliants et des cartes postales et est utilisé dans les e-mails et les sites Web. Les fichiers Pub contiennent du texte ainsi que des données graphiques bitmap et vectorielles.
p2: Les métadonnées de l'éditeur sont des propriétés (informations) qui décrivent les documents PUB. Ce sont des propriétés standard telles que l'éditeur, le titre, le dernier auteur, l'organisation, l'URL, la langue et d'autres informations similaires. Il y a aussi des données qui sont générées automatiquement après avoir travaillé avec un fichier comme sa taille ou l'heure de la dernière édition. Ces informations utiles sont stockées avec le document.
p3: Outre les fonctionnalités de conversion et de lecture, cette solution d'API PUB pour Java vous permet de modifier les métadonnées standard au moyen des classes DocSummaryInfo et SummaryInfo, comme illustré dans l'exemple de code suivant. Vous pouvez également utiliser l'API pour créer votre propre application Metadata Editor.
p4: Avant de coder les métadonnées, vous devez intégrer l'API Java PUB Metadata. L'exemple suivant vous montrera comment modifier la propriété "Langue".
---

{{<section widget>}}
---
title: Comment modifier les métadonnées PUB à l'aide de Java
item1: "Afin de modifier les métadonnées PUB, nous utiliserons [Aspose.PUB for Java API](https://products.aspose.com/pub/java/) qui est une conversion riche en fonctionnalités, puissante et facile à utiliser API pour la plate-forme Java. Vous pouvez télécharger sa dernière version directement depuis [Aspose Maven Repository](https://repository.aspose.com/pub/) et l'installer dans votre Maven -based project en ajoutant les configurations suivantes au fichier pom.xml."
---

{{<section feature1>}}
---
title: Afficher et modifier les métadonnées PUB sur Java
item1: "Le processus de lecture des métadonnées de l'éditeur comprend les étapes suivantes :"
item2: Téléchargez votre fichier PUB en utilisant [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) Méthode de [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Classe.
item3: Analyser le fichier via la méthode [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) de [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser).
item4: Modifier les métadonnées, par exemple la langue au moyen de [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Méthode de [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Classe.
---

{{<section feature2>}}
---
title: Configuration requise
item1: Aspose.PUB pour Java est pris en charge sur tous les principaux systèmes d'exploitation. Assurez-vous simplement que vous disposez des prérequis suivants.
item2: J2SE 8.0 (1.8) ou supérieur.
---

{{<section codeexample>}}
---
title: Code Java pour mettre à jour les métadonnées PUB
---