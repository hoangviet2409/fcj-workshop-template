---
title: "Nhật ký Tuần 12"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---
### Kế hoạch chốt chặng Tuần 12:

* Thiết lập hệ thống đo lường hiệu năng, bắt lỗi tập trung bằng CloudWatch và thông báo SNS.
* Chạy End-to-End Test toàn hệ thống để giả lập các đoạn kịch bản tai nạn hỏng hóc thực tiễn.
* Thu thập, biên soạn tài liệu nghiệm thu cuối cùng dọn đường cho việc lấy giấy chứng nhận Tốt nghiệp.

### Hạng mục cuối khóa:
| Ngày | Mô tả kết việc | Bắt đầu | Kết thúc | Nguồn tham chiếu |
| --- | --- | :---: | :---: | --- |
| 78 | Trỏ log của các khối Lambda chạy ngầm về một nơi duy nhất trên Amazon CloudWatch Logs để dễ tra cứu. | 03/07/2026 | 03/07/2026 |  |
| 79 | Cài đặt bẫy CloudWatch Alarm chuyên săn đón các xung đột bất thường (chẳng hạn nhiệt độ máy xe đột biến). | 04/07/2026 | 04/07/2026 |  |
| 80 | Bật dịch vụ SNS, gắn liền vào Alarm để hễ thông số xe chạm mốc là email khẩn bật ngay lập tức. | 05/07/2026 | 05/07/2026 |  |
| 81 | Bật xe ảo chạy quá đà (105 độ C) để test thử độ nhạy của phản ứng hệ thống (E2E), xem AI có gọi email thành công không. | 06/07/2026 | 06/07/2026 |  |
| 82 | Quét lại cơ chế cấp quyền IAM Role lần chót, rà soát dứt điểm các lỗi CORS còn sót trên nền API Gateway. | 07/07/2026 | 07/07/2026 |  |
| 83 | Cú chót: Xác nhận nộp bộ báo cáo Khóa luận tốt nghiệp đồ sộ cùng nguyên bộ source code hoàn chỉnh. | 08/07/2026 | 08/07/2026 |  |
| 84 | Hậu cần: Rà soát quét sạch các Cluster, Database không dùng đến để bảo tồn chi phí thẻ tín dụng. | 09/07/2026 | 09/07/2026 |  |


### Trái ngọt sau 12 Tuần:

* Hệ sinh thái kiểm soát tập trung đã hình thành rõ nét: thấy lỗi xe là bắn thông báo ngay không trễ nhịp.
* Hệ thống vượt qua bài Test E2E khắc nghiệt, chứng tỏ luồng tưới máu Data từ phần cứng đến AI thực thi hoàn hảo.
* Source Code bàn giao sạch đẹp với tiêu chuẩn phân quyền tối thiểu nghiêm ngặt.
* Đạt được cột mốc Tốt nghiệp đúng hạn đợt 08/07/2026 và hạ bệ các tài nguyên dư thừa.
