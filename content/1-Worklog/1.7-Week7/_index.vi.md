---
title: "Nhật ký Tuần 7"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
### Mục tiêu lớn của Tuần 7:

* Quản trị kho lưu trữ tài nguyên tĩnh với dung lượng vô hạn thông qua Amazon S3.
* Biến S3 Bucket thành một máy chủ web thực thụ nhờ tính năng Static Website Hosting.
* Tích hợp mạng lưới phân phối nội dung toàn cầu Amazon CloudFront để bứt phá tốc độ tải trang.

### Chi tiết lộ trình:
| Ngày | Bảng kê hoạt động | Bắt đầu | Kết thúc | Nguồn học tập |
| --- | --- | :---: | :---: | --- |
| 43 | So sánh chi tiết từng hạng mục lưu trữ (Storage Class) của S3 nhằm định ra chiến lược lưu trữ tiết kiệm. | 29/05/2026 | 29/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 44 | Lập trình sẵn S3 Bucket mới với chế độ Public Access Block bật 100% để loại trừ nguy cơ rò rỉ dữ liệu. | 30/05/2026 | 30/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 45 | Bật công tắc Static Website Hosting, đẩy toàn bộ source code giao diện tĩnh lên bucket. | 31/05/2026 | 31/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 46 | Xử lý triệt để lỗi Cross-Origin bằng file cấu hình CORS và thiết lập S3 Bucket Policy tương thích. | 01/06/2026 | 01/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 47 | Khởi chạy Amazon CloudFront Distribution trỏ trực tiếp về nguồn dữ liệu tĩnh vừa dựng tại S3. | 02/06/2026 | 02/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 48 | Chặn đường vào cửa sau của S3 bằng Origin Access Control (OAC), ép người dùng chỉ được gọi qua CDN. | 03/06/2026 | 03/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 49 | Chạy tool kiểm tra hiệu suất truy cập đầu cuối của CloudFront, sau đó thực hiện clean-up gọn gàng. | 04/06/2026 | 04/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |


### Thành tích ghi nhận:

* Tổ chức thành công kho dữ liệu an toàn tuyệt đối với chuẩn bảo mật khép kín từ Amazon S3.
* Hệ thống Frontend được tăng tốc truy xuất, sẵn sàng đón tải cao mà không sập nhờ CloudFront.
* Có kinh nghiệm sâu sắc trong việc tùy biến chính sách vùng cấm (CORS, OAC) cho các tệp tin lưu trữ chia sẻ.
