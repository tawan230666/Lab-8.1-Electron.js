# 🚀 My First Electron App (ภาษาไทย + Emoji Supported)

โปรเจกต์นี้เป็นการทดลองสร้าง **Electron Desktop App** แบบพื้นฐาน  
โดยใช้เทคโนโลยี **HTML + CSS + JavaScript**  
และได้ทำการ **แก้ไขปัญหาการแสดงผลภาษาไทยและ Emoji**  
ให้สามารถใช้งานได้อย่างถูกต้องในระบบ Linux / WSL / VM ต่าง ๆ

---

## 👨‍💻 ผู้จัดทำ

- **ธาวัน ทิพคุณ (Tawan Tippkhun) รหัสนักศึกษา 67543210033-6**  
  สาขาวิศวกรรมซอฟต์แวร์ มทร.ล้านนา  
  GitHub: [@tawan230666](https://github.com/tawan230666)

---

## 🧩 ปัญหาเดิม (Before Fix)

ก่อนแก้ไขโปรแกรม **ไม่สามารถแสดงภาษาไทยและอีโมจิได้ถูกต้อง**  
ข้อความกลายเป็นสี่เหลี่ยม (�) ทั้งหมด

📷 **ภาพก่อนแก้ไข**
![Before Fix – Not Support Thai/Emoji](./img/problem.png)

---

## ✅ หลังแก้ไข (After Fix)

หลังจากปรับปรุงฟอนต์และกำหนด stack ให้รองรับภาษาไทยและ emoji  
รวมถึงเพิ่ม fallback font และ Twemoji (สำหรับระบบที่ไม่มี emoji font)  
แอปสามารถแสดงผลได้ถูกต้อง ทั้งตัวอักษรไทยและอีโมจิ 🎉

📷 **ภาพหลังแก้ไข**
![After Fix – Thai and Emoji Supported](./img/Solve%20problems.png)

---

## 🪄 ฟีเจอร์หลักในแอป

### 1️⃣ ปุ่ม “🎊 ทักทาย”
กดเพื่อแสดงข้อความทักทายจากแอป
📷 **ภาพผลลัพธ์การทักทาย**
![Greeting Dialog](./img/greet.png)

---

### 2️⃣ ปุ่ม “⏰ แสดงเวลา”
กดเพื่อดูเวลาปัจจุบันในรูปแบบภาษาไทย (พ.ศ.)
📷 **ภาพผลลัพธ์แสดงเวลา**
![Show Time Dialog](./img/Show%20time.png)

---

### 3️⃣ ปุ่ม “🎨 เปลี่ยนสี”
กดเพื่อเปลี่ยนสีพื้นหลังของแอปแบบสุ่ม (Gradient Transition)
📷 **ภาพผลลัพธ์เมื่อเปลี่ยนสี**
![Change Color Result](./img/change%20color.png)

---

## 🛠️ เทคโนโลยีที่ใช้

| ส่วน | รายละเอียด |
|------|-------------|
| 💻 Framework | [Electron.js](https://www.electronjs.org/) |
| 🎨 Frontend | HTML + CSS (Glassmorphism UI) |
| ⚙️ Script | JavaScript (Vanilla) |
| 🌐 Font | Noto Sans Thai / Noto Color Emoji / Sarabun |
| 🧱 Platform Tested | Ubuntu 24.04 / Electron 33.x |

---

## 📦 โครงสร้างโปรเจกต์

```bash
my-first-electron-app/
├── index.html       # UI หลักของแอป
├── main.js          # Main process (Electron)
├── package.json     # ข้อมูลโปรเจกต์
└── assets/
    └── (ภาพประกอบ, ฟอนต์, ไอคอน)
```

---

## 📚 สรุปผลการพัฒนา

✅ รองรับภาษาไทยครบทุกจุด  
✅ Emoji แสดงได้ทุกตัว (รวมถึงในปุ่มและ Alert)  
✅ ใช้งานได้จริงใน WSL / VM / Linux  
✅ ไม่มีสี่เหลี่ยมหรือสระลอยอีกต่อไป  

> ⚡ จากภาพรวม จะเห็นว่าแอปเวอร์ชันใหม่นี้สามารถแสดงผล UI ได้สมบูรณ์ทั้งด้านฟอนต์ ภาษา และอีโมจิ ซึ่งไม่สามารถทำได้ในเวอร์ชันก่อนหน้า


---

### 🏁 License
MIT License © 2025 Tawan Tippkun
