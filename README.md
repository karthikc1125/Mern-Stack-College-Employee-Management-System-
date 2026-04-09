🚀 MERN Stack Employee Management System

A full-stack Employee Management System built using the MERN stack that allows efficient handling of employee data with authentication, CRUD operations, and user-based data fetching.


---

✨ Features

🔐 User Authentication System (Login / Register)

👤 Same User Data Fetching (Users can only access their own employee records)

📊 Employee CRUD Operations (Create, Read, Update, Delete)

🔎 Search & Filter Employees

⚡ Real-time UI Updates

🌐 RESTful API Integration

📱 Responsive UI Design



---

🏗️ Tech Stack

Layer	Technology

Frontend	React.js + Tailwind CSS
Backend	Node.js + Express.js
Database	MongoDB
Authentication	JWT (JSON Web Tokens)



---

⚙️ Installation

1️⃣ Clone the repository

git clone https://github.com/karthikc1125/code-to-flowchart-generator.git
cd project-folder

2️⃣ Install dependencies

# frontend
npm install

# backend
npm install


---

▶️ Running the Application

Start Backend Server

npm start

Start Frontend

npm run dev


---

🔐 Authentication Flow

1. User registers with email and password


2. Server generates JWT token


3. Token is stored on client side


4. Protected routes verify token before access




---

👤 Same User Data Fetch Logic

Each employee record is linked with a user ID

On login, the system identifies the current user

Backend filters employee data using user ID

Ensures users can only access their own data



---

📊 API Overview

Auth APIs

POST /api/auth/register

POST /api/auth/login


Employee APIs (Protected)

GET /api/employees → Fetch user-specific employees

POST /api/employees → Add employee

PUT /api/employees/:id → Update employee

DELETE /api/employees/:id → Delete employee



---

⚠️ Error Handling

Invalid login credentials

Unauthorized access (JWT validation)

Missing or incorrect data inputs

Server and database errors



---

🎯 Use Cases

🏢 Small company employee tracking

👨‍💼 HR management systems

📚 Learning full-stack MERN development

💻 Practice project for interviews



---

🛠️ Future Improvements

📊 Dashboard analytics

📁 File upload (employee documents)

📧 Email notifications

🔄 Role-based access control (Admin/User)



---

🤝 Contributing

1. Fork the repository


2. Create a feature branch


3. Commit your changes


4. Open a Pull Request


👨‍💻 Author

Karthik C
Full Stack Developer | MERN Enthusiast


---

⭐ Support

If you like this project, give it a ⭐ on GitHub!

