# 🍔 FastFood Web

Web đặt đồ ăn nhanh. Frontend ReactJS + Backend Laravel.

## Tech Stack

- ⚛️ Frontend: ReactJS, JavaScript, SCSS
- 🐘 Backend: Laravel (PHP), MySQL
- 🔐 Auth: JWT

## Cấu trúc project

```
FastFoodWeb/
├── react/          # frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── assets/
└── laravel/        # backend REST API
    ├── app/
    ├── routes/
    └── database/
```

## Cài đặt

**Yêu cầu:** Node.js >= 16, PHP >= 8.0, Composer, MySQL

**Backend**

```bash
cd laravel
composer install
cp .env.example .env

# Sửa .env

php artisan key:generate
php artisan migrate --seed
php artisan serve
# Chạy tại http://localhost:8000
```

**Frontend**

```bash
cd react
npm install
npm start
# Chạy tại http://localhost:3000
```

## Tính năng

**Khách hàng**
- Xem menu, tìm kiếm và lọc món ăn
- Thêm vào giỏ hàng, đặt món
- Thanh toán qua VietQR
- Đăng ký / Đăng nhập tài khoản
- Xem lịch sử đơn hàng

**Admin**
- Quản lý menu, danh mục, giá
- Xử lý đơn hàng (xác nhận, huỷ, hoàn thành)
- Quản lý tài khoản người dùng
- Thống kê doanh thu

## Liên hệ

Nguyễn Duy Hiện - ndhhkb@gmail.com