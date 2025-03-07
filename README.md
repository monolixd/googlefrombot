# 📌 โปรแกรมกรอก Google Form อัตโนมัติ

## 🔍 ภาพรวม
สคริปต์ Python นี้ใช้ Selenium เพื่อกรอกแบบฟอร์ม Google Form อัตโนมัติ โดยจะเข้าถึงฟอร์ม, เลือกคำตอบที่กำหนดไว้ล่วงหน้า และทำการส่งข้อมูลซ้ำตามจำนวนครั้งที่กำหนด

## 🔧 ความต้องการของระบบ
ก่อนใช้งานโปรแกรม ต้องติดตั้งสิ่งต่อไปนี้:

- **Python 3.x**
- **Google Chrome** (แนะนำให้ใช้เวอร์ชันล่าสุด)
- **ChromeDriver** (ต้องตรงกับเวอร์ชันของ Chrome)
- **Selenium** (ไลบรารี Python)

## 📥 วิธีติดตั้ง
ติดตั้ง Selenium โดยใช้คำสั่งนี้:

```bash
pip install selenium
```

จากนั้นดาวน์โหลดและติดตั้ง **ChromeDriver** ให้ตรงกับเวอร์ชันของ Google Chrome ที่ใช้งานอยู่ โดยสามารถดาวน์โหลดได้ที่:

👉 [ChromeDriver Download](https://sites.google.com/chromium.org/driver/)

## 🚀 วิธีใช้งาน
1. แก้ไขสคริปต์ให้ใส่ **URL ของ Google Form** ที่ต้องการใช้งาน
2. ตั้งค่าตัวแปร `num_times` เพื่อกำหนดจำนวนครั้งที่ต้องการกรอกฟอร์ม
3. รันสคริปต์ด้วยคำสั่งนี้:

```bash
python your_script.py
```

## ⚠️ ข้อควรระวัง
- ต้องตรวจสอบว่า **XPath** ของฟิลด์ในฟอร์มตรงกับแบบฟอร์มที่ต้องการใช้งาน
- สคริปต์ใช้ `WebDriverWait` เพื่อให้มั่นใจว่าองค์ประกอบในฟอร์มโหลดเสร็จก่อนคลิก
- หลีกเลี่ยงการส่งข้อมูลซ้ำมากเกินไปเพราะอาจขัดกับนโยบายของ Google

## 🛠 คุณสมบัติเด่น
✅ กรอกแบบฟอร์ม Google Form อัตโนมัติ
✅ รองรับการส่งข้อมูลหลายครั้ง
✅ ใช้ **Explicit Waits** เพื่อให้มั่นใจว่าฟอร์มโหลดเสร็จก่อนคลิก
✅ ปรับแต่งได้ง่าย

## 🔗 แหล่งข้อมูลเพิ่มเติม
- [Selenium Documentation](https://www.selenium.dev/documentation/)
- [Google Forms](https://docs.google.com/forms/)

