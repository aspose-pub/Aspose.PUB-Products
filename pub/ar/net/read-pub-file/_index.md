---
translation: true
template: /_templates/reader-net.md
title: قراءة ملفات PUB | .NET
description: 'افتح ملفات Publisher برمجيًا. حل NET C # API داخل الشركة لقراءة خصائص PUB. استخدمه للاندماج في مشروعك.'
url: /net/read-pub-file/
metakeywords: افتح ملف الناشر. net ، اعرض ملفات الناشر c# ، اقرأ ملفات الناشر ، عارض الناشر لـ c# ، قارئ تنسيق الناشر ، فتاحة ملف الناشر
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: فتاحة ملف PUB
h2: اقرأ ملفات PUB. افتح Publisher مع API لـ .NET
---

{{<section overview>}}
---
p1: يتم استخدام تنسيق ملف مستند الناشر Microsoft <sup> ® </sup> لإنشاء أنواع مختلفة من المنشورات مثل النشرات الإخبارية والكتيبات والنشرات الإعلانية والبطاقات البريدية ، ويتم استخدامه في رسائل البريد الإلكتروني ومواقع الويب. تحتوي ملفات Pub على نص وجداول بالإضافة إلى بيانات الصور النقطية والرسومات المتجهة.
p2: على الرغم من أن التنسيق شائع جدًا ، إلا أنه ليس شائعًا مثل تنسيقات مثل PDF أو DOCX. تطبيق MS Publisher ليس حرًا بحد ذاته.
p3: لذلك في بعض الأحيان يكون مطلوبًا فتح ملفات PUB بدون هذا البرنامج. هذا ضروري عندما تريد إظهار محتوى المستند ، دون تحريره أو معالجته بأي طريقة أخرى ، كما هو الحال عندما يكون لديك عرض تقديمي أو مراجعة. لهذه الأغراض ، يمكنك استخدام تطبيق PUB Viewer متعدد المنصات.
p4: هنا ستحصل على .NET API Solution الذي يتيح لك عرض خصائص مستند MS Publisher مثل الحجم والعرض والارتفاع وأسماء الخطوط المستخدمة وعدد الحقول والألوان.
---

{{<section feature1>}}
---
title: قراءة ملفات Publisher على .NET
item1: "لعرض خصائص ملفات .pub ، ستحتاج إلى اتخاذ الخطوات التالية:"
item2: تكامل .NET PUB API ، والذي لا يعمل فقط مع المستندات ذات الصفحة الواحدة ولكنه يدعم أيضًا ملفات .pub متعددة الصفحات.
item3: قم بتحميل ملف PUB الخاص بك باستخدام طريقة [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/createparser/) الخاصة بـ [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) فئة.
item4: قم بتحليل المستند عبر [*تحليل*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/parse/) طريقة [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) الواجهة.
item5: طباعة الوثيقة [*الخصائص*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties).
---

{{<section feature2>}}
---
title: ابدأ مع .NET PUB API
item1: "هناك طريقتان لتثبيت المنتج:"
item2: قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.PUB '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.PUB ''.
item3: بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: NET Code لقراءة خصائص ملفات PUB
---

{{<section summary>}}
---
item1: لرؤية مثال ReadPubDocument.cs الكود الكامل ، انتقل إلى حل Aspose.PUB.Examples.sln ، في أمثلة net من وثائق Aspose.PUB حيث يمكنك أيضًا العثور على أمثلة أخرى حول كيفية استخدام المكتبة.
---