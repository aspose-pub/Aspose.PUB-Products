---
translation: true
template: /_templates/reader-net.md
title: Чтение файлов PUB | .NET
description: Открывайте файлы Publisher программно. Решение C# .NET API для чтения свойств PUB. Используйте его для интеграции в свой проект.
url: /net/read-pub-file/
metakeywords: открыть pub-файл .net, просмотреть файлы издателя С#, прочитать файлы издателя, средство просмотра издателя для С#, средство чтения формата публикации, средство открытия файлов публикации
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: Просмотр PUB-файлов
h2: Чтение PUB-файлов. Открыть Publisher с API для .NET
---

{{<section overview>}}
---
p1: Формат файла документа Microsoft<sup>®</sup> Publisher используется для создания различных типов публикаций, таких как информационные бюллетени, брошюры, листовки и открытки, а также используется в электронных письмах и на веб-сайтах. Файлы Pub содержат текст, таблицы, а также данные растровой и векторной графики.
p2: Несмотря на то, что формат довольно популярен, он не так популярен, как такие форматы, как PDF или DOCX. Приложение MS Publisher само по себе не является бесплатным.
p3: Поэтому иногда требуется открывать файлы PUB без этой программы. Это необходимо, когда вы хотите показать содержимое документа, не редактируя его и не изменяя каким-либо другим образом, например, когда у вас есть презентация или обзор. Для таких целей вы можете использовать кроссплатформенное приложение PUB Viewer.
p4: Здесь вы получите решение .NET API, которое позволяет просматривать свойства документа MS Publisher, такие как размер, ширина, высота, имена используемых шрифтов, количество полей и цвета.
---

{{<section feature1>}}
---
title: Чтение файлов Publisher в .NET
item1: "Чтобы просмотреть свойства файлов .pub, вам необходимо выполнить следующие действия:"
item2: Интегрируйте .NET PUB API, который работает не только с одностраничными документами, но и поддерживает многостраничные файлы .pub.
item3: Загрузите файл PUB, используя [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/createparser/) метод [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Класс.
item4: Проанализируйте документ с помощью метода [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/parse/) метода [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Интерфейс.
item5: Распечатать документ [*свойства*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties).
---

{{<section feature2>}}
---
title: Начало работы с .NET PUB API
item1: "Существует два способа установки продукта:"
item2: Установите из командной строки как ```nuget install Aspose.PUB``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.PUB```.
item3: Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: Код .NET для чтения свойств файлов PUB
---

{{<section summary>}}
---
item1: Чтобы увидеть полный код примера ReadPubDocument.cs, перейдите к решению Aspose.PUB.Examples.sln в сетевых примерах документации Aspose.PUB, где вы также можете найти другие примеры использования библиотеки.
---