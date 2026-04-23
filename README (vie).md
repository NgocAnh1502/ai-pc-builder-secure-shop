# AI PC Builder & Secure Shop

## 🚀 Tổng quan
Đây là một nền tảng web full-stack tích hợp AI giúp xây dựng cấu hình PC và kinh doanh linh kiện máy tính, cung cấp các đề xuất phần cứng thông minh dựa trên nhu cầu và ngân sách của người dùng.

Hệ thống kết hợp giữa luật logic và học máy để đảm bảo tính tương thích giữa các linh kiện, đồng thời tối ưu hiệu năng. Ngoài ra, nền tảng còn tích hợp các cơ chế an ninh mạng như xác thực, mã hóa dữ liệu và phát hiện hành vi bất thường nhằm mang lại trải nghiệm an toàn, ổn định và có khả năng mở rộng.

---

## 🧠 Tính năng

### 🤖 Gợi ý cấu hình bằng AI
- Đề xuất cấu hình PC dựa trên:
  - Ngân sách
  - Mục đích sử dụng (Gaming, AI, Văn phòng,...)
- Ghép linh kiện thông minh
- Tối ưu hiệu năng theo từng nhu cầu

### 🔍 Hệ thống kiểm tra tương thích
- Kiểm tra socket CPU – Mainboard  
- Ước lượng công suất nguồn (PSU)  
- Kiểm tra tương thích RAM và GPU  

### 🛒 Chức năng thương mại điện tử
- Duyệt và tìm kiếm linh kiện  
- Xem chi tiết sản phẩm  
- Quản lý sản phẩm (Admin)  

### 🔐 Xác thực & phân quyền
- Đăng ký / đăng nhập an toàn  
- Phân quyền người dùng (Admin / User)  

---

## 🏗️ Công nghệ sử dụng

- **Frontend:** Next.js (TypeScript)  
- **Backend API:** Node.js + Express.js  
- **AI Service:** Python (FastAPI) + OpenAI API / Local Model  
- **Cơ sở dữ liệu:** PostgreSQL  
- **ORM:** Prisma  

---

## 🔐 Tính năng bảo mật

- Xác thực bằng JWT  
- Mã hóa mật khẩu với bcrypt  
- Giới hạn request API (chống spam / DDoS)  
- HTTP headers bảo mật với Helmet  
- Kiểm tra và làm sạch dữ liệu đầu vào  

### Bảo vệ chống:
- SQL Injection  
- XSS (Cross-Site Scripting)  
- Tấn công brute-force  

---

## 🤖 Cơ chế AI

Hệ thống gợi ý sử dụng mô hình kết hợp:

### Layer luật (Rule-based)
- Đảm bảo tính tương thích phần cứng  
- Loại bỏ cấu hình không hợp lệ  

### Layer AI/ML
- Đề xuất linh kiện tối ưu theo nhu cầu  
- Cải thiện chất lượng gợi ý theo thời gian  

### Ví dụ
**Input:**
- Ngân sách: 1000 USD  
- Mục đích: Gaming  

**Output:**
- CPU: Ryzen 5 7600  
- GPU: RTX 4060  
- RAM: 16GB  

---

## 📌 Hướng phát triển

- Nâng cấp mô hình AI cá nhân hóa  
- Theo dõi giá linh kiện theo thời gian thực  
- Phân tích hành vi người dùng  
- Tích hợp thanh toán online  
- Triển khai với Docker và CI/CD  

---

## 📄 Giấy phép
Dự án được phát triển phục vụ mục đích học tập và nghiên cứu.
