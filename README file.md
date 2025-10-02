# Quiz App

The **Quiz App** is a full-fledged application built using the **MERN stack** (MongoDB, Express.js, React, Node.js).  
It provides a complete solution for quiz management, allowing admins to create and manage quizzes while students can participate and track their performance.

---

## 🚀 Features

### 👨‍💻 Admin
- Create quizzes related to any subject.
- Publish quizzes for students.
- Enter and manage quiz scores.
- Track records of all students who have attempted quizzes.

Note: for admin user, please use this object and add in your mongodb compass:
{
  "_id": {
    "$oid": "68d94d3bc891c4d5a0bc0de3"
  },
  "name": "Admin",
  "email": "a@mail.com",
  "password": "$2a$10$qUVK3LVohqacdkmtKm6t4ug0NSpugJwxBTd7vuf79wGW4MVZbX2tG",
  "type": "admin",
  "__v": 0
}

admin credentials: 
email: a@mail.com
password: qwerty

### 🎓 Students
- Participate in quizzes assigned to their account.
- View and track quiz history.
- Check their scores and performance over time.

---

## 🛠️ Tech Stack
- **Frontend**: React.js  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  

---

## 📂 Project Structure
```
/frontend      -> React frontend
/backend      -> Node.js + Express backend
/database    -> MongoDB collections
```

---

## ⚡ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/awdhesh-student/quiz-app.git
   cd quiz-app
   ```

2. Install dependencies for both frontend and backend:
   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

3. Start the backend server:
   ```bash
   cd backend
   npm run start
   ```
The server will start on port 8000

4. Running the Project:
   Set up the environment variables. Create a .env file in the server directory and add the following variables:

   MONGO_DB=your_mongo_db_compass_connection_string
   PORT=8000
   JWT_KEY=your_jwt_secret

   NOTE: `Replace your_mongo_db_compass_connection_string and your_jwt_secret with your actual MongoDB Compass connection string and JWT secret key.`

5. Start the frontend:
   ```bash
   cd frontend
   npm run dev
   ```

6. Open the app in your browser at:
   ```
   http://localhost:5173
   ```

---
