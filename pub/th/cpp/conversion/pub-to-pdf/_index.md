---
translation: true
template: /_templates/conversion-child.md
title: แปลง PUB เป็น PDF | C++
description: แปลง PUB เป็น PDF โดยใช้ C++ API บน Windows, Linux และ Mac OS X ฟังก์ชันการแปลง Publisher ที่รวมเข้ากับโซลูชันของคุณเองได้ง่าย
url: /cpp/conversion/pub-to-pdf/
metakeywords: pub เป็น pdf c++, แปลง pub เป็น pdf cpp, c++ pub เป็น pdf, ผู้จัดพิมพ์เป็น pdf c++
family: pub
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: แปลง PUB เป็น PDF
h2: สำนักพิมพ์เป็น PDF ตัวแปลง ฟังก์ชันการแปลง С++ API
---

{{<section overview>}}
---
p1: รูปแบบไฟล์เอกสาร Microsoft<sup>®</sup> Publisher ใช้สำหรับสร้างสิ่งพิมพ์ประเภทต่างๆ เช่น จดหมายข่าว โบรชัวร์ ใบปลิว และไปรษณียบัตร และใช้ในอีเมลและเว็บไซต์ ไฟล์ Pub มีข้อความรวมถึงข้อมูลบิตแมปและกราฟิกแบบเวกเตอร์
p2: เนื่องจากผลิตภัณฑ์ Microsoft<sup>®</sup> อื่นๆ ทั้งหมด แอปพลิเคชัน Publisher ไม่ได้ให้บริการฟรี และเนื่องจากไฟล์ในรูปแบบนี้สามารถเปิดได้โดยโปรแกรมนี้เท่านั้นเพื่อแชร์ผลงานของคุณในบางครั้ง คุณจะต้องแปลงไฟล์ PUB ให้อยู่ในรูปแบบที่แพร่หลายมากขึ้น ที่นิยมมากที่สุดคือการแปลง PUB เป็น PDF ถึงตอนนี้ รูปแบบนี้ได้รับการสนับสนุนโดยอุปกรณ์ที่ทันสมัยทั้งหมด และสามารถเปิดได้ในเบราว์เซอร์โดยไม่ต้องติดตั้งซอฟต์แวร์เพิ่มเติมใดๆ นี่คือฟังก์ชันการแปลง PUB เป็น PDF สำหรับ C++ ไลบรารีนี้ยังสามารถใช้สำหรับสร้างโครงการของคุณเอง
p3: ก่อนทำการแปลง คุณต้องรวม C++ PUB เข้ากับ PDF Converter API ซึ่งใช้งานได้ไม่เฉพาะกับเอกสารหน้าเดียว แต่ยังรองรับไฟล์ .pub แบบหลายหน้าด้วย
---

{{<section feature1>}}
---
title: การแปลง PUB เป็น PDF บน C++
item1: โหลดไฟล์ PUB โดยใช้ [*CreateParser()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) วิธีการของ [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) คลาส
item2: แยกวิเคราะห์ไฟล์โดยใช้ [*Parse()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) วิธีการของ [*IPubParser*](https://apireference.aspose) .com/pub/cpp/class/aspose.pub.i_pub_parser) อินเทอร์เฟซ
item3: เรียกใช้การแปลงโดยใช้ [*ConvertToPdf()*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter#acdea381bc8f2a2799e73a039b09ecdb5) วิธีการของ [*IPdfConverter*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter) อินเทอร์เฟซ
---

{{<section feature2>}}
---
title: เริ่มต้นใช้งาน C++ PUB API
item1: ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.PUB.cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.PUB.cpp```
item2: หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/pub/cpp)
---

{{<section codeexample>}}
---
title: รหัส C++ สำหรับการแปลง PUB เป็น PDF
---

{{<section summary>}}
---
p1: การแปลง PUB เป็น PDF เป็นขั้นตอนที่จำเป็นใน PUB เป็นการแปลงรูปแบบอื่น หลังจากนั้น ไฟล์ที่แปลงแล้วสามารถแปลงเป็นรูปแบบที่ต้องการได้
p2: คุณยังสามารถลองใช้แอปพลิเคชันข้ามแพลตฟอร์ม PUB เป็น PDF มีอินเทอร์เฟซที่เรียบง่ายและกระบวนการนี้ใช้เวลาเพียงไม่กี่วินาที
p3: "โซลูชันนี้ช่วยให้คุณ: แปลงไฟล์ Publisher หลายไฟล์ แปลง PUB เป็น PDF และบันทึกเอกสารที่แปลงแล้วบนอุปกรณ์ของคุณ"
---