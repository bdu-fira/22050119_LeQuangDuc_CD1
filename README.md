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
| Lê Quang Đức    |        chỉnh sửa Word, sửa Web , kết nối database, up github, đưa lên cloud (đã buil lên được docker, nhưng chưa đưa lên aws được)   |   100%      |
| Tô Gia Dân      |  Backend, Word, đưa ra ý kiến cùng phát triển đề tài        |     100%    |
| Phạm Hoàng Hùng |     Power Point, Frontend, Poster, đưa ra ý kiến cùng phát triển đề tài    |      100%   |

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

![image](https://github.com/user-attachments/assets/f50fa97b-da0d-4401-a758-67d44ad472a4)


## 6. Thiết Kế Cơ Sở Dữ Liệu

![image](https://github.com/user-attachments/assets/7889826f-8d37-4dd2-bcb9-ebb8ef593a0b)

## 7. sơ đồ ERD xuất từ 
![image](https://github.com/user-attachments/assets/6dca8d58-daaf-40ee-ad6f-4eede0aa3af3)

## 8. Giao Diện Hệ Thống

### Giao diện người dùng:

- Trang chủ  
![image](https://github.com/user-attachments/assets/5a3dac7d-d41e-42aa-af60-87eac04f06b4)


- Danh mục sản phẩm  
  ![image](https://github.com/user-attachments/assets/2e947215-b7e9-4516-ad77-777f9cc40439)


- Giỏ hàng  
![image](https://github.com/user-attachments/assets/868449f1-1e8e-4d04-9336-f30b67653ccd)


- Đăng nhập & Đăng ký
  + Đăng Ký 
  ![image](https://github.com/user-attachments/assets/f6061c25-d5c3-4dd4-baf0-007445956397)
  + Đăng Nhập
    ![image](https://github.com/user-attachments/assets/f5fee5c0-3985-463f-a1fd-d2d0f7859778)


### Giao diện quản trị:

- Quản lý sản phẩm  
![image](https://github.com/user-attachments/assets/d2cd5a6b-768c-4b4c-a621-b6227ad8ca41)


- Quản lý đơn hàng  
![image](https://github.com/user-attachments/assets/cf693fee-9e3e-460c-b4b8-2483b368ee15)


## 9. Kết Quả & Đánh Giá

| Mục tiêu                 | Đạt được | Ghi chú                                        |
| ------------------------ | -------- | ---------------------------------------------- |
| Giao diện hoàn chỉnh     | Đạt      | Gồm hơn 20 giao diện từ người dùng đến admin   |
| Tính năng TMĐT           | Đạt      | Đăng ký, đăng nhập, giỏ hàng, theo dõi đơn,... |
| Quản trị & phân quyền    | Đạt      | Có sơ đồ và giao diện cụ thể                   |
| Tích hợp thanh toán thật | Chưa Đạt | Mới ở mức mô phỏng                             |
| Thống kê phân tích       | Chưa Đạt | Chưa thực hiện                                 |

## 10. Hướng Phát Triển

- Tích hợp cổng thanh toán thật (VNPay, Momo)
- Thêm chức năng đánh giá sản phẩm, wishlist
- Thống kê doanh thu, sản phẩm bán chạy
- Tối ưu tốc độ tải trang & bảo mật nâng cao
- Giao diện mobile + hỗ trợ đa ngôn ngữ

## 11. Tổng Kết

Đồ án đã đáp ứng đầy đủ các mục tiêu đề ra, mô phỏng được hệ thống Web shop thời trang thực tế. Hệ thống mang tính ứng dụng cao, có thể triển khai thực tế sau khi bổ sung các tính năng thanh toán và bảo mật chuyên sâu hơn.

## 12. Tài Liệu Tham Khảo
-	Express – Node.js web application framework. Truy cập tại: https://expressjs.com/en/starter/installing.html The Odin Project. 
-	Fullstack JavaScript Path. Truy cập tại: https://www.theodinproject.com/paths/full-stack-javascript 
-	W3Schools. SQL Tutorial. Truy cập tại: https://www.w3schools.com/sql/ PostgreSQL.
-	"Eloquent JavaScript" by Marijn Haverbeke
-  "CSS Secrets" by Lea Verou
-  "JavaScript: The Good Parts" by Douglas Crockford
-  "Node.js Design Patterns" by Mario Casciaro and Luciano Mammino
-  -	ReactJS. React – A JavaScript library for building user interfaces. Truy cập tại: https://reactjs.org/docs/getting-started.html 
