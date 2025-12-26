# Hướng Dẫn Cài Đặt Chi Tiết

## Yêu cầu hệ thống
- Node.js phiên bản 14.0.0 trở lên
- npm phiên bản 6.0.0 trở lên
- MySQL Server 8.0 trở lên

## Bước 1: Cài đặt Node.js
1. Tải Node.js từ https://nodejs.org/
2. Cài đặt theo hướng dẫn
3. Kiểm tra cài đặt:
```bash
node --version
npm --version
```

## Bước 2: Cài đặt MySQL
1. Tải MySQL từ https://dev.mysql.com/downloads/
2. Cài đặt và tạo user root
3. Khởi động MySQL service

## Bước 3: Thiết lập Database
1. Mở MySQL Workbench hoặc command line
2. Chạy các file SQL theo thứ tự:
   - `00_RESET_DATABASE.sql`
   - `01_CREATE_DATABASE.sql`
   - `02_CREATE_VIEWS.sql`
   - `03_CREATE_PROCEDURES.sql`
   - `TRA_VINH_PAGODA.sql`

## Bước 4: Cài đặt dự án
1. Clone repository
2. Chạy `npm install`
3. Cấu hình kết nối database (nếu cần)
4. Chạy `npm start`

## Khắc phục sự cố
- Nếu gặp lỗi port 3000 đã được sử dụng, thay đổi port trong package.json
- Nếu không kết nối được database, kiểm tra thông tin kết nối
- Nếu thiếu dependencies, chạy `npm install` lại