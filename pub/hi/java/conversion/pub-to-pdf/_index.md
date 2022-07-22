﻿---
translation: true
template: /_templates/conversion-child-java.md
title: PUB को PDF में बदलें | जावा
description: विंडोज़, लिनक्स और मैक ओएस एक्स पर जावा एपीआई का उपयोग करके पीयूबी को पीडीएफ में कनवर्ट करें। प्रकाशक रूपांतरण कार्यक्षमता जो आपके स्वयं के समाधान में एकीकृत करना आसान है।
url: /java/conversion/pub-to-pdf/
metakeywords: पब से पीडीएफ जावा, पब को पीडीएफ में बदलें जावा, जावा पब को पीडीएफ में, प्रकाशक को पीडीएफ में जावा;
family: pub
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: PUB को PDF में बदलें
h2: पीडीएफ कनवर्टर के लिए प्रकाशक। जावा एपीआई रूपांतरण कार्यक्षमता।
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> प्रकाशक दस्तावेज़ फ़ाइल स्वरूप का उपयोग विभिन्न प्रकाशन प्रकार जैसे न्यूज़लेटर, ब्रोशर, फ़्लायर्स और पोस्टकार्ड बनाने के लिए किया जाता है और ईमेल और वेबसाइटों में उपयोग किया जाता है। पब फाइलों में टेक्स्ट के साथ-साथ बिटमैप और वेक्टर ग्राफिक्स डेटा भी होता है।
p2: अन्य सभी Microsoft<sup>®</sup> उत्पादों की तरह प्रकाशक एप्लिकेशन स्वयं मुक्त नहीं है। और चूंकि प्रारूप की फ़ाइल केवल इस कार्यक्रम द्वारा आपके काम के परिणामों को साझा करने के लिए खोली जा सकती है, कभी-कभी आपको एक पब फ़ाइल को अधिक अच्छी तरह से फैले प्रारूप में परिवर्तित करना होगा। सभी में सबसे लोकप्रिय PUB से PDF रूपांतरण है। अब तक, यह प्रारूप सभी आधुनिक उपकरणों द्वारा समर्थित है और बिना किसी अतिरिक्त सॉफ़्टवेयर को स्थापित किए ब्राउज़र में भी खोला जा सकता है। यहाँ जावा के लिए PUB से PDF रूपांतरण कार्यक्षमता है। इस पुस्तकालय का उपयोग आपका अपना प्रोजेक्ट बनाने के लिए भी किया जा सकता है।
p3: रूपांतरण चलाने से पहले आपको जावा पब को पीडीएफ कन्वर्टर एपीआई में एकीकृत करने की आवश्यकता है, जो न केवल सिंगल-पेज दस्तावेज़ों के साथ काम करता है बल्कि मल्टीपेज .पब फाइलों का भी समर्थन करता है।
---

{{<section widget>}}
---
title: जावा का उपयोग करके पब को पीडीएफ में कैसे बदलें
item1: "PUB को PDF में बदलने के लिए, हम [Aspose.PUB for Java API](https://products.aspose.com/pub/java) का उपयोग करेंगे, जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान रूपांतरण API है। जावा मंच। आप इसका नवीनतम संस्करण सीधे [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pub) से डाउनलोड कर सकते हैं और इसे अपने Maven में इंस्टॉल कर सकते हैं निम्नलिखित विन्यास को pom.xml में जोड़कर -आधारित परियोजना।"
---

{{<section feature1>}}
---
title: जावा पर पब से पीडीएफ रूपांतरण
item1: '[* createParser()*](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) विधि का उपयोग करके PUB फ़ाइल लोड करें [*PubFactory*](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory) कक्षा।'
item2: '[* पार्स()*](https://apireference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) का उपयोग करके पार्स फ़ाइल .aspose.com/pub/java/com.aspose.pub/IPubParser) इंटरफ़ेस।'
item3: '[*ConvertToPdf()*](https://apireference.aspose.com/pub/java/com.aspose.pub/IPdfConverter#convertToPdf-com.aspose.pub.Document-java.lang.String का उपयोग करके PUB को PDF में बदलें -) विधि [*IPdfConverter*](https://apireference.aspose.com/pub/java/com.aspose.pub/IPdfConverter) इंटरफेस।'
---

{{<section feature2>}}
---
title: सिस्टम आवश्यकताएं
item1: जावा के लिए Aspose.PUB सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।
item2: "J2SE 8.0 (1.8) या इसके बाद के संस्करण।"
---

{{<section codeexample>}}
---
title: पब से पीडीएफ रूपांतरण के लिए जावा कोड
---

{{<section summary>}}
---
p1: PUB से PDF रूपांतरण किसी भी अन्य प्रारूप रूपांतरण के लिए PUB में एक आवश्यक कदम है। इसके बाद, रूपांतरित फ़ाइल को आवश्यक प्रारूप में परिवर्तित किया जा सकता है।
p2: आप PUB से PDF क्रॉस-प्लेटफ़ॉर्म एप्लिकेशन भी आज़मा सकते हैं। इसका एक बहुत ही सरल इंटरफ़ेस है और इस प्रक्रिया में केवल कुछ सेकंड लगेंगे।
p3: "समाधान आपको अनुमति देता है: एकाधिक प्रकाशक फ़ाइलों को रूपांतरित करें, PUB को PDF में बदलें, और रूपांतरित दस्तावेज़ों को अपने डिवाइस पर सहेजें।"
---