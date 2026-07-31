---
title: "Nhật ký công việc Tuần 10 [Dự kiến]"
date: "2026-06-15"
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu Tuần 10:

- Tích hợp AWS S3 để lưu trữ an toàn các bản sao lưu hệ thống và xuất dữ liệu telemetry tĩnh.
- Cấu hình tên miền tùy chỉnh và định tuyến SSL/TLS bằng AWS Route 53.
- Hoàn thiện tài liệu kiến trúc hệ thống và chuẩn bị tài liệu báo cáo dự án (portfolio showcase).

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành |
| :--- | :-------- | :----------- | :-------------- |
| 1 | **Tích hợp S3:** Cấu hình chính sách AWS S3 bucket và kết nối dịch vụ FastAPI để tự động xuất dữ liệu telemetry và sao lưu cơ sở dữ liệu. | 10/08/2026 | 11/08/2026 |
| 3 | **Cấu hình DNS & Tên miền:** Liên kết tên miền tùy chỉnh qua AWS Route 53, cập nhật các khối cấu hình Nginx server blocks và hoàn tất quản lý chứng chỉ HTTPS. | 12/08/2026 | 13/08/2026 |
| 5 | **Kiểm tra Cuối & Hoàn thiện Tài liệu:** Thực hiện đánh giá hạ tầng end-to-end, dọn dẹp các cấu hình dịch vụ systemd và hoàn thiện bài trình bày portfolio dự án. | 14/08/2026 | 15/08/2026 |

### Kết quả đạt được trong Tuần 10:

- Tích hợp thành công AWS S3 bucket cho việc sao lưu dữ liệu lâu dài và xuất báo cáo tĩnh.
- Hoàn tất toàn bộ tài liệu kỹ thuật và phân tích kiến trúc chi tiết để phục vụ báo cáo/portfolio.

---

👉 **Kết quả:** Dự án đã hoàn thành thành công! Bảng điều khiển Giám sát & Điều khiển IoT Full-stack đã đi vào hoạt động thực tế, bảo mật và vận hành ổn định trên hạ tầng nguyên bản của AWS (EC2, RDS, S3, Route 53) được quản lý bởi Linux systemd.