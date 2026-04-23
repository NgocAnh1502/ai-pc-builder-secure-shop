# AI PC Builder & Secure Shop

## 🚀 Overview
* A full-stack AI-powered PC building and e-commerce platform that provides intelligent hardware recommendations based on user needs and budget constraints.  
The system leverages machine learning and rule-based logic to ensure component compatibility and optimize performance configurations.  
Additionally, it integrates cybersecurity mechanisms such as authentication, data encryption, and threat detection to deliver a secure, reliable, and scalable user experience.

* Một nền tảng web full-stack tích hợp AI hỗ trợ xây dựng cấu hình PC và kinh doanh linh kiện máy tính, cung cấp các đề xuất phần cứng thông minh dựa trên nhu cầu sử dụng và ngân sách của người dùng.  
Hệ thống kết hợp luật logic và học máy để đảm bảo tính tương thích giữa các linh kiện và tối ưu hiệu năng.  
Đồng thời, nền tảng tích hợp các cơ chế an ninh mạng như xác thực, mã hóa dữ liệu và phát hiện hành vi bất thường nhằm đảm bảo trải nghiệm an toàn và ổn định.

---

## 🧠 Features

### 🤖 AI Recommendation
- Suggest PC builds based on:
  - Budget
  - Usage (Gaming, AI, Office, etc.)
- Intelligent component matching
- Performance optimization per use-case

### 🔍 Compatibility Engine
- CPU – Mainboard socket matching
- PSU power estimation
- RAM & GPU compatibility validation

### 🛒 E-commerce Features
- Browse and search components
- Product detail view
- Admin product management

### 🔐 Security & Authentication
- Secure login/register system
- Role-based access (Admin/User)

---

## 🏗️ Tech Stack

- **Frontend:** Next.js (TypeScript)  
- **Backend API:** Node.js + Express.js  
- **AI Service:** Python (FastAPI) + OpenAI API / Local Model  
- **Database:** PostgreSQL  
- **ORM:** Prisma  

### 🔐 Security
- JWT Authentication  
- bcrypt (password hashing)  
- helmet (secure headers)  
- express-rate-limit (API protection)  

---

## 🔐 Cybersecurity Features

- JWT-based authentication system  
- Password hashing with bcrypt  
- API rate limiting to prevent abuse  
- Secure HTTP headers with Helmet  
- Input validation & sanitization  
- Protection against:
  - SQL Injection  
  - XSS  
  - Brute-force attacks  

---

## 🤖 AI Logic

The recommendation system is designed as a hybrid model:

- **Rule-based layer:**
  - Ensures hardware compatibility
  - Filters invalid configurations

- **AI/ML layer:**
  - Suggests optimal components based on user needs
  - Improves recommendation quality over time

### Example:
- Input: Budget = $1000, Purpose = Gaming  
- Output:
  - CPU: Ryzen 5 7600  
  - GPU: RTX 4060  
  - RAM: 16GB  

---
