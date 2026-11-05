# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Nguyễn Khánh Đức
- **Mã số sinh viên:** 24810320072
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** Bài 6.1: HỆ THỐNG QUẢN LÝ BÁN HÀNG & SIÊU THỊ MINI (RETAIL
SALES SYSTEM)
---

## KẾT QUẢ THỰC HÀNH

- Giao diện chính
<img width="1565" height="992" alt="Screenshot 2026-11-05 143450" src="https://github.com/user-attachments/assets/2172c194-68ef-4532-a8ff-671d6faf71bd" />

- Xác nhận thanh toán thành công
<img width="1548" height="980" alt="Screenshot 2026-11-05 143556" src="https://github.com/user-attachments/assets/855716fd-9be0-4892-85cc-3e54f94f87b6" />

- Hiển thị top 5 sản phẩm bán chạy nhất
<img width="1557" height="994" alt="Screenshot 2026-11-05 143604" src="https://github.com/user-attachments/assets/5b3d4cb8-8937-495a-9667-a548d9ff3d9c" />

## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `SaleDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
