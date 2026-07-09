---
title: "Nhật ký Tuần 10"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
### Mục tiêu chính trong tuần 10:

* Tham gia thiết lập hệ thống truyền nhận dữ liệu viễn trắc (telemetry) thông qua dịch vụ AWS IoT Core.
* Sử dụng Amazon SQS để xây dựng hàng đợi, đảm bảo tính liên tục và không thất thoát dữ liệu nền tảng.
* Ứng dụng AWS Lambda (Telemetry Processor) để tự động hóa khâu xử lý thông tin và đẩy dữ liệu vào Amazon DynamoDB.

### Chi tiết các công việc đã thực hiện:
| Ngày | Mô tả công việc | Thời gian bắt đầu | Thời gian hoàn thành | Trích dẫn / Nguồn |
| --- | --- | :---: | :---: | --- |
| 64 | Triển khai cấu hình cho AWS IoT Core. Tạo các đối tượng (Thing) tương ứng với phương tiện và cài đặt chứng chỉ X.509 để đảm bảo kết nối mã hóa. | 19/06/2026 | 19/06/2026 | |
| 65 | Viết script lập trình giả lập dữ liệu xe (Vehicle Simulator), từ đó đẩy thông tin telemetry lên IoT Core qua giao thức MQTT. | 20/06/2026 | 20/06/2026 | |
| 66 | Quy định các Rule Engine trong AWS IoT nhằm tự động thu thập các gói tin MQTT do thiết bị phát ra. | 21/06/2026 | 21/06/2026 | |
| 67 | Tạo Amazon SQS dạng Standard Queue đóng vai trò bộ đệm tạm thời cho các luồng tin nhắn telemetry. | 22/06/2026 | 22/06/2026 | |
| 68 | Khởi tạo hàm AWS Lambda đóng vai trò là Telemetry Processor, tiến hành phân tích các thông số thô được lấy ra từ SQS. | 23/06/2026 | 23/06/2026 | |
| 69 | Khai báo SQS làm Trigger kích hoạt Lambda Processor, cài đặt luồng xử lý dữ liệu theo mẻ (Batch processing). | 24/06/2026 | 24/06/2026 | |
| 70 | Hoàn thiện mã logic bên trong Lambda để lọc lỗi, lưu giữ các cập nhật về thông số phương tiện vào cơ sở dữ liệu DynamoDB. | 25/06/2026 | 25/06/2026 | |


### Kết quả công tác:

* Khởi tạo thành công chu trình IoT Telemetry, cho phép đưa thông số từ Simulator lên AWS IoT Core một cách bảo mật.
* Hệ thống có khả năng tự động điều phối dữ liệu mạnh mẽ nhờ tích hợp hàng đợi SQS cùng hàm xử lý AWS Lambda.
* Lưu trữ an toàn các sự kiện về hành trình và cảm biến xe cộ vào Amazon DynamoDB.
