<p align="center">
<b>KHOA CÔNG NGHỆ THÔNG TIN – ĐẠI HỌC ĐẠI NAM</b><br/>
🚀 FITDNU HR AI – HỆ THỐNG QUẢN LÝ NHÂN SỰ TÍCH HỢP AI
</p>

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

**FITDNU HR AI** là hệ thống **Quản lý Nhân sự (HR Management System)** được xây dựng trên nền tảng **ERP Odoo**, tích hợp **Trí tuệ Nhân tạo (AI)** nhằm:

* Tự động hóa quy trình chấm công
* Phát hiện gian lận thông minh
* Tính lương tự động theo luật Việt Nam
* Hỗ trợ báo cáo trực quan, realtime

Dự án được phát triển tại **Phòng thí nghiệm AIoT – Khoa Công nghệ Thông tin – Đại học Đại Nam**, phù hợp cho:

* 🎓 Học phần Thực tập / Thực doanh nghiệp
* 🧠 Nghiên cứu ứng dụng AI trong hệ thống ERP
* 🏢 Triển khai mô hình quản lý nhân sự cho doanh nghiệp vừa và nhỏ

---

## 🖼️ 2. Giao diện & Hình ảnh phần mềm

### 🔐 2.1. Giao diện đăng nhập

<p align="center">
  <img src="Screenshot 2026-01-22 220451.png" width="85%"/>
</p>

* Đăng nhập hệ thống
* Phân quyền theo vai trò (Admin / HR / Nhân viên)

---

### 📊 2.2. Dashboard quản trị nhân sự

<p align="center">
  <img src="Screenshot 2026-01-22 220559.png" width="95%"/>
</p>

* Quản lý hồ sơ nhân sự
* Thống kê tỷ lệ đi làm đúng giờ
* Cảnh báo AI theo thời gian thực

---

### ⏱️ 2.3. Dashboard chấm công & AI

<p align="center">
  <img src="Screenshot 2026-01-22 220630.png" width="95%"/>
</p>

* Theo dõi chấm công trong ngày
* Phát hiện bất thường bằng AI
* Phê duyệt và điều chỉnh công

---

## ⭐ 3. Chức năng chính

### 3.1. Chấm công thông minh

* Nhận diện khuôn mặt bằng AI
* Xác thực vị trí GPS
* Chống gian lận chấm công

### 3.2. Phát hiện gian lận

* Phân tích hành vi chấm công
* Phát hiện các trường hợp:

  * Giờ làm việc bất thường
  * Sai vị trí chấm công
  * Trùng lặp hoặc bất hợp lý về thời gian
* Chấm điểm rủi ro (Risk Score) cho từng nhân viên

### 3.3. Tính lương tự động

* Tính lương theo ngày công & tăng ca (OT)
* Áp dụng phụ cấp, BHXH, thuế TNCN theo quy định Việt Nam
* Xuất bảng lương và payslip

### 3.4. Quản lý nhân sự

* Hồ sơ nhân viên
* Phòng ban & chức vụ
* Hợp đồng lao động
* Lịch sử công tác

---

## 🛠️ 4. Công nghệ sử dụng

### 4.1. Nền tảng ERP – Odoo 15.0

* ERP mã nguồn mở
* Kiến trúc module chuyên biệt cho HR

### 4.2. Backend – Python

* Xử lý nghiệp vụ HR
* Tính toán chấm công và tiền lương

### 4.3. Frontend – XML / JavaScript

* Giao diện theo chuẩn Odoo
* Dashboard trực quan

### 4.4. AI & Machine Learning

* OpenCV
* TensorFlow
* Face Recognition
* Isolation Forest (phát hiện bất thường)

### 4.5. Cơ sở dữ liệu – PostgreSQL

* Lưu trữ dữ liệu nhân sự, chấm công và bảng lương

---

## 🚀 5. Cài đặt & Triển khai

```bash
git clone https://github.com/NinhNinh-nvn/TTDN-16-04-N6.git
cd TTDN-16-04-N6
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python odoo-bin -c odoo.conf -d fitdnu_hr_ai
```

👉 Truy cập hệ thống tại: **[http://localhost:8069](http://localhost:8069)**

---

## 🏗️ 6. Kiến trúc hệ thống

* **Client:** Web Browser
* **Backend:** Odoo Server (Python)
* **AI Engine:** Xử lý nhận diện & phát hiện gian lận
* **Database:** PostgreSQL

---

## 📦 7. Cấu trúc thư mục

```text
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
```

---

## 📞 8. Liên hệ

**Người thực hiện dự án**

👤 **Nguyễn Việt Ninh**
🎓 Sinh viên Khoa Công nghệ Thông tin
🏫 **Đại học Đại Nam**
