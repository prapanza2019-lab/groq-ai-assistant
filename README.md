# ⚡ GroqAI Assistant

แอปพลิเคชัน Web AI Chat + สรุปเนื้อหา ที่ขับเคลื่อนด้วย **Groq API** — เร็วกว่า GPT ถึง 10 เท่า

![Preview](https://img.shields.io/badge/Groq-AI-purple?style=for-the-badge&logo=lightning)
![HTML](https://img.shields.io/badge/HTML-CSS-JS-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## ✨ ฟีเจอร์

| ฟีเจอร์ | คำอธิบาย |
|---------|----------|
| 💬 **AI Chat** | แชทกับ AI แบบ real-time streaming |
| 📝 **สรุปเนื้อหา** | สรุปข้อความได้ 4 แบบ (สั้น, กลาง, ละเอียด, bullet) |
| ⚙️ **ตั้งค่าได้ครบ** | เลือก model, temperature, system prompt ได้เอง |
| 🎨 **UI สวยงาม** | Dark theme, animation, responsive design |
| 🔒 **ปลอดภัย** | API Key เก็บแค่ใน localStorage เบราว์เซอร์ |
| 📱 **Responsive** | ใช้ได้ทั้งมือถือและ desktop |

---

## 🚀 วิธีใช้งาน

### วิธีที่ 1: เปิดไฟล์โดยตรง
```bash
# เปิด index.html ในเบราว์เซอร์ได้เลย ไม่ต้อง install อะไร
open index.html
```

### วิธีที่ 2: Deploy บน GitHub Pages
1. Fork หรือ clone repository นี้
2. ไปที่ **Settings → Pages**
3. เลือก Branch: `main` → Folder: `/ (root)`
4. กด **Save** — รอสักครู่แล้วเว็บจะ live ทันที!

### วิธีที่ 3: ใช้ Live Server (VS Code)
```bash
# ติดตั้ง Live Server extension แล้วกด Go Live
```

---

## 🔑 ขั้นตอนการตั้งค่า

1. **รับ Groq API Key ฟรี** ที่ [console.groq.com](https://console.groq.com)
2. เปิดแอป → ไปที่เมนู **"ตั้งค่า API"**
3. วาง API Key ที่ขึ้นต้นด้วย `gsk_...`
4. กด **"บันทึกและเชื่อมต่อ"**
5. เริ่มแชทได้เลย! 🎉

---

## 🤖 AI Models ที่รองรับ

| Model | ความเร็ว | จุดเด่น |
|-------|----------|---------|
| 🦙 LLaMA 3.3 70B | เร็วมาก | ฉลาดที่สุด (แนะนำ) |
| ⚡ LLaMA 3.1 8B | เร็วที่สุด | เหมาะกับ chatbot ทั่วไป |
| 🌀 Mixtral 8x7B | เร็ว | context window ยาว |
| 💎 Gemma 2 9B | เร็ว | ดีสำหรับภาษาอังกฤษ |

---

## 📁 โครงสร้างไฟล์

```
groq-ai-assistant/
└── index.html          # ไฟล์เดียว ครบทุกอย่าง (HTML + CSS + JS)
```

> **Single-file app** — ง่ายต่อการ deploy ไม่ต้อง build หรือ install

---

## 🛠️ เทคโนโลยีที่ใช้

- **Groq API** — LLM inference เร็วที่สุดในโลก
- **Vanilla HTML/CSS/JS** — ไม่มี framework ไม่ต้อง build
- **Font Awesome 6** — ไอคอนสวยงาม
- **Google Fonts** — ฟอนต์ Sarabun & Inter
- **SSE Streaming** — แสดงผลแบบ real-time

---

## 📸 หน้าจอโปรแกรม

```
┌─────────────────────────────────────────────────────┐
│  ⚡ GroqAI  │  แชทกับ AI                    🗑 ⚙   │
│             │                                       │
│  💬 แชท    │   🤖 สวัสดี! ฉัน GroqAI              │
│  📝 สรุป   │                                       │
│  ⚙ ตั้งค่า │   [ พิมพ์ข้อความที่นี่...    ] [→]   │
└─────────────────────────────────────────────────────┘
```

---

## 📄 License

MIT License — ใช้งานได้ฟรี แก้ไขได้ตามต้องการ

---

<div align="center">
  สร้างด้วย ❤️ และ ⚡ Groq AI
</div>
