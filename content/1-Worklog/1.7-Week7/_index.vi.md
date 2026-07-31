---
title: "Nhật ký công việc Tuần 7"
date: "2026-07-27"
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu Tuần 7:

- Phát triển logic nghiệp vụ cốt lõi và các REST API CRUD cho quản lý thiết bị.
- Triển khai kiểm tra dữ liệu nghiêm ngặt bằng Pydantic schemas.
- Hoàn thành kiểm thử backend và tự động khởi tạo tài liệu OpenAPI/Swagger chi tiết.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành |
| :--- | :-------- | :----------- | :-------------- |
| 1 | **Phát triển CRUD API Thiết bị:** Triển khai các endpoint tạo mới, cập nhật cho nhật ký thiết bị IoT (`/api/v1/devices`). | 27/07/2026 | 27/07/2026 |
| 2 | **Endpoint Dữ liệu Telemetry:** Xây dựng các API tiếp nhận và truy vấn dữ liệu lịch sử cảm biến thiết bị cùng các tham số lọc query parameters. | 28/07/2026 | 29/07/2026 |
| 4 | **Kiểm thử với Postman & Tối ưu API:** Xác minh tất cả endpoint API, các trường hợp ngoại lệ (edge cases) và bảo mật JWT token bằng bộ test suite của Postman. | 30/07/2026 | 30/07/2026 |
| 5 | **Hoàn thiện tài liệu API:** Dọn dẹp các route tag của API, xuất tài liệu OpenAPI JSON / Swagger UI. | 31/07/2026 | 01/08/2026 |

### Kết quả đạt được trong Tuần 7:

- Phát triển hoàn chỉnh toàn bộ các API CRUD cho quản lý thiết bị và xử lý dữ liệu telemetry.
- Đảm bảo ứng dụng hoạt động ổn định nhờ cơ chế xác thực đầu vào tập trung.
- Hoàn thiện mã nguồn backend sẵn sàng cho môi trường production kèm tài liệu Swagger tương tác.

---

👉 **Kết quả:** Sau Tuần 7, dịch vụ FastAPI backend hoàn chỉnh đã được kiểm thử toàn diện và viết tài liệu đầy đủ, sẵn sàng cho việc tích hợp với React Frontend và triển khai lên EC2 ở Tuần 8.