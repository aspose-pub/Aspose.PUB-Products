---
translation: true
template: /_templates/metadata-java.md
title: Yayıncıyı Düzenle | PUB Meta Verileri | Java
description: Platformlar arası PUB Java API Çözümünü kullanarak Yayıncı dosyaları Meta Verilerini okuyun. Şirket içi Java API, SummaryInfo ve DocSummaryInfo özelliklerine erişmenizi sağlar.
url: /java/metadata/pub/
metakeywords: pub meta verilerini düzenle java, pub dosyası meta verileri java, yayıncı meta veri düzenleyicisi java, pub dosyası meta verilerini oku java, pub meta verilerini oku java
family: pub
platformtag: java
feature: metadata
aliases: /java/meta veri/
---

{{<section banner>}}
---
h1: PUB Meta Verilerini Düzenle
h2: MS Publisher dosyasını okuyun. Java için PUB Metatada düzenleyici API'si
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Yayıncı belge dosya formatı, haber bültenleri, broşürler, el ilanları ve kartpostallar gibi çeşitli yayın türleri oluşturmak için kullanılır ve E-postalarda ve Web Sitelerinde kullanılır. Pub dosyaları, bitmap ve vektör grafik verilerinin yanı sıra metin içerir.
p2: Yayıncı Meta Verileri, PUB belgelerini tanımlayan özelliklerdir (bilgi). Yayıncı, başlık, son yazar, kuruluş, URL, dil ve diğer benzer bilgiler gibi standart özelliklerdir. Boyutu veya son düzenleme zamanı gibi bir dosyayla çalıştıktan sonra otomatik olarak oluşturulan veriler de vardır. Bu faydalı bilgiler belgeyle birlikte saklanır.
p3: Dönüştürme ve Okuma işlevinin yanı sıra Java için bu PUB API çözümü, aşağıdaki kod örneğinde gösterildiği gibi DocSummaryInfo ve SummaryInfo sınıfları aracılığıyla standart meta verileri düzenlemenize olanak tanır. API'yi kendi Meta Veri Düzenleyici uygulamanızı oluşturmak için de kullanabilirsiniz.
p4: Meta Verileri kodlamadan önce Java PUB Meta Veri API'sini entegre etmeniz gerekir. Aşağıdaki örnek size "Dil" özelliğini nasıl düzenleyeceğinizi gösterecektir.
---

{{<section widget>}}
---
title: Java Kullanarak PUB Meta Verileri Nasıl Düzenlenir
item1: "PUB Meta Verilerini Düzenlemek için, zengin özelliklere sahip, güçlü ve kullanımı kolay bir dönüşüm olan [Aspose.PUB for Java API](https://products.aspose.com/pub/java/) kullanacağız. Java platformu için API. En son sürümünü doğrudan [Maven](https://repository.aspose.com/pub/) adresinden indirebilir ve Maven'inize yükleyebilirsiniz. pom.xml dosyasına aşağıdaki konfigürasyonları ekleyerek proje tabanlı bir proje oluşturun."
---

{{<section feature1>}}
---
title: Java'da PUB Meta Verilerini Görüntüleme ve Düzenleme
item1: "Yayıncı Meta Veri okuma süreci aşağıdaki adımlardan oluşur:"
item2: '[*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) yöntemini kullanarak PUB dosyanızı yükleyin [*PubFactory*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Sınıf.'
item3: Dosyayı [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) yöntemiyle ayrıştırın [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) Arayüzü.
item4: Meta verileri düzenleyin, örneğin [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) aracılığıyla Dil  Yöntemi [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Sınıf.
---

{{<section feature2>}}
---
title: sistem gereksinimleri
item1: Aspose.PUB for Java, tüm büyük işletim sistemlerinde desteklenir. Sadece aşağıdaki ön koşullara sahip olduğunuzdan emin olun.
item2: J2SE 8.0 (1.8) veya üzeri.
---

{{<section codeexample>}}
---
title: PUB Meta Verilerini Güncellemek için Java Kodu
---