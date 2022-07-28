---
translation: true
template: /_templates/conversion-net.md
title: โซลูชัน PUB Converter API | .NET
url: /net/conversion/
description: แปลงไฟล์ Microsoft Publisher โดยทางโปรแกรมผ่านไลบรารี C# โซลูชัน API อย่างง่ายเพื่อสร้างโปรเจ็กต์ .NET ตัวแปลง PUB ของคุณเอง
metakeywords: 'ตัวแปลง pub net, แปลงไฟล์ pub net, ตัวแปลง pub c#, แปลงไฟล์ pub c #'
family: pub
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: แปลงไฟล์ PUB
h2: ฟังก์ชันตัวแปลงของ Microsoft<sup>®</sup> Publisher เพื่อสร้างแอปพลิเคชัน .NET ข้ามแพลตฟอร์ม
---

{{<section overview>}}
---
p1: รูปแบบไฟล์เอกสาร Microsoft<sup>®</sup> Publisher ใช้สำหรับสร้างสิ่งพิมพ์ประเภทต่างๆ เช่น จดหมายข่าว โบรชัวร์ ใบปลิว และไปรษณียบัตร และใช้ในอีเมลและเว็บไซต์ ไฟล์ Pub มีข้อความรวมถึงข้อมูลบิตแมปและกราฟิกแบบเวกเตอร์
p2: แม้ว่ารูปแบบจะค่อนข้างเป็นที่นิยม แต่ก็ไม่เป็นที่นิยมเท่ารูปแบบเช่น PDF หรือ DOCX แอปพลิเคชัน MS Publisher นั้นไม่ฟรี ดังนั้นจึงจำเป็นต้องแปลงไฟล์ที่มีนามสกุล .pub ไปเป็นรูปแบบอื่นที่มีการกระจายอย่างดีและสะดวกสบายต่อการใช้งาน นี่คือฟังก์ชันการแปลงสำหรับ .NET ไลบรารี C# นี้มีฟังก์ชันการแปลงที่จำเป็นซึ่งสามารถใช้สำหรับการสร้างโครงการของคุณเอง
---

{{<section feature1>}}
---
title: แปลงไฟล์ .pub ของผู้จัดพิมพ์
item1: มาดูการทำงานผ่านการแปลง PUB เป็น PDF
item2: "ขั้นตอนการแปลงของผู้เผยแพร่โฆษณาประกอบด้วยขั้นตอนถัดไป:"
item3: ผสานรวม .NET PUB เข้ากับ PDF Converter API ซึ่งใช้งานได้ไม่เฉพาะกับเอกสารหน้าเดียว แต่ยังรองรับไฟล์ .pub แบบหลายหน้าอีกด้วย
item4: โหลดไฟล์ PUB โดยใช้คลาส [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//)
item5: CreateParser และ Parse ผ่าน [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//parse/) วิธีการของ [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//) อินเทอร์เฟซ
item6: เรียกใช้การแปลงโดยใช้วิธีการ [*ConvertToPdf*()](https://reference.aspose.com/pub/net/aspose.pub/ipdfconverter//converttopdf/)
---

{{<section codeexample>}}
---
title: รหัส C# สำหรับการแปลง PUB เป็น PDF ของผู้จัดพิมพ์
---

{{<section summary>}}
---
p1: การแปลง PUB เป็นรูปแบบอื่นสามารถทำได้หลังจากแปลงไฟล์เป็นรูปแบบ PDF จากนั้นไฟล์ที่แปลงนี้สามารถแปลงเป็นรูปแบบที่ต้องการได้
p2: "คุณยังสามารถลองใช้แอปพลิเคชันข้ามแพลตฟอร์มของ Publisher Converter มันมีอินเทอร์เฟซที่ง่ายมาก และกระบวนการนี้จะใช้เวลาเพียงไม่กี่วินาที โซลูชันช่วยให้:"
p3: แปลงไฟล์ Publisher หลายไฟล์
p4: แปลง PUB เป็น PDF, HTML, EPUB, DOCX, SVG และรูปแบบรูปภาพอื่น ๆ อีกมากมาย
p5: บันทึกเอกสารที่แปลงแล้วบนอุปกรณ์ของคุณ
---
