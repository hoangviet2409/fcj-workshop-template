---
title: "Nhật ký Tuần 2"
date: 2026-04-24
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
### Mục tiêu cốt lõi của Tuần 2:

* Nắm bắt nguyên lý cấp quyền và quản lý tài khoản người dùng trực thuộc dịch vụ AWS IAM.
* Xây dựng rào chắn bảo mật cấp cao nhất cho tài khoản gốc (Root account).
* Đưa vào sử dụng tính năng giám sát AWS Budgets nhằm bảo đảm chi tiêu không vượt quá hạn mức khi làm Lab.

### Tiến độ công việc đã triển khai:
| Ngày | Mô tả công việc chi tiết | Bắt đầu | Kết thúc | Nguồn tài liệu |
| --- | --- | :---: | :---: | --- |
| 8 | Thiết lập một tài khoản AWS mới và cấu hình sơ bộ những tính năng an toàn cơ bản nhất. | 24/04/2026 | 24/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 9 | Ràng buộc tài khoản Root bằng tính năng Xác minh bước hai (MFA). | 25/04/2026 | 25/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 10 | Làm quen với bảng điều khiển IAM: thử nghiệm lập mới User, tập hợp vào các Group và phân phối quyền hạn. | 26/04/2026 | 26/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 11 | Ủy thác quyền Quản trị viên (Administrator Access) cho tài khoản IAM User sẽ dùng chính để chạy hệ thống. | 27/04/2026 | 27/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 12 | Thao tác trên giao diện AWS Budgets, thiết lập ngưỡng cước phí để nhận email thông báo khi vượt mức. | 28/04/2026 | 28/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 13 | Đào sâu vào các loại Budget phức tạp hơn như Usage Budget hay dự khoản Savings Plans. | 29/04/2026 | 29/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 14 | Xem qua cơ chế hoạt động của trung tâm hỗ trợ AWS (Support Center) và học cách hủy/xóa các tài nguyên đã khởi tạo để tránh hao tổn. | 30/04/2026 | 30/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |


### Thành quả thu nhận:

* Root account đã được đóng băng an toàn trước các rủi ro bằng cơ chế mã xác nhận linh động MFA.
* Củng cố kiến thức điều phối linh hoạt các tập luật (Policy) trong IAM cho User và Group.
* Tránh được rủi ro tài chính phát sinh ngoài ý muốn nhờ cài cắm thành công AWS Budgets tự động cảnh báo.
