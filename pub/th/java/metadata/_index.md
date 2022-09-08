---
translation: true
template: /_templates/metadata-java.md
title: แก้ไขผู้เผยแพร่ | ข้อมูลเมตาของ PUB | Java
description: อ่านข้อมูลเมตาไฟล์ของผู้เผยแพร่โดยใช้โซลูชัน PUB Java API ข้ามแพลตฟอร์ม Java API ภายในองค์กรช่วยให้คุณเข้าถึงคุณสมบัติ SummaryInfo และ DocSummaryInfo
url: /java/metadata/pub/
metakeywords: แก้ไข pub metadata java, pub file metadata java, java ตัวแก้ไขข้อมูลเมตาของผู้เผยแพร่, อ่านไฟล์ pub metadata java, อ่าน pub metadata java
family: pub
platformtag: java
feature: metadata
aliases: /java/ข้อมูลเมตา/
---

{{<section banner>}}
---
h1: แก้ไขข้อมูลเมตาของ PUB
h2: อ่านไฟล์ MS Publisher API ตัวแก้ไข PUB Metatada สำหรับ Java
---

{{<section overview>}}
---
p1: รูปแบบไฟล์เอกสาร Microsoft<sup>®</sup> Publisher ใช้สำหรับสร้างสิ่งพิมพ์ประเภทต่างๆ เช่น จดหมายข่าว โบรชัวร์ ใบปลิว และไปรษณียบัตร และใช้ในอีเมลและเว็บไซต์ ไฟล์ Pub มีข้อความรวมถึงข้อมูลบิตแมปและกราฟิกแบบเวกเตอร์
p2: ข้อมูลเมตาของผู้จัดพิมพ์คือคุณสมบัติ (ข้อมูล) ที่อธิบายเอกสาร PUB เป็นคุณสมบัติมาตรฐาน เช่น ผู้เผยแพร่ ชื่อ ผู้เขียนคนสุดท้าย องค์กร URL ภาษา และข้อมูลอื่นๆ ที่คล้ายคลึงกัน นอกจากนี้ยังมีข้อมูลที่สร้างขึ้นโดยอัตโนมัติหลังจากทำงานกับไฟล์ เช่น ขนาดหรือเวลาแก้ไขล่าสุด ข้อมูลที่เป็นประโยชน์นี้ถูกเก็บไว้พร้อมกับเอกสาร
p3: นอกจากฟังก์ชันการแปลงและการอ่านแล้ว โซลูชัน PUB API สำหรับ Java นี้ยังช่วยให้คุณแก้ไขข้อมูลเมตามาตรฐานโดยใช้คลาส DocSummaryInfo และ SummaryInfo ตามที่แสดงในตัวอย่างโค้ดต่อไปนี้ คุณยังสามารถใช้ API เพื่อสร้างแอปพลิเคชัน Metadata Editor ของคุณเองได้
p4: ก่อนการเข้ารหัส Metadata คุณต้องผสานรวม Java PUB Metadata API ตัวอย่างต่อไปนี้จะแสดงวิธีการแก้ไขคุณสมบัติ "ภาษา"
---

{{<section widget>}}
---
title: วิธีแก้ไขข้อมูลเมตา PUB โดยใช้ Java
item1: "ในการแก้ไขข้อมูลเมตาของ PUB เราจะใช้ [Aspose.PUB for Java API](https://products.aspose.com/pub/java/) ซึ่งเป็นการแปลงที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย API สำหรับแพลตฟอร์ม Java คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก [Aspose Maven Repository](https://repository.aspose.com/pub/) และติดตั้งภายใน Maven ของคุณ - ตามโครงการโดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml"
---

{{<section feature1>}}
---
title: ดูและแก้ไขข้อมูลเมตาของ PUB บน Java
item1: "กระบวนการอ่านข้อมูลเมตาของผู้จัดพิมพ์ประกอบด้วยขั้นตอนถัดไป:"
item2: อัปโหลดไฟล์ PUB ของคุณโดยใช้ [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) วิธีการของ [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) คลาส
item3: แยกวิเคราะห์ไฟล์ผ่าน [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) วิธีการของ [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) อินเทอร์เฟซ
item4: แก้ไขข้อมูลเมตา เช่น ภาษาโดยใช้ [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) วิธีการของ [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) คลาส
---

{{<section feature2>}}
---
title: ความต้องการของระบบ
item1: Aspose.PUB สำหรับ Java รองรับระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้
item2: J2SE 8.0 (1.8) หรือสูงกว่า
---

{{<section codeexample>}}
---
title: รหัส Java เพื่ออัปเดตข้อมูลเมตา PUB
---