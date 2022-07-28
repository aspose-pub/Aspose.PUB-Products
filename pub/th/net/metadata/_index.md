---
translation: true
template: /_templates/metadata-net.md
title: แก้ไขผู้เผยแพร่ | ข้อมูลเมตาของ PUB | .NET
description: อ่านข้อมูลเมตาไฟล์ของผู้เผยแพร่โดยใช้โซลูชัน PUB .NET API ข้ามแพลตฟอร์ม .NET API ภายในองค์กรช่วยให้คุณเข้าถึงคุณสมบัติ SummaryInfo และ DocSummaryInfo
url: /net/metadata/pub/
metakeywords: แก้ไข pub metadata net, ข้อมูลเมตาของไฟล์ pub C#, ตัวแก้ไขข้อมูลเมตาของผู้เผยแพร่ .net, อ่านข้อมูลเมตาของไฟล์ pub C#, อ่านข้อมูลเมตาของ pub .net
family: pub
platformtag: net
feature: metadata
aliases: /net/ข้อมูลเมตา/
---

{{<section banner>}}
---
h1: แก้ไขข้อมูลเมตาของ PUB
h2: อ่านไฟล์ MS Publisher API ตัวแก้ไข PUB Metatada สำหรับ .NET
---

{{<section overview>}}
---
p1: รูปแบบไฟล์เอกสาร Microsoft<sup>®</sup> Publisher ใช้สำหรับสร้างสิ่งพิมพ์ประเภทต่างๆ เช่น จดหมายข่าว โบรชัวร์ ใบปลิว และไปรษณียบัตร และใช้ในอีเมลและเว็บไซต์ ไฟล์ Pub มีข้อความรวมถึงข้อมูลบิตแมปและกราฟิกแบบเวกเตอร์
p2: ข้อมูลเมตาของผู้จัดพิมพ์คือคุณสมบัติ (ข้อมูล) ที่อธิบายเอกสาร PUB เป็นคุณสมบัติมาตรฐาน เช่น ผู้เผยแพร่ ชื่อ ผู้เขียนคนสุดท้าย องค์กร URL ภาษา และข้อมูลอื่นๆ ที่คล้ายคลึงกัน นอกจากนี้ยังมีข้อมูลที่สร้างขึ้นโดยอัตโนมัติหลังจากทำงานกับไฟล์ เช่น ขนาดหรือเวลาแก้ไขล่าสุด ข้อมูลที่เป็นประโยชน์นี้ถูกเก็บไว้พร้อมกับเอกสาร
p3: นอกจากฟังก์ชันการแปลงและการอ่านแล้ว โซลูชัน PUB API สำหรับ .NET นี้ยังให้คุณแก้ไขข้อมูลเมตามาตรฐานโดยใช้คลาส DocSummaryInfo และ SummaryInfo ตามที่แสดงในตัวอย่างโค้ดต่อไปนี้ คุณยังสามารถใช้ API เพื่อสร้างแอปพลิเคชัน Metadata Editor ของคุณเองได้
p4: ก่อนเขียนโค้ด Metadata คุณต้องผสานรวม C# .NET PUB Metadata API ตัวอย่างต่อไปนี้จะแสดงวิธีการแก้ไขคุณสมบัติ "บริษัท"
---

{{<section feature1>}}
---
title: แก้ไขข้อมูลเมตาของไฟล์ PUB บน .NET
item1: "กระบวนการอ่านข้อมูลเมตาของผู้จัดพิมพ์ประกอบด้วยขั้นตอนถัดไป:"
item2: อัปโหลดไฟล์ PUB โดยใช้ [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Method ของ [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) คลาส
item3: แยกวิเคราะห์เอกสารผ่าน [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Method ของ [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) อินเทอร์เฟซ
item4: แก้ไขข้อมูลเมตา เช่น บริษัท โดยใช้ [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Method of [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) คลาส
---

{{<section feature2>}}
---
title: เริ่มต้นใช้งาน .NET PUB API
item1: ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.PUB``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.PUB```
item2: หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/pub/net/)
---

{{<section codeexample>}}
---
title: .NET Code เพื่อแก้ไขข้อมูลเมตาของ PUB
---