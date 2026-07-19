---
title: "Worklog Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:
* Đảm bảo tính sẵn sàng cao (High Availability) cho hệ thống máy chủ.
* Thiết lập cơ chế tự động mở rộng theo tải (Auto Scaling).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu kiến trúc High Availability (HA) trên AWS.                                                                                                                                       | 04/05/2026   | 04/05/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 3   | - Nghiên cứu Application Load Balancer (ALB) và Target Groups.                                                                                                                              | 05/05/2026   | 05/05/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 4   | - Tìm hiểu Amazon Auto Scaling Group (ASG) và Launch Templates.                                                                                                                             | 06/05/2026   | 06/05/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 5   | - Viết Bash script (User Data) để tự động cài đặt Web Server. <br> - Xây dựng các chiến lược scaling (Dynamic, Scheduled).                                                                  | 07/05/2026   | 07/05/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 6   | - **Thực hành:** <br>&emsp; + Triển khai ALB kết hợp ASG trên Custom VPC <br>&emsp; + Cấu hình Dynamic Scaling Policy <br>&emsp; + Stress test CPU                                          | 08/05/2026   | 08/05/2026      | <https://cloudjourney.awsstudygroup.com/>|

### Kết quả đạt được tuần 3:
* Tự động hóa cài đặt môi trường web qua EC2 User Data.
* Triển khai ALB phân phối traffic mượt mà qua nhiều Availability Zone.
* ASG hoạt động chuẩn xác, tự động co giãn số lượng máy chủ theo tải cấu hình.