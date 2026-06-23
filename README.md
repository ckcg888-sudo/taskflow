# TaskFlow

เว็บแอป TaskFlow แบบ static สำหรับใช้งานผ่าน GitHub Pages

## บัญชีทดลอง

- `admin` / `demo123`
- `manager` / `demo123`
- `staff` / `demo123`
- `staff2` / `demo123`

## สิทธิ์และบทบาท

- `Admin`: จัดการผู้ใช้ งาน โปรเจกต์ รายงาน และตั้งค่าทั้งหมด
- `Manager`: จัดการงานและโปรเจกต์ ดูรายงานและรายชื่อพนักงาน แต่ไม่ลบผู้ใช้
- `Staff`: ดูและแก้ไขเฉพาะงานที่ตัวเองรับผิดชอบ เพิ่มงานให้ตัวเองได้
- `Guest`: ดูข้อมูลอย่างเดียว

## เปิดใช้งานบน GitHub Pages

1. สร้าง repository ใหม่ใน GitHub
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้น repository
3. ไปที่ `Settings > Pages`
4. เลือก `Deploy from a branch`
5. เลือก branch `main` และ folder `/root`
6. กด `Save`

ข้อมูลในแอปถูกเก็บใน browser localStorage ของผู้ใช้แต่ละเครื่อง
