---
translation: true
template: /_templates/conversion-child.md
title: تحويل PUB إلى PDF | C ++
description: قم بتحويل PUB إلى PDF باستخدام C ++ API على أنظمة التشغيل Windows و Linux و Mac OS X. وظيفة تحويل الناشر التي يسهل دمجها في الحل الخاص بك.
url: /cpp/conversion/pub-to-pdf/
metakeywords: pub إلى pdf c ++ ، تحويل pub إلى pdf cpp ، c ++ pub to pdf ، الناشر إلى pdf c ++
family: pub
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: تحويل PUB إلى PDF
h2: الناشر لتحويل PDF. С ++ وظائف التحويل API.
---

{{<section overview>}}
---
p1: يتم استخدام تنسيق ملف مستند الناشر Microsoft <sup> ® </sup> لإنشاء أنواع مختلفة من المنشورات مثل النشرات الإخبارية والكتيبات والنشرات الإعلانية والبطاقات البريدية ، ويتم استخدامه في رسائل البريد الإلكتروني ومواقع الويب. تحتوي ملفات Pub على نص بالإضافة إلى بيانات الصور النقطية والرسومات المتجهة.
p2: نظرًا لأن جميع منتجات Microsoft <sup> ® </sup> الأخرى ، فإن تطبيق Publisher ليس مجانيًا بحد ذاته. ونظرًا لأن ملف التنسيق لا يمكن فتحه إلا بواسطة هذا البرنامج لمشاركة نتائج عملك ، فسيتعين عليك أحيانًا تحويل ملف PUB إلى تنسيق أكثر انتشارًا. الأكثر شيوعًا على الإطلاق هو تحويل PUB إلى PDF. الآن ، هذا التنسيق مدعوم من قبل جميع الأجهزة الحديثة ويمكن حتى فتحه في متصفح دون تثبيت أي برامج إضافية. فيما يلي وظيفة تحويل PUB إلى PDF لـ C ++. يمكن أيضًا استخدام هذه المكتبة لإنشاء مشروعك الخاص.
p3: قبل تشغيل التحويل ، تحتاج إلى دمج C ++ PUB to PDF Converter API ، والتي لا تعمل فقط مع المستندات ذات الصفحة الواحدة ولكنها تدعم أيضًا ملفات .pub متعددة الصفحات.
---

{{<section feature1>}}
---
title: تحويل PUB إلى PDF على C ++
item1: قم بتحميل ملف PUB عن طريق [*CreateParser()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) طريقة [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) فئة.
item2: تحليل الملف باستخدام [*Parse()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) طريقة [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) الواجهة.
item3: قم بتشغيل التحويل عن طريق [*ConvertToPdf()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter#acdea381bc8f2a2799e73a039b09ecdb5) طريقة [*IPdfConverter*](https://واجهةapireference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter).
---

{{<section feature2>}}
---
title: ابدأ مع C ++ PUB API
item1: قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.PUB.cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.PUB.cpp ''.
item2: بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/pub/cpp/).
---

{{<section codeexample>}}
---
title: كود C ++ لتحويل PUB إلى PDF
---

{{<section summary>}}
---
p1: يعد تحويل PUB إلى PDF خطوة مطلوبة في PUB إلى أي تحويل تنسيق آخر. بعد ذلك ، يمكن تحويل الملف المحول إلى التنسيق المطلوب.
p2: يمكنك أيضًا تجربة تطبيق PUB to PDF عبر الأنظمة الأساسية. يحتوي على واجهة بسيطة للغاية وستستغرق العملية بضع ثوانٍ فقط.
p3: "يتيح لك الحل: تحويل ملفات Publisher متعددة ، وتحويل PUB إلى PDF ، وحفظ المستندات المحولة على جهازك."
---