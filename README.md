# Tính Năng Nâng Cao (NC3 & NC4) - Lab A7

## 1. NC3 – PendingIntent cho Thông Báo
- **Mô tả:** Tích hợp `PendingIntent` vào thông báo. Khi bấm vào thông báo trên thanh trạng thái, ứng dụng sẽ tự động mở lại màn hình chính (`MainActivity`) và ẩn thông báo.

## 2. NC4 – Sơ Đồ Luồng Xin Quyền Chuẩn Google
- **Mô tả:** Tài liệu hóa quy trình xin quyền Runtime (Camera & Thông báo) bằng sơ đồ hoạt động (Activity Diagram) theo chuẩn 3 nhánh của Google:
  1. **Đã cấp quyền:** Chạy trực tiếp chức năng.
  2. **Cần giải thích:** Hiện hộp thoại giải thích lý do trước khi xin lại.
  3. **Lần đầu / Bị chặn:** Gọi xin quyền hệ thống hoặc hướng dẫn người dùng mở Cài đặt ứng dụng.
