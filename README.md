# 🏢 Smart Dormitory Management System

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

Smart Dorm เป็นระบบบริหารจัดการหอพักที่ออกแบบมาเพื่อช่วยให้การจัดการของผู้เช่าและนิติบุคคลสะดวกขึ้น โดยมีฟีเจอร์สำหรับการจัดการห้องพัก การแจ้งซ่อม การจัดการบิล และการประกาศข่าวสาร

---

## ✨ Features

### 👤 Tenant Features

- **Personal Dashboard:** ดูข้อมูลห้องพักและประกาศล่าสุดได้ง่าย
- **Billing System:** ตรวจสอบบิลค่าน้ำ-ค่าไฟและอัพโหลดหลักฐานการโอนเงิน
- **Maintenance Requests:** แจ้งซ่อมพร้อมแนบรูปภาพและติดตามสถานะ
- **Profile Management:** แก้ไขข้อมูลส่วนตัวและรีเซ็ตรหัสผ่าน

### 🛠️ Admin Features

- **Room Management:** จัดการสถานะห้องพักและข้อมูลผู้เช่า
- **Billing Management:** สร้างบิล ตรวจสอบการชำระเงิน และยืนยันสลิป
- **Maintenance Tracking:** ติดตามคำร้องขอซ่อม แก้สถานะ และมอบหมายงาน
- **Announcements:** ประกาศข่าวให้ผู้เช่าทุกคนเห็น

---

## 🚀 Tech Stack

- **Frontend:** React 18 + TypeScript + Vite
- **Styling:** Tailwind CSS 4 + Lucide React icons
- **Backend:** Node.js + Express
- **Database:** PostgreSQL with `pg`
- **Authentication:** JWT + BcryptJS
- **Infrastructure:** Docker & Docker Compose
- **Deployment:** Local development with Vite and Docker

---

## 🛠️ Getting Started

### Prerequisites

- Node.js v18 ขึ้นไป
- Docker Desktop

### 1. Clone and Install Dependencies

```bash
git clone https://github.com/clumsyz/smart-dorm.git
cd smart-dorm
npm install
```

### 2. Start the Database and pgAdmin

```bash
npm run docker:up
```

จากนั้นเปิด pgAdmin ที่:

```text
http://localhost:5050
```

Login credentials:

- Email: `admin@smartdorm.com`
- Password: `admin123`

### 3. Initialize the Database

```bash
npm run setup:db
```

### 4. Run the Application

```bash
npm run dev:api
npm run dev
```

เปิดเว็บแอปได้ที่:

```text
http://localhost:5173
```

### 5. Stop the System

```bash
npm run docker:down
```

---

Developed with ❤️ by [ClumsyZ](https://github.com/clumsyz)
