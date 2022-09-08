---
translation: true
template: /_templates/metadata-java.md
title: Sunting Penerbit | Metadata PUB | Jawa
description: Baca file Publisher Metadata menggunakan PUB Java API Solution lintas platform. Java API lokal memberi Anda akses ke properti SummaryInfo dan DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: edit metadata pub java, metadata file pub java, editor metadata penerbit java, baca metadata file pub java, baca metadata pub java
family: pub
platformtag: java
feature: metadata
aliases: /java/metadata/
---

{{<section banner>}}
---
h1: Edit Metadata PUB
h2: Baca file Penerbit MS. API editor Metatada PUB untuk Java
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Format file dokumen penerbit digunakan untuk membuat berbagai jenis publikasi seperti buletin, brosur, pamflet, dan kartu pos, serta digunakan dalam Email dan Situs Web. File pub berisi teks serta bitmap dan data grafik vektor.
p2: Metadata Publisher adalah properti (informasi) yang menjelaskan dokumen PUB. Mereka adalah properti standar seperti penerbit, judul, penulis terakhir, organisasi, URL, bahasa, dan informasi serupa lainnya. Ada juga data yang dihasilkan secara otomatis setelah bekerja dengan file seperti ukurannya atau waktu pengeditan terakhir. Informasi yang berguna ini disimpan bersama dengan dokumen.
p3: Bersama dengan fungsi Konversi dan Membaca, solusi PUB API untuk Java ini memungkinkan Anda mengedit metadata standar melalui kelas DocSummaryInfo dan SummaryInfo seperti yang ditunjukkan dalam contoh kode berikut. Anda juga dapat menggunakan API untuk membuat aplikasi Editor Metadata Anda sendiri.
p4: Sebelum coding Metadata, Anda perlu mengintegrasikan Java PUB Metadata API. Contoh berikut akan menunjukkan cara mengedit properti "Bahasa".
---

{{<section widget>}}
---
title: Cara Mengedit Metadata PUB Menggunakan Java
item1: "Untuk Mengedit Metadata PUB, kami akan menggunakan [Aspose.PUB for Java API](https://products.aspose.com/pub/java/) yang merupakan konversi yang kaya fitur, kuat, dan mudah digunakan API untuk platform Java. Anda dapat mengunduh versi terbarunya langsung dari [Aspose Maven Repository](https://repository.aspose.com/pub/) dan menginstalnya di dalam Maven Anda -proyek berbasis dengan menambahkan konfigurasi berikut ke pom.xml."
---

{{<section feature1>}}
---
title: Lihat dan Edit Metadata PUB di Java
item1: "Proses membaca Metadata penerbit terdiri dari langkah-langkah berikut:"
item2: Unggah file PUB Anda menggunakan [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) Metode [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/pubfactory/) Kelas.
item3: Parsing file melalui [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) metode [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) Antarmuka.
item4: Edit metadata mis. Bahasa melalui [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Metode [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Kelas.
---

{{<section feature2>}}
---
title: Persyaratan sistem
item1: Aspose.PUB untuk Java didukung di semua sistem operasi utama. Pastikan saja Anda memiliki prasyarat berikut.
item2: J2SE 8.0 (1.8) atau lebih tinggi.
---

{{<section codeexample>}}
---
title: Kode Java untuk Memperbarui Metadata PUB
---