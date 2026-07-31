---
title: "Nhật ký công việc Tuần 3"
date: "2026-06-29"
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu Tuần 3:

- Hiểu rõ các thành phần mạng cốt lõi của Amazon VPC và sơ đồ kiến trúc đám mây.
- Thực hành bài Lab: Thiết kế và tự tay khởi tạo một Custom VPC từ đầu.
- Cấu hình subnets, bảng tuyến đường (Route Tables), Internet Gateway và các quy tắc bảo mật mạng.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành |
| :--- | :-------- | :----------- | :-------------- |
| 1 | **Lý thuyết VPC & Quy hoạch CIDR:** Học cách tính toán dải địa chỉ IPv4 CIDR, kiến trúc VPC, Subnet Public vs. Private và các Availability Zone. | 29/06/2026 | 29/06/2026 |
| 2 | **Lab Tạo Custom VPC:** Tạo một Custom VPC (`10.0.0.0/16`) cùng với các public và private subnet phân bổ trên nhiều AZ khác nhau. | 30/06/2026 | 30/06/2026 |
| 3 | **Định tuyến & Internet Gateway:** Gán Internet Gateway (IGW) và cấu hình Route Tables để cho phép các public subnet truy cập Internet. | 01/07/2026 | 01/07/2026 |
| 4 | **Quy tắc Bảo mật Mạng:** Cấu hình Security Groups (stateful) và Network ACLs (stateless) để kiểm soát lưu lượng mạng chiều vào/ra. | 02/07/2026 | 02/07/2026 |
| 5 | **Kiểm tra & Xác minh VPC:** Triển khai tài nguyên thử nghiệm tạm thời bên trong các subnet để kiểm tra kết nối và tính cô lập của mạng. | 03/07/2026 | 04/07/2026 |

### Kết quả đạt được trong Tuần 3:

- Xây dựng thành công một mạng ảo cô lập tùy chỉnh (VPC) hoàn chỉnh từ đầu.
- Cấu hình định tuyến Internet chuẩn xác thông qua Internet Gateway và Route Tables.
- Triển khai mô hình phòng thủ mạng nhiều lớp sử dụng Security Groups và NACLs tùy chỉnh.

---

👉 **Kết quả:** Sau Tuần 3, hạ tầng mạng Custom VPC an toàn đã đi vào hoạt động ổn định, sẵn sàng làm môi trường mạng để khởi tạo các máy chủ EC2 ở Tuần 4.