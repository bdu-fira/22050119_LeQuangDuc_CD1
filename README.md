<h3 align="center"><b>TRƯỜNG ĐẠI HỌC BÌNH DƯƠNG</b></h3>
<h4 align="center">KHOA CÔNG NGHỆ THÔNG TIN, ROBOT VÀ TRÍ TUỆ NHÂN TẠO</h4>

<h1 align="center"><b>ĐỒ ÁN CHUYÊN ĐỀ 1</b></h1>
<h2 align="center"><b>WEBSITE BÁN QUẦN ÁO</b></h2>

---

## Giảng Viên Hướng Dẫn

Họ và tên        
---------------- 
-  Dương Anh Tuấn   
-  Hồ Ngọc Giàu     
-  Nguyễn Hữu Quyền 
-  Nguyễn Thanh Sơn

---

## Thành Viên Nhóm

| MSSV     | Họ và tên       | Lớp    |
| -------- | --------------- | ------ |
| 22050119 | Lê Quang Đức    | 25TH01 |
| 22050023 | Tô Gia Dân      | 25TH01 |
| 22050033 | Phạm Hoàng Hùng | 25TH01 |

---

## Phân Công Công Việc

| Thành viên      | Nhiệm vụ | Tham Gia |
| --------------- | -------- | ------- |
| Lê Quang Đức    |        chỉnh sửa Word,Frontend, Backend, kết nối database, up github, đưa lên cloud (đã buil lên được docker, nhưng chưa đưa lên aws được)   |   100%      |
| Tô Gia Dân      |  Backend, Word        |     100%    |
| Phạm Hoàng Hùng |     Power Point, Frontend, Poster    |      100%   |

---

## Mục Lục

1. Giới thiệu đề tài
2. Mục tiêu
3. Phạm vi
4. Yêu cầu chức năng & phi chức năng
5. Kiến trúc hệ thống & mô hình usecase
6. Thiết kế CSDL
7. Giao diện hệ thống
8. Kết quả & Đánh giá
9. Hướng phát triển
10. Tổng kết

---

## 1. Giới Thiệu Đề Tài

Website bán quần áo là một hệ thống thương mại điện tử được xây dựng nhằm hỗ trợ người dùng trong việc mua sắm thời trang một cách dễ dàng và tiện lợi, đồng thời giúp nhà quản lý giám sát đơn hàng, sản phẩm và nhân viên hiệu quả hơn.

## 2. Mục Tiêu

- Xây dựng một hệ thống quản lý bán quần áo đầy đủ chức năng.
- Giao diện thân thiện, dễ sử dụng.
- Tích hợp đầy đủ các tính năng TMĐT: giỏ hàng, đăng nhập, quản lý đơn,...
- Hệ thống có thể mở rộng dễ dàng trong tương lai.

## 3. Phạm Vi

- Người dùng: Xem, tìm kiếm, thêm sản phẩm vào giỏ, thanh toán, theo dõi đơn hàng.
- Nhân viên: Quản lý đơn, cập nhật trạng thái, hỗ trợ khách hàng.
- Quản trị viên: Quản lý sản phẩm, danh mục, tài khoản, phân quyền.

## 4. Yêu Cầu Hệ Thống

### 4.1 Chức Năng

- Đăng ký, đăng nhập
- Giỏ hàng
- Quản lý sản phẩm
- Quản lý danh mục
- Phân quyền tài khoản
- Theo dõi trạng thái đơn hàng
- Tìm kiếm sản phẩm

### 4.2 Phi Chức Năng

- Bảo mật cao (HTTPS, mã hóa, chống SQL Injection)
- Hỗ trợ nhiều người dùng đồng thời
- Responsive design (tương thích mọi thiết bị)
- Hệ thống dễ bảo trì và mở rộng

## 5. Kiến Trúc Hệ Thống & Mô Hình Usecase

- Thiết kế theo mô hình MVC (Model - View - Controller)
- Usecase tổng quát cho các chức năng của khách hàng, nhân viên, quản trị viên

![Mô hình usecase tổng quát](https://i.imgur.com/zyxgUse.jpg)

## 6. Thiết Kế Cơ Sở Dữ Liệu

![Sơ đồ thực thể quan hệ](https://i.imgur.com/fakeEntityERD.jpg)

## 7. Giao Diện Hệ Thống

### Giao diện người dùng:

- Trang chủ  
  ![Giao diện trang chủ](https://i.imgur.com/pageHome.jpg)

- Danh mục sản phẩm  
  ![Giao diện danh mục](https://i.imgur.com/pageCategory.jpg)

- Giỏ hàng  
  ![Giao diện giỏ hàng](https://i.imgur.com/pageCart.jpg)

- Đăng nhập & Đăng ký  
  ![Giao diện đăng nhập](https://i.imgur.com/pageLogin.jpg)

### Giao diện quản trị:

- Quản lý sản phẩm  
  ![Quản lý sản phẩm](https://i.imgur.com/pageAdminProduct.jpg)

- Quản lý đơn hàng  
  ![Quản lý đơn hàng](https://i.imgur.com/pageAdminOrder.jpg)

## 8. Kết Quả & Đánh Giá

| Mục tiêu                 | Đạt được | Ghi chú                                        |
| ------------------------ | -------- | ---------------------------------------------- |
| Giao diện hoàn chỉnh     | Đạt      | Gồm hơn 20 giao diện từ người dùng đến admin   |
| Tính năng TMĐT           | Đạt      | Đăng ký, đăng nhập, giỏ hàng, theo dõi đơn,... |
| Quản trị & phân quyền    | Đạt      | Có sơ đồ và giao diện cụ thể                   |
| Tích hợp thanh toán thật | Chưa Đạt | Mới ở mức mô phỏng                             |
| Thống kê phân tích       | Chưa Đạt | Chưa thực hiện                                 |

## 9. Hướng Phát Triển

- Tích hợp cổng thanh toán thật (VNPay, Momo)
- Thêm chức năng đánh giá sản phẩm, wishlist
- Thống kê doanh thu, sản phẩm bán chạy
- Tối ưu tốc độ tải trang & bảo mật nâng cao
- Giao diện mobile + hỗ trợ đa ngôn ngữ

## 10. Tổng Kết

Đồ án đã đáp ứng đầy đủ các mục tiêu đề ra, mô phỏng được hệ thống Web shop thời trang thực tế. Hệ thống mang tính ứng dụng cao, có thể triển khai thực tế sau khi bổ sung các tính năng thanh toán và bảo mật chuyên sâu hơn.
