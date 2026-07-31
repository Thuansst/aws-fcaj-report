---
title: "Nhật ký công việc Tuần 2"
date: "2026-06-22"
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu Tuần 2:

- Làm chủ các khái niệm cốt lõi về AWS IAM và các thực hành bảo mật tốt nhất (security best practices).
- Thực hành các bài lab IAM để quản lý người dùng (Users), nhóm (Groups) và chính sách (Policies).
- Cấu hình IAM Roles và các chính sách JSON tùy chỉnh tuân thủ Nguyên tắc quyền tối thiểu (Principle of Least Privilege).

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành |
| :--- | :-------- | :----------- | :-------------- |
| 1 | **Nền tảng & Tìm hiểu sâu về IAM:** Tìm hiểu kiến trúc IAM, sự khác biệt giữa Định danh (Identity) và Truy cập (Access), Users, Groups, Roles và Policies. | 22/06/2026 | 22/06/2026 |
| 2 | **Lab Quản lý User & Group:** Tạo các IAM User cho admin và developer, gán vào các User Group và bắt buộc bật MFA cho từng người dùng. | 23/06/2026 | 23/06/2026 |
| 3 | **Viết Chính sách Tùy chỉnh (Custom Policy):** Soạn thảo và kiểm thử các chính sách JSON tùy chỉnh bằng IAM Policy Simulator để giới hạn quyền trên tài nguyên. | 24/06/2026 | 24/06/2026 |
| 4 | **IAM Roles & Phân quyền Dịch vụ:** Cấu hình IAM Roles để chuẩn bị sử dụng cho EC2 instance mà không cần lưu cứng (hardcode) thông tin xác thực. | 25/06/2026 | 25/06/2026 |
| 5 | **Kiểm toán Bảo mật & Cấu hình Thông tin Xác thực:** Tạo AWS Access Keys phục vụ truy cập CLI từ máy cục bộ, đồng thời kiểm tra Access Advisor và Báo cáo Thông tin Xác thực (Credential Reports). | 26/06/2026 | 27/06/2026 |

### Kết quả đạt được trong Tuần 2:

- Làm chủ các nguyên tắc cốt lõi về quản trị định danh và quyền truy cập trên AWS.
- Xây dựng thành công các chính sách JSON tùy chỉnh và xác minh phân quyền thông qua Policy Simulator.
- Thiết lập hệ thống IAM Users và Roles an toàn, loại bỏ hoàn toàn việc phụ thuộc vào tài khoản Root cho các thao tác hàng ngày.

---

👉 **Kết quả:** Sau Tuần 2, hệ thống kiểm soát truy cập và các giao thức bảo mật đã được cấu hình hoàn chỉnh thông qua IAM, tạo nền tảng an toàn để thiết kế mạng VPC tùy chỉnh ở Tuần 3.