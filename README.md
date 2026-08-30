# ihavecpu-ai-extension-version

ประกาศเวอร์ชันล่าสุดของ Chrome extension **Zaapi AI Reply Assistant** (iHaveCPU × Cipher)

Extension จะเช็ค `version.json` ที่นี่อัตโนมัติ ถ้ามีเวอร์ชันใหม่กว่าที่ติดตั้งอยู่ จะขึ้นแบนเนอร์เตือนใน panel
ให้แอดมินติดต่อทีมงานเพื่อรับไฟล์อัปเดต (แจกแบบ manual) แล้วรีเฟรชที่ `chrome://extensions`

repo นี้เก็บ **เฉพาะ `version.json`** — ไม่มีโค้ด/ไฟล์ extension (ตัวไฟล์แจกแยกทาง manual)

## ออกเวอร์ชันใหม่ (dev)
แก้ `latest` + `notes` ใน `version.json` แล้ว commit + push → แอดมินเห็นแบนเนอร์เตือนภายในไม่กี่นาที
