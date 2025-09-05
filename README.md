# 📝 Diggy Note: Your Digital Notebook, Always Within Reach

**Diggy Note** is a user-friendly, feature-rich note-taking web application built with the **MERN stack** (MongoDB, Express.js, React, Node.js). It's designed to help you capture your thoughts, ideas, and to-dos in an organized and accessible way, from any device with an internet connection.

🔗 [Try it live](https://full-stack-note-app-ashy.vercel.app/signup)

---

## 🌟 Key Features

- **Effortless Note Creation**  
  Quickly jot down notes with a clean and intuitive editor. Format your text, create lists, and add attachments with ease.

- **Seamless Organization**  
  Categorize your notes with customizable notebooks and tags. Find what you need instantly with powerful search functionality.

- **Collaboration Made Easy**  
  Share notes or entire notebooks with others for collaborative brainstorming, project planning, or knowledge sharing.

- **Secure and Reliable**  
  Notes are securely stored in the cloud with MongoDB, ensuring your data is always safe and accessible.

- **Responsive Design**  
  Access and manage your notes from desktop, tablet, or smartphone with a clean responsive interface.

- **Offline Support** (If applicable)  
  Work on your notes even without internet; changes sync automatically once you're back online.

---

## 👤 Who It's For

- 🎓 Students taking notes in class or studying
- 💼 Professionals managing tasks or brainstorming
- ✍️ Writers capturing ideas or researching
- 🧠 Anyone who needs a powerful, accessible digital notebook

---

## ⚙️ Tech Stack

| Category    | Technology                            |
|-------------|----------------------------------------|
| Frontend    | React.js, Tailwind CSS, Vite           |
| Backend     | Node.js, Express.js                    |
| Database    | MongoDB Atlas                          |
| Auth        | JWT (JSON Web Tokens)                  |
| Hosting     | Vercel (Frontend), Render/Railway (API)|

---

## 📁 Folder Structure

### Backend `/backend`

- `index.js` – Express server entry point  
- `models/` – Mongoose models for User & Note  
- `utilities.js` – Utility functions  
- `.env` – Environment variables (JWT_SECRET, MONGO_URI)  
- `package.json` – Backend dependencies  

### Frontend `/frontend/notes-app`

- `components/` – Reusable UI (Cards, Navbar, Input, Toasts)  
- `pages/` – Page views (Login, SignUp, Home, LandingPage)  
- `utils/` – Global CSS & helpers  
- `App.jsx` – Root component  
- `tailwind.config.js` – Tailwind CSS config  
- `vite.config.js` – Vite build config  

---

## 🔑 Environment Variables

In `/backend/.env`:

```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

## 🚀 Local Setup

### Clone and Install

```bash
git clone https://github.com/yourusername/diggy-note
cd diggy-note
```

### Backend

```bash
cd backend
npm install
npm start
```

### Frontend

```bash
cd frontend/notes-app
npm install
npm run dev
```

---

## ✅ To-Do / Enhancements

- [ ] Add markdown or rich text editor
- [ ] Add dark mode support
- [ ] Add tag filters and sorting
- [ ] Enable real-time collaboration (WebSockets)
- [ ] Add offline-first PWA features

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 📬 Contact

**Author:** Raja Gupta

* 📌 GitHub: [@rajagupta142](https://github.com/rajagupta142)
* 📌 LinkedIn: \[Your LinkedIn URL]
* 📩 Email: \[Your Email Address]
```
