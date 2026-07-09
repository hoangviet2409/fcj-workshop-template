---
title: "Nhật ký Tuần 3"
date: 2026-05-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
### Mục tiêu then chốt Tuần 3:

* Kiến tạo mạng lưới máy chủ đám mây độc lập bên trong nền tảng AWS bằng Amazon VPC.
* Chia tách không gian mạng thành các phân khu Subnet và điều hướng luồng dữ liệu bằng Route Table.
* Dựng rào chắn an ninh đa lớp ngăn chặn gói tin độc hại với quyền lực của Security Group và NACL.

### Nhật trình triển khai:
| Ngày | Mô tả công việc đã làm | Bắt đầu | Kết thúc | Nguồn tài liệu |
| --- | --- | :---: | :---: | --- |
| 15 | Phân tích lõi kiến trúc của Amazon VPC, học cách tính toán và chia dải địa chỉ IP theo chuẩn CIDR. | 01/05/2026 | 01/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 16 | Phân biệt cấu trúc bảo vệ Stateful của Security Group và quy cách xét duyệt Stateless chặt chẽ của NACL. | 02/05/2026 | 02/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 17 | Nghiên cứu các phương pháp liên kết mạng tiên tiến như Load Balancer, kết nối VPN hay kênh truyền AWS Direct Connect. | 03/05/2026 | 03/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 18 | Thực thi tạo VPC trống, xẻ nhỏ không gian IP để cấp phát cho hai vùng mạng Public và mạng Private. | 04/05/2026 | 04/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 19 | Mount thiết bị Internet Gateway (IGW) vào mạng và cấu hình băng thông ra ngoài cho hệ thống máy chủ Public. | 05/05/2026 | 05/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 20 | Khởi động NAT Gateway đứng tại Public Subnet nhằm hỗ trợ Private Subnet có thể lấy dữ liệu ẩn danh từ Internet. | 06/05/2026 | 06/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 21 | Lắp đặt các quy tắc chống xâm nhập trên tường lửa Security Group và Network ACL để chặn/mở cổng dịch vụ theo ý muốn. | 07/05/2026 | 07/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |


### Đúc kết giá trị:

* Tự tay xây dựng được môi trường mạng riêng VPC tuân thủ nguyên tắc cách ly bảo mật không gian.
* Vạch trần đường đi của Dữ liệu thông qua các thành phần định tuyến như Route Table, IGW và NAT Gateway.
* Làm chủ sức mạnh phân quyền truy cập thông qua sự kết hợp linh hoạt giữa Security Group và NACL.
