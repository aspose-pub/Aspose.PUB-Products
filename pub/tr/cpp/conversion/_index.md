---
translation: true
template: /_templates/conversion.md
title: PUB Dönüştürücü API çözümü | C++
url: /cpp/conversion/
description: Microsoft Publisher dosyalarını C++ kitaplığı aracılığıyla Programlı olarak dönüştürün. Kendi PUB dönüştürücü C++ projenizi oluşturmak için basit API çözümü.
metakeywords: pub cpp dönüştürücü, pub dosyasını cpp dönüştürün
family: pub
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: PUB dosyasını dönüştür
h2: Platformlar arası C++ uygulamaları oluşturmak için yayıncı dönüştürücü işlevi.
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Yayıncı belge dosya formatı, haber bültenleri, broşürler, el ilanları ve kartpostallar gibi çeşitli yayın türleri oluşturmak için kullanılır ve E-postalarda ve Web Sitelerinde kullanılır. Pub dosyaları, bitmap ve vektör grafik verilerinin yanı sıra metin içerir.
p2: Format oldukça popüler olsa da, PDF veya DOCX gibi formatlar kadar popüler değildir. MS Publisher uygulamasının kendisi ücretsiz değildir. Bu nedenle, genellikle .pub uzantılı dosyaları başka, iyi yayılmış ve kullanımı rahat bir formata dönüştürmek gerekir. İşte C++ için dönüştürme işlevi. Bu kitaplık, kendi projenizi oluşturmak için kullanılabilecek gerekli dönüştürme işlevselliğini içerir.
---

{{<section feature1>}}
---
title: Publisher .pub dosyalarını dönüştürün
item1: PUB'dan PDF'ye dönüştürme yoluyla işlevselliğe bakalım.
item2: "Yayıncı Dönüşüm süreci aşağıdaki adımlardan oluşur:"
item3: Yalnızca tek sayfalık belgelerle değil, aynı zamanda çok sayfalı .pub dosyalarını da destekleyen C++ PUB to PDF Converter API'yi entegre edin.
item4: '[*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Sınıfını kullanarak PUB dosyasını yükleyin.'
item5: '[*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Yöntemiyle Ayrıştırıcı Oluştur ve Ayrıştır [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Arayüz.'
item6: Dönüştürmeyi [*ConvertToPdf*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter) Yöntemiyle çalıştırın.
---

{{<section codeexample>}}
---
title: Publisher PUB'u PDF'ye Dönüştürmek için C++ Kodu
---

{{<section summary>}}
---
p1: PUB'un başka bir formata dönüştürülmesi, dosyanın PDF formatına dönüştürülmesinden sonra mümkündür ve daha sonra bu dönüştürülmüş dosya gerekli formata dönüştürülebilir.
p2: "Publisher Converter çapraz platform uygulamasını da deneyebilirsiniz. Çok basit bir arayüze sahiptir ve işlem sadece birkaç saniye sürecektir. Çözüm şunları sağlar:"
p3: Birden çok Publisher dosyasını dönüştürün.
p4: PUB'u PDF, HTML, EPUB, DOCX, SVG ve diğer birçok görüntü formatına dönüştürün.
p5: Dönüştürülen belgeleri cihazınıza kaydedin.
---