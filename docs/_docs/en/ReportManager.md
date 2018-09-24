---
title: Quản lý báo cáo thống kê
permalink: /quan-ly-bao-cao-thong-ke
---

### **1. Mục đích chức năng**
* Chức năng định nghĩa báo cáo thống kê hỗ trợ người tạo những báo cáo trên hệ thống dựa trên các câu truy vấn dữ liệu từ cơ cở dữ liệu.

### **2. Màn hình chức năng**
* Đăng nhập với quyền Quản trị, và thực hiện các bước sau:

     ![](assets/reportmanager/mnReportManager.png)

     * (1): Hiển thị chức năng
     * (2): Tab Quản Trị
     * (3): Quản lý báo cáo thống kê

* Màn hình hiển thị như sau:

     ![](assets/reportmanager/ReportManager.png)

     * (4): Vùng Tìm kiếm dữ liệu
     * (5): Vùng Danh sách các báo cáo
     * (6): Nút Thêm - Tạo mới báo cáo
     * (7): Nút Sửa - Sửa báo cáo
     * (8): Nút Tải Lại - Tải lại trang

### **3. Chức năng tìm kiếm**
* Thực hiện tìm kiếm dữ liệu tại vùng Tìm kiếm như hình sau:

     ![](assets/reportmanager/ReportManagerSearch.png)

     * (1): Tìm kiếm bằng cách nhập tên báo cáo, mô tả
     * (2): Nút Tìm kiếm – thực hiện chức năng tìm kiếm các thông tin được nhập vào và trả về kết quả như hình sau:

     ![](assets/reportmanager/ReportManagerSearchResult.png)

     * (3): Danh sách kết quả trả về sau khi tìm kiếm

### **4. Chức năng tạo mới báo cáo**
* Nhấn Nút (6) Thêm tại phần 1, hiển thị màn hình Thêm mới báo cáo như hình sau:

     ![](assets/reportmanager/ReportDetailsAdd.png)

     * (1) Nút Lưu - Lưu báo cáo vào cơ sở dữ liệu
     * (2) Nút Chạy thử - Chạy thử báo cáo
     * (3) Tên báo cáo
     * (4) Mô tả của báo cáo
     * (5) Danh sách toàn bộ bảng cơ sở dữ liệu
     * (6) Lược đồ quan hệ các bảng
     * (7) Bảng truy vấn, dùng để hỗ trợ người dùng viết câu truy vấn trực quan
     * (8) Truy vấn sql

* **Hướng dẫn dùng Truy vấn Sql để tạo báo cáo**
     1.	Chọn tab Truy vấn Sql
     2.	Nhập trực tiếp câu truy vấn Sql vào ô nhập liệu
     3.	Nhấn chạy thử để xem kết quả
     4.	Nhấn **Lưu** để lưu dữ liệu báo cáo vào cơ sở dữ liệu

* **Hướng dẫn dùng Bảng truy vấn để tạo báo cáo**
     1.	Người dùng xác định những trường cần hiển thị trong báo cáo sẽ tương ứng với cột nào, bảng nào bên dưới cơ sở dữ liệu.
     2.	Người dùng nhấn chuột chọn bảng từ Danh sách bên trái

        ![](assets/reportmanager/ReportDetailsTableQuery.png)

     3.	Chọn các cột cần thiết trong báo cáo. Trên bảng Truy vấn sẽ xuất hiện những cột được chọn

        ![](assets/reportmanager/ReportDetailsTableQuerySelectColumn.png)

     4.	Nếu cột được chọn có điều kiện thì nhập vào ô Điều kiện. *Lưu ý:* các Điều kiện cùng cột sẽ AND với nhau, nếu cần điều kiện 'hoặc' thì nhập vào các cột Or bên cạnh
     5.	Nhấn nút **Chạy thử** để xem kết quả
     6.	Nhấn **Lưu** để lưu dữ liệu báo cáo vào cơ sở dữ liệu

* **Ví dụ 1:** Xuất báo cáo các công nhân nữ trên toàn tập đoàn. Bảng truy vấn sẽ như sau:

     ![](assets/reportmanager/ReportDetailsvd1.png)

* **Ví dụ 2:** Xuất báo cáo các công nhân ở công trường Landmark 81 và Đảo Kim Cương. Bảng truy vấn sẽ như sau:

     ![](assets/reportmanager/ReportDetailsvd2.png)

* **Lưu ý:** Sau khi tạo xong mẫu báo cáo thống kê việc tiếp theo để người dùng có thể sử dụng được báo cáo vừa tạo cần thực hiện những bước sau:

     1. Vào phần hướng dẫn [Quản lý chức năng](/quan-ly-chuc-nang) thực hiện thêm chứ năng mới với URL là: **~/Core/DynamicReports/DynamicReport.aspx?REPORT=BC** với **BC** là tên báo cáo vừa tạo
     2. Thực hiện phân quyền chức năng vừa tạo cho user xem hướng dẫn [Phân quyền người dùng](/phan-quyen-nguoi-dung)

### **5. Chức năng sủa báo cáo thống kê**
* Nhấn Nút (7) Sửa tại phần 1, hiển thị màn hình sửa báo cáo như hình sau:

     ![](assets/reportmanager/ReportDetailsEdit.png)

     * (1): Tên báo cáo
     * (2): Mô tả báo cáo
     * (3): Câu truy vẫn     
* Nút chức năng
     * (4): Nút Quay lại – Quay lại trang danh sách báo cáo
     * (5: Nút Tải lại – Tải lại trang
     * (6) Nút Lưu - Lưu báo cáo vào cơ sở dữ liệu
     * (7) Nút Chạy thử - Chạy thử báo cáo