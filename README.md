คุณสามารถเขียน **README.md** ให้บอกวิธีรัน Frontend และ Backend แบบชัดเจนได้ประมาณนี้:

````markdown
# Check It Off Project

## Prerequisites

- Node.js (สำหรับ frontend)
- npm (มาพร้อม Node.js)
- Java 21 (สำหรับ backend)
- Maven (หรือใช้ `mvnw` ที่มากับโปรเจกต์)
- Docker (ถ้าต้องการรัน MySQL + phpMyAdmin ผ่าน Docker)

---

## รัน Frontend

1. เข้าไปที่โฟลเดอร์ frontend:

```bash
cd frontend
````

2. ติดตั้ง dependencies (ครั้งแรก):

```bash
npm install
```

3. รันโปรเจกต์:

```bash
npm run dev
```

Frontend จะรันที่ `http://localhost:5173/`

---

## รัน Backend

### Option 1: ใช้ Maven Wrapper (แนะนำ)

1. เข้าไปที่โฟลเดอร์ backend:

```powershell
cd backend/checkitoff-backend
```

2. รัน Spring Boot:

```powershell
.\mvnw.cmd spring-boot:run
```

### Option 2: ใช้ IntelliJ IDEA

1. เปิดโปรเจกต์ backend ใน IntelliJ IDEA
2. เปิดไฟล์ `CheckitoffBackendApplication.java`
3. กดปุ่ม **Run** (เครื่องหมาย ▶️) เพื่อรัน Spring Boot
4. Backend จะรันที่ `http://localhost:8080/`

---

## Database (MySQL + phpMyAdmin) ผ่าน Docker (Optional)

1. เข้าไปที่โฟลเดอร์ `checkitoff-db`:

```bash
cd checkitoff-db
```

2. รัน Docker Compose:

```bash
docker compose up -d
```

3. phpMyAdmin จะรันที่ `http://localhost:9000/`

   * Username: `root`
   * Password: `password`

```

---

ถ้าคุณอยาก ผมช่วยทำ **เวอร์ชัน README.md แบบสั้น ๆ สำหรับส่งงานอาจารย์** ที่เน้น “รันง่าย ๆ ไม่ต้องตั้งค่าเยอะ” ให้ด้วยได้เลย จะได้ไม่งงตอนอาจารย์รัน.  

คุณอยากให้ผมทำไหม?
```
