---
translation: true
template: /_templates/metadata-net.md
title: Редактировать Publisher | Метаданные PUB | .NET
description: Чтение метаданных файлов Publisher с помощью решения PUB .NET API. Локальный .NET API предоставляет доступ к свойствам SummaryInfo и DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: редактировать net метаданных публикации, метаданные файла публикации C#, редактор метаданных Publisher .net, читать метаданные файла публикации C#, читать метаданные публикации .net
family: pub
platformtag: net
feature: metadata
aliases: /net/метаданные/
---

{{<section banner>}}
---
h1: Редактировать метаданные PUB
h2: Прочитайте файл MS Publisher. API редактора PUB Metatada для .NET
---

{{<section overview>}}
---
p1: Формат файла документа Microsoft<sup>®</sup> Publisher используется для создания различных типов публикаций, таких как информационные бюллетени, брошюры, листовки и открытки, а также используется в электронных письмах и на веб-сайтах. Файлы Pub содержат текст, а также данные растровой и векторной графики.
p2: Метаданные Publisher — это свойства (информация), описывающие документы PUB. Это стандартные свойства, такие как издатель, название, последний автор, организация, URL-адрес, язык и другая подобная информация. Также есть данные, которые генерируются автоматически после работы с файлом, например, его размер или время последнего редактирования. Эта полезная информация хранится вместе с документом.
p3: Наряду с функциями преобразования и чтения это решение PUB API для .NET позволяет редактировать стандартные метаданные с помощью классов DocSummaryInfo и SummaryInfo, как показано в следующем примере кода. Вы также можете использовать API для создания собственного приложения «Редактор метаданных».
p4: Перед кодированием метаданных необходимо интегрировать C# .NET PUB Metadata API. В следующем примере показано, как редактировать свойство «Компания».
---

{{<section feature1>}}
---
title: Редактировать метаданные файлов PUB в .NET
item1: "Процесс чтения метаданных Publisher состоит из следующих шагов:"
item2: Загрузите файл PUB, используя [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) метод [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory) Класс.
item3: Проанализируйте документ с помощью метода [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) метода [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser) Интерфейс.
item4: Редактировать метаданные, например, компанию с помощью метода [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) метода [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Класс.
---

{{<section feature2>}}
---
title: Начало работы с .NET PUB API
item1: Установите из командной строки как ```nuget install Aspose.PUB``` или через консоль диспетчера пакетов Visual Studio с ```Install-Package Aspose.PUB```.
item2: Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.com/pub/net).
---

{{<section codeexample>}}
---
title: Код .NET для редактирования метаданных PUB
---