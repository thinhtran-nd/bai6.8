# bai6.8
# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Trần Xuân Thịnh
- **Mã số sinh viên:** 24810320263
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI 6.8: HỆ THỐNG QUẢN LÝ BÀN BIDA & DỊCH VỤ GIẢI TRÍ (BILLIARDS CLUB MANAGEMENT SYSTEM)
---

## KẾT QUẢ THỰC HÀNH
1. Màn hình Chính / Tổng quan hệ thống:
<img width="1267" height="715" alt="GD" src="https://github.com/user-attachments/assets/0288e72e-c50d-43a7-a21b-e2b251780c7a" />



2. Màn hình Quản lý Danh mục (CRUD - Thêm/Sửa/Xóa):
<img width="1271" height="710" alt="CN1" src="https://github.com/user-attachments/assets/ef5ad39a-b601-4714-836d-5fdcb02a8be1" />


3. Màn hình Thực thi Nghiệp vụ chính (Lập Hóa đơn / Bán hàng /Chấm công / Đặt phòng):
<img width="1264" height="711" alt="CN2" src="https://github.com/user-attachments/assets/e02d003e-dc23-4295-ab7f-08508ae65e55" />


4. Màn hình Báo cáo - Thống kê:
<img width="1266" height="713" alt="KQ" src="https://github.com/user-attachments/assets/807fb571-21de-490a-9ba5-8596e18731cb" />


## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `SaleDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
