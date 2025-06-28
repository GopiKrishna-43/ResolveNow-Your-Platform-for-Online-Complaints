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

bash
Copy
Edit
npm install
Environment setup (.env file):

env
Copy
Edit
MONGO_URI=mongodb+srv://GopiKrishna:142023Sri@cluster0.cj0djeh.mongodb.net/complaintDB?retryWrites=true&w=majority&appName=Cluster0
PORT=5000
Run the backend:

bash
Copy
Edit
node server.js
If the frontend exists, navigate to the frontend folder and run it with npm start.

📬 API Routes
POST /register – Register user

POST /login – Login user

POST /complaint – Submit complaint

GET /complaints – Get all complaints (admin)
