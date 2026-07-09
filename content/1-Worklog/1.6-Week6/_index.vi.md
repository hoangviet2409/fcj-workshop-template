---
title: "Nhật ký Tuần 6"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
### Mục tiêu hướng tới ở Tuần 6:

* Thâm nhập sâu hơn vào kiến thức về không gian lưu trữ của EC2 và các phương pháp Auto Scaling.
* Tìm hiểu quy định phân định ranh giới bảo mật của AWS qua mô hình Shared Responsibility.
* Ứng dụng nền tảng Amazon Cognito cấp quyền người dùng và ghi nhật ký giám sát hoạt động.

### Tiến trình thực tiễn:
| Ngày | Hạng mục thực hành/lý thuyết | Bắt đầu | Kết thúc | Nguồn học liệu |
| --- | --- | :---: | :---: | --- |
| 36 | Mở rộng khái niệm Amazon Machine Image (AMI) và kết hợp với AWS Backup để lên lịch sao lưu Snapshot định kỳ. | 22/05/2026 | 22/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 37 | Đối chiếu hai trường phái lưu trữ dành cho server: Ổ cứng mạng Amazon EBS và ổ đĩa phù du cục bộ Instance Store. | 23/05/2026 | 23/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 38 | Đánh giá tính năng ổ đĩa chia sẻ Amazon EFS và cấu hình luật co giãn (Auto Scaling Group) dựa trên tải của EC2. | 24/05/2026 | 24/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 39 | Nhận diện rõ trách nhiệm bảo an của nhà cung cấp và của khách hàng thông qua mô hình Shared Responsibility. | 25/05/2026 | 25/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 40 | Đăng ký Amazon Cognito làm trung tâm nhận diện người dùng, thử nghiệm đăng nhập phát sinh JWT. | 26/05/2026 | 26/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 41 | Bật công cụ kiểm tra rủi ro mã lệnh AWS Security Hub và kích hoạt theo dõi thao tác người dùng bằng AWS CloudTrail. | 27/05/2026 | 27/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 42 | Chỉnh sửa IAM Role chuẩn chỉnh để đảm bảo mã Lambda có đủ quyền tương tác riêng tư với SQS hoặc DynamoDB. | 28/05/2026 | 28/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |


### Thành tích đạt được:

* Ra quyết định quy hoạch khả năng lưu trữ (EBS/EFS) kết hợp cùng độ linh hoạt của Auto Scaling Group một cách dứt khoát.
* Minh bạch được bổn phận bảo vệ hạ tầng vật lý của hệ thống AWS và bổn phận bảo mật dữ liệu khách hàng.
* Gắn kết vững chắc bước xác thực qua Cognito và luôn lưu vết lại nhật ký dịch vụ nhờ CloudTrail liên tục quét.
