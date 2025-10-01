
# My-Todo-App 📝  
A task management app built with the MERN stack, Firebase Authentication, and Cloudinary.

## 🚀 Live Demo
[https://my-todo-app-k5lq.vercel.app](https://my-todo-app-k5lq.vercel.app)

## 📌 Description
**My-Todo-App** is a task management system built with the **MERN stack** and integrates third-party services like **Firebase Authentication** and **Cloudinary**.  

This application enables three main user flows:  
- **Users manage tasks** with CRUD functionality, filtering by priority and deadlines.  
- **Users authenticate securely** using Email/Password or Google OAuth with Firebase.  
- **Users personalize profiles** by updating details and uploading profile images stored on Cloudinary.  

## ✨ Features
- Responsive **React.js UI** for task management.  
- Authentication powered by **Firebase (Email/Password & Google OAuth)**.  
- Secure backend with **Node.js, Express, MongoDB, JWT, and Mongoose**.  
- Task filtering by **priority and deadlines**.  
- **Profile management** with image uploads via Cloudinary.  

## 🛠️ Tech Stack
- **Frontend:** React.js, Firebase Auth  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)


## ⚙️ Installation & Setup  

### 1️⃣ Clone the Repository
``` bash
git clone https://github.com/your-username/my-todo-app.git
cd my-todo-app
```

# 🔑 Environment Variables  
To run this project, you will need to create `.env` files in both **client/** and **backend/** folders.  


## 🌐 Frontend (`client/.env`)

```
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_BASE_URL=http://localhost:5000
```

## 🌐 Frontend (`client/.env`)
```
MONGO=your_mongodb_connection_string
REFRESH_TOKEN_SECRET=your_refresh_secret
ACCESS_TOKEN_SECRET=your_access_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

