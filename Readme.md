GIỚI THIỆU ĐỀ TÀI
----
Hiện nay hình thức xem phim chiếu rạp không còn xa lạ với chúng ta, nó không chỉ đơn thuần để giải trí, giảm bớt áp lực, mà còn mang lại những trải nghiệm, kích thích trí tưởng tượng và tạo ra những cảm xúc mạnh mẽ.
Vì lẽ đó nhu cầu xem phim chiếu rạp của con người ngày càng tăng, nó dần trở thành một phần không thể thiếu trong cuộc sống, nắm bắt được điều đó đã có rất nhiều cụm rạp được xây dựng nằm rải rác khắp Việt Nam nhằm đáp ứng nhu cầu của khách hàng. 
Để vừa giúp quản trị viên trong việc thống kê, quản lý được số lượng cụm rạp lớn vừa tạo sự thuận tiện cho khách hàng khi giờ đây khách hàng chỉ cần ngồi tại nhà vẫn có thể chọn suất chiếu và mua vé mà không cần phải đến trực tiếp tại rạp  thì nhóm em quyết định thực hiện việc thiết kế, xây dựng website quản lý hệ thống rạp chiếu phim dành cho quản trị viên lẫn khách hàng.



Sơ đồ cấu trúc (Class Diagram)
----
![image](https://github.com/user-attachments/assets/ff0fffd4-c38c-4f59-9c92-3a58d57a87ec)

----
Sơ đồ chức năng
---
![image](https://github.com/user-attachments/assets/8f857da5-4804-4760-a087-22de09852fef)
----
Sơ đồ Use Case
----
![image](https://github.com/user-attachments/assets/b298a0b3-a13e-499f-a650-d901bd72da50)


# 🎬 Website Quản Lý Hệ Thống Rạp Chiếu Phim

## 🧾 Mục Đích Dự Án

Dự án được thực hiện nhằm xây dựng một **website quản lý hệ thống rạp chiếu phim** phục vụ **cả quản trị viên và khách hàng**, với mục tiêu:

- Giúp khách hàng dễ dàng **đặt vé xem phim trực tuyến**, lựa chọn ghế, nhận mã khuyến mãi, mua combo ăn uống, v.v.
- Hỗ trợ quản trị viên **quản lý phim, phòng chiếu, lịch chiếu, vé, nhân viên, doanh thu** và nhiều nghiệp vụ khác.
- Tích hợp các chức năng thực tiễn như gửi mail, xác thực OTP, chuyển đổi ngôn ngữ, thống kê dữ liệu...

---

## 👥 Thành Viên & Nhiệm Vụ

| MSSV       | Họ và Tên           |
|------------|---------------------|
| 21012097   | Lê Quang Trường     | 



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
Giao điện người dùng
---
![image](https://github.com/user-attachments/assets/166aca1b-6a15-4533-8f41-cdee52f628fd)
---
Giao điện ADmin
---
![image](https://github.com/user-attachments/assets/e7fb996b-b51c-4763-9412-462658121139)



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
