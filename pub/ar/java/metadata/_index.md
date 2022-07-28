---
translation: true
template: /_templates/metadata-java.md
title: تحرير الناشر | البيانات الوصفية لـ PUB | جافا
description: اقرأ بيانات تعريف ملفات Publisher باستخدام PUB Java API Solution عبر الأنظمة الأساسية. تمنحك واجهة برمجة تطبيقات Java المحلية الوصول إلى خصائص SummaryInfo و DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: تحرير البيانات الوصفية للناشر ، جافا ، البيانات الوصفية لملف الناشر ، جافا ، محرر البيانات الوصفية للناشر ، جافا ، اقرأ البيانات الوصفية لملف الناشر جافا ، اقرأ البيانات الوصفية للناشر جافا
family: pub
platformtag: java
feature: metadata
aliases: / java / metadata /
---

{{<section banner>}}
---
h1: تحرير PUB Metadata
h2: قراءة ملف MS Publisher. واجهة برمجة تطبيقات محرر PUB Metatada لجافا
---

{{<section overview>}}
---
p1: يتم استخدام تنسيق ملف مستند الناشر Microsoft <sup> ® </sup> لإنشاء أنواع مختلفة من المنشورات مثل النشرات الإخبارية والكتيبات والنشرات الإعلانية والبطاقات البريدية ، ويتم استخدامه في رسائل البريد الإلكتروني ومواقع الويب. تحتوي ملفات Pub على نص بالإضافة إلى بيانات الصور النقطية والرسومات المتجهة.
p2: البيانات الوصفية للناشر هي خصائص (معلومات) تصف مستندات PUB. إنها خصائص قياسية مثل الناشر والعنوان والمؤلف الأخير والمؤسسة وعنوان URL واللغة ومعلومات أخرى مماثلة. هناك أيضًا بيانات يتم إنشاؤها تلقائيًا بعد العمل مع ملف مثل حجمه أو وقت التحرير الأخير. يتم تخزين هذه المعلومات المفيدة مع المستند.
p3: إلى جانب وظائف التحويل والقراءة ، يتيح لك حل PUB API لـ Java تحرير البيانات الوصفية القياسية عن طريق فئتي DocSummaryInfo و SummaryInfo كما هو موضح في نموذج التعليمات البرمجية التالي. يمكنك أيضًا استخدام واجهة برمجة التطبيقات لإنشاء تطبيق محرر البيانات الوصفية الخاص بك.
p4: قبل تشفير البيانات الوصفية ، تحتاج إلى دمج Java PUB Metadata API. سيوضح لك المثال التالي كيفية تحرير خاصية "اللغة".
---

{{<section widget>}}
---
title: كيفية تحرير PUB Metadata باستخدام Java
item1: "لتحرير PUB Metadata ، سنستخدم [Aspose.PUB for Java API](https://products.aspose.com/pub/java/) وهو تحويل غني بالميزات وقوي وسهل الاستخدام API لمنصة جافا. يمكنك تنزيل أحدث إصدار مباشرة من [Maven](https://repository.aspose.com/pub/) وتثبيته داخل Maven الخاص بك مشروع قائم على أساس إضافة التكوينات التالية إلى ملف pom.xml."
---

{{<section feature1>}}
---
title: عرض وتحرير PUB Metadata على Java
item1: "تتكون عملية قراءة البيانات الوصفية للناشر من الخطوات التالية:"
item2: قم بتحميل ملف PUB الخاص بك باستخدام [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) طريقة [*PubFactory*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) فئة.
item3: تحليل الملف عبر طريقة [*تحليل*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) لـ [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) الواجهة.
item4: تحرير البيانات الوصفية ، مثل اللغة عن طريق [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) طريقة [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) فئة.
---

{{<section feature2>}}
---
title: متطلبات النظام
item1: Aspose.PUB for Java مدعوم على جميع أنظمة التشغيل الرئيسية. فقط تأكد من أن لديك المتطلبات الأساسية التالية.
item2: J2SE 8.0 (1.8) أو أعلى.
---

{{<section codeexample>}}
---
title: كود جافا لتحديث بيانات PUB الوصفية
---