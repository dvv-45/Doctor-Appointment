# 🏥 Doctor Appointment System

A full-stack Doctor Appointment Booking Platform that allows patients to book appointments with doctors, manage bookings, make online payments, and enables administrators to manage doctors and appointments efficiently.

---

## 🚀 Live Demo

### Frontend
https://doctor-appointment-frontend-2wmr.onrender.com

### Admin Panel
https://doctor-appointment-admin-2iin.onrender.com

### Backend API
https://doctor-appointment-backend-p679.onrender.com
---

## ✨ Features

### User Features
- User Registration and Login
- JWT Authentication
- Browse Available Doctors
- Filter Doctors by Speciality
- Book Appointments
- View Appointment History
- Cancel Appointments
- Online Payment Integration using Razorpay
- User Profile Management

### Doctor Features
- Doctor Login
- View Appointments
- Manage Availability
- Update Profile Information
- Dashboard with Appointment Statistics

### Admin Features
- Secure Admin Authentication
- Add New Doctors
- View Doctor List
- Manage Appointments
- Dashboard Analytics
- Upload Doctor Images using Cloudinary

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router DOM
- Axios
- Tailwind CSS
- React Toastify

### Backend
- Node.js
- Express.js
- JWT Authentication
- Multer
- Bcrypt
- Cloudinary
- Razorpay

### Database
- MongoDB Atlas
- Mongoose

### Deployment
- Render
- MongoDB Atlas
- Cloudinary

---

## 📂 Project Structure

```bash
Doctor-Appointment/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── admin/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── config/
│   └── package.json
│
└── README.md
```

---

## 🔐 Authentication

- JWT-based authentication
- Protected Routes
- Role-based access for Admin, Doctor, and User
- Password Hashing using Bcrypt

---

## 💳 Payment Gateway

Integrated Razorpay Payment Gateway for online appointment payments.

Features:
- Secure Order Creation
- Payment Verification
- Payment Status Tracking

---

## ☁️ Cloudinary Integration

Used Cloudinary for:

- Doctor Profile Image Upload
- Image Storage
- Fast Image Delivery


## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/dvv-45/Doctor-Appointment.git
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Admin

```bash
cd admin
npm install
npm run dev
```

### Backend

```bash
cd backend
npm install
npm start
```

---

## 🔑 Environment Variables

Create `.env` files and add:

### Backend

```env
MONGODB_URL=
JWT_SECRET=
ADMIN_EMAIL=
ADMIN_PASSWORD=
CLOUDINARY_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_SECRET_KEY=
RAZORPAY_KEY_ID=
RAZORPAY_KEY_SECRET=
CURRENCY=INR
```

### Frontend

```env
VITE_BACKEND_URL=
VITE_RAZORPAY_KEY_ID=
```

### Admin

```env
VITE_BACKEND_URL=
```

---

## 🎯 Future Improvements

- Email Notifications
- SMS Reminders
- Doctor Verification System
- Appointment Rescheduling
- Video Consultation
- Search and Filter Enhancements

---

## 👨‍💻 Author

**Dhanishetti Vishnu**

- B.Tech Information Technology
- National Institute of Technology Raipur

GitHub:
https://github.com/dvv-45

---
