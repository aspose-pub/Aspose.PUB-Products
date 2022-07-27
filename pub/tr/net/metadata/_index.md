---
translation: true
template: /_templates/metadata-net.md
title: Yayıncıyı Düzenle | PUB Meta Verileri | .NET
description: PUB .NET API Çözümünü kullanarak Yayıncı Meta Verilerini okuyun. Yerel C# /NET API, SummaryInfo ve DocSummaryInfo özelliklerine erişmenizi sağlar.
url: /net/metadata/pub/
metakeywords: pub metadata net'i düzenle, pub dosyası metadata C#, yayıncı metadata editor .net, pub dosyası metadata C# oku, pub metadata oku .net
family: pub
platformtag: net
feature: metadata
aliases: /net/meta veri/
---

{{<section banner>}}
---
h1: PUB Meta Verilerini Düzenle
h2: MS Publisher dosyasını okuyun. .NET için PUB Meta Veri düzenleyici API'si
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Yayıncı belge dosya formatı, haber bültenleri, broşürler, el ilanları ve kartpostallar gibi çeşitli yayın türleri oluşturmak için kullanılır ve E-postalarda ve Web Sitelerinde kullanılır. Pub dosyaları, bitmap ve vektör grafik verilerinin yanı sıra metin içerir.
p2: Yayıncı Meta Verileri, PUB belgelerini tanımlayan özelliklerdir (bilgi). Yayıncı, başlık, son yazar, kuruluş, URL, dil ve diğer benzer bilgiler gibi standart özelliklerdir. Boyutu veya son düzenleme zamanı gibi bir dosyayla çalıştıktan sonra otomatik olarak oluşturulan veriler de vardır. Bu faydalı bilgiler belgeyle birlikte saklanır.
p3: Dönüştürme ve Okuma işlevinin yanı sıra, .NET için bu PUB API çözümü, aşağıdaki kod örneğinde gösterildiği gibi DocSummaryInfo ve SummaryInfo sınıfları aracılığıyla standart meta verileri düzenlemenize olanak tanır. API'yi kendi Meta Veri Düzenleyici uygulamanızı oluşturmak için de kullanabilirsiniz.
p4: Meta Verileri kodlamadan önce, C# .NET PUB Meta Veri API'sini entegre etmeniz gerekir. Aşağıdaki örnek size "Şirket" özelliğini nasıl düzenleyeceğinizi gösterecektir.
---

{{<section feature1>}}
---
title: .NET'te PUB Dosyalarının Meta Verilerini Düzenleme
item1: "Yayıncı Meta Veri okuma süreci aşağıdaki adımlardan oluşur:"
item2: PUB dosyanızı [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) kullanarak yükleyin [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory) Sınıf.
item3: Belgeyi [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) aracılığıyla ayrıştırın [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser) Arayüzü.
item4: Meta verileri düzenleyin ör. Şirket [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Sınıf.
---

{{<section feature2>}}
---
title: .NET PUB API'sini Kullanmaya Başlayın
item1: Komut satırından ```nuget install Aspose.PUB``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.PUB`` ile kurun.
item2: Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/pub/net) adresinden bir ZIP dosyasında alın.
---

{{<section codeexample>}}
---
title: PUB Meta Verilerini Düzenlemek için .NET Kodu
---