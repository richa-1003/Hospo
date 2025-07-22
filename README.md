# 🏥 Hospital Appointment Booking App

An easy-to-use full-stack web app for booking doctor appointments online!  
Patients can book slots 🗓️, doctors can manage schedules 🩺, and admins control everything ⚙️.

<img width="1920" height="906" alt="Screenshot (149)" src="https://github.com/user-attachments/assets/87c0afca-6861-4023-9c4a-1a9c22329fe7" /> <img width="1905" height="704" alt="Screenshot (148)" src="https://github.com/user-attachments/assets/cb578281-ba7f-43be-8d24-a3fe237bfa07" />
<img width="1920" height="847" alt="Screenshot (147)" src="https://github.com/user-attachments/assets/1db9eabe-68f2-4f2a-bd15-838ac47e90a9" />


## 🚀 Features

- 🔐 **User Authentication & Authorization** (JWT-based)
- 🩺 **Doctor Directory** with filters by specialization and availability
- 📅 **Real-Time Appointment Booking System**
- 📊 **Admin Dashboard** to manage doctors, users, and appointments
- 📱 **Responsive UI** for mobile, tablet, and desktop

(assets/Screenshot (147).png)
(assets/Screenshot (148).png)
(assets/Screenshot (149).png)

## 🔧 Tech Stack

**Frontend** 🖥️  
- ⚛️ React.js  
- 🎨 Material UI  
- 📦 Redux Toolkit  

**Backend** 🛠️  
- 🧠 Node.js + Express  
- 🗄️ MongoDB + Mongoose  
- 🔐 JWT + bcrypt (Authentication)  

---

## 🔗 Live Demo

👉 [Check it Out on Render 🌐](https://hospo-1-02h8.onrender.com)

## 🚀 How to Run the Project

### 🧩 Step 1: Clone the Repo
```bash
git clone https://github.com/your-username/hospital-app.git
cd Hospo

### 🧩 Step 2: install dependencies

# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install



### 🔧  Step 3: Set Environment Variables
In /backend/.env:
```env
# 🌍 Currency Configuration
CURRENCY="INR"

# 🔐 JWT Secret Key
JWT_SECRET="HiThere!"

# 🧑‍💼 Admin Panel Credentials
ADMIN_EMAIL="admin@example.com"
ADMIN_PASSWORD="your password"

# 🌐 MongoDB Setup (Required)
MONGODB_URI="mongodb+srv://<username>:<password>@cluster0.mongodb.net"

# ☁️ Cloudinary Configuration (Required)
CLOUDINARY_NAME="daw3hr0qy"
CLOUDINARY_API_KEY="888591474757575"
CLOUDINARY_SECRET_KEY="n6omdrkOGvT0KeIRk7G3ydLtupA"

# 💳 Razorpay Integration
RAZORPAY_KEY_ID="your_razorpay_key_id"
RAZORPAY_KEY_SECRET="your_razorpay_key_secret"


### 📦  Step 4: Run The App

# Backend 
cd backend
npm run server

# Frontend 
cd ../frontend
npm run dev

# admin
cd ../admin
npm run dev


🧑‍💼 Admin Panel
Admin Login 👉 /admin/login

Can manage 🧑‍⚕️ doctors, 👥 users, 📅 appointments

Only accessible to users with admin role





📝 Author
👩‍💻 Developed by Richa
📫 Email: richa020310@gmail.com
🌍 GitHub: @richa-1003

