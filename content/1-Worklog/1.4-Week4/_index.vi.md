---
title: "Worklog Tuần 4"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:
* Quản lý lưu trữ Object (Amazon S3) và tự động hóa vòng đời dữ liệu.
* Bảo vệ dữ liệu bằng công cụ KMS mã hóa và phân quyền S3 Bucket Policy.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu Amazon S3, các Storage Classes (Standard, IA, Glacier).                                                                                                                          | 11/05/2026   | 11/05/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 3   | - Nghiên cứu tính năng S3 Versioning & Lifecycle Rules.                                                                                                                                     | 12/05/2026   | 12/05/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 4   | - **Thực hành:** <br>&emsp; + Tạo S3 Bucket, cấu hình Block Public Access <br>&emsp; + Viết Bucket Policy giới hạn quyền truy cập                                                           | 13/05/2026   | 13/05/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 5   | - Tìm hiểu hệ thống AWS KMS (Key Management Service) và mã hóa tĩnh.                                                                                                                        | 14/05/2026   | 14/05/2026      | <https://cloudjourney.awsstudygroup.com/>|
| 6   | - **Thực hành:** <br>&emsp; + Khởi tạo Customer Managed Keys (CMK) <br>&emsp; + Bật mã hóa SSE-KMS <br>&emsp; + Tạo Lifecycle chuyển dữ liệu cũ sang Glacier                                | 15/05/2026   | 15/05/2026      | <https://cloudjourney.awsstudygroup.com/>|

### Kết quả đạt được tuần 4:
* Hiểu sâu các tầng lưu trữ S3, áp dụng Lifecycle Rules để tự động hóa giảm thiểu chi phí.
* Chặn hoàn toàn nguy cơ rò rỉ dữ liệu public qua Block Public Access và Bucket Policy.
* Tích hợp thành công AWS KMS để mã hóa dữ liệu tĩnh an toàn.