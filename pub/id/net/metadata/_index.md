---
translation: true
template: /_templates/metadata-net.md
title: Sunting Penerbit | Metadata PUB | .NET
description: Baca file Publisher Metadata menggunakan PUB .NET API Solution lintas platform. .NET API lokal memberi Anda akses ke properti SummaryInfo dan DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: edit net metadata pub, metadata file pub C#, editor metadata penerbit .net, baca metadata file pub C#, baca metadata pub .net
family: pub
platformtag: net
feature: metadata
aliases: /net/metadata/
---

{{<section banner>}}
---
h1: Edit Metadata PUB
h2: Baca file Penerbit MS. API editor Metatada PUB untuk .NET
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Format file dokumen penerbit digunakan untuk membuat berbagai jenis publikasi seperti buletin, brosur, pamflet, dan kartu pos, serta digunakan dalam Email dan Situs Web. File pub berisi teks serta bitmap dan data grafik vektor.
p2: Metadata Publisher adalah properti (informasi) yang menjelaskan dokumen PUB. Mereka adalah properti standar seperti penerbit, judul, penulis terakhir, organisasi, URL, bahasa, dan informasi serupa lainnya. Ada juga data yang dihasilkan secara otomatis setelah bekerja dengan file seperti ukurannya atau waktu pengeditan terakhir. Informasi yang berguna ini disimpan bersama dengan dokumen.
p3: Bersama dengan fungsi Konversi dan Membaca, solusi API PUB untuk .NET ini memungkinkan Anda mengedit metadata standar melalui kelas DocSummaryInfo dan SummaryInfo seperti yang ditunjukkan dalam contoh kode berikut. Anda juga dapat menggunakan API untuk membuat aplikasi Editor Metadata Anda sendiri.
p4: Sebelum coding Metadata, Anda perlu mengintegrasikan C# .NET PUB Metadata API. Contoh berikut akan menunjukkan cara mengedit properti "Perusahaan".
---

{{<section feature1>}}
---
title: Edit Metadata File PUB di .NET
item1: "Proses membaca Metadata penerbit terdiri dari langkah-langkah berikut:"
item2: Unggah file PUB Anda menggunakan [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Metode [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory) Kelas.
item3: Parsing dokumen melalui [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Metode [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser) Antarmuka.
item4: Edit metadata mis. Perusahaan melalui [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Metode [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Kelas.
---

{{<section feature2>}}
---
title: Memulai dengan .NET PUB API
item1: Instal dari baris perintah sebagai ```nuget install Aspose.PUB``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.PUB```.
item2: Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/pub/net).
---

{{<section codeexample>}}
---
title: Kode .NET untuk Mengedit Metadata PUB
---