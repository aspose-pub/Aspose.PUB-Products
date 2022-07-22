---
translation: true
template: /_templates/conversion-java.md
title: โซลูชัน PUB Converter API | Java
url: /java/conversion/
description: แปลงไฟล์ Microsoft Publisher โดยทางโปรแกรมผ่านไลบรารี Java โซลูชัน API อย่างง่ายเพื่อสร้างโปรเจ็กต์ Java ตัวแปลง PUB ของคุณเอง
metakeywords: ตัวแปลง pub java, แปลงไฟล์ pub java
family: pub
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: แปลงไฟล์ PUB
h2: ฟังก์ชันตัวแปลงผู้เผยแพร่เพื่อสร้างแอปพลิเคชัน Java ข้ามแพลตฟอร์ม
---

{{<section overview>}}
---
p1: รูปแบบไฟล์เอกสาร Microsoft<sup>®</sup> Publisher ใช้สำหรับสร้างสิ่งพิมพ์ประเภทต่างๆ เช่น จดหมายข่าว โบรชัวร์ ใบปลิว และไปรษณียบัตร และใช้ในอีเมลและเว็บไซต์ ไฟล์ Pub มีข้อความรวมถึงข้อมูลบิตแมปและกราฟิกแบบเวกเตอร์
p2: แม้ว่ารูปแบบจะค่อนข้างเป็นที่นิยม แต่ก็ไม่เป็นที่นิยมเท่ารูปแบบเช่น PDF หรือ DOCX แอปพลิเคชัน MS Publisher นั้นไม่ฟรี ดังนั้นจึงจำเป็นต้องแปลงไฟล์ที่มีนามสกุล .pub ไปเป็นรูปแบบอื่นที่มีการกระจายอย่างดีและสะดวกสบายต่อการใช้งาน นี่คือฟังก์ชันการแปลงสำหรับ Java ไลบรารีนี้มีฟังก์ชันการแปลงที่จำเป็นซึ่งสามารถใช้สำหรับการสร้างโครงการของคุณเอง
---

{{<section feature1>}}
---
title: แปลงไฟล์ .pub ของผู้จัดพิมพ์
item1: มาดูการทำงานผ่านการแปลง PUB เป็น PDF
item2: "ขั้นตอนการแปลงของผู้เผยแพร่โฆษณาประกอบด้วยขั้นตอนถัดไป:"
item3: ผสานรวม Java PUB เข้ากับ PDF Converter API ซึ่งใช้งานได้ไม่เฉพาะกับเอกสารหน้าเดียว แต่ยังรองรับไฟล์ .pub แบบหลายหน้า
item4: โหลดไฟล์ PUB โดยใช้คลาส [*PubFactory*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory)
item5: CreateParser และ Parse ผ่าน [*Parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) วิธีการของ [*IPubParser*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) อินเทอร์เฟซ
item6: เรียกใช้การแปลงโดยใช้ [*ConvertToPdf*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPdfConverter#convertToPdf-com.aspose.pub.Document-java.io.OutputStream-) วิธีการ
---

{{<section codeexample>}}
---
title: รหัส Java เพื่อแปลง Publisher PUB เป็น PDF
---

{{<section summary>}}
---
p1: การแปลง PUB เป็นรูปแบบอื่นสามารถทำได้หลังจากแปลงไฟล์เป็นรูปแบบ PDF จากนั้นไฟล์ที่แปลงนี้สามารถแปลงเป็นรูปแบบที่ต้องการได้
p2: "คุณยังสามารถลองใช้แอปพลิเคชันข้ามแพลตฟอร์มของ Publisher Converter มันมีอินเทอร์เฟซที่ง่ายมาก และกระบวนการนี้จะใช้เวลาเพียงไม่กี่วินาที โซลูชันช่วยให้:"
p3: แปลงไฟล์ Publisher หลายไฟล์
p4: แปลง PUB เป็น PDF, HTML, EPUB, DOCX, SVG และรูปแบบรูปภาพอื่น ๆ อีกมากมาย
p5: บันทึกเอกสารที่แปลงแล้วบนอุปกรณ์ของคุณ
---