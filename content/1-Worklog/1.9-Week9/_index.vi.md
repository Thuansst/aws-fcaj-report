---
title: "Nhật ký công việc Tuần 9 [Dự kiến]"
date: "2026-06-15"
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu Tuần 9:

- Khám phá Amazon S3 cho lưu trữ đối tượng trên đám mây và tải lên hình ảnh hồ sơ/thiết bị.
- Cấu hình định tuyến tên miền tùy chỉnh bằng AWS Route 53.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành |
| :--- | :-------- | :----------- | :-------------- |
| 1 | **Nền tảng AWS S3 & Cài đặt:** Tìm hiểu các lớp lưu trữ S3, chính sách bucket (bucket policies) và tạo một bucket public-read cho các tệp tĩnh tải lên. | 10/08/2026 | 10/08/2026 |
| 2 | **Tích hợp S3 với Backend:** Triển khai API tải tệp đơn giản trong FastAPI sử dụng thư viện SDK `boto3` để lưu trữ tài nguyên hình ảnh trên S3. | 11/08/2026 | 11/08/2026 |
| 3 | **Cấu hình Tên miền với Route 53:** Tạo Hosted Zone trên AWS Route 53 và cấu hình các bản ghi A cơ bản trỏ về máy chủ EC2. | 12/08/2026 | 12/08/2026 |
| 4 | **Liên kết Tài nguyên Giao diện:** Cập nhật React frontend để hiển thị các tài nguyên động và ảnh đại diện người dùng được truy xuất trực tiếp từ các đường dẫn URL S3. | 13/08/2026 | 13/08/2026 |
| 5 | **Kiểm thử & Xác minh:** Kiểm tra luồng tải ảnh lên và khả năng phân giải DNS xuyên suốt giữa frontend, backend và S3. | 14/08/2026 | 15/08/2026 |

### Kết quả đạt được trong Tuần 9:

- Tìm hiểu và tích hợp thành công lưu trữ đám mây Amazon S3 vào FastAPI.
- Cấu hình ánh xạ tên miền tùy chỉnh và quản lý DNS thành công bằng AWS Route 53.

---

👉 **Kết quả:** Sau Tuần 9, dự án đã có thêm các cải tiến đám mây thiết yếu (lưu trữ S3 & tên miền tùy chỉnh), giúp mở rộng trải nghiệm các dịch vụ AWS mà không làm tăng phức tạp kiến trúc hệ thống.