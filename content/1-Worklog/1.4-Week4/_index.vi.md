---
title: "Nhật ký Tuần 4"
date: 2026-05-08
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
### Mục tiêu lớn trong Tuần 4:

* Thực thi tạo lập các hệ thống Amazon EC2 ảo hóa và làm chủ quy trình kết nối shell từ xa hợp lệ.
* Giao tiếp và định tuyến tên miền nội bộ cũng như công cộng qua cơ sở hạ tầng Amazon Route 53.
* Nắm bắt mô hình Infrastructure as Code (IaC) để gom nhóm tài nguyên bằng mã kịch bản AWS CloudFormation.

### Nội dung các phiên làm việc:
| Ngày | Bảng kê đầu việc thực tế | Bắt đầu | Kết thúc | Nguồn tham chiếu |
| --- | --- | :---: | :---: | --- |
| 22 | Cấu hình và gọi khởi chạy một EC2 instance chạy nhân Linux nằm lọt trong phân lớp mạng cục bộ. | 08/05/2026 | 08/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 23 | Xử lý giao thức SSH để chui vào bên trong máy chủ (sử dụng cặp khóa Key Pair và Endpoint hỗ trợ kết nối bảo mật). | 09/05/2026 | 09/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 24 | Mổ xẻ nguyên lý Amazon Route 53 để hiểu cách dịch vụ này phân phối lưu lượng và biên dịch tên miền (DNS). | 10/05/2026 | 10/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 25 | Nghiên cứu tài liệu chính thống về IaC, tìm hiểu cách AWS CloudFormation biến toàn bộ các cú pháp cấu hình thành nút mạng thực. | 11/05/2026 | 11/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 26 | Set up Route 53 Resolver Rule nhằm trỏ traffic truy vấn (query) qua lại một cách logic và thông suốt. | 12/05/2026 | 12/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 27 | Tự tay biên dịch một tệp tin CloudFormation (Template) dạng mẫu để ra lệnh cho AWS dựng máy chủ tự động mà không cần click tay. | 13/05/2026 | 13/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 28 | Fix bug, kiểm soát log khi SSH chập chờn, dọn dẹp môi trường Route 53 để hoàn tất cụm bài học Module 02. | 14/05/2026 | 14/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |


### Hiệu quả thu được:

* Hoàn toàn tự tin cấp phát và vận hành máy chủ EC2 trực tuyến với cấp độ mã hóa truy cập sâu.
* Khai thác trơn tru tuyến mạng DNS liên tục nhờ bảng cấu hình của Amazon Route 53.
* Loại bỏ thao tác thủ công, ứng dụng lập trình hạ tầng CloudFormation Template để triển khai đồng loạt.
