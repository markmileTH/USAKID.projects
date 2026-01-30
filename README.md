# USAKID.projects
ESP32 Marauder (Thai Distribution for CYD-2432S028R)

![e35062c6-d2b9-49ba-ba4e-341a112fdb58](https://github.com/user-attachments/assets/55c89c6b-8076-4282-a367-24732b6d97e3)

โปรเจกต์นี้เป็นการเผยแพร่ต่อ (Unofficial Thai Distribution) ของ ESP32 Marauder
โดยปรับรูปแบบเอกสารเป็นภาษาไทย เพื่อให้ง่ายต่อการศึกษา ทดลอง และพัฒนา
ไม่มีการแก้ไขโค้ดต้นฉบับ และยังคงอ้างอิงแหล่งที่มาเดิมอย่างครบถ้วน

⚠️ โปรเจกต์นี้มีไว้เพื่อ การศึกษา การวิจัย และการทดสอบความปลอดภัยของระบบที่ตนเองมีสิทธิ์เท่านั้น
ผู้ใช้งานต้องรับผิดชอบต่อการใช้งานของตนเอง

🔎 เกี่ยวกับ ESP32 Marauder

ESP32 Marauder เป็นเฟิร์มแวร์สำหรับบอร์ด ESP32
ที่ออกแบบมาเพื่อการเรียนรู้และทดสอบด้าน Wireless / IoT Security เช่น

Wi-Fi / BLE Scan

Packet Monitoring

Beacon / Probe Analysis

Wardriving

Bluetooth Low Energy Scan

Evil Portal (บางบอร์ด)

🔗 โปรเจกต์ต้นฉบับ (Official Repository)
https://github.com/justcallmekoko/ESP32Marauder

🔗 Release ต้นฉบับ
https://github.com/justcallmekoko/ESP32Marauder/releases

🧩 Launcher ที่ใช้

โปรเจกต์นี้ใช้ ESP32 Web Launcher ของ
Brian Morcelli (bmorcelli) เพื่อความสะดวกในการแฟลชเฟิร์มแวร์

🔗 Launcher
https://bmorcelli.github.io/Launcher/

Launcher นี้ช่วยให้สามารถแฟลช ESP32 ผ่าน Web Browser (Chrome / Edge)
โดยไม่ต้องติดตั้ง Arduino IDE หรือ ESP-IDF

🧪 บอร์ดที่ใช้ทดสอบ

ทดสอบแล้วกับบอร์ดดังต่อไปนี้:

CYD-2432S028R

หน้าจอ TFT 2.8 นิ้ว (240x320)

ESP32

Dual USB

รองรับ SD Card

📦 ไฟล์ที่ใช้

เฟิร์มแวร์ที่ใช้กับบอร์ดนี้คือ:

esp32_marauder_v1_10_1_beta_20260128_cyd_2432S028_2usb.bin

💾 วิธีการใช้งาน (SD Card Mode)
1. เตรียมอุปกรณ์

บอร์ด CYD-2432S028R

SD Card (FAT32)

สาย USB

คอมพิวเตอร์

2. ใส่ไฟล์ลง SD Card

ฟอร์แมต SD Card เป็น FAT32

คัดลอกไฟล์ต่อไปนี้ลงใน SD Card

esp32_marauder_v1_10_1_beta_20260128_cyd_2432S028_2usb.bin


⚠️ ไม่ต้องเปลี่ยนชื่อไฟล์

3. ใส่ SD Card เข้าบอร์ด

เสียบ SD Card เข้าช่องของบอร์ด CYD-2432S028R

4. แฟลชเฟิร์มแวร์

ใช้ ESP32 Launcher หรือ Bootloader ของบอร์ด (ขึ้นกับรุ่น)

บอร์ดจะอ่านไฟล์จาก SD Card และทำการแฟลช

5. รีสตาร์ทบอร์ด

เมื่อแฟลชเสร็จ บอร์ดจะบูตเข้าสู่ ESP32 Marauder

🖥️ การควบคุม

ใช้ หน้าจอสัมผัส (Touch Screen) ของ CYD

เมนูจะแสดงบนหน้าจอโดยตรง

ไม่จำเป็นต้องใช้ Serial Monitor

📚 แหล่งอ้างอิง

ESP32 Marauder (ต้นฉบับ)
https://github.com/justcallmekoko/ESP32Marauder

ESP32 Marauder Releases
https://github.com/justcallmekoko/ESP32Marauder/releases

ESP32 Web Launcher
https://bmorcelli.github.io/Launcher/

⚠️ ข้อควรระวังและกฎหมาย

ห้ามใช้กับเครือข่ายที่ตนเอง ไม่มีสิทธิ์

มีไว้เพื่อการศึกษาและทดสอบเท่านั้น

ผู้พัฒนาและผู้เผยแพร่ ไม่รับผิดชอบ ต่อการใช้งานที่ผิดกฎหมาย

🤝 เครดิต

@justcallmekoko — ผู้พัฒนา ESP32 Marauder

@bmorcelli — ผู้พัฒนา ESP32 Web Launcher

ผู้จัดทำ README ภาษาไทย — เพื่อการศึกษาและเผยแพร่ความรู้
