เขียน prompt video 2 prompt สำหรับ 2 วิดีโอ สำหรับสินค้าที่เปิดอยู่ในแท็บนี้.
- ฉากถ่ายในห้องนอนมินิมอล โล่งๆ ไม่มีของตกแต่ง
- เพศตัวละคร ให้ถามผู้ใช้ก่อน
- ภาษา: 
> shopee.co.th > ภาษาไทย
---
> shopee.com.my > ภาษา Malay+English ตามสไตล์คนมาเลย์ ห้ามใช้คำที่คนอินโดนีเซียใช้
- template video
```
[Virtual] ...
[Constraints] Strictly maintain the exact design, color, and details of the product identical to the reference image without any modifications. No subtitles, text overlay. No additional logos, labels.
[Audio] {เสียงพากย์ ผู้หญิง/ผู้ชาย ภาษา… :"...."}
```
>> - คำบังคับใน prompt "Based on reference images"
>> - ต้องระบุขนาดสินค้า(ถ้ามี)
>> - เสียงพากย์ 20-25 คำต่อ 1 วิด๊โอ
---
**[Virtual] วิดีโอแรก:**
เริ่มเฟรมแรก - 3 วินาที มีผู้หญิงยืนข้างๆสินค้า , based on reference images
หลังจากนั้นกล้องถ่ายไปยังสินค้าโดยใช้เทคนิค Macro+quick cuts เปลี่ยนมุมกล้องหรือคัทอย่างน้อย 3 ครั้ง
อนุญาติให้มือลูปสัมผัสสินค้าเท่านั้น ห้ามทำอย่างอื่นกับสินค้า


**[Virtual] วิดีโอที่2**
วิดีโอถ่ายสินค้า , based on reference images ไม่มีคนในซีน ให้สุมการเคลื่อนกล้องจาก 
random(Pool_A) + random(Pool_B)

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

> ทั้งสอง prompt อธิบายการเคลื่อนของกล้องเท่านั้น ห้ามอธิบายลักษณะสินค้า
---
> ตอบใน code block แยกกัน
