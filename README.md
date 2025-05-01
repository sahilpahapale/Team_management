# Team Management Application
A full-stack web application for managing team members, built with React.js, Node.js, Express, and MongoDB.

# Features
Add new team members with profile images

View all team members in a grid layout

View detailed information about each team member

Responsive design using Material-UI

Image upload functionality

RESTful API endpoints

# Prerequisites
Node.js (v14 or higher)

MongoDB

npm or yarn

# Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/team-management-app.git
cd team-management-app
Install backend dependencies

bash
Copy
Edit
npm install
Install frontend dependencies

bash
Copy
Edit
cd client
npm install
Create an uploads directory in the root folder

bash
Copy
Edit
mkdir uploads
Start MongoDB service on your machine

# Running the Application
Start the backend server (from the root directory):

bash
Copy
Edit
npm run dev
Start the frontend development server (from the client directory):

bash
Copy
Edit
cd client
npm start
Open your browser and navigate to:
http://localhost:3000

# API Endpoints
GET /api/members – Get all team members

GET /api/members/:id – Get a specific team member

POST /api/members – Add a new team member

# Technologies Used
Frontend
React.js

Material-UI

React Router

Axios

Backend
Node.js

Express

MongoDB

Multer (for file uploads)
