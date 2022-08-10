---
translation: true
template: /_templates/metadata-cpp.md
title: Редактировать Publisher | Метаданные PUB | С++
description: Чтение метаданных файлов Publisher с помощью решения PUB C++ API. Локальный API C++ предоставляет доступ к свойствам SummaryInfo и DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: редактировать метаданные публикации, метаданные файла публикации, редактор метаданных Publisher, читать метаданные файла публикации, читать метаданные публикации
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/метаданные/
---

{{<section banner>}}
---
h1: Редактировать метаданные PUB
h2: Прочитайте файл MS Publisher. API редактора PUB Metatada для C++
---

{{<section overview>}}
---
p1: Формат файла документа Microsoft<sup>®</sup> Publisher используется для создания различных типов публикаций, таких как информационные бюллетени, брошюры, листовки и открытки, а также используется в электронных письмах и на веб-сайтах. Файлы Pub содержат текст, а также данные растровой и векторной графики.
p2: Метаданные Publisher — это свойства (информация), описывающие документы PUB. Это стандартные свойства, такие как издатель, название, последний автор, организация, URL-адрес, язык и другая подобная информация. Также есть данные, которые генерируются автоматически после работы с файлом, например, его размер или время последнего редактирования. Эта полезная информация хранится вместе с документом.
p3: Наряду с функциями преобразования и чтения это решение PUB API для C++ позволяет редактировать стандартные метаданные с помощью классов DocSummaryInfo и SummaryInfo, как показано в следующем примере кода. Вы также можете использовать API для создания собственного приложения «Редактор метаданных».
p4: Перед кодированием метаданных необходимо интегрировать C++ PUB Metadata API. В следующем примере показано, как редактировать свойство «Категория».
---

{{<section feature1>}}
---
title: Просмотр и редактирование метаданных PUB на C++
item1: "Процесс чтения метаданных Publisher состоит из следующих шагов:"
item2: Загрузите файл PUB, используя [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) метод [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Класс.
item3: Разобрать файл с помощью [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) метода [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Интерфейс.
item4: Редактировать метаданные, например категорию, с помощью [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) методом [*DocSummaryInfo*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Класс.
---

{{<section feature2>}}
---
title: Начните работу с CPP PUB API
item1: Установите из командной строки как ```nuget install Aspose.PUB.cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.PUB.cpp```.
item2: Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.com/pub/cpp/).
---

{{<section codeexample>}}
---
title: Код C++ для изменения метаданных PUB
---
