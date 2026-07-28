**prompt แปลง csv > json**
*** ไม่มีคน ***
```
สินค้า Desktop desk
ตัวะครชาย
Override  ค่าเหล่านี้ :
> final_image_prompt, final_image_prompt_2 = "none"

> final_video_prompt_part_1 8-10 วินาที
ใช้เทมเพลทหลัก
โดยแก้เฉพาะ motion กับ Audio และเพิ่ม ข้อความ text overlay ชื่อสินค้า สไตล์มินิมอล ตำแหน่งส่วนบนของวิดีโอ ปรากฏตั้งแต่เฟรมแรก
motion = random(Pool_A) + random(Pool_B)

Pool สำหรับ Random
🅐 Pool A — ช่วงแรก:
1) Slow Pan Left→Right + Micro-shake
2) Slow Pan Right→Left + Micro-shake
3) Tilt Up
4) Subtle Truck
5) Tilt Down

🅑 Pool B — ช่วงหลัง :
1) Subtle Zoom Out (Pull Back)
2) Subtle Pedestal Rise
3) Handheld Micro-shake (static with life)
4) Gentle Freeze with Depth Blur

⚠️ Motion อธิบายการเคลื่อนของกล้องเท่านั้น ห้ามอธิบายลักษณะสินค้า
⚠️ เพิ่ม prompt บังคับให้สินค้าสินค้าอยู่ในลักษณะเดิมตลอดเวลา

> final_video_prompt_part_2 8-10 วินาที
เริ่มฉาก (first frame) มือแตะที่ขอบโต๊ะจากทางด้านหนึ่ง กล้องเคลื่อนตามมือที่ลูบขอบโต๊ะไปอีกด้าน ไม่เห็นหน้าคน

Setting ของทั้ง 2 video ห้องมินิมอลโล่งๆ แสงสว่างปานกลาง และไม่ใช่ห้องจากรูปอ้างอิง
```
