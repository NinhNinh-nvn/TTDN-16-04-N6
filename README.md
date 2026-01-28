🎓 KHOA CÔNG NGHỆ THÔNG TIN – ĐẠI HỌC ĐẠI NAM
🚀 FITDNU HR AI – HỆ THỐNG QUẢN LÝ NHÂN SỰ TÍCH HỢP AI
<p align="center"> <img src="dnu_logo.png" alt="Dai Nam University" height="80"/> <img src="fitdnu_logo.png" alt="FIT DNU" height="80"/> <img src="aiotlab_logo.png" alt="AIoTLab" height="80"/> </p>

📄 Poster dự án: Xem Poster FITDNU HR AI

📖 1. Giới thiệu

FITDNU HR AI là hệ thống Quản lý Nhân sự (Human Resource Management) được phát triển trên nền tảng ERP Odoo, tích hợp Trí tuệ Nhân tạo (AI) nhằm tự động hóa và nâng cao hiệu quả quản lý nhân sự trong doanh nghiệp.

Dự án được triển khai tại Phòng thí nghiệm AIoT – Khoa Công nghệ Thông tin – Đại học Đại Nam, phục vụ:

Học phần Thực tập / Thực doanh nghiệp

Nghiên cứu AI ứng dụng trong hệ thống ERP

Mô phỏng và thử nghiệm hệ thống HR cho doanh nghiệp thực tế

🧾 2. Poster dự án
<p align="center"> <a href="N6Poster.pdf"> <strong>📄 Click để xem Poster FITDNU HR AI</strong> </a> </p>

Poster thể hiện:

Tổng quan hệ thống

Kiến trúc giải pháp

Công nghệ sử dụng

Các chức năng chính

Minh họa giao diện phần mềm

🖼️ 3. Giao diện & Hình ảnh phần mềm
🔐 3.1. Giao diện đăng nhập hệ thống
<p align="center"> <img src="Screenshot 2026-01-22 220451.png" width="85%"> </p>

Đăng nhập hệ thống ERP HR

Phân quyền theo vai trò: Admin / HR / Quản lý / Nhân viên

Kiểm soát truy cập dữ liệu nhân sự

📊 3.2. Dashboard tổng quan quản trị nhân sự
<p align="center"> <img src="Screenshot 2026-01-22 220559.png" width="95%"> </p>

Thống kê tổng số nhân viên

Tỷ lệ đi làm đúng giờ

Cảnh báo gian lận từ AI

Biểu đồ dữ liệu theo thời gian thực

⏱️ 3.3. Dashboard chấm công & giám sát AI
<p align="center"> <img src="Screenshot 2026-01-22 220630.png" width="95%"> </p>

Theo dõi trạng thái chấm công trong ngày

Phát hiện hành vi bất thường

Hỗ trợ phê duyệt tự động / thủ công

⭐ 4. Chức năng chính của hệ thống
4.1. Chấm công thông minh

Nhận diện khuôn mặt bằng AI

Chống chấm công hộ, ảnh giả, video giả

Xác thực vị trí GPS

Lưu trữ dữ liệu realtime

4.2. Phát hiện gian lận bằng AI

Phân tích hành vi chấm công

Phát hiện các bất thường:

Giờ làm không hợp lý

Trùng thời gian

Sai vị trí

Chấm điểm rủi ro (Risk Score)

4.3. Tính lương tự động

Tính lương theo ngày công & tăng ca

Áp dụng phụ cấp, bảo hiểm, thuế TNCN

Xuất bảng lương & payslip

4.4. Quản lý nhân sự

Hồ sơ nhân viên chi tiết

Quản lý phòng ban

Quản lý hợp đồng lao động

Theo dõi lịch sử công tác

🛠️ 5. Công nghệ sử dụng (có minh họa phần mềm)
5.1. Nền tảng ERP – Odoo 15.0
<p align="center"> <img src="Screenshot 2026-01-22 220559.png" width="90%"> </p>

ERP mã nguồn mở

Xây dựng hệ thống HR theo mô hình module

5.2. Backend – Python
<p align="center"> <img src="Screenshot 2026-01-22 220630.png" width="90%"> </p>

Xử lý nghiệp vụ HR

Tính toán chấm công & lương

Kết nối AI Engine

5.3. Frontend – XML / JavaScript
<p align="center"> <img src="Screenshot 2026-01-22 220451.png" width="85%"> </p>

Xây dựng giao diện người dùng

Tuân thủ chuẩn UI của Odoo ERP

5.4. AI & Machine Learning

OpenCV

TensorFlow

Face Recognition

Isolation Forest

Ứng dụng trong chấm công & phát hiện gian lận.

5.5. Cơ sở dữ liệu

PostgreSQL

Lưu trữ dữ liệu nhân sự, chấm công, bảng lương

🚀 6. Cài đặt & triển khai (tóm tắt)
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

Mục đích liên hệ:

Trao đổi học thuật

Hợp tác nghiên cứu

Phát triển & mở rộng dự án

📝 10. Bản quyền
© 2026 AIoTLab – Khoa Công nghệ Thông tin – Đại học Đại Nam
Người thực hiện: Nguyễn Việt Ninh
All rights reserved.
