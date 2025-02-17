> [!NOTE]
> ข้อมูลทังหมดแปลจาก [Bruce](https://github.com/pr3y/Bruce) นะครับ🐹

![image](https://github.com/pr3y/Bruce/blob/main/media/pictures/bruce_banner.jpg)

# 🦈Bruce
Bruce ตั้งใจให้เป็นเฟิร์มแวร์ ESP32 อเนกประสงค์ที่รองรับฟีเจอร์ที่น่ารังเกียจมากมายที่เน้นไปที่การอำนวยความสะดวกในการปฏิบัติงานของทีม Red นอกจากนี้ยังรองรับผลิตภัณฑ์ m5stack และใช้งานได้ดีกับ Cardputer, Sticks, M5Cores, T-Decks และ T-Embeds

# 🏗️ วิธีการติดตั้ง
### วิธีที่ง่ายที่สุดในการติดตั้ง Bruce คือการใช้ Web Flasher อย่างเป็นทางการของ Bruce!
### เว็บ: [Bruce-flasher](https://bruce.computer/flasher)
หรือคุณสามารถดาวน์โหลดไบนารีล่าสุดจากรุ่นหรือการดำเนินการและแฟลชในเครื่องโดยใช้ esptool.py
```
esptool.py --port /dev/ttyACM0 write_flash 0x00000 Bruce-<device>.bin
```
**สำหรับอุปกรณ์ m5stack**
หากคุณใช้ M5Launcher บน m5stack อยู่แล้ว คุณสามารถติดตั้งด้วย OTA ได้ 
หรือคุณสามารถเบิร์นมันได้โดยตรงจากเครื่องมือ m5burner เพียงค้นหา 'Bruce' (งานสร้างอย่างเป็นทางการของฉันจะถูกอัปโหลดโดย "เจ้าของ" และมีรูปถ่าย) ในหมวดหมู่อุปกรณ์ที่คุณต้องการและคลิกที่เบิร์น
