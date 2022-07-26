---
translation: true
template: /_templates/metadata-java.md
title: प्रकाशक संपादित करें | पब मेटाडेटा | जावा
description: क्रॉस-प्लेटफ़ॉर्म PUB Java API समाधान का उपयोग करके प्रकाशक फ़ाइलें मेटाडेटा पढ़ें। ऑन-प्रिमाइसेस Java API आपको समरीइन्फो और DocSummaryInfo प्रॉपर्टीज़ तक पहुँच प्रदान करता है।
url: /java/metadata/pub/
metakeywords: पब मेटाडेटा जावा संपादित करें, पब फ़ाइल मेटाडेटा जावा, प्रकाशक मेटाडेटा संपादक जावा, पब फ़ाइल मेटाडेटा जावा पढ़ें, पब मेटाडेटा जावा पढ़ें
family: pub
platformtag: java
feature: metadata
aliases: /जावा/मेटाडेटा/
---

{{<section banner>}}
---
h1: पब मेटाडेटा संपादित करें
h2: एमएस प्रकाशक फ़ाइल पढ़ें। जावा के लिए पब मेटाटाडा संपादक एपीआई
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> प्रकाशक दस्तावेज़ फ़ाइल स्वरूप का उपयोग विभिन्न प्रकाशन प्रकार जैसे न्यूज़लेटर, ब्रोशर, फ़्लायर्स और पोस्टकार्ड बनाने के लिए किया जाता है और ईमेल और वेबसाइटों में उपयोग किया जाता है। पब फाइलों में टेक्स्ट के साथ-साथ बिटमैप और वेक्टर ग्राफिक्स डेटा भी होता है।
p2: प्रकाशक मेटाडेटा गुण (सूचना) है जो PUB दस्तावेज़ों का वर्णन करता है। वे मानक गुण हैं जैसे प्रकाशक, शीर्षक, अंतिम लेखक, संगठन, URL, भाषा और अन्य समान जानकारी। एक डेटा भी है जो फ़ाइल के आकार या अंतिम संपादन समय जैसी फ़ाइल के साथ काम करने के बाद स्वचालित रूप से उत्पन्न होता है। यह उपयोगी जानकारी दस्तावेज़ के साथ संग्रहीत की जाती है।
p3: रूपांतरण और पठन कार्यक्षमता के साथ, जावा के लिए यह पब एपीआई समाधान आपको DocSummaryInfo और सारांशइन्फो कक्षाओं के माध्यम से मानक मेटाडेटा को संपादित करने देता है जैसा कि निम्नलिखित कोड नमूने में दिखाया गया है। आप अपना खुद का मेटाडेटा संपादक एप्लिकेशन बनाने के लिए एपीआई का उपयोग भी कर सकते हैं।
p4: मेटाडेटा को कोड करने से पहले, आपको जावा पब मेटाडेटा एपीआई को एकीकृत करना होगा। निम्नलिखित उदाहरण आपको दिखाएगा कि "भाषा" संपत्ति को कैसे संपादित किया जाए।
---

{{<section widget>}}
---
title: जावा का उपयोग करके पब मेटाडेटा को कैसे संपादित करें
item1: "पब मेटाडेटा को संपादित करने के लिए, हम [Aspose.PUB for Java API](https://products.aspose.com/pub/java) का उपयोग करेंगे जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान रूपांतरण है जावा प्लेटफॉर्म के लिए एपीआई। आप इसका नवीनतम संस्करण सीधे [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pub) से डाउनलोड कर सकते हैं और इसे अपने Maven में इंस्टॉल कर सकते हैं निम्नलिखित विन्यास को pom.xml में जोड़कर -आधारित परियोजना।"
---

{{<section feature1>}}
---
title: जावा पर पब मेटाडेटा देखें और संपादित करें
item1: "प्रकाशक मेटाडेटा पढ़ने की प्रक्रिया में अगले चरण होते हैं:"
item2: '[*createParser*()](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) विधि का उपयोग करके अपनी PUB फ़ाइल अपलोड करें [*PubFactory*](https://apireference.aspose.com/pub/java/com.aspose.pub/PubFactory) क्लास।'
item3: '[*IPdfConverter*](https://apireference) की विधि से पार्स फ़ाइल [*पार्स*()](https://apireference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) .aspose.com/pub/java/com.aspose.pub/IPubParser) इंटरफ़ेस।'
item4: '[*setLanguage*()](https://apireference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) विधि द्वारा मेटाडेटा संपादित करें जैसे भाषा DocSummaryInfo*](https://apireference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) क्लास।'
---

{{<section feature2>}}
---
title: सिस्टम आवश्यकताएं
item1: जावा के लिए Aspose.PUB सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।
item2: J2SE 8.0 (1.8) या इसके बाद के संस्करण।
---

{{<section codeexample>}}
---
title: पब मेटाडेटा अपडेट करने के लिए जावा कोड
---