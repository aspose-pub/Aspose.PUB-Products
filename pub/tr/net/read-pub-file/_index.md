---
translation: true
template: /_templates/reader-net.md
title: PUB dosyalarını oku | .NET
description: Publisher dosyalarını programlı olarak açın. PUB özelliklerini okumak için C# .NET API çözümü. Projenize entegre etmek için kullanın.
url: /net/read-pub-file/
metakeywords: pub dosyasını aç .net, yayıncı dosyalarını görüntüle c#, yayıncı dosyalarını oku, c# için yayıncı görüntüleyici, pub format okuyucu, pub dosya açıcı
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: PUB dosya açacağı
h2: PUB dosyalarını okuyun. .NET için API ile Publisher'ı açın
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Yayıncı belge dosya formatı, haber bültenleri, broşürler, el ilanları ve kartpostallar gibi çeşitli yayın türleri oluşturmak için kullanılır ve E-postalarda ve Web Sitelerinde kullanılır. Pub dosyaları metin, tabloların yanı sıra bitmap ve vektör grafik verilerini içerir.
p2: Format oldukça popüler olsa da, PDF veya DOCX gibi formatlar kadar popüler değildir. MS Publisher uygulamasının kendisi ücretsiz değildir.
p3: Bu yüzden bazen PUB dosyalarını bu program olmadan açmak gerekir. Bu, örneğin bir sunumunuz veya incelemeniz olduğunda olduğu gibi, belgenin içeriğini herhangi bir şekilde düzenlemeden veya değiştirmeden göstermek istediğinizde gereklidir. Bu amaçlar için, platformlar arası bir PUB Görüntüleyici uygulaması kullanabilirsiniz.
p4: Burada MS Publisher belgesinin boyut, genişlik, yükseklik, kullanılan yazı tiplerinin adları, alan sayısı ve renkler gibi özelliklerini görüntülemenizi sağlayan .NET API Çözümünü alacaksınız.
---

{{<section feature1>}}
---
title: .NET'te Yayıncı dosyalarını okuyun
item1: ".pub dosyalarının özelliklerini görüntülemek için sonraki adımları uygulamanız gerekir:"
item2: Yalnızca tek sayfalık belgelerle değil, aynı zamanda çok sayfalı .pub dosyalarını da destekleyen .NET PUB API'sini entegre edin.
item3: PUB dosyanızı [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) [*PubFactory*](https:/) kullanarak yükleyin /reference.aspose.com/pub/net/aspose.pub/pubfactory) Sınıf.
item4: Belgeyi [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) aracılığıyla ayrıştırın [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Arayüzü.
item5: Belgeyi yazdırın [*properties*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties).
---

{{<section feature2>}}
---
title: .NET PUB API'sini Kullanmaya Başlayın
item1: "Ürünü kurmanın iki yolu vardır:"
item2: Komut satırından ```nuget install Aspose.PUB``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.PUB`` ile kurun.
item3: Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/pub/net/) adresinden bir ZIP dosyasında alın.
---

{{<section codeexample>}}
---
title: PUB dosyalarının özelliklerini okumak için .NET Kodu
---

{{<section summary>}}
---
item1: ReadPubDocument.cs örneğinin tam kodunu görmek için Aspose.PUB Documentation'ın net örneklerinde Aspose.PUB.Examples.sln çözümüne gidin, burada kitaplığın nasıl kullanılacağına dair başka örnekler de bulabilirsiniz.
---