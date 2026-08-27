# QL-C-U-L-NG — Badminton Ops Prototype

Prototype giao diện quản lý CLB cầu lông, xây dựng dựa trên bộ ảnh tham chiếu được cung cấp.

## Mục tiêu thiết kế

- Màu chủ đạo: trắng, `#0074BD` (xanh dương), `#EF5627` (cam).
- Giữ tinh thần UI gọn, nhiều khoảng trắng, card/table rõ ràng.
- Luồng chính: Lịch → Điểm danh/Vote → Chi phí buổi → Chia tiền → Công nợ → Quỹ → Báo cáo.
- Có landing page “cách hoạt động” và dashboard quản trị mô phỏng.
- Responsive cho desktop và mobile.

## Chạy local

Không cần cài package. Dùng một web server tĩnh, ví dụ `python -m http.server 8080`, rồi mở `http://localhost:8080`.

## Phạm vi hiện tại

Đây là prototype frontend dùng dữ liệu demo. Các thao tác như thêm giao dịch, chốt buổi, điểm danh và tìm thành viên được mô phỏng trên trình duyệt.

Bước tiếp theo có thể nối backend/database, xác thực người dùng, phân quyền CLB, API giao dịch và triển khai production.
