# Medibridge – Backend 
> **Secure • Fast • Scalable Healthcare API Platform**

---

## 🚀 Overview  
The **Medibridge Backend** is a robust, modular, and secure REST API built using **Node.js, Express, MongoDB, and JWT Authentication**.  
It powers the MediBridge ecosystem by managing users, authentication, health records, appointments, and AI-powered modules.

Designed for:
- 🔐 High-security healthcare workflows  
- ⚡ Fast API responses  
- ☁️ Cloud deployment (Azure / Render / Railway)  
- 🧩 Scalable architecture with reusable modules  

---

## 🌟 Features  
- **Node.js + Express REST API**  
- **MongoDB with Mongoose ORM**  
- **JWT Authentication & Authorization**  
- **CORS-enabled**  
- **Environment-based configuration**  
- **Centralized error handling**  
- **Modular folder structure**  
- **Cloud deployment ready**  

---

## 🧱 Tech Stack  

| Category | Technology |
|---------|------------|
| Runtime | Node.js |
| Framework | Express.js |
| Database | MongoDB Atlas |
| ORM | Mongoose |
| Auth | JWT (JSON Web Token) |
| Environment Variables | dotenv |
| Deployment | Azure / Render / Railway |
| Logging | Console + Middleware |

---

## 📂 Project Structure  

```bash
backend/
├─ src/
│  ├─ config/
│  │  └─ db.js                  # MongoDB connection
│  ├─ controllers/              # Business logic
│  ├─ models/                   # Mongoose schemas
│  ├─ routes/                   # Express route definitions
│  ├─ middleware/
│  │  ├─ authMiddleware.js      # JWT authentication
│  │  └─ errorHandler.js        # Centralized error handler
│  ├─ utils/                    # Helper functions
│  ├─ server.js                 # Server startup
│  └─ app.js                    # Express app config
├─ .env.example                 # Sample environment variables
├─ package.json
├─ package-lock.json
└─ README.md
```
