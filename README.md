# resolvenow-your-platform-for-online-complaints
# Complaint Registry 📝

A full-stack web application for registering and managing complaints. Built with Node.js, Express, MongoDB, and React, this project provides a simple and efficient way for users to file complaints and for administrators to manage and resolve them.

## 🔧 Features

- User registration and authentication
- Complaint submission with category and description
- Admin panel for viewing and resolving complaints
- Real-time status updates
- RESTful API integration between frontend and backend
- MongoDB database for data persistence

## 🛠️ Tech Stack

**Frontend:**
- React
- HTML/CSS/JavaScript

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose

## 📁 Project Structure

complaint-registery-master/
├── backend/
│ ├── index.js
│ ├── server.js
│ ├── config.js
│ ├── Schema.js
│ ├── models/
│ ├── .env
│ └── package.json
├── frontend/ (if available)
│ └── ...
├── README.md

bash
Copy
Edit

## 🚀 Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/complaint-registery.git
cd complaint-registery/backend
Install dependencies:

bash
Copy
Edit
npm install
Create a .env file in the backend directory:

env
Copy
Edit
MONGO_URI=mongodb+srv://GopiKrishna:142023Sri@cluster0.cj0djeh.mongodb.net/complaintDB?retryWrites=true&w=majority&appName=Cluster0
PORT=5000
Start the backend server:

bash
Copy
Edit
node server.js
If frontend is available, navigate to the frontend directory and run the React app.

📬 API Endpoints
Method	Endpoint	Description
POST	/register	Register new user
POST	/login	Login existing user
POST	/complaint	Submit a new complaint
GET	/complaints	Get all complaints (admin)

🧪 Testing
You can use tools like Postman or Insomnia to test backend endpoints.
