# CV
# 📦 Inventory Management System (Hệ thống Quản lý Kho & Đơn hàng)

![Status](https://img.shields.io/badge/status-completed-green.svg)
![.NET Core](https://img.shields.io/badge/.NET%20Core-8.0-purple)
![SQL Server](https://img.shields.io/badge/Database-SQL%20Server-lightgrey)

> **Mô tả ngắn:** Một ứng dụng web toàn diện được xây dựng bằng ASP.NET Core MVC để quản lý quy trình nhập/xuất kho, theo dõi đơn hàng và quản lý người dùng với phân quyền chặt chẽ.

---

## 🚀 Giới thiệu (Introduction)

Dự án này được phát triển nhằm giải quyết bài toán quản lý hàng hóa cho các doanh nghiệp vừa và nhỏ. Hệ thống tập trung vào tính bảo mật, khả năng quản lý dữ liệu lớn và giao diện thân thiện với người dùng. Đây là dự án thực tế áp dụng các kiến trúc chuẩn của **ASP.NET Core** và **Entity Framework Core**.

---

## 🛠 Công nghệ sử dụng (Tech Stack)

* **Core Framework:** ASP.NET Core MVC (.NET 8.0)
* **Database:** SQL Server
* **ORM:** Entity Framework Core (Code-First Approach)
* **Front-end:** HTML5, CSS3, Bootstrap 5, JavaScript
* **Authentication:** ASP.NET Core Identity
* **Tools:** Visual Studio 2022, SQL Server Management Studio (SSMS)

---

## ✨ Chức năng chính (Key Features)

### 1. Quản trị hệ thống (Admin Panel)
* **Quản lý người dùng (User Management):** Xem danh sách, phân quyền (Role-based Authorization: Admin/User), khóa/mở khóa tài khoản.
* **Dashboard:** Thống kê tổng quan số lượng đơn hàng và tồn kho.
* **Quản lý sản phẩm:** Thêm, sửa, xóa, xem chi tiết sản phẩm và danh mục.

### 2. Bảo mật (Security & Identity)
* **Đăng ký/Đăng nhập:** Xác thực người dùng an toàn.
* **Bảo mật 2 lớp (2FA):** Tích hợp tính năng xác thực hai yếu tố để tăng cường bảo mật.
* **Xác nhận Email:** Quy trình xác thực tài khoản qua email khi đăng ký.

### 3. Xử lý dữ liệu (Data & Logic)
* **Data Seeding:** Tự động sinh hơn 50 bản ghi mẫu (Sản phẩm, Đơn hàng) để phục vụ quá trình kiểm thử (Testing).
* **Quản lý đơn hàng:** Theo dõi trạng thái đơn hàng (Mới, Đang xử lý, Hoàn thành).
* **Validation:** Kiểm tra dữ liệu đầu vào chặt chẽ ở cả Client-side và Server-side.

---

## 📸 Hình ảnh Demo (Screenshots)

*(Hãy thay thế các đường link bên dưới bằng ảnh chụp màn hình thực tế dự án của bạn)*

| Trang chủ (Home) | Trang Quản trị (Admin) |
| :---: | :---: |
| <img src="path/to/image1.png" width="400"> | <img src="path/to/image2.png" width="400"> |

| Đăng nhập (Login) | Chi tiết đơn hàng |
| :---: | :---: |
| <img src="path/to/image3.png" width="400"> | <img src="path/to/image4.png" width="400"> |

---

## ⚙️ Cài đặt & Chạy dự án (Installation)

Để chạy dự án này trên máy local, vui lòng làm theo các bước sau:

1.  **Clone repository:**
    ```bash
    git clone [https://github.com/username/Inventory-Management.git](https://github.com/username/Inventory-Management.git)
    ```
2.  **Cấu hình Database:**
    * Mở file `appsettings.json`.
    * Chỉnh sửa chuỗi kết nối `ConnectionStrings` phù hợp với SQL Server của bạn.
3.  **Cập nhật Database (Migration):**
    * Mở **Package Manager Console** trong Visual Studio.
    * Chạy lệnh:
        ```bash
        update-database
        ```
4.  **Chạy ứng dụng:**
    * Nhấn `F5` hoặc `Ctrl + F5` trong Visual Studio.

---

## 👤 Tác giả (Author)

**[Tên của bạn]**
* **Role:** Web Developer
* **Email:** [Email của bạn]
* **LinkedIn:** [Link Profile LinkedIn của bạn]

---
*Cảm ơn bạn đã ghé thăm dự án này! Nếu thấy hữu ích, hãy tặng mình 1 ⭐️ nhé.*
