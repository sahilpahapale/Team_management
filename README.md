# 🧑‍💼 Team Management Application

A full-stack web application for managing team members, built with **React.js**, **Node.js**, **Express**, and **MongoDB**.

---

## ✨ Features

-  Add new team members with profile images  
-  View all team members in a grid layout  
-  View detailed information about each team member  
-  Responsive design using **Material-UI**  
-  Image upload functionality  
-  RESTful API endpoints  

---

## 🔧 Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)  
- [MongoDB](https://www.mongodb.com/)  
- npm or yarn  

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/team-management-app.git
   cd team-management-app
   ```

2. **Install backend dependencies**
   ```bash
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd client
   npm install
   ```

4. **Create an uploads directory**
   ```bash
   mkdir uploads
   ```

5. **Start MongoDB service** on your machine

---

## 🚀 Running the Application

Start the backend server:
```bash
npm run dev
```

Start the frontend development server:
```bash
cd client
npm start
```

Visit: [http://localhost:3000](http://localhost:3000)

---

## 📡 API Endpoints

- `GET /api/members` – Fetch all team members  
- `GET /api/members/:id` – Fetch a specific team member  
- `POST /api/members` – Add a new team member  

---

## 🧰 Technologies Used

### Frontend
- React.js  
- Material-UI  
- React Router  
- Axios  

### Backend
- Node.js  
- Express  
- MongoDB  
- Multer (file uploads)
