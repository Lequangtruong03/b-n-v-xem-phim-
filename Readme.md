![image](https://github.com/user-attachments/assets/b14bb59c-9b59-4a17-b17a-75e4c4e00f37)

# 🎬 Website Quản Lý Hệ Thống Rạp Chiếu Phim

## 🧾 Mục Đích Dự Án

Dự án được thực hiện nhằm xây dựng một **website quản lý hệ thống rạp chiếu phim** phục vụ **cả quản trị viên và khách hàng**, với mục tiêu:

- Giúp khách hàng dễ dàng **đặt vé xem phim trực tuyến**, lựa chọn ghế, nhận mã khuyến mãi, mua combo ăn uống, v.v.
- Hỗ trợ quản trị viên **quản lý phim, phòng chiếu, lịch chiếu, vé, nhân viên, doanh thu** và nhiều nghiệp vụ khác.
- Tích hợp các chức năng thực tiễn như gửi mail, xác thực OTP, chuyển đổi ngôn ngữ, thống kê dữ liệu...

---

## 👥 Thành Viên & Nhiệm Vụ

| MSSV       | Họ và Tên           | Nhiệm Vụ Chính                                                                 |
|------------|---------------------|--------------------------------------------------------------------------------|
| 23010654   | Bùi Hoàng Huy       | - Phân tích yêu cầu đề tài, chức năng hệ thống, nghiên cứu mô hình dữ liệu    |
| 21012097   | Lê Quang Trường     | - Xây dựng Model, Migration, Controller trong Laravel, xử lý logic nghiệp vụ  |
| 23010178   | Nguyễn Huy Hiệp     | - Thiết kế giao diện người dùng với Blade Template, giao diện đặt vé, lịch    |

🔄 **Cả nhóm cùng thực hiện:**
- Tích hợp hệ thống (Model – View – Controller)
- Kiểm thử chức năng (đặt vé, quản lý phim, lịch chiếu, người dùng...)
- Viết báo cáo, tạo slide và file README

---

## ⚙️ Công Nghệ Sử Dụng

- **Ngôn ngữ chính**: PHP (Laravel Framework)
- **Giao diện người dùng**: Blade Template (Laravel)
- **Cơ sở dữ liệu**: MySQL
- **Công cụ hỗ trợ**: Composer, Git, VSCode, Figma

---

## 🧩 Các Chức Năng Chính

- 📅 **Đặt vé trực tuyến**: Chọn phim, rạp, phòng, ghế, combo, thanh toán online
- 🎬 **Quản lý phim, rạp, phòng chiếu, lịch chiếu**
- 🪑 **Quản lý ghế theo loại (thường, VIP, couple)**
- 🧾 **Tạo và quản lý mã khuyến mãi, combo thức ăn**
- 📈 **Thống kê doanh thu theo phim, rạp, thời gian, loại vé**
- 👤 **Quản lý tài khoản người dùng và nhân viên**
- 🔐 **Xác thực OTP, gửi email đặt vé, khôi phục mật khẩu**
- 🌐 **Chuyển đổi ngôn ngữ (Tiếng Việt / English)**

---

## 🚀 Hướng Dẫn Cài Đặt

```bash
git clone https://github.com/your-username/ten-du-an.git
cd ten-du-an
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
