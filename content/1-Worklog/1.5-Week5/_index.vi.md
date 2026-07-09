---
title: "Nhật ký Tuần 5"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
### Mục tiêu tiêu điểm Tuần 5:

* Thay đổi tư duy triển khai hệ thống thông thường sang mô hình điện toán phi máy chủ (Serverless).
* Khởi tạo và liên kết các REST API bằng cách phối hợp Amazon API Gateway với AWS Lambda.
* Nghiên cứu bài toán gỡ rối (decoupling) ứng dụng bằng SQS, SNS và học cách lưu dữ liệu bằng DynamoDB.

### Bảng công việc chi tiết:
| Ngày | Hạng mục thực hiện | Bắt đầu | Kết thúc | Nguồn bài giảng |
| --- | --- | :---: | :---: | --- |
| 29 | Đọc hiểu lý thuyết Serverless, phân tích ưu thế và nhận biết cách AWS Lambda lắng nghe sự kiện (Event-driven). | 15/05/2026 | 15/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 30 | Nắm bắt phương pháp xử lý hàng đợi tin nhắn (Message Queue) để tách rời các chu trình bằng Amazon SQS. | 16/05/2026 | 16/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 31 | Biên soạn mã nguồn cho hàm Lambda, cấu hình để hàm này tự kích hoạt và tiêu thụ Data lấy từ SQS. | 17/05/2026 | 17/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 32 | Rà soát kiến trúc luân chuyển sự kiện Pub/Sub, thấy được hiệu năng khuếch tán dữ liệu của hệ thống SNS. | 18/05/2026 | 18/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 33 | Học cách đánh chỉ mục NoSQL trên Amazon DynamoDB, vạch ra ranh giới giữa Partition Key và Sort Key. | 19/05/2026 | 19/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 34 | Lắp ráp luồng tương tác thực tế: Một Request chạm tới API Gateway, gọi Lambda và ghi nhận vào bảng DynamoDB. | 20/05/2026 | 20/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 35 | Chạy thử nghiệm phản hồi của luồng API, fix bug các hàm và dọn sạch các template dư thừa ra khỏi tài khoản. | 21/05/2026 | 21/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |


### Đánh giá thành tựu:

* Thích nghi tốt với thiết kế và triển khai mô hình Serverless không cần duy trì tài nguyên phần cứng liên tục.
* Tự xây dựng được một chuỗi RESTful API hiện đại xuyên suốt từ Frontend tới Backend (API Gateway - Lambda - DynamoDB).
* Phân bổ thiết kế hệ thống rời rạc, chống lỗi đứt quãng thông qua hàng đợi SQS và trung tâm thông báo SNS.
