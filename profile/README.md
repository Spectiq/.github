# 🕶️ Spectiq

A modern eyewear e-commerce platform inspired by Lenskart, built with a scalable full-stack architecture.

---

## 🚀 Tech Stack

- Frontend: Next.js, TypeScript, Tailwind CSS  
- Backend: Node.js, Express.js  
- Database: PostgreSQL (Supabase)  
- Image Storage: Cloudinary  
- Authentication: JWT, Google SSO  

---

## ✨ Features

- Product listing & filtering  
- Product detail pages  
- Cart management  
- User authentication  
- Order placement  
- Image upload & optimization  

---

## 🏗️ Architecture

Next.js (Frontend)
      ↓
Express API
      ↓
PostgreSQL (Supabase)
      ↓
Cloudinary (Images)

---

## ⚙️ Setup

```bash
# clone repo
git clone <repo-url>

# install backend
cd backend
npm install
npm run dev

# install frontend
cd frontend
npm install
npm run dev
```

---

## 🌐 Environment Variables

### Backend

```
DATABASE_URL=your_postgres_url
JWT_SECRET=your_secret
CLOUDINARY_CLOUD_NAME=xxx
CLOUDINARY_API_KEY=xxx
CLOUDINARY_API_SECRET=xxx
```

### Frontend

```
NEXT_PUBLIC_API_URL=http://localhost:5000
NEXT_PUBLIC_GOOGLE_CLIENT_ID=your_client_id
```

---

## 📌 Note

- Images are stored in Cloudinary  
- Database is hosted on Supabase  
- Frontend and backend are deployed separately  

---

## 👨‍💻 Author

- Atul Bansal
- Riya Bansal
