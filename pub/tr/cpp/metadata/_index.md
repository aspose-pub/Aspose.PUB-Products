---
translation: true
template: /_templates/metadata-cpp.md
title: Yayıncıyı Düzenle | PUB Meta Verileri | C++
description: PUB C++ API Çözümünü kullanarak Yayıncı dosyaları Meta Verilerini okuyun. Şirket içi C++ API, SummaryInfo ve DocSummaryInfo özelliklerine erişmenizi sağlar.
url: /cpp/metadata/pub/
metakeywords: pub meta verilerini düzenle, pub dosyası meta verilerini, yayıncı meta veri düzenleyicisini, pub dosyası meta verilerini oku, pub meta verilerini oku
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/meta veri/
---

{{<section banner>}}
---
h1: PUB Meta Verilerini Düzenle
h2: MS Publisher dosyasını okuyun. C++ için PUB Metatada düzenleyici API'si
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Yayıncı belge dosya formatı, haber bültenleri, broşürler, el ilanları ve kartpostallar gibi çeşitli yayın türleri oluşturmak için kullanılır ve E-postalarda ve Web Sitelerinde kullanılır. Pub dosyaları, bitmap ve vektör grafik verilerinin yanı sıra metin içerir.
p2: Yayıncı Meta Verileri, PUB belgelerini tanımlayan özelliklerdir (bilgi). Yayıncı, başlık, son yazar, kuruluş, URL, dil ve diğer benzer bilgiler gibi standart özelliklerdir. Boyutu veya son düzenleme zamanı gibi bir dosyayla çalıştıktan sonra otomatik olarak oluşturulan veriler de vardır. Bu faydalı bilgiler belgeyle birlikte saklanır.
p3: Dönüştürme ve Okuma işlevinin yanı sıra, C++ için bu PUB API çözümü, aşağıdaki kod örneğinde gösterildiği gibi DocSummaryInfo ve SummaryInfo sınıfları aracılığıyla standart meta verileri düzenlemenize olanak tanır. API'yi kendi Meta Veri Düzenleyici uygulamanızı oluşturmak için de kullanabilirsiniz.
p4: Meta Verileri kodlamadan önce, C++ PUB Meta Veri API'sini entegre etmeniz gerekir. Aşağıdaki örnek size "Kategori" özelliğini nasıl düzenleyeceğinizi gösterecektir.
---

{{<section feature1>}}
---
title: PUB Meta Verilerini C++'da Görüntüleme ve Düzenleme
item1: "Yayıncı Meta Veri okuma süreci aşağıdaki adımlardan oluşur:"
item2: '[*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) [*PubFactory*](https://apireference) yöntemini kullanarak PUB dosyanızı yükleyin .aspose.com/pub/cpp/class/aspose.pub.pub_factory) Sınıf.'
item3: Dosyayı [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) aracılığıyla ayrıştırın [*IPubParser*](https://apireference.aspose) .com/pub/cpp/class/aspose.pub.i_pub_parser) Arayüz.
item4: Meta verileri düzenleyin, örneğin [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) aracılığıyla Kategori düzenleyin [*DocSummaryInfo*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Sınıf.
---

{{<section feature2>}}
---
title: CPP PUB API'sini Kullanmaya Başlayın
item1: Komut satırından ``nuget install Aspose.PUB.cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.PUB.cpp`` ile kurun.
item2: Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/pub/cpp) adresinden bir ZIP dosyasında alın.
---

{{<section codeexample>}}
---
title: PUB Meta Verilerini Değiştirmek için C++ Kodu
---
