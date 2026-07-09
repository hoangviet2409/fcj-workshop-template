---
title: "Nhật ký Tuần 11"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
### Các cột mốc Tuần 11:

* Triển khai code giao diện Web lên môi trường lưu trữ tĩnh S3 và đóng gói bằng CDN CloudFront.
* Xây dựng luồng đăng nhập Cognito và ứng dụng nó để khóa các kết nối vào API Gateway.
* Khắc phục các đoạn mã cuối của AWS Lambda, đặc biệt là cấy ghép thành công bộ não Google Gemini AI.

### Chi tiết các bước làm:
| Ngày | Khối lượng tiến hành | Bắt đầu | Kết thúc | Nguồn học |
| --- | --- | :---: | :---: | --- |
| 71 | Đẩy các tệp tin tĩnh (HTML/JS) sinh ra từ bộ build Frontend vào vùng chứa S3 Website. | 26/06/2026 | 26/06/2026 |  |
| 72 | Thiết đặt đám mây phân phối CDN qua CloudFront nhằm giảm tải độ trễ, bọc lại S3 bằng chuẩn OAC. | 27/06/2026 | 27/06/2026 |  |
| 73 | Vẽ luồng làm việc cho User Pool thuộc Amazon Cognito, đảm bảo sinh Token JWT hợp lệ khi thao tác. | 28/06/2026 | 28/06/2026 |  |
| 74 | Bật Amazon API Gateway, gán lớp bảo vệ Cognito Authorizer chặn đứng mọi kết nối API giả mạo. | 29/06/2026 | 29/06/2026 |  |
| 75 | Viết kịch bản tính toán bên trong AWS Lambda (API Handler), cung cấp luồng rút trích dữ liệu vào DynamoDB. | 30/06/2026 | 30/06/2026 |  |
| 76 | Link thư viện Google Gemini AI vào vùng xử lý Lambda, cung cấp text tư vấn xử lý lỗi xe cho tài xế. | 01/07/2026 | 01/07/2026 |  |
| 77 | Khớp nối Front-End gọi tới Back-End, đánh giá trực quan mã nguồn, đóng gói bản phát hành để sẵn sàng Test. | 02/07/2026 | 02/07/2026 |  |


### Điểm sáng kết quả:

* Hệ thống giao diện được host trên mây một cách vững chãi, tốc độ tải website siêu tốc trên nền CloudFront.
* Dàn API nội bộ được cách ly triệt để bằng hàng rào bảo mật Authorizer do người dùng đích danh định đoạt.
* Biến ứng dụng quản lý xe thành một hệ thống thông minh, tự động phán đoán hỏng hóc bằng trí tuệ nhân tạo Gemini.
* Hoàn thành chặng đường code dài hơi và chuẩn bị chạy quy trình rà soát bảo mật.
