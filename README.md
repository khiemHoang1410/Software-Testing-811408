# Báo cáo Môn học Kiểm thử Phần mềm - Project ProShop eCommerce

Đây là repository chứa mã nguồn và báo cáo chi tiết cho môn học Kiểm thử Phần mềm (Mã học phần: 841408).
Dự án thực hiện kiểm thử trên ứng dụng **ProShop** - một nền tảng thương mại điện tử (eCommerce) đầy đủ tính năng được xây dựng bằng MERN Stack (MongoDB, Express, React, Node.js) và Redux Toolkit.

**Sinh viên thực hiện:**
* **Hoàng Sỹ Khiêm** * **3121410263** ---

## 📂 Giới thiệu Dự án

ProShop là một ứng dụng mua sắm trực tuyến hoàn chỉnh (v2.0), bao gồm các chức năng từ xem sản phẩm, giỏ hàng, thanh toán cho đến quản trị viên quản lý đơn hàng.

### 🛠 Công nghệ sử dụng:
* **Frontend:** React.js, Redux Toolkit, React Bootstrap.
* **Backend:** Node.js, Express.js.
* **Database:** MongoDB (NoSQL).
* **Payment:** PayPal & Credit/Debit Integration.

### ✨ Các tính năng chính (Features):
* **Người dùng:**
    * Giỏ hàng (Shopping Cart) đầy đủ chức năng.
    * Đánh giá và xếp hạng sản phẩm (Reviews & Ratings).
    * Tìm kiếm và Phân trang sản phẩm.
    * Quy trình thanh toán (Checkout) với PayPal/Thẻ tín dụng.
    * Quản lý hồ sơ cá nhân và lịch sử đơn hàng.
* **Quản trị viên (Admin):**
    * Quản lý sản phẩm (Thêm, Sửa, Xóa).
    * Quản lý người dùng.
    * Quản lý chi tiết đơn hàng và trạng thái giao hàng.
* **Hệ thống:**
    * Top sản phẩm nổi bật (Carousel).
    * Database seeder (Tự động tạo dữ liệu mẫu).



---

## 📝 Báo cáo Đồ án (Full Report)

Toàn bộ quá trình phân tích yêu cầu, lập Test Plan, thiết kế Test Case (Manual/Automation), Test API và kết quả kiểm thử được trình bày chi tiết trong báo cáo LaTeX.

### 🔗 [>> CLICK VÀO ĐÂY ĐỂ XEM BÁO CÁO TRÊN OVERLEAF <<](https://www.overleaf.com/read/link_project_cua_ngai_o_day)

*(Giảng viên có thể xem trực tiếp file PDF được build từ Overleaf hoặc xem lịch sử chỉnh sửa tại link trên)*

---

## 🚀 Hướng dẫn Cài đặt & Chạy Project (Local)

Để chạy dự án này trên máy cá nhân, vui lòng thực hiện các bước sau:

### 1. Cấu hình biến môi trường (.env)
Tạo file `.env` ở thư mục gốc và điền các thông tin sau (lấy từ `.env.example`):

```env
NODE_ENV = development
PORT = 5000
MONGO_URI = [Điền MongoDB URI của bạn vào đây]
JWT_SECRET = [Điền chuỗi bí mật bất kỳ]
PAYPAL_CLIENT_ID = [Điền PayPal Client ID của bạn]
PAGINATION_LIMIT = 8