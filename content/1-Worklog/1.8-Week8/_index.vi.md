---
title: "Worklog Tuần 8"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:
* Đồng bộ chuẩn giao tiếp API giữa các thành phần.
* Dựng xong khung hạ tầng nền tảng cho AI Processor.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- |
| 2   | - Họp đồng bộ API contract (request/response) giữa Frontend, Backend và AI Processor.                                                                                             | 08/06/2026   | 08/06/2026      |
| 3   | - Bắt đầu dựng khung mã nguồn cho Lambda AI Processor.                                                                                                                            | 09/06/2026   | 09/06/2026      |
| 4   | - Thực hiện thử gọi External AI API để kiểm tra kết nối.                                                                                                                          | 10/06/2026   | 10/06/2026      |
| 5   | - Thiết kế JSON schema chuẩn đầu ra cho output của AI.                                                                                                                            | 11/06/2026   | 11/06/2026      |
| 6   | - Rà soát lại JSON schema và hoàn thiện phần khung Lambda cơ bản.                                                                                                                 | 12/06/2026   | 12/06/2026      |

### Kết quả đạt được tuần 8:
* Thống nhất được API contract toàn hệ thống để chuẩn bị tích hợp.
* Gọi thành công External API từ bên trong AWS Lambda.
* Khóa (lock) định dạng JSON Schema đầu ra để đảm bảo frontend hiển thị chính xác.