## 🚁 DRONE-SERVER (Node.js Express Backend)

ส่วนนี้คือ **Backend API Server** สำหรับจัดการข้อมูลโดรนและบันทึก Log ต่างๆ พัฒนาด้วย **Node.js** และ **Express** โดยดึงข้อมูลจากแหล่งภายนอกที่กำหนดในไฟล์ `.env`



## 🛠️ การติดตั้งและการรัน

### 1. ติดตั้ง Dependencies

เปิด Terminal ในโฟลเดอร์โปรเจกต์และรัน:

```bash
npm install
```

### 2. ตั้งค่าตัวแปรสภาพแวดล้อม(.env)

```bash
DRONE_URL = https://script.google.com/macros/s/AKfycbzwclqJRodyVjzYyY-NTQDb9cWG6Hoc5vGAABVtr5-jPA_ET_2IasrAJK4aeo5XoONiaA/exec
DRONE_LOG = https://app-tracking.pockethost.io/api/collections/drone_logs/records
API_TOKEN = 20250901efx
```

### 3. รันเซิร์ฟเวอร์

```bash
node server.js
```
