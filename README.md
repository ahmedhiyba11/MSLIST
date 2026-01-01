# 🎬 MS List — AI-Powered Movie & Show Recommendation Platform

MS List is a MERN-based movie and show recommendation web app that helps users discover content intelligently.  
It includes personalized watchlists, progress tracking, and an AI-enhanced recommendation system powered by text embeddings.

---

## 🚀 Features

### 🔹 User Features
- Browse movies & shows from the database  
- Add shows to **MS List (Watchlist) or custom watchlist**  
- Track what you're currently watching  
- Get smart AI-based recommendations  
- Explore by genre, popularity & moods  
- Responsive, modern UI built with React

### 🤖 AI Recommendation System
- Generates embeddings for each movie or show  
- Uses cosine similarity to recommend similar content  
- No heavy ML training required  
- Fully works with your own database content  

### 🔹 Admin Panel
- Add, update, and delete movies  
- Manage genres and categories  
- Dashboard for user & content analytics  

---

## 🧠 How AI Recommendation Works
MS List uses **text-embedding vectors** generated from each show's: 
- description   
These vector are compared using cosine similarity to find the closest matches.  
This gives Netflix-style AI recommendations without training a model.

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- Axios  
- React Router  
- Modern UI with custom CSS / Tailwind (optional)

### Backend
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- Gemini Embeddings API  

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/ms-list.git
cd ms-list
```
2️⃣ Install backend dependencies  
3️⃣ Install frontend (MS List) dependencies  
4️⃣ Environment variables  
5️⃣ Run the backend
```bash
cd backend
nodemon index.js
```
6️⃣ Run the frontend
```bash
cd MS List
npm run dev
```
📌 Folder Structure
```bash
ms-list/
 ├── MS List/           # React Frontend
 ├── backend/           # Node + Express Backend
 │   ├── controllers/   # backend controllers
 │   ├── middleware/    # backend middlewares
 │   ├── models/        # MongoDB Schemas
 │   ├── routes/        # API Routes
 │   ├── utils/         # Summary, Embedding & Similarity Logic
 └── README.md
```
### 🎯 Future Enhancements
- A Community tab
### 📜 License
- This project is open-source and free to use.
### 💡 Author
Created by Prithviraj  
If you like the project, consider ⭐ staring the repository!

<p align="center">
  <img src="https://img.shields.io/badge/MERN-Stack-blue" />
  <img src="https://img.shields.io/badge/React-18.0-61DAFB?logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-Express-339933?logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-6.0-47A248?logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Google-Gemini_Embeddings-4285F4?logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

