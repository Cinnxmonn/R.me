## Term Project
The Term Project SE331 Component-Based Software Development 2<br>
**project-01-the-anti-fake-news-system-check-it-off Phase II** <br>
**Frontend Deployment :** https://the-social-anti-fake-news-system-ph.vercel.app/ <br>
**Backend Deployment :**  <br> I have to admit that the backend deployment was not completed because the frontend was deployed but could not connect to the backend. <br>
Ajan may run the backend and frontend separately on machines to test the system.
<br>

## Group Member : Check It Off Phase II
- **Name:** Nawapon Somruang  
- **Student ID:** 662115027  
<br>

## Check it off Anti-Fake News System Phase 2.
**Local Testing:** Teachers may download the project files from , then run the frontend and backend separately on machines:
<br>

**1.Run Frontend:**  
```bash
cd frontend
npm install
npm run dev
```

The frontend will run at `http://localhost:5173` (or the port shown when running `npm run dev`)

---

## Run Backend

1. เข้าไปที่โฟลเดอร์ backend
```bash
cd backend
````

2. ติดตั้ง dependencies (ถ้าเป็น Node.js)

```bash
npm install
```

หรือถ้าเป็น Spring Boot:

```bash
./mvnw clean install
```

3. รัน backend

```bash
npm run dev    # ถ้าเป็น Node.js
```

หรือ

```bash
./mvnw spring-boot:run   # ถ้าเป็น Spring Boot
```

Backend จะรันที่ `http://localhost:8080` (หรือ port ที่ config ไว้)

```

---

💡 **Tip:** คุณอาจเพิ่มบอกว่าต้องรัน **Backend ก่อน** แล้วค่อยรัน Frontend เพื่อให้ API เชื่อมต่อได้ตรง ๆ  

---

ถ้าคุณอยาก ผมช่วยเขียนเป็น **README แบบเต็ม ๆ ที่รวม Frontend + Backend + Notes สำหรับ Env** ให้เรียบร้อยเลยก็ได้ จะได้สวย ๆ อ่านง่าย ๆ.  

คุณอยากให้ผมทำแบบนั้นไหม?
```
