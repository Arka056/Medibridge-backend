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
## 🔧 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Arka056/Medibridge-backend.git
cd Medibridge-backend
```
### 2️⃣ Install Dependencies  
```bash
npm install
```
### 3️⃣ Environment Variables
Create .env file:  
```bash
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret-key
PORT=5000
```
### 4️⃣ Start Development Server
```bash
npm run dev
```
### 5️⃣ Start Production Server
```bash
npm start
```
### 6️⃣ Preview Production Build
```bash
npm run preview
```
---

### 🛡 Security
This backend follows healthcare API security practices:
* JWT authentication
* Password encryption (bcrypt)
* Input validation
* CORS protection
* Error handling middleware
* Sanitized database requests

---

### 📈 Deployment
**☁️ Azure App Service**
* Deployed in Azure Portal using *Azure Web Service*
* Set ```npm start``` as startup command
* Add env variables

---

### 🤝 Contributing

1. Fork the repository
2. Create a new branch  ```git checkout -b feature/my-feature```
3. Commit your changes
4. Push the branch
5. Create a Pull Request
Contributions are welcome! 
We appreciate contributions that enhance performance, improve accessibility, or enhance the user experience!

### 📜 License

This project is licensed under the MIT License.

### 💬 Feedback
If you have suggestions or ideas to improve this UI, feel free to open an issue or share your thoughts.

### ⭐ Support
If you like this project, please ⭐ star the repository on GitHub — it motivates development!

Thank you for exploring the **Medi-Bridge AI Platform**!

Crafted with ❤️ for a **Smarter Healthcare** future.
