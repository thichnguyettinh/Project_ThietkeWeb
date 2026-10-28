# Tiệm bánh 3N2T — Bánh Ngọt Ngon

Website giới thiệu bánh ngọt và phụ kiện sinh nhật, được xây dựng cho dự án học phần Thiết kế Web.

## Thông tin học phần
* **Học phần:** Thiết kế Web
* **Khoa:** Công nghệ Thông tin — Trường Đại học Sư phạm TP. Hồ Chí Minh
* **Mã lớp:** 2411COMP180201
* **Giảng viên hướng dẫn:** ThS. Lương Trần Hy Hiến

## Tính năng
* Hiển thị danh sách sản phẩm gồm bánh ngọt và phụ kiện.
* Tìm kiếm sản phẩm theo tên.
* Xem chi tiết sản phẩm, gồm hình ảnh, mô tả và giá.
* Thêm sản phẩm vào giỏ hàng, thay đổi số lượng, xóa sản phẩm và xem tổng tiền.
* Giao diện đăng nhập quản trị và chỉnh sửa thông tin sản phẩm ở phía trình duyệt.
* Các khu vực giới thiệu và liên hệ.

> **Lưu ý:** Đây là website tĩnh minh họa giao diện phía người dùng. Dữ liệu giỏ hàng và thao tác quản trị chỉ hoạt động trong trình duyệt hiện tại; dự án chưa kết nối máy chủ, cơ sở dữ liệu hay cổng thanh toán. Đăng nhập quản trị không phải cơ chế bảo mật thực tế.

## Cách chạy
Không cần cài đặt thư viện hoặc build dự án:
1. Mở `index.html` trực tiếp bằng trình duyệt; hoặc
2. Mở thư mục dự án bằng Visual Studio Code và chạy `index.html` với tiện ích Live Server. 

Website tải phông chữ Lora từ Google Fonts, vì vậy cần kết nối Internet để hiển thị phông chữ này.

## Cấu trúc dự án
```text
project_thietkeweb/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    ├── images/
    │   ├── logo, biểu tượng và ảnh giao diện
    │   ├── ảnh bánh (cake-*)
    │   └── ảnh phụ kiện (accessory-*)
    └── js/
        └── script.js
