# ข้าวกล่องเดลิเวอรี่ v1

ระบบรับออเดอร์ข้าวกล่อง จัดเส้นทาง และใบงานไรเดอร์

## โครง

- `backend/` — Express + TypeScript + MySQL (auth, customers, orders, riders, plans, tracking, simulation)
- `frontend/` — Angular (หน้าลูกค้า, หลังบ้าน, ใบงานไรเดอร์)

## รัน

```bash
# backend
cd backend
cp .env.example .env
npm install
npm run db:migrate
npm run dev

# frontend
cd frontend
npm install
npm run start:local
```

## ทีม

- Hexxxxxxx — backend
- egobluu — backend
- Minee25 — frontend
- CallMeSova — frontend
