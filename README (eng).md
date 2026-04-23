# AI PC Builder & Secure Shop

## 🚀 Overview
A full-stack AI-powered PC building and e-commerce platform that provides intelligent hardware recommendations based on user needs and budget constraints.

The system combines machine learning and rule-based logic to ensure component compatibility and optimize performance configurations. Additionally, it integrates cybersecurity mechanisms such as authentication, data encryption, and threat detection to deliver a secure, reliable, and scalable user experience.

---

## 🧠 Features

### 🤖 AI Recommendation
- Suggest PC builds based on:
  - Budget
  - Usage (Gaming, AI, Office, etc.)
- Intelligent component matching
- Performance optimization for each use case

### 🔍 Compatibility Engine
- CPU – Motherboard socket matching
- PSU power estimation
- RAM & GPU compatibility validation

### 🛒 E-commerce System
- Browse and search components
- Product detail pages
- Admin dashboard for product management

### 🔐 Authentication & Authorization
- Secure login and registration
- Role-based access control (Admin / User)

---

## 🏗️ Tech Stack

- **Frontend:** Next.js (TypeScript)  
- **Backend API:** Node.js + Express.js  
- **AI Service:** Python (FastAPI) + OpenAI API / Local Model  
- **Database:** PostgreSQL  
- **ORM:** Prisma  

---

## 🔐 Cybersecurity Features

- JWT-based authentication  
- Password hashing with bcrypt  
- API rate limiting (DDoS & abuse prevention)  
- Secure HTTP headers with Helmet  
- Input validation & sanitization  

### Protected Against:
- SQL Injection  
- Cross-Site Scripting (XSS)  
- Brute-force attacks  

---

## 🤖 AI Logic

The recommendation system follows a hybrid approach:

### Rule-based Layer
- Ensures hardware compatibility  
- Filters out invalid configurations  

### AI/ML Layer
- Suggests optimal components based on user needs  
- Continuously improves recommendation quality  

### Example
**Input:**
- Budget: $1000  
- Purpose: Gaming  

**Output:**
- CPU: Ryzen 5 7600  
- GPU: RTX 4060  
- RAM: 16GB  

---

## 📌 Future Improvements

- Advanced ML model for personalized recommendations  
- Real-time price tracking & optimization  
- User behavior analytics  
- Integration with payment gateway  
- Deployment with Docker & CI/CD pipeline  

---

## 📄 License
This project is developed for educational and research purposes.
