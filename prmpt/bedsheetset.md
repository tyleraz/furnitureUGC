**ชุดผ้าปู สินค้าปรากฏทีละชิ้น ไม่มีคน***
```
[core] 10-second stop motion video, raw authentic unpolished UGC moment, iPhone handheld style. Middle-class Thai home bedroom, natural clutter, natural ambient lighting. 
[virtual] Starts with fitted sheet. Pillows, duvet, and blanket appear sequentially at 0.3-second intervals. Static camera transitions to handheld pan after all items appear. Bedding matches reference image. NO hands, fingers, or arms.
[audio] {Male Malay/English voice-over: "Set lengkap dengan comforter, fitted sheet, pillowcase dan bolster case, sesuai Queen atau King. Pilih corak favourite anda dan tekan beli sekarang sebelum stok habis!"}.

```
**ชุดคำสั่งที่ต้องให้ ai ประมวลก่อนนำไปใช้***
```
Template หลัก
[Core + Start] A candid vertical UGC video of '[product]', [size](ถ้ามี), starting from the reference image.
[Motion] {การเคลื่อนไหวของกล้อง}
[Camera/Tech] 9:16, 30fps. iPhone 16 Pro Max camera quality, subtle grain, and rolling shutter effect. 
[Lighting/Focus] Practical window/room lighting, documentary-style feel. Occasional brief soft focus. 
[Constraints] Focus strictly on the object; NO logos, lables, or subtitles.
[Audio]  เสียงพูด[gender][ภาษา] 'Voice over script/vo_script part 1 หรือ part 2'

motion ของ "final_video_prompt_part_1" = random(Pool_A) + random(Pool_B)"
motion ของ "final_video_prompt_part_2" = "Fast-paced sequence with quick cuts between different camera angles of the character and the item. "

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
⚠️ prompt บังคับให้ฉากเป็นบ้านมินิมอล แสงสว่างปานกลาง และไม่ใช่ห้องจากรูปอ้างอิง
⚠️ เพิ่ม prompt บังคับให้สินค้าสินค้าอยู่ในลักษณะเดิมตลอดเวลา
```
