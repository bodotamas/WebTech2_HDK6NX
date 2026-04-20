# Hungarian Fine Dining

Ez a repository a Miskolci Egyetem Web Technológiák 2 című tantárgyhoz készült.  
Egy modern ételrendelő webalkalmazást tartalmaz — Angular + Node.js + MongoDB.

## Technológiák

### Backend

- Node.js + Express.js
- TypeScript / JavaScript
- MongoDB + Mongoose
- JWT authentikáció
- bcryptjs jelszó hashelés

### Frontend

- Angular
- TypeScript
- HTML
- CSS
- Angular Reactive Forms
- PayPal SDK
- Térképes címkezelés

### A projekt indítása

1. Klónozás
2. A backend/src mappában létre kell hozni egy .env fájlt, ahol meg kell adni a MONGODB URL-t (MongoDB Atlas).
3. Függöségek letöltése az npm install segítségével
4. Backend elindítása (npm start) (http://localhost:5001)
5. Frontend elindítása (npm start) (http://localhost:4200)

## Előfeltételek

- Node.js (v18+)
- MongoDB (v6+ vagy MongoDB Atlas)
- Angular CLI: `npm install -g @angular/cli`

## Telepítés és indítás

### 1. Backend

```bash
cd backend
npm install
npm run dev
