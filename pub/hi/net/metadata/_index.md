---
translation: true
template: /_templates/metadata-net.md
title: प्रकाशक संपादित करें | पब मेटाडेटा | .NET
description: क्रॉस-प्लेटफ़ॉर्म PUB .NET API समाधान का उपयोग करके प्रकाशक फ़ाइलें मेटाडेटा पढ़ें। ऑन-प्रिमाइसेस .NET API आपको समरीइन्फो और DocSummaryInfo प्रॉपर्टीज़ तक पहुँच प्रदान करता है।
url: /net/metadata/pub/
metakeywords: पब मेटाडेटा नेट संपादित करें, पब फ़ाइल मेटाडेटा C#, प्रकाशक मेटाडेटा संपादक .net, पब फ़ाइल मेटाडेटा C# पढ़ें, पब मेटाडेटा .net पढ़ें
family: pub
platformtag: net
feature: metadata
aliases: /नेट/मेटाडेटा/
---

{{<section banner>}}
---
h1: पब मेटाडेटा संपादित करें
h2: एमएस प्रकाशक फ़ाइल पढ़ें। .NET के लिए पब मेटाटाडा संपादक एपीआई
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> प्रकाशक दस्तावेज़ फ़ाइल स्वरूप का उपयोग विभिन्न प्रकाशन प्रकार जैसे न्यूज़लेटर, ब्रोशर, फ़्लायर्स और पोस्टकार्ड बनाने के लिए किया जाता है और ईमेल और वेबसाइटों में उपयोग किया जाता है। पब फाइलों में टेक्स्ट के साथ-साथ बिटमैप और वेक्टर ग्राफिक्स डेटा भी होता है।
p2: प्रकाशक मेटाडेटा गुण (सूचना) है जो PUB दस्तावेज़ों का वर्णन करता है। वे मानक गुण हैं जैसे प्रकाशक, शीर्षक, अंतिम लेखक, संगठन, URL, भाषा और अन्य समान जानकारी। एक डेटा भी है जो फ़ाइल के आकार या अंतिम संपादन समय जैसी फ़ाइल के साथ काम करने के बाद स्वचालित रूप से उत्पन्न होता है। यह उपयोगी जानकारी दस्तावेज़ के साथ संग्रहीत की जाती है।
p3: रूपांतरण और पठन कार्यक्षमता के साथ, .NET के लिए यह पब एपीआई समाधान आपको DocSummaryInfo और सारांशइन्फो कक्षाओं के माध्यम से मानक मेटाडेटा को संपादित करने देता है जैसा कि निम्नलिखित कोड नमूने में दिखाया गया है। आप अपना खुद का मेटाडेटा संपादक एप्लिकेशन बनाने के लिए एपीआई का उपयोग भी कर सकते हैं।
p4: मेटाडेटा को कोड करने से पहले, आपको C# .NET PUB मेटाडेटा API को एकीकृत करना होगा। निम्नलिखित उदाहरण आपको दिखाएगा कि "कंपनी" संपत्ति को कैसे संपादित किया जाए।
---

{{<section feature1>}}
---
title: .NET पर पब फ़ाइलों का मेटाडेटा संपादित करें
item1: "प्रकाशक मेटाडेटा पढ़ने की प्रक्रिया में अगले चरण होते हैं:"
item2: '[*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) विधि का उपयोग करके अपनी PUB फ़ाइल अपलोड करें [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) कक्षा।'
item3: दस्तावेज़ को [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) के माध्यम से पार्स करें। aspose.com/pub/net/aspose.pub/ipubparser) इंटरफ़ेस।
item4: '[*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) के माध्यम से मेटाडेटा संपादित करें जैसे कंपनी [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) कक्षा।'
---

{{<section feature2>}}
---
title: .NET पब एपीआई के साथ आरंभ करें
item1: कमांड लाइन से ```nuget install Aspose.PUB``` के रूप में या `````Install-Package Aspose.PUB`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।
item2: वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/pub/net/) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
---

{{<section codeexample>}}
---
title: पब मेटाडेटा संपादित करने के लिए .NET कोड
---