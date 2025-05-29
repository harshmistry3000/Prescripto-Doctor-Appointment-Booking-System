# Prescripto-Doctor-Appointment-Booking-System
Project: Prescripto – Doctor Appointment Booking System 🩺📱

![Screenshot 2025-04-14 134052](https://github.com/user-attachments/assets/66ab9df5-3534-4fe0-ba22-9cf4513d709f)



📌 Description:
Prescripto is a full-stack web application built to digitalize and simplify the process of booking doctor appointments online 🏥. Patients can register, search for available doctors 👨‍⚕️👩‍⚕️, view availability 🕒, and book appointments 📅 with secure payment through Razorpay 💳. Doctors can manage their schedules, and admins can monitor the entire system via dashboards 🧑‍💼.

It features real-time appointment booking, login/authentication 🔐, role-based access 👥, and responsive UI ⚛️📱 for seamless experience across all devices. This project offers practical experience in handling databases, cloud services, payment integrations, and modular architecture for scalable apps.

⚙️ Technologies Used:
Frontend: React.js ⚛️, Axios, CSS

Backend: Node.js, Express.js 🔧

Database: MongoDB Atlas ☁️

Payment Gateway: Razorpay 💳

Cloud Media Storage: Cloudinary ☁️

Authentication: JWT 🔐

Hosting (if deployed): [Add here if used, e.g., Vercel / Render / Netlify / Cyclic]

🚀 How It Works:
Patient Signup/Login: Register or log in securely using JWT authentication 🔐

Doctor Listings: View a list of available doctors with specialization, location, and timings

Appointment Booking: Select doctor and available time, then confirm booking

Razorpay Integration: Make secure payments online 💳

Role-Based Dashboard:

Patients: View appointments

Doctors: Manage appointments

Admins: Manage all users and data

Responsive UI: Optimized for both desktop and mobile 📱

🛠️ How to Set Up and Run Locally

1️⃣ Clone the Repository
git clone https://github.com/whotfvasu/Prescripto.git
cd Prescripto

2️⃣ Install Dependencies
Backend
cd backend
npm install

Frontend
Open another terminal:
cd frontend
npm install

3️⃣ Create a .env File in /backend
Inside the backend folder, create a .env file and add your credentials:
env
MONGODB_URI=your_mongodb_uri

CLOUDINARY_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_cloudinary_api_key

CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key

ADMIN_EMAIL=admin@example.com

ADMIN_PASSWORD=your_admin_password

JWT_SECRET=your_jwt_secret

RAZORPAY_KEY_ID=your_razorpay_key

RAZORPAY_KEY_SECRET=your_razorpay_secret

CURRENCY=INR

STRIPE_SECRET_KEY=your_stripe_secret_key (optional if not used)

⚠️ You must replace the placeholders with actual values from:
MongoDB Atlas

Cloudinary

Razorpay

Your admin credentials and JWT secret



4️⃣ Start the Backend Server

npm start

Runs at http://localhost:4000


5️⃣ Start the Frontend React App

cd frontend

npm start

Runs at http://localhost:3000
