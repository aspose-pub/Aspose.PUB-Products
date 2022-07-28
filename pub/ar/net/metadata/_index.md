---
translation: true
template: /_templates/metadata-net.md
title: تحرير الناشر | البيانات الوصفية لـ PUB |.NET
description: اقرأ بيانات تعريف ملفات Publisher باستخدام PUB .NET API Solution عبر الأنظمة الأساسية. يمنحك .NET API المحلي الوصول إلى خصائص SummaryInfo و DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: 'تحرير شبكة البيانات الوصفية للناشر ، البيانات الوصفية لملف الناشر C # ، محرر البيانات الوصفية للناشر. net ، قراءة البيانات الوصفية لملف الناشر C # ، قراءة البيانات الوصفية للناشر. net'
family: pub
platformtag: net
feature: metadata
aliases: / net / metadata /
---

{{<section banner>}}
---
h1: تحرير PUB Metadata
h2: قراءة ملف MS Publisher. محرر PUB Metatada API لـ .NET
---

{{<section overview>}}
---
p1: يتم استخدام تنسيق ملف مستند الناشر Microsoft <sup> ® </sup> لإنشاء أنواع مختلفة من المنشورات مثل النشرات الإخبارية والكتيبات والنشرات الإعلانية والبطاقات البريدية ، ويتم استخدامه في رسائل البريد الإلكتروني ومواقع الويب. تحتوي ملفات Pub على نص بالإضافة إلى بيانات الصور النقطية والرسومات المتجهة.
p2: البيانات الوصفية للناشر هي خصائص (معلومات) تصف مستندات PUB. إنها خصائص قياسية مثل الناشر والعنوان والمؤلف الأخير والمؤسسة وعنوان URL واللغة ومعلومات أخرى مماثلة. هناك أيضًا بيانات يتم إنشاؤها تلقائيًا بعد العمل مع ملف مثل حجمه أو وقت التحرير الأخير. يتم تخزين هذه المعلومات المفيدة مع المستند.
p3: إلى جانب وظائف التحويل والقراءة ، يتيح لك حل PUB API لـ .NET تحرير البيانات الوصفية القياسية عن طريق فئتي DocSummaryInfo و SummaryInfo كما هو موضح في نموذج التعليمات البرمجية التالي. يمكنك أيضًا استخدام واجهة برمجة التطبيقات لإنشاء تطبيق محرر البيانات الوصفية الخاص بك.
p4: 'قبل تشفير البيانات الوصفية ، تحتاج إلى دمج C # .NET PUB Metadata API. سيوضح لك المثال التالي كيفية تعديل خاصية "الشركة".'
---

{{<section feature1>}}
---
title: تحرير البيانات الوصفية لملفات PUB على .NET
item1: "تتكون عملية قراءة البيانات الوصفية للناشر من الخطوات التالية:"
item2: قم بتحميل ملف PUB الخاص بك باستخدام طريقة [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) الخاصة بـ [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) فئة.
item3: قم بتحليل المستند عبر [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) طريقة [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) الواجهة.
item4: تحرير البيانات الوصفية ، مثل الشركة عن طريق [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) طريقة [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) فئة.
---

{{<section feature2>}}
---
title: ابدأ مع .NET PUB API
item1: قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.PUB '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.PUB ''.
item2: بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: NET Code لتحرير PUB Metadata
---