# 📝 ThinkBoard — Full-Stack Note Taking App

A modern, responsive **full-stack note-taking application** built with the MERN stack. ThinkBoard allows users to create, view, edit, and delete notes with a clean and simple interface.

🔗 **Live Demo:** https://mern-thinkboard-946s.vercel.app/

---

## 🚀 Features

* ✨ Create new notes
* 📖 View all notes
* 🔍 View individual note details
* ✏️ Edit existing notes
* 🗑️ Delete notes
* 🔔 Toast notifications
* 📱 Responsive UI
* ⚡ Fast React + Vite frontend
* 🌐 REST API backend
* ☁️ MongoDB database
* 🚀 Production deployment with Vercel and Render
* 🔐 CORS configured for production

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* React Router
* Axios
* Tailwind CSS
* DaisyUI
* Lucide React
* React Hot Toast

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* CORS
* dotenv

### Deployment

* **Frontend:** Vercel
* **Backend:** Render
* **Database:** MongoDB

---

## 📂 Project Structure

```text
mern-thinkboard/
│
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   └── notesController.js
│   ├── models/
│   │   └── Note.js
│   ├── routes/
│   │   └── notesRoutes.js
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── lib/
│   │   └── App.jsx
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

## 🔄 Application Flow

```text
React Frontend
      │
      │ Axios / REST API
      ▼
Express.js Backend
      │
      │ Mongoose
      ▼
MongoDB Database
```

### Production Architecture

```text
User
 │
 ▼
Vercel
React + Vite Frontend
 │
 │ HTTPS API Requests
 ▼
Render
Node.js + Express Backend
 │
 │ MongoDB Connection
 ▼
MongoDB Atlas
```

---

## 🔗 API Endpoints

| Method | Endpoint         | Description       |
| ------ | ---------------- | ----------------- |
| GET    | `/api/notes`     | Get all notes     |
| GET    | `/api/notes/:id` | Get a single note |
| POST   | `/api/notes`     | Create a note     |
| PUT    | `/api/notes/:id` | Update a note     |
| DELETE | `/api/notes/:id` | Delete a note     |

---

## ⚙️ Environment Variables

### Backend

Create a `.env` file inside the backend folder:

```env
PORT=5001
MONGODB_URI=your_mongodb_connection_string
NODE_ENV=development
FRONTEND_URL=http://localhost:5173
```

### Frontend

Create a `.env` file inside the frontend folder:

```env
VITE_API_URL=http://localhost:5001/api
```

For production:

```env
VITE_API_URL=https://mern-thinkboard-master-gghx.onrender.com/api
```

> Never commit `.env` files or database credentials to GitHub.

---

## 💻 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/DasSubham-2005/mern-thinkboard.git
cd mern-thinkboard
```

### 2. Install Backend Dependencies

```bash
cd backend
npm install
```

### 3. Start Backend

```bash
npm run dev
```

Backend will run on:

```text
http://localhost:5001
```

### 4. Install Frontend Dependencies

Open another terminal:

```bash
cd frontend
npm install
```

### 5. Start Frontend

```bash
npm run dev
```

Frontend will run on:

```text
http://localhost:5173
```

---

## 📸 Screenshots

Add screenshots of the application here:

```text
screenshots/
├── homepage.png
├── create-note.png
├── note-details.png
└── edit-note.png
```

---

## 🌟 What I Learned

While building ThinkBoard, I worked with:

* Building REST APIs with Express.js
* MongoDB database integration using Mongoose
* CRUD operations
* React state management with `useState`
* API requests using Axios
* React Router navigation
* Environment variable configuration
* CORS configuration
* Production deployment
* Connecting a Vercel frontend with a Render backend
* Debugging frontend/backend API issues

---

## 🚀 Future Improvements

* 🔐 User authentication and authorization
* 👤 Personal notes for each user
* 🔎 Search notes
* 🏷️ Categories and tags
* 🌙 Dark/light theme customization
* 📌 Pin important notes
* 📅 Note sorting and filtering
* 🔒 JWT authentication
* ☁️ Improved production monitoring

---

## 👨‍💻 Author

**Subham Das**

Computer Science & Engineering Student
Interested in **Machine Learning, Data Science, AI, and Full-Stack Development**

### Connect With Me

* GitHub: https://github.com/DasSubham-2005
* LinkedIn: https://www.linkedin.com/in/subham-das-a316422b4

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.

cd frontend
npm install
npm run dev
```
# mern-thinkboard
