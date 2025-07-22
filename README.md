# 🏥 Hospital Appointment Booking App

An easy-to-use full-stack web app for booking doctor appointments online!  
Patients can book slots 🗓️, doctors can manage schedules 🩺, and admins control everything ⚙️.

---

## 🔧 Tech Stack

**Frontend** 🖥️  
- ⚛️ React.js  
- 🎨 Material UI  
- 📦 Redux Toolkit  

**Backend** 🛠️  
- 🧠 Node.js + Express  
- 🗄️ MongoDB + Mongoose  
- 🔐 JWT + bcrypt (Authentication)  
- ✉️ Nodemailer (Emails)  
- 📲 Twilio (SMS)

---

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


🧑‍💼 Admin Panel
Admin Login 👉 /admin/login

Can manage 🧑‍⚕️ doctors, 👥 users, 📅 appointments

Only accessible to users with admin role

🌐 Live Demo
🚨 frontend - https://hospo-1-02h8.onrender.com


📝 Author
👩‍💻 Developed by Richa
📫 Email: richa020310@gmail.com
🌍 GitHub: @richa-1003

