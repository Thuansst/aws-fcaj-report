---
title: "Nhật ký công việc Tuần 4"
date: "2026-07-06"
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu Tuần 4:

- Hiểu rõ các thành phần cốt lõi của Amazon EC2, các loại instance và mô hình lưu trữ.
- Thực hành bài Lab: Khởi tạo và cấu hình một máy chủ EC2 Ubuntu bên trong Custom VPC.
- Cấu hình truy cập SSH, Elastic IP và Security Groups để sẵn sàng làm server hosting.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành |
| :--- | :-------- | :----------- | :-------------- |
| 1 | **Nền tảng EC2 & Chọn AMI:** Tìm hiểu các dòng EC2 instance, mô hình chi phí, ổ đĩa EBS và lựa chọn Ubuntu 24.04 LTS AMI. | 06/07/2026 | 06/07/2026 |
| 2 | **Lab Khởi tạo EC2:** Triển khai một instance `t3.micro` bên trong public subnet của Custom VPC với SSH Key Pair tùy chỉnh. | 07/07/2026 | 07/07/2026 |
| 3 | **Elastic IP & Security Groups:** Cấp phát một Elastic IP (EIP) cho instance và cấu hình quy tắc SG cho SSH (cổng 22), HTTP (cổng 80) và FastAPI (cổng 8000). | 08/07/2026 | 08/07/2026 |
| 4 | **Kết nối Server & Cấu hình Môi trường:** Kết nối SSH vào máy chủ EC2 từ terminal cục bộ. | 09/07/2026 | 09/07/2026 |
| 5 | **Kiểm tra & Xác minh Instance:** Chạy một HTTP server cơ bản để kiểm tra kết nối từ bên ngoài và các quy tắc Security Group. | 10/07/2026 | 11/07/2026 |

### Kết quả đạt được trong Tuần 4:

- Khởi tạo và cấu hình thành công máy chủ EC2 nằm trong Custom VPC.
- Thiết lập quản trị SSH an toàn bằng Key Pair và cấu hình định tuyến public cố định với Elastic IP.
- Chuẩn bị sẵn sàng môi trường Linux và các quy tắc mạng để phục vụ cho các dịch vụ backend.

---

👉 **Kết quả:** Sau Tuần 4, hạ tầng máy chủ đám mây (EC2) đã hoạt động ổn định và có thể truy cập được, tạo tiền đề để thiết kế schema và cài đặt cơ sở dữ liệu ở Tuần 5.