# RecruiteX

This is a full-stack **Job Portal Application** built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. It allows users to create accounts, post jobs, and apply for jobs. Admins can manage job listings and users.

## 🛠️ Tech Stack

- **Frontend:** React.js, Axios, React Router DOM, TailwindCSS / Bootstrap (optional)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **State Management:** React Context API
- **Others:** Toast Notifications, REST APIs

## 🔑 Features

### 👤 User Features:
- Register and login (JWT-based auth)
- View all available job listings
- Apply for jobs
- Update profile

### 🏢 Employer Features:
- Post new jobs
- View applications for their posted jobs
- Edit and delete job listings

### ⚙️ Admin Features (if applicable):
- View all users
- Delete any job or user
- Manage roles

## 📂 Folder Structure

job-portal/
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── server.js
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── context/
│ │ └── App.js
└── README.md

