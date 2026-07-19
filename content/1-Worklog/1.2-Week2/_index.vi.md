---
title: "Worklog Tuần 2"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:
* Nắm vững kiến trúc mạng cốt lõi (Networking) trên đám mây.
* Tự xây dựng môi trường mạng ảo cách ly (VPC) chuẩn doanh nghiệp.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu Amazon VPC, phân biệt Public và Private Subnet.                                                                                                                                  | 27/04/2026   | 27/04/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 3   | - Nghiên cứu Route Tables, Internet Gateway (IGW) và NAT Gateway.                                                                                                                           | 28/04/2026   | 28/04/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 4   | - **Thực hành:** <br>&emsp; + Khởi tạo Custom VPC <br>&emsp; + Cấu hình 2 Public Subnets & 2 Private Subnets <br>&emsp; + Gắn IGW, định tuyến ra Internet                                   | 29/04/2026   | 29/04/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 5   | - Phân biệt Security Groups (Stateful) và Network ACLs (Stateless). <br> - Tìm hiểu giám sát lưu lượng mạng VPC Flow Logs.                                                                  | 30/04/2026   | 30/04/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 6   | - **Thực hành:** <br>&emsp; + Khởi tạo NAT Gateway cho Private Subnet <br>&emsp; + Triển khai EC2 kiểm tra kết nối <br>&emsp; + Bật VPC Flow Logs                                           | 01/05/2026   | 01/05/2026      | <https://cloudjourney.awsstudygroup.com/>|

### Kết quả đạt được tuần 2:
* Xây dựng thành công hạ tầng mạng Multi-AZ trên VPC với các phân lớp Public/Private rõ ràng.
* Cấu hình Route Tables điều hướng traffic chính xác giữa Subnet, IGW và NAT Gateway.
* Làm chủ tường lửa Security Groups và bật tính năng phân tích VPC Flow Logs phục vụ bảo mật.