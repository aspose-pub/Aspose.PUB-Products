---
translation: true
template: /_templates/reader-net.md
title: อ่านไฟล์ PUB | .NET
description: เปิดไฟล์ Publisher โดยทางโปรแกรม โซลูชัน C# .NET API เพื่ออ่านคุณสมบัติ PUB ใช้เพื่อรวมเข้ากับโครงการของคุณ
url: /net/read-pub-file/
metakeywords: เปิดไฟล์ pub .net, ดูไฟล์ผู้เผยแพร่ c#, อ่านไฟล์ผู้เผยแพร่, โปรแกรมดูผู้เผยแพร่สำหรับ c# โปรแกรมอ่านรูปแบบผับ, ตัวเปิดไฟล์ pub
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: ที่เปิดไฟล์ PUB
h2: อ่านไฟล์ PUB เปิด Publisher ด้วย API สำหรับ .NET
---

{{<section overview>}}
---
p1: รูปแบบไฟล์เอกสาร Microsoft<sup>®</sup> Publisher ใช้สำหรับสร้างสิ่งพิมพ์ประเภทต่างๆ เช่น จดหมายข่าว โบรชัวร์ ใบปลิว และไปรษณียบัตร และใช้ในอีเมลและเว็บไซต์ ไฟล์ Pub ประกอบด้วยข้อความ ตาราง ตลอดจนข้อมูลบิตแมปและกราฟิกแบบเวกเตอร์
p2: แม้ว่ารูปแบบจะค่อนข้างเป็นที่นิยม แต่ก็ไม่เป็นที่นิยมเท่ารูปแบบเช่น PDF หรือ DOCX แอปพลิเคชัน MS Publisher นั้นไม่ฟรี
p3: ดังนั้นบางครั้งจำเป็นต้องเปิดไฟล์ PUB โดยไม่มีโปรแกรมนี้ สิ่งนี้จำเป็นเมื่อคุณต้องการแสดงเนื้อหาของเอกสาร โดยไม่ต้องแก้ไขหรือจัดการด้วยวิธีอื่น เช่น เมื่อคุณมีงานนำเสนอหรือรีวิว เพื่อวัตถุประสงค์ดังกล่าว คุณอาจใช้แอปพลิเคชัน PUB Viewer ข้ามแพลตฟอร์ม
p4: ที่นี่ คุณจะได้รับโซลูชัน .NET API ที่ให้คุณดูคุณสมบัติของเอกสาร MS Publisher เช่น ขนาด ความกว้าง ความสูง ชื่อของแบบอักษรที่ใช้ จำนวนฟิลด์ และสี
---

{{<section feature1>}}
---
title: อ่านไฟล์ผู้จัดพิมพ์บน .NET
item1: "หากต้องการดูคุณสมบัติของไฟล์ .pub คุณจะต้องทำตามขั้นตอนต่อไปนี้:"
item2: ผสานรวม .NET PUB API ซึ่งใช้งานได้ไม่เฉพาะกับเอกสารหน้าเดียว แต่ยังรองรับไฟล์ .pub แบบหลายหน้าอีกด้วย
item3: อัปโหลดไฟล์ PUB โดยใช้ [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) Method ของ [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) คลาส
item4: แยกวิเคราะห์เอกสารผ่าน [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse) Method ของ [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) อินเทอร์เฟซ
item5: พิมพ์เอกสาร [*properties*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties)
---

{{<section feature2>}}
---
title: เริ่มต้นใช้งาน .NET PUB API
item1: "มีสองวิธีในการติดตั้งผลิตภัณฑ์:"
item2: ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.PUB``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.PUB```
item3: หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/pub/net/)
---

{{<section codeexample>}}
---
title: .NET รหัสเพื่ออ่านคุณสมบัติไฟล์ PUB
---

{{<section summary>}}
---
item1: หากต้องการดูตัวอย่างโค้ดแบบเต็มของ ReadPubDocument.cs ให้ไปที่โซลูชัน Aspose.PUB.Examples.sln ในตัวอย่างสุทธิของเอกสารประกอบ Aspose.PUB ซึ่งคุณสามารถหาตัวอย่างอื่นๆ เกี่ยวกับวิธีการใช้ไลบรารีได้
---