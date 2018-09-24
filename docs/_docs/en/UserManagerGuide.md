---
title: Quản lý người dùng
permalink: /quan-ly-nguoi-dung
---

### **1. Màn hình quản lý người dùng**
* Đăng nhập với quyền Quản trị, và thực hiện các bước sau:

     ![](assets/usermanager/mnUserManager.png)

     * (1): Hiển thị chức năng
     * (2): Tab Quản Trị
     * (3): Quản lý người dùng

* Màn hình hiển thị như sau:

     ![](assets/usermanager/UserManager.png)

     * (4): Vùng Tìm kiếm dữ liệu
     * (5): Vùng Danh sách các user
     * (6): Nút Thêm – thực hiện thêm mới user
     * (7): Nút Sửa – thực hiện sửa thông tin user
     * (8): Nút Xóa – thực hiện xóa user
     * (9): Nút Tải lại – thực hiện tải lại trang

### **2. Chức năng tìm kiếm**
* Thực hiện tìm kiếm dữ liệu tại vùng Tìm kiếm như hình sau:

     ![](assets/usermanager/UserManagerSearch.png)

     * (1): Tìm kiếm bằng cách nhập tên đăng nhập, tên, email của user
     * (2): Nút Tìm kiếm – thực hiện chức năng tìm kiếm các thông tin được nhập vào và trả về kết quả như hình sau:

     ![](assets/usermanager/UserManagerSearchResult.png)

### **3. Chức năng tạo mới người dùng**
* Nhấn Nút (6) Thêm tại phần 1, hiển thị màn hình Thêm mới người dùng như hình sau:

     ![](assets/usermanager/UserDetailsAdd.png)

* Thông tin người dùng mới
     * (1): Nhập tên đăng nhập của người dùng: tên đăng nhập chứa ký tự từ A-Z và từ 0-9, không có khoảng trắng và không chứa tiếng Việt có dấu. 
     * (2): Nhập mật khẩu cho user. Tối thiểu là 6 ký tự
     * (3): Nhập họ của user
     * (4): Nhập tên của user
     * (5): Nhập email của user. Email phải đúng định dạng: ...@....
     * (6): Chọn ngôn ngữ sử dụng
     * (7): Phân quyền quản trị hay người dùng bình thường
     * (8): Tài khoản có khóa hay không
* Phòng ban
     * (9): Chọn phòng ban trực thuộc (Nếu phòng ban chưa có thực hiện thêm phòng ban mới ở mục hướng dẫn **[Quản lý dữ liệu nền](/quan-ly-du-lieu-nen)** với loại dữ liệu là ***Department Mode***)
* Chứng thực
     * (10): Chọn chế độ chứng thực đăng nhập nội bộ hoặc LDAP (Nếu chế độ chứng thực bằng LDAP chưa có thực hiện thêm chế độ chứng thực mới ở mục hướng dẫn **[Quản lý dữ liệu nền](/quan-ly-du-lieu-nen)** với loại dữ liệu là ***Authentication Mode***) khi chọn chế độ chứng thực dạng LDAP thì phải nhập ***tài khoản principal*** là user sử dụng trong LDAP
* Email thông báo
     * (11): Cấu hình cảnh báo qua email
* Nút chức năng
     * (12): Nút Lưu – thực hiện lưu dữ liệu vừa nhập
     * (13): Nút Tải lại – Tải lại trang
     * (14): Nút Quay lại – Quay lại trang danh sách người dùng

### **4. Chức năng sửa thông tin người dùng**
* Nhấn Nút (7) Sửa tại phần 1, hiển thị màn hình Sửa người dùng như hình sau:

     ![](assets/usermanager/UserDetailsEdit.png)
     
* Thông tin người dùng
     * (1): Nhập họ của user
     * (2): Nhập tên của user
     * (3): Nhập email của user. Email phải đúng định dạng: ....@....
     * (4): Chọn ngôn ngữ sử dụng
     * (5): Phân quyền quản trị hay người dùng bình thường
     * (6): Chọn thẻ có bị khóa hay không
* Phòng ban
     * (7): Chọn phòng ban trực thuộc (Nếu phòng ban chưa có thực hiện thêm phòng ban mới ở mục hướng dẫn **[Quản lý dữ liệu nền](/quan-ly-du-lieu-nen)** với loại dữ liệu là ***Department Mode***)
* Chứng thực
     * (8): Chọn chế độ chứng thực đăng nhập nội bộ hoặc LDAP (Nếu chế độ chứng thực bằng LDAP chưa có thực hiện thêm chế độ chứng thực mới ở mục hướng dẫn **[Quản lý dữ liệu nền](/quan-ly-du-lieu-nen)** với loại dữ liệu là ***Authentication Mode*** sau đó thực hiện tạo thông tin server chứng thực trong mục hướng dẫn Quản lý chứng thực với tên server trùng với mã khi tạo chế độ chứng thực) khi chọn chế độ chứng thực dạng LDAP thì phải nhập ***tài khoản principal*** là user sử dụng trong LDAP
* Email thông báo
     * (9): Cấu hình cảnh báo qua email
* Nút chức năng
     * (10): Nút Quay lại – Quay lại trang danh sách người dùng
     * (11): Nút Thêm – Thêm một người dung mới
     * (12): Nút Lưu – thực hiện lưu dữ liệu vừa nhập
     * (13): Nút Thiết lập mật khẩu – Thiết lập lại mật khẩu cho người dùng
     * (14): Nút Tải lại – Tải lại trang

### **5. Chức năng xóa người dùng**
* Tại màn hình Quản lý người dùng, tại vùng Danh sách người dùng thực hiện xóa 1 người dùng như hình sau:

     ![](assets/usermanager/UserDetailsDelete.png)

     * (1): Chọn người dùng muốn xóa khỏi hệ thống
     * (2): Nút Delete – thực hiện xóa tên user

* Sau khi nhấn vào Nút (2) Xóa thì hiển thị màn hình:

     ![](assets/usermanager/UserDetailsDeleteOK.png)

     * (3): Nút Có – thực hiện xóa thành công
     * (4): Nút Không – không thực hiện xóa

### **6. Chức năng thiết lập lại mật khẩu**
* Tại màn hình (4) Thông tin người dùng, Quản trị viên thực hiện nhấn vào nút (13) Thiết lập lại mật khẩu, màn hình xuất hiện thông tin yêu cầu mật khẩu mới:

     ![](assets/usermanager/UserDetailsChangePass.png)

     * (1): Mật khẩu mới: Nhập mật khẩu mới của người dùng
     * (2): Lặp lại Mật khẩu mới: Nhập lại mật khẩu mới của người dùng giống với (1)
     * (3): Nút Đồng ý: xác nhận thông tin vừa nhập
