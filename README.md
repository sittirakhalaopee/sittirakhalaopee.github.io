[README.txt](https://github.com/user-attachments/files/34623153/README.txt)
BOSS SITTIRAK HALAOPEE — PORTFOLIO (BLUE & YELLOW)

เปิดดูเว็บไซต์:
- ดับเบิลคลิก index.html เพื่อเปิดใน Chrome
- เว็บไซต์รองรับมือถือ แท็บเล็ต และคอมพิวเตอร์
- ปุ่ม TH / EN ใช้สลับภาษา
- เว็บแบ่งเป็น 3 หัวข้อหลัก: Video, Graphic, Motion

ข้อมูลที่ใส่ไว้แล้ว:
1) รูปโปรไฟล์ (Hero):
   ใช้ไฟล์ assets/Portfolio - Hero Card.png (1080 x 1350 px พื้นหลังโปร่งใส)
   แสดงแบบ 4:5 ขยายเล็กน้อยเมื่อวางเมาส์ และคลิกเพื่อดูรูปใหญ่ (lightbox)
   ถ้าจะเปลี่ยนรูป ให้วางไฟล์ใหม่ทับชื่อเดิม หรือแก้ src ในส่วน hero-photo

2) รูปผลงาน (Graphic Design):
   ใช้รูปทั้งหมดใน assets/projects/Graphics/ จำนวน 11 รูป
   (เพิ่มใหม่: Chaba Menu_Flyer_Mockup_5.png, Chaba Profile.png, THESIS_SULIN_POSTER.jpg, UNDERCOVER Agent.png)
   แสดงแบบการ์ดสี่เหลี่ยมจัตุรัส (object-fit: contain) จึงไม่ถูกตัดขอบ
   คลิกรูปเพื่อดูขนาดใหญ่ได้ในหน้าเว็บ (lightbox) กด Esc หรือคลิกพื้นหลังเพื่อปิด
   เพิ่ม/ลบผลงานได้ที่แท็ก <article class="project"> ในหัวข้อ Graphic
   ชื่อผลงานแก้ได้ที่ <h3> และคำอธิบายแก้ได้ในตัวแปร copy (g1Meta - g11Meta)

3) วิดีโอ (Video 10 คลิป / Motion 3 คลิป):
   ฝังจาก Vimeo / YouTube ด้วยลิงก์ใน data-video ของแต่ละ .video-frame
   - Video (Vimeo): 1245172670, 1245175135, 1245171486, 947725938, 880364148, 1245198496
   - Video (YouTube): zTdTz5_WSio, gSlkA4mdk4o, MKeO_3NORL4, VOpecCGGPqQ
   - Motion: 1245171483, 605267831, 947725938
   แก้หรือเพิ่มคลิปได้โดยเปลี่ยนค่า data-video เป็นลิงก์ Vimeo หรือ YouTube
   ปุ่มขยายเต็มจออยู่มุมขวาบนของวิดีโอแต่ละคลิป

4) Resume:
   ไฟล์ assets/Boss-Sittirak-Halaopee-Resume.pdf มีอยู่แล้ว
   หากแก้ไข resume ให้บันทึกทับไฟล์เดิม

5) ประวัติการทำงาน:
   มีข้อมูลจริงแล้ว: Champion3, Bangkok University, Lexicon Business Communication และ Achievements
   แก้ข้อความได้ที่แท็ก <div class="experience"> ในหัวข้อ About และในตัวแปร copy (exp1, exp2, exp3, ach)

6) ช่องทางติดต่อ:
   อีเมลปัจจุบัน: Sittirak.h@gmail.com
   มีเฉพาะ Email, Vimeo และ Instagram (ปุ่ม Facebook ถูกนำออกแล้ว)
   ไอคอนโซเชียลเป็น SVG อยู่ใน index.html ไม่ต้องโหลดรูปเพิ่ม

7) ไอคอนโปรแกรม:
   ไฟล์อยู่ใน assets/Program/ ได้แก่ Photoshop, Illustrator, Premiere Pro, After Effects, DaVinci Resolve
   หากต้องการเพิ่มโปรแกรม ให้เพิ่มแท็ก <span class="program"> ในส่วน About Me

9) โหมดมืด (Dark mode):
   ปุ่มไอคอนพระจันทร์/พระอาทิตย์ (ขาวดำ) อยู่แถบด้านบนข้างปุ่มเปลี่ยนภาษา
   โหมดมืดจะเปลี่ยนพื้นหลังทุกส่วนเป็นสีเข้ม รวมถึงการ์ดผลงาน หมวด About และ Contact
   การเลือกจะถูกจดจำไว้ในเครื่อง (localStorage) และจำลองสีให้เบราว์เซอร์ด้วย color-scheme

10) รูป Hero ขยายเมื่อวางเมาส์ (hover) และกดเพื่อซูม:
    รูปโปรไฟล์ในหัวข้อ Hero จะขยายเล็กน้อยเมื่อชี้เมาส์ไปที่รูป และกดที่รูปเพื่อดูขนาดใหญ่ (lightbox) เช่นเดียวกับรูปผลงาน Graphic

11) วิดีโอเต็มจอ:
    ปุ่มขยาย (ไอคอนลูกศรสี่ทิศ) อยู่ท้ายการ์ดทุกคลิปใน Video และ Motion
    กดแล้ววิดีโอขยายเต็มจอ กดปุ่ม × หรือ Esc เพื่อย่อ

แก้ไขเว็บไซต์:
- ใช้ Visual Studio Code (ฟรี): https://code.visualstudio.com/
- เปิดโฟลเดอร์นี้ แล้วแก้ index.html
- บันทึกไฟล์และรีเฟรช Chrome เพื่อดูผล

เผยแพร่ฟรีด้วย GitHub Pages:
1. สมัคร https://github.com/
2. สร้าง Public repository ชื่อ YOUR-USERNAME.github.io
3. อัปโหลด index.html และโฟลเดอร์ assets ทั้งหมด
4. เข้า Settings > Pages
5. เลือก Deploy from a branch > main > /(root) > Save
6. เว็บไซต์จะอยู่ที่ https://YOUR-USERNAME.github.io

หมายเหตุ:
- รูปโปรไฟล์ รูปผลงาน และไอคอนโปรแกรมอยู่ในโฟลเดอร์ assets/ แล้ว
- วิดีโอ 1 คลิป (Vimeo 605267831 — AGASA X1) แสดงผล 401 เพราะการตั้งค่าความเป็นส่วนตัวของ Vimeo
  ให้เข้าไปที่ Vimeo > Video settings > Privacy > Where can this be embedded > เลือก "Anywhere"
- ไฟล์รูปใน assets/projects/Graphics/ มีขนาดใหญ่ (รวมประมาณ 10 MB) ถ้าเว็บโหลดช้าให้ย่อรูปก่อน
- Google Fonts ต้องเชื่อมต่ออินเทอร์เน็ตเพื่อโหลดฟอนต์ Kanit และ Prompt
- คลิป YouTube: ถ้าเปิด index.html โดยดับเบิลคลิก (file://) จะเห็นการ์ดพรีวิวพร้อมข้อความ "เปิดบน YouTube"
  เพราะ YouTube บล็อก embed ที่ไม่มี Referer (Error 153) — ถ้าเปิดผ่าน localhost หรือเว็บจริง วิดีโอจะเล่นในหน้าเว็บได้
- คลิป "ซูหลิน" (zTdTz5_WSio) เจ้าของปิดการอนุญาตฝังไว้ จึงแสดงการ์ดเปิด YouTube ในทุกกรณี
  ถ้าต้องการให้เล่นในหน้าเว็บ ให้เจ้าของไปเปิด Video settings > Allow embedding ที่ YouTube
