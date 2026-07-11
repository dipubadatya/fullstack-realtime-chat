# ✨ Full Stack Real-Time Chat Application

A modern real-time chat application built with the MERN stack, Socket.io, Tailwind CSS, and DaisyUI.

## 🚀 Features

- 🌟 MERN Stack (MongoDB, Express.js, React.js, Node.js)
- 🔐 JWT Authentication & Authorization
- 💬 Real-time messaging with Socket.io
- 🟢 Online/Offline user status
- 🖼️ Profile image upload with Cloudinary
- 🎨 Responsive UI using Tailwind CSS & DaisyUI
- ⚡ Global state management with Zustand
- 🐞 Client & Server-side error handling
- 🚀 Production-ready deployment support

---

## 📁 Project Structure

```text
chat-app/
│
├── backend/
│   ├── src/
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md
```

---

# ⚙️ Backend Setup

## 1. Navigate to backend

```bash
cd backend
```

## 2. Install dependencies

```bash
npm install
```

## 3. Create a `.env` file

```env
MONGODB_URI=your_mongodb_connection_string

PORT=5001

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```

## 4. Start Backend

Development

```bash
npm run dev
```

Production

```bash
npm start
```

---

# 💻 Frontend Setup

## 1. Navigate to frontend

```bash
cd frontend
```

## 2. Install dependencies

```bash
npm install
```

## 3. Start Frontend

Development

```bash
npm run dev
```

Build

```bash
npm run build
```

Preview Production Build

```bash
npm run preview
```

---

# 🚀 Running the Complete Project

### Terminal 1

```bash
cd backend
npm run dev
```

### Terminal 2

```bash
cd frontend
npm run dev
```

Frontend

```
http://localhost:5173
```

Backend

```
http://localhost:5001
```

---

## 🛠 Tech Stack

- MongoDB
- Express.js
- React.js
- Node.js
- Socket.io
- Zustand
- Tailwind CSS
- DaisyUI
- JWT Authentication
- Cloudinary
