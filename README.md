<div align="center">

# 🌟 Dynamic Portfolio with MongoDB

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
</p>

<p align="center">
  <strong>A modern, full-stack web application for creating and managing dynamic portfolios</strong>
</p>

<p align="center">
  ✨ Admin Management • 🎨 Modern UI • 🚀 Fast Performance • 📱 Responsive Design
</p>

</div>

---

## 🚀 Features

- 🔐 **Admin Registration & Authentication**: Secure admin registration and login system
- 📊 **Portfolio Management**: Add, update, and manage portfolio content dynamically
- 🎨 **Modern UI**: Responsive frontend using React, Vite, and Tailwind CSS
- 🚀 **RESTful API**: Backend API built with Express.js and MongoDB
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices
- ⚡ **Fast Performance**: Optimized with Vite for lightning-fast development

## 📁 Project Structure

```text
.
├── backend
│   ├── config/           # Database configuration
│   ├── controllers/      # Route controllers
│   ├── middleware/       # Authentication middleware
│   ├── models/           # Mongoose models
│   ├── routes/           # API routes
│   ├── package.json      # Backend dependencies
│   └── server.js         # Express server entry point
├── frontend
│   ├── src/
│   │   ├── components/   # Reusable React components
│   │   ├── pages/        # Page components
│   │   ├── styles/       # CSS (Tailwind)
│   │   └── utils/        # Utility functions (API calls)
│   ├── index.html        # Main HTML file
│   ├── package.json      # Frontend dependencies
│   └── vite.config.js    # Vite configuration
└── README.md
```

## 🚀 Getting Started

### 📋 Prerequisites

- 🟢 Node.js (v16+ recommended)
- 🍃 MongoDB (local or Atlas)

### ⚙️ Backend Setup

1. Navigate to the backend folder:
   
   ```sh
   cd backend
   ```

2. Install dependencies:
   
   ```sh
   npm install
   ```

3. Configure MongoDB:
   - Edit `config/db.js` to set your MongoDB URI.

4. Start the backend server:
   
   ```sh
   npm start
   ```

### 🎨 Frontend Setup

1. Navigate to the frontend folder:
   
   ```sh
   cd frontend
   ```

2. Install dependencies:
   
   ```sh
   npm install
   ```

3. Start the frontend development server:
   
   ```sh
   npm run dev
   ```

### 🌐 Accessing the App

- 🎨 **Frontend**: [http://localhost:5173](http://localhost:5173)
- 🔧 **Backend API**: [http://localhost:5000](http://localhost:5000) (default)

## 📖 Folder Details

### 🔧 Backend

- `config/db.js`: MongoDB connection setup
- `controllers/`: Handles business logic for routes
- `middleware/auth.js`: Authentication middleware
- `models/Admin.js`: Mongoose schema for admin users
- `routes/adminRoutes.js`: API endpoints for admin actions
- `server.js`: Main Express server file

### 🎨 Frontend

- `src/components/`: Footer, Loader, etc.
- `src/pages/`: Admin registration, update, and home pages
- `src/utils/api.js`: API utility functions
- `src/styles/index.css`: Tailwind CSS styles

## 🎯 Customization

- 📝 Update portfolio sections and admin features as needed
- 👥 Extend authentication and add more user roles if required

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

## 🤝 Contributors

- 👨‍💻 Your Name
- 🌟 [Add more contributors here]

<br>

### ⭐ Don't forget to star this repository if it helped you!

<br>

**Made with ❤️ and lots of ☕**

</div>