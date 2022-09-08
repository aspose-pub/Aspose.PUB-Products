---
translation: true
template: /_templates/metadata-java.md
title: Редактировать Publisher | Метаданные PUB | Ява
description: Чтение метаданных файлов Publisher с помощью кросс-платформенного решения PUB Java API. Локальный Java API предоставляет доступ к свойствам SummaryInfo и DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: редактировать метаданные pub, Java-метаданные pub, редактор метаданных Publisher java, читать метаданные pub-файла java, читать pub-метаданные java
family: pub
platformtag: java
feature: metadata
aliases: /java/метаданные/
---

{{<section banner>}}
---
h1: Редактировать метаданные PUB
h2: Прочитайте файл MS Publisher. API редактора PUB Metatada для Java
---

{{<section overview>}}
---
p1: Формат файла документа Microsoft<sup>®</sup> Publisher используется для создания различных типов публикаций, таких как информационные бюллетени, брошюры, листовки и открытки, а также используется в электронных письмах и на веб-сайтах. Файлы Pub содержат текст, а также данные растровой и векторной графики.
p2: Метаданные Publisher — это свойства (информация), описывающие документы PUB. Это стандартные свойства, такие как издатель, название, последний автор, организация, URL-адрес, язык и другая подобная информация. Также есть данные, которые генерируются автоматически после работы с файлом, например, его размер или время последнего редактирования. Эта полезная информация хранится вместе с документом.
p3: Наряду с функциями преобразования и чтения это решение PUB API для Java позволяет редактировать стандартные метаданные с помощью классов DocSummaryInfo и SummaryInfo, как показано в следующем примере кода. Вы также можете использовать API для создания собственного приложения «Редактор метаданных».
p4: Перед кодированием метаданных необходимо интегрировать API метаданных Java PUB. В следующем примере показано, как изменить свойство «Язык».
---

{{<section widget>}}
---
title: Как редактировать метаданные PUB с помощью Java
item1: "Для редактирования метаданных PUB мы будем использовать [Aspose.PUB for Java API](https://products.aspose.com/pub/java/), который представляет собой многофункциональное, мощное и простое в использовании преобразование API для платформы Java. Вы можете загрузить его последнюю версию непосредственно с [Aspose Maven Repository](https://repository.aspose.com/pub/) и установить в свой Maven. на основе проекта, добавив следующие конфигурации в файл pom.xml."
---

{{<section feature1>}}
---
title: Просмотр и редактирование метаданных PUB на Java
item1: "Процесс чтения метаданных Publisher состоит из следующих шагов:"
item2: Загрузите файл PUB с помощью [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) метода [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Класс.
item3: Разобрать файл с помощью метода [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) метода [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) Интерфейс.
item4: Отредактируйте метаданные, например, язык с помощью метода [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Класс.
---

{{<section feature2>}}
---
title: Системные Требования
item1: Aspose.PUB для Java поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.
item2: J2SE 8.0 (1.8) или выше.
---

{{<section codeexample>}}
---
title: Код Java для обновления метаданных PUB
---