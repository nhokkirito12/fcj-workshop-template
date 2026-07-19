---
title: "Sự kiện 1: AWS FIRST CLOUD AI JOURNEY COMMUNITY DAY"
date: 2026-07-09
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

### Tổng quan sự kiện
* **Tên sự kiện:** AWS FIRST CLOUD AI JOURNEY COMMUNITY DAY
* **Thời gian:** 09:00, Ngày 23/05/2026
* **Địa điểm:** Tầng 26, Tháp Bitexco, 02 Hải Triều, Phường Sài Gòn, Thành phố Hồ Chí Minh
* **Vai trò:** Người tham dự (Attendee)
* **Diễn giả:** Tinh Truong, Anh Pham, Thinh Nguyen, Mai Nguyen, Uyen Le, Thao Nguyen, Duc Dao, Vy Lam

### Những Chủ Đề Trọng Tâm & Bài Học Rút Ra

**1. Tối ưu và Bảo vệ Hạ tầng từ mạng Biên (Edge)**
Thông qua bài chia sẻ của anh Thinh Nguyen, Amazon CloudFront được tái định nghĩa không đơn thuần là một giải pháp CDN mà còn là một lớp khiên bảo mật vững chắc. Nhờ chính sách giá cước cố định (Flat-rate Pricing), doanh nghiệp có thể tránh được những tổn thất tài chính bất ngờ do các đợt tấn công DDoS gây ra. Những kỹ thuật đáng chú ý được đề cập bao gồm việc che giấu hệ thống máy chủ gốc (Origin Cloaking) bằng VPC Origin, cùng với năng lực tiêu diệt các nguy cơ bảo mật ngay từ rìa mạng.

**2. Hiểu đúng về Cơ chế của LLM và Tương tác AI**
Hai phiên thảo luận trong phần này đã định hình lại tư duy làm việc với các Mô hình ngôn ngữ lớn (LLM):
* **Tối ưu hóa Context (Ngữ cảnh):** Diễn giả Tinh Truong nhấn mạnh nguyên nhân khiến AI đưa ra phản hồi kém chất lượng chủ yếu xuất phát từ dữ liệu đầu vào thiếu chuẩn xác. Để ứng dụng AI vào thực tiễn, người dùng bắt buộc phải thiết lập một cấu trúc rõ ràng bao gồm: Mục tiêu, Dữ liệu cung cấp, Các giới hạn và Tiêu chuẩn đánh giá kết quả.
* **Sự thật về tính Nhất quán (Tất định):** Diễn giả Duc Dao đã chỉ ra sai lầm khi cho rằng thiết lập Temperature = 0 sẽ cho ra các câu trả lời hoàn toàn giống nhau 100%. Điều này bị ảnh hưởng bởi những sai số liên quan đến dấu phẩy động trên phần cứng GPU và cách API xử lý gộp batch. Giải pháp tối ưu và an toàn hơn là thiết lập mức Temp=0.1, kết hợp với việc xây dựng một hệ thống có cơ chế chịu lỗi tốt.

**3. Tự động hóa Dữ liệu và Mô hình Multi-Agent (Đa tác nhân)**
* **Mô hình Hội đồng Tín dụng Ảo:** Chị Vy Lam mang đến một ví dụ thực tiễn ấn tượng về ứng dụng Amazon Bedrock để đánh giá điểm tín dụng cho các startup thông qua hệ thống Đa tác nhân. Việc giao nhiệm vụ cho từng AI chuyên biệt (như tác nhân Phân tích rủi ro hay Chuyên viên Tài chính) chạy trong một VPC khép kín đã giúp rút ngắn đến 95% thời gian xử lý hồ sơ.
* **Xử lý Dữ liệu No-Code:** Màn trình diễn công cụ Amazon QuickSight Q của Anh Pham đã chứng minh khả năng vượt trội của AI tác nhân. Công cụ này cho phép chuyển đổi dữ liệu thô thành các biểu đồ báo cáo trực quan và quy trình tự động hoàn toàn thông qua các câu lệnh ngôn ngữ tự nhiên.

**4. Khả năng Tạo Nguyên mẫu Nhanh (Rapid Prototyping)**
Đội LotusHacks, gồm các thành viên Mai, Uyen và Thao, đã kể lại hành trình phát triển dự án UTMorpho chỉ trong vòng 36 tiếng. Bài học cốt lõi là các sản phẩm công nghệ tuyệt vời nhất luôn bắt rễ từ những "nỗi đau" thực tế của người dùng. Ngoài ra, nhóm cũng khẳng định rằng lượng token tiêu thụ cho việc AI sinh mã giao diện (UI) có thể được giảm thiểu tối đa nhờ áp dụng kỹ thuật smart-diffing.

### Góc nhìn cá nhân
Sự kiện là cầu nối hoàn hảo giữa các nền tảng lý thuyết AI và tính ứng dụng thực tiễn trong quy mô doanh nghiệp. Những bài học chuyên sâu về cách dùng VPC để cô lập hệ thống AI hay dùng CloudFront làm lá chắn bảo vệ biên mạng đóng vai trò rất lớn trong định hướng thiết kế hạ tầng của tôi sau này. Sự kiện đã minh chứng rõ ràng một điều: quá trình đưa AI vào vận hành đòi hỏi nhiều hơn là việc chỉ thao tác gọi mô hình; nó bị chi phối mạnh mẽ bởi khả năng quản lý ngữ cảnh nghiêm ngặt, mức độ an toàn của dữ liệu và sự vững chắc của mạng lưới hạ tầng.

### Hình ảnh từ Sự kiện

![Hình ảnh sự kiện 1](/images/Event1-1.png)
![Hình ảnh sự kiện 2](/images/Event1-2.png)