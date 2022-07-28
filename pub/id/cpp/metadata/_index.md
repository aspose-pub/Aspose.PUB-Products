---
translation: true
template: /_templates/metadata-cpp.md
title: Sunting Penerbit | Metadata PUB | C++
description: Baca Metadata file Publisher menggunakan PUB C++ API Solution. C++ API lokal memberi Anda akses ke properti SummaryInfo dan DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: edit metadata pub, metadata file pub, editor metadata penerbit, baca metadata file pub, baca metadata pub
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/metadata/
---

{{<section banner>}}
---
h1: Edit Metadata PUB
h2: Baca file Penerbit MS. API editor Metatada PUB untuk C++
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Format file dokumen penerbit digunakan untuk membuat berbagai jenis publikasi seperti buletin, brosur, pamflet, dan kartu pos, serta digunakan dalam Email dan Situs Web. File pub berisi teks serta bitmap dan data grafik vektor.
p2: Metadata Publisher adalah properti (informasi) yang menjelaskan dokumen PUB. Mereka adalah properti standar seperti penerbit, judul, penulis terakhir, organisasi, URL, bahasa, dan informasi serupa lainnya. Ada juga data yang dihasilkan secara otomatis setelah bekerja dengan file seperti ukurannya atau waktu pengeditan terakhir. Informasi yang berguna ini disimpan bersama dengan dokumen.
p3: Bersama dengan fungsi Konversi dan Membaca, solusi PUB API untuk C++ ini memungkinkan Anda mengedit metadata standar melalui kelas DocSummaryInfo dan SummaryInfo seperti yang ditunjukkan dalam contoh kode berikut. Anda juga dapat menggunakan API untuk membuat aplikasi Editor Metadata Anda sendiri.
p4: Sebelum coding Metadata, Anda perlu mengintegrasikan C++ PUB Metadata API. Contoh berikut akan menunjukkan cara mengedit properti "Category".
---

{{<section feature1>}}
---
title: Lihat & Edit Metadata PUB di C++
item1: "Proses membaca Metadata penerbit terdiri dari langkah-langkah berikut:"
item2: Unggah file PUB Anda menggunakan [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Metode [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Kelas.
item3: Parsing file melalui [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Metode [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Antarmuka.
item4: Edit metadata mis. Kategori melalui [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Metode [*DocSummaryInfo*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Kelas.
---

{{<section feature2>}}
---
title: Memulai dengan CPP PUB API
item1: Instal dari baris perintah sebagai ``` nuget install Aspose.PUB.cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.PUB.cpp```.
item2: Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/pub/cpp/).
---

{{<section codeexample>}}
---
title: Kode C++ untuk Memodifikasi Metadata PUB
---
