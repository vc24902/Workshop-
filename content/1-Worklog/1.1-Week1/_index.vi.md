---
title: "Worklog Tuần 1"
date: 2026-04-12
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Mục tiêu tuần 1:

* Làm quen với môi trường thực tập và các kiến thức nền tảng về AWS Cloud.
* Hiểu về Identity and Access Management (IAM) và quản lý quyền truy cập của người dùng.
* Tìm hiểu cách triển khai và quản lý các Amazon EC2 Instance.
* Hiểu các kiến thức cơ bản về Amazon VPC và kiến trúc mạng.
* Tìm hiểu cách lưu trữ một website tĩnh bằng Amazon S3.
* Thực hành sử dụng IAM Role cùng với AWS CLI để truy cập tài nguyên AWS một cách an toàn.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ----------------------------------------- |
| 2 | - Tham gia buổi định hướng thực tập và tìm hiểu lộ trình thực tập.<br>- Tìm hiểu về AWS Cloud và các nhóm dịch vụ AWS phổ biến.<br>- Tạo IAM Group và IAM User.<br>- Gán AdministratorAccess Policy và xác minh đăng nhập bằng tài khoản IAM. | 12/04/2026 | 12/04/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - Tìm hiểu các kiến thức cơ bản về Amazon EC2.<br>- Khởi tạo một Amazon Linux EC2 Instance.<br>- Cấu hình Security Group (SSH và HTTP).<br>- Kết nối đến EC2 bằng SSH.<br>- Cài đặt Apache Web Server và triển khai một trang web đơn giản. | 13/04/2026 | 13/04/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | - Tìm hiểu các khái niệm về Amazon VPC.<br>- Tạo một VPC tùy chỉnh.<br>- Cấu hình Public Subnet và Private Subnet.<br>- Gắn Internet Gateway (IGW).<br>- Cấu hình Route Table và bật tính năng tự động gán Public IPv4. | 14/04/2026 | 14/04/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | - Tìm hiểu Amazon S3.<br>- Tạo một S3 Bucket.<br>- Tải các tệp website lên.<br>- Cấu hình Bucket Policy.<br>- Bật Static Website Hosting và kiểm tra khả năng truy cập website. | 15/04/2026 | 15/04/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6 | - Tìm hiểu IAM Role và AWS CLI.<br>- Tạo IAM Role cho EC2.<br>- Gán AmazonS3ReadOnlyAccess Policy.<br>- Kết nối đến EC2 bằng SSH.<br>- Thực hành các lệnh AWS CLI để truy cập tài nguyên AWS và hiểu về quyền IAM. | 16/04/2026 | 16/04/2026 | https://cloudjourney.awsstudygroup.com/ |

### Kết quả đạt được tuần 1:

* Đã làm quen với môi trường thực tập, mục tiêu học tập trong tuần và các kiến thức nền tảng về AWS Cloud.

* Hiểu mục đích của AWS Identity and Access Management (IAM), bao gồm:
  * Tạo IAM Group và IAM User.
  * Gán Policy và quản lý quyền truy cập.
  * Đăng nhập an toàn bằng tài khoản IAM thay vì sử dụng tài khoản Root.

* Triển khai thành công một Amazon EC2 Instance và học được cách:
  * Cấu hình Security Group.
  * Kết nối đến EC2 thông qua SSH.
  * Cài đặt Apache Web Server.
  * Triển khai một trang web đơn giản.

* Có được kiến thức cơ bản về mạng Amazon VPC, bao gồm:
  * Tạo một VPC tùy chỉnh.
  * Cấu hình Public Subnet và Private Subnet.
  * Gắn Internet Gateway.
  * Cấu hình Route Table.
  * Gán địa chỉ Public IPv4.

* Triển khai thành công một website tĩnh bằng Amazon S3 thông qua:
  * Tạo một S3 Bucket.
  * Tải các tệp website lên.
  * Cấu hình Bucket Policy.
  * Bật Static Website Hosting.

* Tìm hiểu cách IAM Role hoạt động cùng với AWS CLI:
  * Tạo IAM Role cho EC2.
  * Gán AmazonS3ReadOnlyAccess Policy.
  * Sử dụng AWS CLI để tương tác với các dịch vụ AWS.
  * Liệt kê thành công các S3 Bucket.
  * Hiểu lỗi AccessDenied do thiếu quyền IAM.

* Nâng cao kinh nghiệm thực hành với các dịch vụ AWS cốt lõi bao gồm IAM, EC2, VPC, S3 và AWS CLI thông qua các bài thực hành.

* Phát triển sự hiểu biết tốt hơn về các phương pháp bảo mật tốt nhất trên AWS bằng cách phân tách quyền người dùng thông qua IAM User, IAM Role và Policy thay vì sử dụng tài khoản Root.