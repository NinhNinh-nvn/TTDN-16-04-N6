# 🎓 KHOA CÔNG NGHỆ THÔNG TIN – ĐẠI HỌC ĐẠI NAM  
# 🚀 FITDNU HR AI – HỆ THỐNG QUẢN LÝ NHÂN SỰ TÍCH HỢP AI

<p align="center">
  <img src="dnu_logo.png" alt="Dai Nam University" height="80"/>
  <img src="fitdnu_logo.png" alt="FIT DNU" height="80"/>
  <img src="aiotlab_logo.png" alt="AIoTLab" height="80"/>
</p>

<p align="center">
📄 <strong>Poster dự án:</strong> <a href="N6Poster.pdf">Xem Poster FITDNU HR AI</a>
</p>

---

## 📖 1. Giới thiệu

**FITDNU HR AI** là hệ thống **Quản lý Nhân sự (Human Resource Management System)** được xây dựng trên nền tảng **ERP Odoo**, tích hợp **Trí tuệ Nhân tạo (AI)** nhằm tự động hóa, giám sát và nâng cao hiệu quả quản lý nhân sự trong doanh nghiệp.

Hệ thống hướng tới:
- Số hóa toàn bộ quy trình nhân sự
- Giảm gian lận trong chấm công
- Tự động hóa tính lương
- Hỗ trợ ra quyết định cho nhà quản lý

📍 Dự án được triển khai tại **Phòng thí nghiệm AIoT – Khoa Công nghệ Thông tin – Đại học Đại Nam**, phục vụ cho:
- 🎓 Học phần Thực tập / Thực doanh nghiệp
- 🧠 Nghiên cứu AI ứng dụng trong ERP
- 🏢 Mô phỏng hệ thống HR doanh nghiệp

---

## 🧾 2. Poster dự án

<p align="center">
  <a href="N6Poster.pdf">
    <strong>📄 Click để xem Poster FITDNU HR AI</strong>
  </a>
</p>

**Poster thể hiện:**
- Tổng quan hệ thống
- Kiến trúc giải pháp
- Công nghệ sử dụng
- Chức năng chính
- Minh họa giao diện phần mềm

---

## 🖼️ 3. Giao diện & Hình ảnh phần mềm

### 🔐 3.1. Giao diện đăng nhập

<p align="center">
  <img src="Screenshot 2026-01-22 220451.png" width="85%">
</p>

- Đăng nhập hệ thống ERP HR
- Phân quyền: Admin / HR / Quản lý / Nhân viên
- Kiểm soát truy cập dữ liệu

---

### 📊 3.2. Dashboard quản trị nhân sự

<p align="center">
  <img src="Screenshot 2026-01-22 220559.png" width="95%">
</p>

- Thống kê nhân sự
- Tỷ lệ đi làm đúng giờ
- Cảnh báo gian lận AI
- Biểu đồ realtime

---

### ⏱️ 3.3. Dashboard chấm công & AI

<p align="center">
  <img src="Screenshot 2026-01-22 220630.png" width="95%">
</p>

- Theo dõi chấm công trong ngày
- Phát hiện bất thường
- Phê duyệt tự động / thủ công

---

## ⭐ 4. Chức năng chính

### 4.1. Chấm công thông minh
- Nhận diện khuôn mặt AI
- Chống chấm công hộ
- Xác thực GPS
- Lưu trữ realtime

### 4.2. Phát hiện gian lận
- Phân tích hành vi
- Phát hiện:
  - Giờ làm bất thường
  - Trùng thời gian
  - Sai vị trí
- Chấm điểm rủi ro (Risk Score)

### 4.3. Tính lương tự động
- Tính lương theo công & OT
- Phụ cấp, bảo hiểm, thuế TNCN
- Xuất payslip

### 4.4. Quản lý nhân sự
- Hồ sơ nhân viên
- Phòng ban
- Hợp đồng lao động
- Lịch sử công tác

---

## 🛠️ 5. Công nghệ sử dụng

### 5.1. ERP – Odoo 15.0
<p align="center">
  <img src="Screenshot 2026-01-22 220559.png" width="90%">
</p>

- ERP mã nguồn mở
- Kiến trúc module HR

### 5.2. Backend – Python
<p align="center">
  <img src="Screenshot 2026-01-22 220630.png" width="90%">
</p>

- Xử lý nghiệp vụ HR
- Tính toán lương & công
- Kết nối AI Engine

### 5.3. Frontend – XML / JavaScript
<p align="center">
  <img src="Screenshot 2026-01-22 220451.png" width="85%">
</p>

- Giao diện theo chuẩn Odoo
- UI thân thiện người dùng

### 5.4. AI & Machine Learning
- OpenCV
- TensorFlow
- Face Recognition
- Isolation Forest

### 5.5. Cơ sở dữ liệu
- PostgreSQL
- Lưu trữ HR, Attendance, Payroll

---

## 🚀 6. Cài đặt & triển khai

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python odoo-bin -c odoo.conf -d fitdnu_hr_ai
👉 Truy cập: http://localhost:8069

🏗️ 7. Kiến trúc hệ thống
Client: Web Browser

Backend: Odoo Server

AI Engine

Database: PostgreSQL

📦 8. Cấu trúc thư mục
.
├── README.md
├── N6Poster.pdf
├── Screenshot 2026-01-22 220451.png
├── Screenshot 2026-01-22 220559.png
├── Screenshot 2026-01-22 220630.png
├── aiotlab_logo.png
├── dnu_logo.png
├── fitdnu_logo.png
└── fitdnu_hr_ai.zip
📞 9. Liên hệ
Người thực hiện dự án

👤 Nguyễn Việt Ninh

🎓 Sinh viên Khoa Công nghệ Thông tin

🏫 Đại học Đại Nam

🧠 Phòng thí nghiệm AIoT – FIT DNU

Mục đích liên hệ

Trao đổi học thuật

Hợp tác nghiên cứu

Phát triển dự án

📝 10. Bản quyền
© 2026 AIoTLab – Khoa Công nghệ Thông tin – Đại học Đại Nam
Người thực hiện: Nguyễn Việt Ninh
All rights reserved.
