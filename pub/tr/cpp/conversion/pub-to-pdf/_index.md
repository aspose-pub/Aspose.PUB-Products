---
translation: true
template: /_templates/conversion-child.md
title: PUB'u PDF'ye Dönüştür | C++
description: Windows, Linux ve Mac OS X'te C++ API'sini kullanarak PUB'u PDF'ye dönüştürün. Kendi çözümünüze entegre edilmesi kolay yayıncı dönüştürme işlevi.
url: /cpp/conversion/pub-to-pdf/
metakeywords: pub'ı pdf c++'a, pub'ı pdf cpp'ye, c++ pub'ı pdf'ye, yayıncıyı pdf c++'a dönüştürün
family: pub
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: PUB'u PDF'ye dönüştür
h2: Yayıncıdan PDF'ye Dönüştürücü. С++ API Dönüştürme işlevi.
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Yayıncı belge dosya formatı, haber bültenleri, broşürler, el ilanları ve kartpostallar gibi çeşitli yayın türleri oluşturmak için kullanılır ve E-postalarda ve Web Sitelerinde kullanılır. Pub dosyaları, bitmap ve vektör grafik verilerinin yanı sıra metin içerir.
p2: Diğer tüm Microsoft<sup>®</sup> ürünleri gibi Publisher uygulamasının kendisi ücretsiz değildir. Ve formatın dosyası sadece bu program tarafından çalışmanızın sonuçlarını paylaşmak için açılabildiğinden, bazen bir PUB dosyasını daha iyi yayılmış bir formata dönüştürmek zorunda kalacaksınız. En popüler olanı PUB'dan PDF'ye dönüştürmedir. Şimdiye kadar, bu biçim tüm modern cihazlar tarafından desteklenmektedir ve herhangi bir ek yazılım yüklemeden bir tarayıcıda bile açılabilir. İşte C++ için PUB'dan PDF'ye dönüştürme işlevi. Bu kütüphane aynı zamanda kendi projenizi oluşturmak için de kullanılabilir.
p3: Dönüştürmeyi çalıştırmadan önce, yalnızca tek sayfalık belgelerle değil, aynı zamanda çok sayfalı .pub dosyalarını da destekleyen C++ PUB'u PDF Converter API'ye entegre etmeniz gerekir.
---

{{<section feature1>}}
---
title: C++'da PUB'dan PDF'ye Dönüştürme
item1: PUB dosyasını [*CreateParser()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) [*PubFactory*](https://) aracılığıyla yükleyin apireference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Sınıf.
item2: '[*Parse()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) kullanarak dosyayı ayrıştırın [*IPubParser*](https://apireference.aspose) .com/pub/cpp/class/aspose.pub.i_pub_parser) Arayüz.'
item3: Dönüştürmeyi [*ConvertToPdf()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter#acdea381bc8f2a2799e73a039b09ecdb5) Yöntemiyle çalıştırın [*IPdfConverter*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter) Arayüz.
---

{{<section feature2>}}
---
title: C++ PUB API'sini Kullanmaya Başlayın
item1: Komut satırından ``nuget install Aspose.PUB.cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.PUB.cpp`` ile kurun.
item2: Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/pub/cpp/) adresinden bir ZIP dosyasında alın.
---

{{<section codeexample>}}
---
title: PUB'dan PDF'ye Dönüştürme için C++ Kodu
---

{{<section summary>}}
---
p1: PUB'dan PDF'ye Dönüştürme, PUB'da herhangi bir başka formata Dönüştürme için gerekli bir adımdır. Bundan sonra, dönüştürülen dosya gerekli biçime dönüştürülebilir.
p2: Ayrıca PUB to PDF çapraz platform uygulamasını deneyebilirsiniz. Çok basit bir arayüze sahiptir ve işlem sadece birkaç saniye sürecektir.
p3: "Çözüm şunları yapmanızı sağlar: Birden çok Publisher dosyasını dönüştürün, PUB'u PDF'ye dönüştürün ve dönüştürülmüş belgeleri cihazınıza kaydedin."
---