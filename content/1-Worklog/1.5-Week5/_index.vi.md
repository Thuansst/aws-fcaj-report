---
title: "Nhật ký công việc Tuần 5"
date: "2026-07-13"
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu Tuần 5:

- Thiết kế Sơ đồ quan thực thể (ERD) chuẩn hóa cho ứng dụng.
- Khởi tạo và cấu hình môi trường cơ sở dữ liệu PostgreSQL.
- Viết các kịch bản (script) khởi tạo và kiểm thử schema cơ sở dữ liệu.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành |
| :--- | :-------- | :----------- | :-------------- |
| 1 | **Phân tích Yêu cầu & Phác thảo ERD:** Xác định các thực thể cốt lõi của ứng dụng (Thết bị/Devices, Nhật ký thiết bị/Device Logs, Lệnh điều khiển/Commands) và phác thảo các mối quan hệ ERD ban đầu. | 13/07/2026 | 13/07/2026 |
| 2 | **Tối ưu hóa Schema Cơ sở dữ liệu:** Xác định Khóa chính (Primary Key), Khóa ngoại (Foreign Key) và đánh chỉ mục (index) cho các trường được truy vấn thường xuyên. | 14/07/2026 | 15/07/2026 |
| 4 | **Viết Script SQL & Thiết lập Migration:** Viết các script khởi tạo SQL (`schema`) để tạo bảng và các ràng buộc dữ liệu. | 16/07/2026 | 16/07/2026 |
| 5 | **Xác minh & Bảo mật Cơ sở Dữ liệu:** Cấu hình các tham số kết nối cơ sở dữ liệu, thiết lập thông tin xác thực an toàn và chạy các truy vấn mẫu để kiểm tra. | 17/07/2026 | 18/07/2026 |

### Kết quả đạt được trong Tuần 5:

- Thiết kế và hoàn thiện thành công Sơ đồ ERD cơ sở dữ liệu quan hệ.
- Xác minh tính toàn vẹn của schema và nạp dữ liệu mẫu ban đầu (seed data) để chuẩn bị tích hợp API backend.

---

👉 **Kết quả:** Sau Tuần 5, schema cơ sở dữ liệu cốt lõi và môi trường PostgreSQL đã được thiết lập hoàn chỉnh, cung cấp tầng lưu trữ dữ liệu tin cậy cho việc phát triển FastAPI backend ở Tuần 6.