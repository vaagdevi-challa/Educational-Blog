# 🧠 Educational Blog Platform

A full-stack **Educational Blog Platform** where users can **create**, **read**, **edit**, and **delete** blogs focused on educational content. Built with the **MERN stack (MongoDB, Express, React, Node.js)**, it offers a seamless and responsive user experience.

---

## ✨ Features

- 📝 User authentication with secure JWT tokens
- 📰 Create, edit, and delete educational blog posts
- 🔍 Search and filter blogs by keyword or category
- 👥 User profiles with personal blog history
- 💬 Commenting functionality (extendable)
- 🌐 Responsive design for desktop and mobile
- 🔐 Protected routes and middleware for API security

---

## 🚀 Tech Stack

| Technology | Description                        |
|------------|------------------------------------|
| React      | Frontend UI Library                |
| Node.js    | JavaScript runtime (backend)       |
| Express.js | Web framework for Node.js          |
| MongoDB    | NoSQL database                     |
| Mongoose   | MongoDB object modeling            |
| JWT        | Authentication & route protection  |
| Axios      | HTTP client for frontend API calls |
| CSS        | Styling with modular files         |

---

## 📂 Project Structure
<pre> 
educational-blog/
│
├── backend/                         # Express.js backend
│   ├── server.js                    # Entry point of the backend server
│   ├── .env                         # Environment variables
│   ├── config/
│   │   └── db.js                    # MongoDB connection setup
│   ├── models/
│   │   ├── User.js                  # User schema
│   │   └── Blog.js                  # Blog schema
│   ├── middleware/
│   │   └── authMiddleware.js        # Middleware for auth routes
│   ├── routes/
│   │   ├── authRoutes.js            # Routes for authentication
│   │   └── blogRoutes.js            # Routes for blog operations
│   └── uploads/                     # Folder for uploaded files/images
│
├── frontend/                        # React frontend
│   └── src/
│       ├── App.js                   # Root component with route definitions
│       ├── index.js                 # Entry point of the React app
│       │
│       ├── components/              # Reusable UI components
│       │   ├── BlogCard.js
│       │   └── Navbar.js
│       │
│       ├── pages/                   # Pages/views of the app
│       │   ├── AuthPage.js
│       │   ├── BlogDashboard.js
│       │   ├── BlogDetail.js
│       │   ├── CreateBlog.js
│       │   ├── EditBlog.js
│       │   ├── EducationalBlog.js
│       │   └── Profile.js
│       │
│       ├── services/                # API calls and backend communication
│       │   └── api.js
│       │
│       └── styles/                  # CSS files for various components/pages
│           ├── auth.css
│           ├── dash.css
│           ├── edit.css
│           ├── global.css
│           ├── home.css
│           └── profile.css
</pre>


---

## 🔧 Getting Started

 ### 1️⃣ Clone the repository
<pre>git clone https://github.com/vaagdevi-challa/Educational-Blog.git
cd educational-blog</pre>

### 2️⃣ Set up the Backend
<pre>cd backend
npm install

Create a .env file and add your environment variables:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Start the backend server:
npm start
</pre>
### 3️⃣ Set up the Frontend
<pre>cd ../frontend
npm install
npm start
</pre>
