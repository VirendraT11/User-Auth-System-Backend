# 🚀 User Authentication System - Backend

Welcome to the **User Authentication System** 🎉! This project is a robust backend application built to handle user registration, login, logout, and secure session management. It implements modern **authentication** and **authorization** practices using **JWT** (JSON Web Tokens) for a seamless and secure user experience.

---

## 📌 **Tech Stack**
- **Node.js** 🌐: Backend runtime environment.
- **Express.js** 🚀: Fast and minimalist web framework for Node.js.
- **MongoDB** 🍃: NoSQL database for efficient data storage.
- **Mongoose** 📜: Elegant MongoDB object modeling for Node.js.
- **JWT (JSON Web Token)** 🔒: Token-based authentication.
- **bcrypt** 🔑: Password hashing for secure storage.
- **dotenv** 📦: Environment variable management.

---

## ✨ **Unique Features**
- **🔒 Secure Authentication**: User authentication using **JWT** tokens with cookies for session management.
- **🛡️ Password Hashing**: User passwords are securely hashed using **bcrypt**.
- **📤 Logout Functionality**: Clearing cookies on logout for enhanced security.
- **🔑 Protected Routes**: Middleware to protect sensitive routes and ensure only authenticated users can access them.
- **🗂️ Modular Code Structure**: Clean and organized file structure for scalability.
- **⏱️ Expiry Management**: Tokens have a configurable expiration time for added security.

---

## 📂 **Project Structure**
```plaintext
User-Auth-System-Backend/
├── config/          # Database configuration
├── middleware/      # Authentication middleware
├── models/          # Mongoose schemas
├── routes/          # API routes
├── server.js        # Entry point
├── .env.example     # Environment variable template
└── package.json     # Project metadata
```

---

## 🌟 **How It Works**
1. **Register**: A new user can register with a unique username, email, and password.
2. **Login**: The user logs in with valid credentials to receive a **JWT** token.
3. **Protected Routes**: Only accessible with a valid token.
4. **Logout**: Users can securely log out by clearing the token.

---

## 🚀 **Getting Started**

### **Prerequisites**
- Install [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/).

### **Setup**
1. Clone the repository:
   ```bash
   git clone https://github.com/VirendraT11/User-Auth-System-Backend.git
   cd User-Auth-System-Backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up the environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```plaintext
     MONGO_URI=your_mongo_connection_string
     JWT_SECRET=your_jwt_secret
     PORT=5000
     ```
4. Start the server:
   ```bash
   npm run dev
   ```
5. Test the endpoints using tools like [Postman](https://www.postman.com/) or [Thunder Client](https://www.thunderclient.com/).

---

## 🛠️ **Endpoints**
### **Auth Routes**
| Method | Endpoint          | Description                    |
|--------|--------------------|--------------------------------|
| POST   | `/api/auth/register` | Register a new user           |
| POST   | `/api/auth/login`    | Login with user credentials   |
| POST   | `/api/auth/logout`   | Logout the current user       |
| GET    | `/api/auth/protected`| Access a protected route      |

---

## 🤝 **Contributing**
Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 🌐 **Connect with Me**
- **Twitter**: [@VirendraCodes](https://twitter.com/VirendraCodes) 🐦
- **LinkedIn**: [Virendra Tambavekar](https://www.linkedin.com/in/virendra-tambavekar-74a384257/) 💼

---

## ⭐ **Show Your Support**
If you found this project helpful or inspiring, please give it a ⭐ on [GitHub](https://github.com/VirendraT11/User-Auth-System-Backend)! 

---

Let me know if you want to add any additional sections or modify anything! 😊
