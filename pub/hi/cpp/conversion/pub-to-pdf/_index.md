---
translation: true
template: /_templates/conversion-child.md
title: PUB को PDF में बदलें | सी++
description: किसी भी सिस्टम पर C++ API का उपयोग करके PUB को PDF में बदलें। प्रकाशक रूपांतरण कार्यक्षमता जो आपके स्वयं के समाधान में एकीकृत करना आसान है।
url: /cpp/conversion/pub-to-pdf/
metakeywords: पब से पीडीएफ सी ++, पब को पीडीएफ में बदलें सीपीपी, सी ++ पब से पीडीएफ, प्रकाशक को पीडीएफ में सी ++
family: pub
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: PUB को PDF में बदलें
h2: पीडीएफ कन्वर्टर के लिए प्रकाशक। ++ एपीआई रूपांतरण कार्यक्षमता।
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> प्रकाशक दस्तावेज़ फ़ाइल स्वरूप का उपयोग विभिन्न प्रकाशन प्रकार जैसे न्यूज़लेटर, ब्रोशर, फ़्लायर्स और पोस्टकार्ड बनाने के लिए किया जाता है और ईमेल और वेबसाइटों में उपयोग किया जाता है। पब फाइलों में टेक्स्ट के साथ-साथ बिटमैप और वेक्टर ग्राफिक्स डेटा भी होता है।
p2: अन्य सभी Microsoft<sup>®</sup> उत्पादों की तरह प्रकाशक एप्लिकेशन स्वयं मुक्त नहीं है। और चूंकि प्रारूप की फ़ाइल केवल इस कार्यक्रम द्वारा आपके काम के परिणामों को साझा करने के लिए खोली जा सकती है, कभी-कभी आपको एक पब फ़ाइल को अधिक अच्छी तरह से फैले प्रारूप में परिवर्तित करना होगा। सभी में सबसे लोकप्रिय PUB से PDF रूपांतरण है। अब तक, यह प्रारूप सभी आधुनिक उपकरणों द्वारा समर्थित है और बिना किसी अतिरिक्त सॉफ़्टवेयर को स्थापित किए ब्राउज़र में भी खोला जा सकता है। यहाँ C++ के लिए PUB से PDF रूपांतरण कार्यक्षमता है। इस पुस्तकालय का उपयोग आपका अपना प्रोजेक्ट बनाने के लिए भी किया जा सकता है।
p3: रूपांतरण चलाने से पहले आपको C++ PUB को PDF कन्वर्टर API में एकीकृत करने की आवश्यकता है, जो न केवल सिंगल-पेज दस्तावेज़ों के साथ काम करता है बल्कि मल्टीपेज .pub फ़ाइलों का भी समर्थन करता है।
---

{{<section feature1>}}
---
title: C++ पर PUB से PDF रूपांतरण
item1: '[*CreateParser()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) विधि के माध्यम से PUB फ़ाइल लोड करें [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) कक्षा।'
item2: '[Parse()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) का उपयोग करके पार्स फ़ाइल [*IPubParser*](https://apireference.aspose) .com/pub/cpp/class/aspose.pub.i_pub_parser) इंटरफ़ेस।'
item3: '[ConvertToPdf()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter#acdea381bc8f2a2799e73a039b09ecdb5) के माध्यम से रूपांतरण चलाएँ [*IPdfConverter*] की विधि (https:// apireference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter) इंटरफ़ेस।'
---

{{<section feature2>}}
---
title: सी++ पब एपीआई के साथ आरंभ करें
item1: कमांड लाइन से ```nuget install Aspose.PUB.cpp``` के रूप में या ````Install-Package Aspose.PUB.cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।
item2: वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/pub/cpp/) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
---

{{<section codeexample>}}
---
title: PUB से PDF रूपांतरण के लिए C++ कोड
---

{{<section summary>}}
---
p1: PUB से PDF रूपांतरण किसी भी अन्य प्रारूप रूपांतरण के लिए PUB में एक आवश्यक कदम है। इसके बाद, रूपांतरित फ़ाइल को आवश्यक प्रारूप में परिवर्तित किया जा सकता है।
p2: आप PUB से PDF क्रॉस-प्लेटफ़ॉर्म एप्लिकेशन भी आज़मा सकते हैं। इसका एक बहुत ही सरल इंटरफ़ेस है और इस प्रक्रिया में केवल कुछ सेकंड लगेंगे।
p3: "समाधान आपको अनुमति देता है: एकाधिक प्रकाशक फ़ाइलों को रूपांतरित करें, PUB को PDF में बदलें, और रूपांतरित दस्तावेज़ों को अपने डिवाइस पर सहेजें।"
---