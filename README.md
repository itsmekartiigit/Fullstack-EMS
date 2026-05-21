# Employee Management System (EMS)

A full-stack Employee Management System built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js). This application helps organizations manage employees, attendance, departments, and employee records efficiently.

## 🚀 Features

### Admin
- Admin Login Authentication
- Dashboard Overview
- Add New Employees
- Update Employee Details
- Delete Employees
- Manage Departments
- View Employee List
- Attendance Management

### Employee
- Employee Login
- View Personal Profile
- Update Profile Information
- View Attendance Records
- Access Dashboard

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router DOM
- Tailwind CSS
- Axios
- Context API

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcryptjs
- Cookie Parser
- CORS
- dotenv
- Nodemailer

## 📂 Project Structure

```
EMS/
│
├── client/
│   ├── src/
│   │   ├── Components/
│   │   ├── Pages/
│   │   ├── Context/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── server.js
│   └── package.json
│
└── README.md
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/itsmekartiigit/Fullstack-EMS.git
cd Fullstack-EMS
```

### Backend Setup

```bash
cd server
npm install
npm start
```

Backend runs on:

```
http://localhost:4000
```

### Frontend Setup

```bash
cd client
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

## 🔐 Environment Variables

Create a `.env` file inside the `server` folder.

```env
PORT=4000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password
```

## 🗄️ Database

MongoDB Atlas is used for storing:

- Employee Details
- Department Information
- Attendance Records
- User Authentication Data

## 📸 Screenshots

### Login Page

Add screenshot here.

### Dashboard

Add screenshot here.

### Employee Management

Add screenshot here.

## API Endpoints

### Authentication

```
POST /api/auth/login
POST /api/auth/logout
```

### Employees

```
GET /api/employees
POST /api/employees
PUT /api/employees/:id
DELETE /api/employees/:id
```

### Attendance

```
GET /api/attendance
POST /api/attendance
```

## 🔒 Security Features

- JWT Authentication
- Password Hashing using bcryptjs
- Protected Routes
- Environment Variables
- CORS Protection

## 📦 Dependencies

### Backend

- express
- mongoose
- dotenv
- cors
- bcryptjs
- jsonwebtoken
- cookie-parser
- nodemailer

### Frontend

- react
- react-router-dom
- axios
- tailwindcss

## 🚀 Deployment

### Frontend

Deploy on:

- Vercel
- Netlify

### Backend

Deploy on:

- Render
- Railway

### Database

- MongoDB Atlas

## 👨‍💻 Author

**Kartik**

GitHub: https://github.com/itsmekartiigit

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, don't forget to star the repository.
