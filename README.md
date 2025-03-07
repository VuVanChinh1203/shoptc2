# 🐶 Shop Thúc Cưng Laravel 🐶

## 📚 Giới thiệu
Shop Thú Cưng Laravel là một website thương mại điện tử được xây dựng bằng **Laravel 10** và **MySQL**, giúp quản lý và bán các sản phẩm thú cưng một cách chuyên nghiệp. Hệ thống hỗ trợ **đăng ký, mua sắm, thanh toán online qua VNPAY**, giúp nâng cao trải nghiệm người dùng.

## 💪 Chức năng nổi bật
### 👤 Người dùng (User)
- Đăng ký, đăng nhập tài khoản.
- Tìm kiếm, lọc và xem chi tiết sản phẩm.
- Quản lý giỏ hàng: thêm, xóa, cập nhật số lượng sản phẩm.
- Thanh toán đơn hàng bằng **COD** hoặc **VNPAY**.
- Theo dõi trạng thái đơn hàng và lịch sử mua sắm.

### 💻 Quản trị viên (Admin)
- Đăng nhập trang quản trị.
- Quản lý sản phẩm: thêm, sửa, xóa và cập nhật thông tin.
- Quản lý khách hàng, đơn hàng và trạng thái giao dịch.
- Tổng quan hệ thống: xem báo cáo, thống kê doanh thu theo thời gian.

## 🎯 Công nghệ sử dụng
- **Backend:** Laravel 10, PHP, MySQL.
- **Frontend:** Blade Template, Bootstrap, JavaScript.
- **Thanh toán:** API VNPAY.
- **Authentication:** Laravel Auth, Middleware.
- **Security:** Bcrypt password hashing, CSRF Protection.

## ⚙️ Các thuật toán chính
- **Quản lý giỏ hàng:** Sử dụng session hoặc database để lưu trạng thái giỏ hàng, xử lý thêm, xóa, cập nhật sản phẩm.
- **Phân trang sản phẩm:** Laravel `paginate()` giúp chia nhỏ danh sách sản phẩm để tối ưu trải nghiệm người dùng.
- **Tìm kiếm sản phẩm:** Dùng SQL `LIKE` hoặc **Full-text search** để hiển thị kết quả chính xác hơn.
- **Tích hợp thanh toán VNPAY:** Gửi yêu cầu thanh toán qua API VNPAY, xử lý callback để cập nhật trạng thái giao dịch.
- **Bảo mật hệ thống:** Middleware kiểm soát quyền truy cập, mã hóa mật khẩu bằng **Bcrypt**, bảo vệ chống **CSRF Attacks**.

## ♻️ Cài đặt và chạy dự án
```bash
# Cài đặt Laravel và các package
tcomposer install

# Cấu hình file môi trường
cp .env.example .env
php artisan key:generate

# Thiết lập database
php artisan migrate --seed

# Chạy server Laravel
php artisan serve

```
<p align="center">
    <img src="imgrm/anh1.png" alt="Log in screen" >
    <img src="imgrm/anh2.png" alt="Forgot password screen" >
    <img src="imgrm/anh3.png" alt="Email password reset link screen" >
    <img src="imgrm/anh4.png" alt="Log in screen" >
    <img src="imgrm/anh5.png" alt="Log in screen" >
    <img src="imgrm/anh6.png" alt="Log in screen" >
    <img src="imgrm/anh7.png" alt="Log in screen" >
    <img src="imgrm/anh8.png" alt="Log in screen" >
    <img src="imgrm/anh9.png" alt="Log in screen" >
</p>


## 🌐 Link quan trọng

- **Demo:** [https://drive.google.com/file/d/1aIMIKDgJb2L9dOgjQtwKujcqcERMKd8f/view?usp=sharing]
- **Website public:** [https://1e4e-2405-4802-1bf2-4260-d87-2ab-5cc1-7064.ngrok-free.app]

## 👨‍🎓 Tác giả
- **Admin:** [Vu VAN CHINH - 2201028922010289]
- **Liên hệ:** [badaokk5722@gmail.com]

