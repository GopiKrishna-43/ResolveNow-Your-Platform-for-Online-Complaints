# resolvenow-your-platform-for-online-complaints
# Complaint Registry 📝

A full-stack web app for users to register complaints and for admins to manage them.

## 🚀 Tech Stack

- **Frontend**: React
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose

## 🔧 Features

- User authentication
- Complaint creation and tracking
- Admin panel for resolving complaints

## 📦 Setup Instructions

1. **Clone the repo**:
   ```bash
   git clone https://github.com/yourusername/complaint-registery.git
   cd complaint-registery/backend
   
Install backend dependencies:
npm install

Run the backend:
node server.js

If the frontend exists, navigate to the frontend folder and run it with npm start.

📬 API Routes
POST /register – Register user

POST /login – Login user

POST /complaint – Submit complaint

GET /complaints – Get all complaints (admin)

# 📝 Complaint Registry

Complaint Registry is a MERN Stack-based application for users to register complaints and for admins to manage and resolve them efficiently.

## 📁 Project Structure

- `frontend/` — React app (User Login, Complaint Submission, Admin View)
- `backend/` — Node.js + Express + MongoDB (API & DB operations)

## 🚀 How to Run

1. Clone this repo
2. Open two terminals:
   - In `/backend` → `npm install` → `npm run dev`
   - In `/frontend` → `npm install` → `npm start`
3. Create a `.env` file in `/backend` with:
   ```env
   MONGO_URI=mongodb+srv://GopiKrishna:142023Sri@cluster0.cj0djeh.mongodb.net/complaintDB?retryWrites=true&w=majority&appName=Cluster0
   PORT=5000
👤 Roles
User: Can submit complaints and track status

Admin: Can view, manage, and resolve complaints

📬 Built with ❤️ by Gopi Krishna
