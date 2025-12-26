# Website Giới Thiệu Các Ngôi Chùa Nổi Tiếng Tỉnh Trà Vinh

## Mô tả dự án
Website giới thiệu các ngôi chùa nổi tiếng của tỉnh Trà Vinh được xây dựng bằng React.js, nhằm quảng bá du lịch tâm linh và văn hóa Khmer Nam Bộ.

## Công nghệ sử dụng
- **Frontend**: React.js
- **Database**: MySQL
- **Styling**: CSS3

## Cấu trúc dự án
```
tra-vinh-pagoda-website/
├── src/
│   ├── components/     # Các component React
│   ├── pages/         # Các trang chính
│   ├── styles/        # File CSS
│   ├── data/          # Dữ liệu temples
│   └── context/       # React Context
├── public/            # File tĩnh
├── database/          # File SQL database
└── package.json       # Dependencies
```

## Cài đặt và chạy dự án

### Yêu cầu hệ thống
- Node.js (v14 trở lên)
- npm hoặc yarn
- MySQL Server

### Cài đặt
1. Clone repository:
```bash
git clone https://github.com/[username]/tra-vinh-pagoda-website.git
cd tra-vinh-pagoda-website
```

2. Cài đặt dependencies:
```bash
npm install
```

3. Thiết lập database:
- Import các file SQL trong thư mục `database/` theo thứ tự
- Cấu hình kết nối database trong ứng dụng

4. Chạy ứng dụng:
```bash
npm start
```

Ứng dụng sẽ chạy tại `http://localhost:3000`

## Tính năng chính
- Hiển thị danh sách các ngôi chùa nổi tiếng
- Chi tiết thông tin từng ngôi chùa
- Giao diện responsive
- Trang quản trị (Admin)
- Trang liên hệ

## Đóng góp
Mọi đóng góp đều được chào đón. Vui lòng tạo issue hoặc pull request.

## Giấy phép
Dự án này được phát hành dưới giấy phép MIT.