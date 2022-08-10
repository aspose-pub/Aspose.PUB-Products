---
translation: true
template: /_templates/metadata-cpp.md
title: แก้ไขผู้เผยแพร่ | ข้อมูลเมตาของ PUB | C++
description: อ่านข้อมูลเมตาของไฟล์ผู้เผยแพร่โดยใช้โซลูชัน PUB C++ API C++ API ภายในองค์กรช่วยให้คุณเข้าถึงคุณสมบัติ SummaryInfo และ DocSummaryInfo
url: /cpp/metadata/pub/
metakeywords: แก้ไขข้อมูลเมตาของ pub, ข้อมูลเมตาของไฟล์ pub, ตัวแก้ไขข้อมูลเมตาของผู้เผยแพร่, อ่านข้อมูลเมตาของไฟล์ pub, อ่านข้อมูลเมตาของ pub
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/ข้อมูลเมตา/
---

{{<section banner>}}
---
h1: แก้ไขข้อมูลเมตาของ PUB
h2: อ่านไฟล์ MS Publisher API ตัวแก้ไข PUB Metatada สำหรับ C++
---

{{<section overview>}}
---
p1: รูปแบบไฟล์เอกสาร Microsoft<sup>®</sup> Publisher ใช้สำหรับสร้างสิ่งพิมพ์ประเภทต่างๆ เช่น จดหมายข่าว โบรชัวร์ ใบปลิว และไปรษณียบัตร และใช้ในอีเมลและเว็บไซต์ ไฟล์ Pub มีข้อความรวมถึงข้อมูลบิตแมปและกราฟิกแบบเวกเตอร์
p2: ข้อมูลเมตาของผู้จัดพิมพ์คือคุณสมบัติ (ข้อมูล) ที่อธิบายเอกสาร PUB เป็นคุณสมบัติมาตรฐาน เช่น ผู้เผยแพร่ ชื่อ ผู้เขียนคนสุดท้าย องค์กร URL ภาษา และข้อมูลอื่นๆ ที่คล้ายคลึงกัน นอกจากนี้ยังมีข้อมูลที่สร้างขึ้นโดยอัตโนมัติหลังจากทำงานกับไฟล์ เช่น ขนาดหรือเวลาแก้ไขล่าสุด ข้อมูลที่เป็นประโยชน์นี้ถูกเก็บไว้พร้อมกับเอกสาร
p3: นอกจากฟังก์ชันการแปลงและการอ่านแล้ว โซลูชัน PUB API สำหรับ C++ ยังช่วยให้คุณแก้ไขข้อมูลเมตามาตรฐานโดยใช้คลาส DocSummaryInfo และ SummaryInfo ตามที่แสดงในตัวอย่างโค้ดต่อไปนี้ คุณยังสามารถใช้ API เพื่อสร้างแอปพลิเคชัน Metadata Editor ของคุณเองได้
p4: ก่อนเขียนโค้ด Metadata คุณต้องผสานรวม C++ PUB Metadata API ตัวอย่างต่อไปนี้จะแสดงวิธีการแก้ไขคุณสมบัติ "หมวดหมู่"
---

{{<section feature1>}}
---
title: ดูและแก้ไขข้อมูลเมตาของ PUB บน C++
item1: "กระบวนการอ่านข้อมูลเมตาของผู้จัดพิมพ์ประกอบด้วยขั้นตอนถัดไป:"
item2: อัปโหลดไฟล์ PUB โดยใช้ [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) วิธีการของ [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) คลาส
item3: แยกวิเคราะห์ไฟล์ผ่าน [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) วิธีการของ [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) อินเทอร์เฟซ
item4: แก้ไขข้อมูลเมตา เช่น หมวดหมู่ โดยใช้ [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) วิธีการของ [*DocSummary:Info*] /apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) คลาส
---

{{<section feature2>}}
---
title: เริ่มต้นกับ CPP PUB API
item1: ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.PUB.cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.PUB.cpp```
item2: หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/pub/cpp/)
---

{{<section codeexample>}}
---
title: รหัส C ++ เพื่อแก้ไขข้อมูลเมตาของ PUB
---
