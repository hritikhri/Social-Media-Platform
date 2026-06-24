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

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1b7c18f9-c8f1-4a29-a707-948e72738b81" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/62d6cb7a-3727-4a9a-b7c7-22ea29460aa5" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8a217ff7-fac4-464e-957d-482fb1f59593" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6c713402-2a6b-4196-8ada-e1bdf19cb8d6" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9b10c392-a7a1-4c26-96ff-0c24a7b4ccf8" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6677ddbf-9be1-4686-856a-c684267a4bda" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/acdd1748-35f9-452d-92b3-bbeb2a30040e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b05433e3-2224-4497-948a-d0b73a6b1097" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5d1a5efa-992c-4138-98ef-11e0cc5a6d67" />



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
