---
translation: true
template: /_templates/conversion-child-java.md
title: แปลง PUB เป็น PDF | Java
description: แปลง PUB เป็น PDF โดยใช้ Java API บน Windows, Linux และ Mac OS X ฟังก์ชันการแปลง Publisher ที่รวมเข้ากับโซลูชันของคุณเองได้ง่าย
url: /java/conversion/pub-to-pdf/
metakeywords: pub เป็น pdf java, แปลง pub เป็น pdf java, java pub เป็น pdf, ผู้เผยแพร่เป็น pdf java
family: pub
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: แปลง PUB เป็น PDF
h2: สำนักพิมพ์เป็น PDF Converter ฟังก์ชันการแปลง Java API
---

{{<section overview>}}
---
p1: รูปแบบไฟล์เอกสาร Microsoft<sup>®</sup> Publisher ใช้สำหรับสร้างสิ่งพิมพ์ประเภทต่างๆ เช่น จดหมายข่าว โบรชัวร์ ใบปลิว และไปรษณียบัตร และใช้ในอีเมลและเว็บไซต์ ไฟล์ Pub มีข้อความรวมถึงข้อมูลบิตแมปและกราฟิกแบบเวกเตอร์
p2: เนื่องจากผลิตภัณฑ์ Microsoft<sup>®</sup> อื่นๆ ทั้งหมด แอปพลิเคชัน Publisher ไม่ได้ให้บริการฟรี และเนื่องจากไฟล์ของรูปแบบนี้สามารถเปิดได้โดยโปรแกรมนี้เท่านั้นเพื่อแชร์ผลงานของคุณในบางครั้ง คุณจะต้องแปลงไฟล์ PUB ให้อยู่ในรูปแบบที่แพร่หลายมากขึ้น ที่นิยมมากที่สุดคือการแปลง PUB เป็น PDF ถึงตอนนี้ รูปแบบนี้ได้รับการสนับสนุนโดยอุปกรณ์ที่ทันสมัยทั้งหมด และสามารถเปิดได้ในเบราว์เซอร์โดยไม่ต้องติดตั้งซอฟต์แวร์เพิ่มเติมใดๆ นี่คือฟังก์ชันการแปลง PUB เป็น PDF สำหรับ Java ไลบรารีนี้ยังสามารถใช้สำหรับสร้างโครงการของคุณเอง
p3: ก่อนทำการแปลง คุณต้องรวม Java PUB เข้ากับ PDF Converter API ซึ่งใช้งานได้ไม่เฉพาะกับเอกสารหน้าเดียว แต่ยังรองรับไฟล์ .pub แบบหลายหน้าด้วย
---

{{<section widget>}}
---
title: วิธีแปลง PUB เป็น PDF โดยใช้ Java
item1: "ในการแปลง PUB เป็น PDF เราจะใช้ [Aspose.PUB สำหรับ Java API](https://products.aspose.com/pub/java/) ซึ่งเป็น API การแปลงที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับ แพลตฟอร์มจาวา คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก [Aspose Maven Repository](https://repository.aspose.com/pub/) และติดตั้งภายใน Maven ของคุณ - ตามโครงการโดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml"
---

{{<section feature1>}}
---
title: การแปลง PUB เป็น PDF บน Java
item1: โหลดไฟล์ PUB โดยใช้ [*createParser()*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) วิธีการของ [*PubFactory*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) คลาส
item2: แยกวิเคราะห์ไฟล์โดยใช้ [*parse()*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) วิธีการของ [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) อินเทอร์เฟซ
item3: แปลง PUB เป็น PDF โดยใช้ [*convertToPdf()*](https://reference.aspose.com/pub/java/com.aspose.pub/IPdfConverter#convertToPdf-com.aspose.pub.Document-java.lang.String-) วิธีการของอินเทอร์เฟซ [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPdfConverter)
---

{{<section feature2>}}
---
title: ความต้องการของระบบ
item1: Aspose.PUB สำหรับ Java รองรับระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้
item2: "J2SE 8.0 (1.8) หรือสูงกว่า"
---

{{<section codeexample>}}
---
title: รหัส Java สำหรับการแปลง PUB เป็น PDF
---

{{<section summary>}}
---
p1: การแปลง PUB เป็น PDF เป็นขั้นตอนที่จำเป็นใน PUB เป็นการแปลงรูปแบบอื่น หลังจากนั้น ไฟล์ที่แปลงแล้วสามารถแปลงเป็นรูปแบบที่ต้องการได้
p2: คุณยังสามารถลองใช้แอปพลิเคชันข้ามแพลตฟอร์ม PUB เป็น PDF มันมีอินเทอร์เฟซที่ง่ายมาก และกระบวนการนี้จะใช้เวลาเพียงไม่กี่วินาที
p3: "โซลูชันนี้ช่วยให้คุณ: แปลงไฟล์ Publisher หลายไฟล์ แปลง PUB เป็น PDF และบันทึกเอกสารที่แปลงแล้วบนอุปกรณ์ของคุณ"
---