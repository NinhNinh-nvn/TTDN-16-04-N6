# 🎓 KHOA CÔNG NGHỆ THÔNG TIN – ĐẠI HỌC ĐẠI NAM  
## 🚀 FITDNU HR AI – HỆ THỐNG QUẢN LÝ NHÂN SỰ TÍCH HỢP AI

<p align="center">
  <img src="dnu_logo.png" alt="Dai Nam University" height="80"/>
  <img src="fitdnu_logo.png" alt="FIT DNU" height="80"/>
  <img src="aiotlab_logo.png" alt="AIoTLab" height="80"/>
</p>

<p align="center">
📄 <strong>Poster dự án:</strong> <a href="N6Poster.pdf">Click để xem Poster FITDNU HR AI</a>
</p>

---

## 📖 1. Giới thiệu

**FITDNU HR AI** là hệ thống **Quản lý Nhân sự (HR Management System)** được xây dựng trên nền tảng **ERP Odoo**, tích hợp **Trí tuệ Nhân tạo (AI)** để:

- Tự động hóa quy trình chấm công
- Phát hiện gian lận thông minh
- Tính lương tự động theo luật Việt Nam
- Hỗ trợ báo cáo trực quan

Dự án được phát triển tại **Phòng thí nghiệm AIoT – Khoa Công nghệ Thông tin – Đại học Đại Nam** và phù hợp cho:

- 🎓 Học phần Thực tập / Thực doanh nghiệp
- 🧠 Nghiên cứu ứng dụng AI trong ERP
- 🏢 Triển khai quản lý nhân sự mẫu cho doanh nghiệp

---

## 🖼️ 2. Giao diện & Hình ảnh phần mềm

### 🔐 2.1. Giao diện đăng nhập
<p align="center">
  <img src="Screenshot 2026-01-22 220451.png" width="85%"/>
</p>
- Đăng nhập vào hệ thống
- Phân quyền theo vai trò

---

### 📊 2.2. Dashboard quản trị nhân sự
<p align="center">
  <img src="Screenshot 2026-01-22 220559.png" width="95%"/>
</p>
- Hồ sơ nhân sự
- Tỷ lệ đi làm đúng giờ
- Cảnh báo AI realtime

---

### ⏱️ 2.3. Dashboard chấm công & AI
<p align="center">
  <img src="Screenshot 2026-01-22 220630.png" width="95%"/>
</p>
- Theo dõi chấm công trong ngày
- Phát hiện bất thường
- Phê duyệt công

---

## ⭐ 3. Chức năng chính

### 3.1. Chấm công thông minh
- Nhận diện khuôn mặt bằng AI
- Xác thực vị trí GPS
- Chống gian lận chấm công

### 3.2. Phát hiện gian lận
- Phân tích hành vi chấm công
- Phát hiện:
  - Giờ làm bất thường
  - Sai vị trí
  - Trùng thời gian
- Chấm điểm rủi ro (Risk Score)

### 3.3. Tính lương tự động
- Tính theo ngày công & OT
- Áp dụng phụ cấp, BHXH, thuế TNCN
- Xuất bảng lương & payslip

### 3.4. Quản lý nhân sự
- Hồ sơ nhân viên
- Phòng ban
- Hợp đồng lao động
- Lịch sử công tác

---

## 🛠️ 4. Công nghệ sử dụng

### 4.1. Nền tảng ERP – Odoo 15.0
- ERP mã nguồn mở  
- Kiến trúc module HR  

### 4.2. Backend – Python
- Xử lý nghiệp vụ
- Tính toán chấm công & lương

### 4.3. Frontend – XML / JavaScript
- Giao diện UI theo chuẩn Odoo

### 4.4. AI & Machine Learning
- OpenCV
- TensorFlow
- Face Recognition
- Isolation Forest

### 4.5. Cơ sở dữ liệu – PostgreSQL
- Lưu trữ dữ liệu nhân sự & bảng lương

---

## 🚀 5. Cài đặt & Triển khai

```bash
git clone https://github.com/NinhNinh-nvn/TTDN-16-04-N6.git
cd TTDN-16-04-N6
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python odoo-bin -c odoo.conf -d fitdnu_hr_ai
👉 Truy cập: http://localhost:8069
## 🏗️ 6. Kiến trúc hệ thống

Client: Web Browser

Backend: Odoo Server

AI Engine

Database: PostgreSQL
## 📦 7. Cấu trúc thư mục
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

📞 8. Liên hệ

Người thực hiện dự án

👤 Nguyễn Việt Ninh

🎓 Sinh viên Khoa Công nghệ Thông tin

🏫 Đại học Đại Nam
