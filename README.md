# Nagraj Engineering Works – HRMS System

A full-stack HR management system for tracking workers, approvals, and user roles.

## 🚀 Live Demo

- **Frontend:** https://nagraj-hrms.netlify.app
- **Backend API:** https://backend-nagraj.onrender.com
- **Health Check:** https://backend-nagraj.onrender.com/api/health

## 📦 Tech Stack

- **Frontend:** React.js, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Deployment:** Netlify (Frontend), Render (Backend)

## 🔐 Default Login Credentials

| Role | Email | Password |
|------|-------|----------|
| Super Admin | a | a123 |
| CEO | ceo | ceo123 |
| HR | h | h123 |
| Production Head | ph | ph123 |
| Contractor | c | c123 |

## 🛠️ Features

- Worker registration with approval workflow
- Role-based dashboards (Admin, CEO, HR, Production Head, Contractor)
- Employee data management with Aadhar upload
- Salary and daily rate calculation
- Punch code generation

## 📂 Project Structure
FINAL NAGRAJ ENGINEERING WORKS/
├── backend/
│ ├── server.js
│ ├── package.json
│ └── vercel.json
└── nagraj-hrms/
├── src/
├── public/
├── .env
└── package.json
## 🧪 Local Setup

### Prerequisites
- Node.js installed
- MongoDB running locally or Atlas connection string

Backend Setup
cd backend
npm install
npm start

Frontend Setup
cd nagraj-hrms
npm install
npm start

Environment Variables
Create .env in nagraj-hrms folder:

text
REACT_APP_API_URL=http://localhost:5002
For production, set on Netlify:

text
REACT_APP_API_URL=https://backend-nagraj.onrender.com

🌍 Deployment
Frontend: Netlify – drag & drop build folder

Backend: Render – connect GitHub repo, set root directory backend

👨‍💻 Author
leminabhagat20

📄 License
This project is for internal use at Nagraj Engineering Works.
