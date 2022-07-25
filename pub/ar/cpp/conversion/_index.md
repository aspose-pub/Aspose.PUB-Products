---
translation: true
template: /_templates/conversion.md
title: حل PUB Converter API | C ++
url: /cpp/conversion/
description: تحويل ملفات Microsoft Publisher برمجياً عبر مكتبة C ++. حل API بسيط لبناء مشروع PUB Converter C ++ الخاص بك.
metakeywords: pub cpp المحول ، تحويل ملف pub cpp
family: pub
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: تحويل ملف PUB
h2: وظيفة محول الناشر لبناء تطبيقات C ++ عبر الأنظمة الأساسية.
---

{{<section overview>}}
---
p1: يتم استخدام تنسيق ملف مستند الناشر Microsoft <sup> ® </sup> لإنشاء أنواع مختلفة من المنشورات مثل النشرات الإخبارية والكتيبات والنشرات الإعلانية والبطاقات البريدية ، ويتم استخدامه في رسائل البريد الإلكتروني ومواقع الويب. تحتوي ملفات Pub على نص بالإضافة إلى بيانات الصور النقطية والرسومات المتجهة.
p2: على الرغم من أن التنسيق شائع جدًا ، إلا أنه ليس شائعًا مثل تنسيقات مثل PDF أو DOCX. تطبيق MS Publisher ليس حرًا بحد ذاته. لذلك غالبًا ما يكون مطلوبًا تحويل الملفات ذات الامتداد .pub إلى تنسيق آخر جيد الانتشار ومريح للاستخدام. فيما يلي وظيفة التحويل لـ C ++. تتضمن هذه المكتبة وظيفة التحويل المطلوبة التي يمكن استخدامها لإنشاء مشروعك الخاص.
---

{{<section feature1>}}
---
title: تحويل ملفات Publisher .pub
item1: دعونا نلقي نظرة على الوظائف من خلال تحويل PUB إلى PDF.
item2: "تتكون عملية تحويل الناشر من الخطوات التالية:"
item3: دمج C ++ PUB to PDF Converter API ، والذي لا يعمل فقط مع المستندات ذات الصفحة الواحدة ولكن أيضًا يدعم ملفات .pub متعددة الصفحات.
item4: قم بتحميل ملف PUB باستخدام فئة [*PubFactory*](https://apireference.aspose.com/pub/cpp/class/aspose.pub.pub_factory).
item5: إنشاء محلل وتحليل عبر [*Parse*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) أسلوب [*IPubParser*](https://apireference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) الواجهة.
item6: قم بتشغيل التحويل عن طريق طريقة [*ConvertToPdf*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter).
---

{{<section codeexample>}}
---
title: كود C ++ لتحويل Publisher PUB إلى PDF
---

{{<section summary>}}
---
p1: يمكن تحويل PUB إلى أي تنسيق آخر بعد تحويل الملف إلى تنسيق PDF ومن ثم يمكن تحويل هذا الملف المحول إلى التنسيق المطلوب.
p2: "يمكنك أيضًا تجربة تطبيق Publisher Converter عبر الأنظمة الأساسية. يحتوي على واجهة بسيطة للغاية وستستغرق العملية بضع ثوانٍ فقط. الحل يسمح بما يلي:"
p3: تحويل ملفات Publisher متعددة.
p4: قم بتحويل PUB إلى PDF و HTML و EPUB و DOCX و SVG والعديد من تنسيقات الصور الأخرى.
p5: احفظ المستندات المحولة على جهازك.
---