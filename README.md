# PokinFlappy_Bird

เกมนี้เป็นเกมอาร์เคดกดปุ่มเดียว (One-button arcade game) ที่ได้แรงบันดาลใจจาก **Flappy Bird**  
ผู้เล่นจะบังคับนกให้กระพือปีกขึ้น เพื่อหลบสิ่งกีดขวาง (ท่อ)  
เป้าหมายคือบินให้นานที่สุดและทำคะแนนสูงสุด
---
## วิธีเปิดโปรเจกต์
1. ดาวน์โหลดหรือ clone repository นี้
2. เปิดใน **Unity (เวอร์ชัน LTS ล่าสุด)**
3. รอ Unity import asset และ package จนเสร็จ
4. เปิดฉากหลัก `MainScene.unity` (อยู่ใน **Assets/Scenes**)
5. กดปุ่ม **Play** หรือทำการ Build ตามขั้นตอนด้านล่าง
---
## วิธี Build
1. ไปที่เมนู **File > Build Settings**
2. เลือก Platform: **Windows (PC, Mac & Linux Standalone)** → Target: Windows
3. กด **Build** และเลือกโฟลเดอร์ปลายทาง (เช่น `Build/`)
4. รันไฟล์ `.exe` ที่ได้ในโฟลเดอร์นั้น
---
## วิธีเล่น
- **การควบคุม:** คลิกเมาส์ซ้าย  
- **การกระทำ:** ทุกครั้งที่คลิก นกจะกระพือปีกขึ้นเล็กน้อย  
- **เป้าหมาย:** ห้ามชนท่อหรือหลุดออกนอกหน้าจอ  
- **การนับคะแนน:** ผ่านช่องท่อ 1 คู่ = +1 คะแนน  
- **Game Over:** เมื่อนกชนท่อหรือตก/บินออกนอกจอ  
- **เริ่มใหม่:** หลัง Game Over กดปุ่ม Restart เพื่อเล่นอีกครั้ง  
---
## ฟีเจอร์ที่มี
- เมนูหลัก (Start / High Score)  
- UI แสดงคะแนนระหว่างเล่น  
- หน้าจอ Game Over แสดง คะแนนล่าสุด / High Score / ปุ่ม Restart  
- Asset ที่ใช้:  
  - UI: Pastel Dream Pack (ToffeeCraft)  
  - Sound: Retro Sounds 32-Bit (BrainzPlayz)  
