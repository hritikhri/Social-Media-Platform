# 🚀 Social Media Platform - MERN Stack

A full-featured **Social Media Platform** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. The platform allows users to create accounts, share posts, like and comment on posts, manage profiles, and receive notifications in real time.

---

## 🌟 Features  

### 🔐 Authentication

* User Signup & Login
* JWT Authentication
* Protected Routes
* Secure Password Hashing

### 👤 User Profile

* Create and Edit Profile
* Upload Profile Picture
* View Other Users' Profiles

### 📝 Posts

* Create New Posts
* Upload Images
* Like / Unlike Posts
* Comment on Posts
* Delete Own Posts

### 🔔 Notifications

* Receive Notifications for Likes & Comments
* Notification API Integration

### 🎨 User Interface

* Responsive Design
* Modern UI
* Fixed Navigation Bar
* Footer Section
* Smooth User Experience

---

## 🛠 Tech Stack

### Frontend

* React.js
* React Router DOM
* CSS3
* JavaScript (ES6+)

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JWT (JSON Web Token)
* bcrypt.js

### Others

* dotenv
* cors
* multer (for image upload)

---

## 📂 Project Structure

```bash
Social-Media-Platform-MERN/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   ├── MainLayout.jsx
│   │   └── styles.css
│
├── backend/
│   ├── config/
│   │   └── db.js
│   │
│   ├── routes/
│   │   ├── auth.js
│   │   ├── posts.js
│   │   └── notifications.js
│   │
│   ├── public/
│   │   └── images/
│   │
│   └── server.js
│
└── README.md
```

---

## ⚙️ Frontend Routing

```jsx
/login       -> Login Page
/signup      -> Signup Page
/            -> Home Feed (Protected)
/:username   -> User Profile (Protected)
```

---

## 🔐 Protected Routes

Users must be authenticated to access:

* Home Feed
* User Profiles
* Post Features
* Notifications

Unauthenticated users are redirected to:

```bash
/login
```

---

## 🔧 Backend API Routes

### Authentication

```bash
POST /api/auth/signup
POST /api/auth/login
```

### Posts

```bash
GET    /api/posts
POST   /api/posts
DELETE /api/posts/:id
PUT    /api/posts/:id/like
POST   /api/posts/:id/comment
```

### Notifications

```bash
GET /api/notifications
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/hritikhri/Social-Media-Platform-MERN-.git
```

### Move into Project

```bash
cd Social-Media-Platform-MERN-
```

### Install Frontend Dependencies

```bash
cd client
npm install
```

### Install Backend Dependencies

```bash
cd ../backend
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key
```

---

## ▶️ Run Frontend

```bash
cd client
npm run dev
```

Runs on:

```text
http://localhost:5173
```

---

## ▶️ Run Backend

```bash
cd backend
npm start
```

Runs on:

```text
http://localhost:5000
```

---

## 📸 Screenshots

Add screenshots here:

```bash
public/
├── login.png
├── home.png
├── profile.png
└── notifications.png
```

---

## 👨‍💻 Developer

**Hritik Kumar**

* Full Stack MERN Developer
* Passionate about building scalable web applications
* Skilled in React, Node.js, MongoDB, Express, and REST APIs

### Connect With Me

GitHub:
https://github.com/hritikhri

LinkedIn:
Add your LinkedIn profile link

Portfolio:
Add your Portfolio URL

---

## ⭐ Support

If you like this project:

⭐ Star this repository

🍴 Fork this repository

🚀 Share it with others

---

## 📄 License

This project is licensed under the MIT License.

---

### Made with ❤️ by Hritik Kumar
