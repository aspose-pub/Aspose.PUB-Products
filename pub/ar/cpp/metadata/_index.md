---
translation: true
template: /_templates/metadata-cpp.md
title: تحرير الناشر | البيانات الوصفية لـ PUB | C ++
description: قراءة بيانات تعريف ملفات Publisher باستخدام PUB C ++ API Solution. تمنحك واجهة برمجة تطبيقات C ++ المحلية الوصول إلى خصائص SummaryInfo و DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: تحرير البيانات الوصفية للناشر ، البيانات الوصفية لملف الناشر ، محرر البيانات الوصفية للناشر ، قراءة البيانات الوصفية لملف الناشر ، قراءة البيانات الوصفية للناشر
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadata/
---

{{<section banner>}}
---
h1: تحرير PUB Metadata
h2: قراءة ملف MS Publisher. واجهة برمجة تطبيقات محرر PUB Metatada لـ C ++
---

{{<section overview>}}
---
p1: يتم استخدام تنسيق ملف مستند الناشر Microsoft <sup> ® </sup> لإنشاء أنواع مختلفة من المنشورات مثل النشرات الإخبارية والكتيبات والنشرات الإعلانية والبطاقات البريدية ، ويتم استخدامه في رسائل البريد الإلكتروني ومواقع الويب. تحتوي ملفات Pub على نص بالإضافة إلى بيانات الصور النقطية والرسومات المتجهة.
p2: البيانات الوصفية للناشر هي خصائص (معلومات) تصف مستندات PUB. إنها خصائص قياسية مثل الناشر والعنوان والمؤلف الأخير والمؤسسة وعنوان URL واللغة ومعلومات أخرى مماثلة. هناك أيضًا بيانات يتم إنشاؤها تلقائيًا بعد العمل مع ملف مثل حجمه أو وقت التحرير الأخير. يتم تخزين هذه المعلومات المفيدة مع المستند.
p3: إلى جانب وظائف التحويل والقراءة ، يتيح لك حل PUB API لـ C ++ تحرير البيانات الوصفية القياسية عن طريق فئتي DocSummaryInfo و SummaryInfo كما هو موضح في نموذج التعليمات البرمجية التالي. يمكنك أيضًا استخدام واجهة برمجة التطبيقات لإنشاء تطبيق محرر البيانات الوصفية الخاص بك.
p4: قبل تشفير البيانات الوصفية ، تحتاج إلى دمج C ++ PUB Metadata API. سيوضح لك المثال التالي كيفية تحرير خاصية "الفئة".
---

{{<section feature1>}}
---
title: عرض وتحرير PUB Metadata على C ++
item1: "تتكون عملية قراءة البيانات الوصفية للناشر من الخطوات التالية:"
item2: قم بتحميل ملف PUB الخاص بك باستخدام [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) طريقة [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) فئة.
item3: تحليل الملف عبر [*تحليل *()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) طريقة [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) الواجهة.
item4: تحرير البيانات الوصفية ، على سبيل المثال الفئة عن طريق [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) طريقة [*DocSummaryInfo*](https:/DocSummaryInfo*]/apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) فئة.
---

{{<section feature2>}}
---
title: ابدأ مع CPP PUB API
item1: قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.PUB.cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.PUB.cpp ''.
item2: بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/pub/cpp/).
---

{{<section codeexample>}}
---
title: كود C ++ لتعديل بيانات PUB الوصفية
---
