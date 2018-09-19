---
category: 3. New
title: '3.1 Admin guide 01'
layout: nil
---
| [./assets/media/image1.jpeg](./assets/media/image1.jpeg) | **CÔNG TY CỔ PHẦN TMDV TÍN HÒA** |
|--------------------------------------------|----------------------------------|


~   copy-right

**TRIỂN KHAI HỆ THỐNG PHẦN MỀM QUẢN LÝ CHO CÔNG TY XÂY DỰNG**

**TÀI LIỆU HƯỚNG DẪN SỬ DỤNG**

**Mã hiệu dự án: CGS**

**Mã hiệu tài liệu: CGS_ADMINGUIDE_V1.0**

**Phiên bản tài liệu: V1.0**

**TPHCM, 11/09/2018**

**Trang ký**

**CÔNG TY CỔ PHẦN TMDV TÍN HÒA**

Người lập: Nguyễn Bá Thiên \<Ngày\> 11/09/2018

Người xem xét: Lý Cẩm Long \<Ngày\>

QA

Người phê duyệt: Trần Anh Minh Huy \<Ngày\>

GĐDA

**CÔNG TY**

Người phê duyệt: \<Ngày\>

QTDA

GĐDA

Tổng quan tài liệu
==================

Mục đích tài liệu
-----------------

-   Tài liệu này nhằm hướng dẫn sử dụng cho hệ thống phần mềm quản lý cho công
    ty xây dựng **CGS**, hệ thống này được xây dựng, cài đặt và triển khai tại
    Trung tâm và các Công trường.

Phạm vi tài liệu
----------------

*HƯỚNG DẪN CÁC CHỨC NĂNG:*

-   Quản trị hệ thống

Đăng nhập, Đăng xuất và Đổi mật khẩu đăng nhập trong hệ thống
=============================================================

Đăng nhập vào hệ thống
----------------------

-   Nhập vào đường dẫn thông qua web browser vào hệ thống Hiển thị màn hình sau:

    ![](/assets/media/213a541b07a0bf9662fa241523d6b78b.png)

-   (1): Tên đăng nhập - Nhập tên đăng nhập của mình

-   (2): Mật khẩu – Nhập mật khẩu

-   (3): Nhớ mật khẩu – Nhớ mật khẩu cho lần đăng nhập tiếp theo

-   (4): Nhấn nút “Đăng nhập” – Thực hiện đăng nhập vào hệ thống

Các tab chức năng khi đăng nhập thành công
------------------------------------------

-   Hiển thị các chức năng sau khi đăng nhập:

![](/assets/media/51fe1b4a15d2a1cc5cde1fa6ea1acdfa.png)

**Tab chức năng:**

-   (1): Tab Trung tâm

-   (2): Tab Quản trị – dùng để quản lý người dung (user), thiết lập nhóm người
    dung, cấu hình hệ thống…

-   (3): Tab Common – hiển thị thông tin người dùng

-   (4): Tab Báo cáo – thực hiện thêm, xuất các biểu mẫu báo cáo nhập từ file
    excel

**Màn hình Dashboard:**

-   (5): Số liệu tổng quan nhân lực

-   (6): Biểu đồ biến động nhân lực

-   (7): Danh sách vi phạm

-   (8): Danh sách hợp đồng hết hạn

-   (9): Danh sách khóa đào tạo

**Thanh công cụ:**

-   (10): Danh sách Công trường

-   (11): Thông tin phiên bản phần mềm

-   (12): Ngày Hệ thống

-   (13): Người dùng hiện tại

-   (14): Đăng xuất

Đăng xuất khỏi hệ thống
-----------------------

-   Sau khi đăng nhập vào hệ thống thì xuất hiện màn hình hệ thống, Người dùng
    muốn đăng xuất khỏi hệ thống thực hiện các bước sau:

![](/assets/media/345ec8b35921b80a144d284d9bdf9f41.png)

![](/assets/media/906099f7de66367418ab9d83e9a2016a.png)

-   (1): Hiển thị chức năng

-   (2): Nhấn vào button “Đăng xuất” – User thoát khỏi hệ thống

-   (3): Nhấn đồng ý nếu đồng ý thoát khỏi hệ thống

-   (4): Nhấn Hủy nếu không đồng ý thoát khỏi hệ thống

Các module
==========

Các chức năng cơ bản của toàn bộ module trên hệ thống

| **Nút chức năng**  | **Mô tả chức năng**                            |
|--------------------|------------------------------------------------|
| Nút **Thêm**       | Để nhập mới dữ liệu vào cơ sở dữ liệu          |
| Nút **Sửa**        | Để sửa dữ liệu đã nhập vào cơ sở dữ liệu       |
| Nút **Xóa**        | Xóa dữ liệu khỏi cơ sở dữ liệu                 |
| Nút **Lưu**        | Lưu dữ liệu đã nhập vào cơ sở dữ liệu          |
| Nút **Tải lại**    | Khôi phục lại dữ liệu đã lưu vào cơ sở dữ liệu |
| Ô **Tìm kiếm**     | Tìm kiếm dữ liệu                               |
| Nút **Xuất Excel** | Xuất dữ liệu ra excel                          |

Một module là một phần độc lập trong hệ thống, được dùng để thực hiện một nghiệp
vụ nhất định hay đơn giản là gom các chức năng con thành một nhóm. Hệ thống CGS
về cơ bản được xây dựng trên một tập hợp nhiều module với các vai trò khác nhau.

Quản Trị Hệ Thống
-----------------

Việc đầu tiên người quản trị hệ thống cần thực hiện là tạo chế độ chứng thực nếu
sử dụng chứng thực qua LDAP xem hướng dẫn ở mục [Quản Lý Chứng
Thực](#_Quản_lý_LDAP) nếu chứng thực trong internal hệ thống thì bỏ qua bước tạo
chứng thực sau đó tạo tài khoản cho người dùng tương tác với hệ thống. Những
bước cần thực hiện như sau:

### Quản trị người dùng

#### Màn hình tổng quát Thiết lập người dùng

![](/assets/media/1f8754d078b96da6d4ee2db6602566b9.png)

Đăng nhập với quyền Quản trị, và thực hiện các bước sau:

-   (1): Hiển thị chức năng

-   (2): Tab Quản Trị

-   (3): Quản lý người dùng

![](/assets/media/fd8347002586c9bdf0d2e9036402f269.png)

Màn hình hiển thị như sau:

-   (4): Vùng Tìm kiếm dữ liệu

-   (5): Vùng Danh sách các user

-   (6): Nút Thêm – thực hiện thêm mới user

-   (7): Nút Sửa – thực hiện sửa thông tin user

-   (8): Nút Xóa – thực hiện xóa user

-   (9): Nút Tải lại – thực hiện tải lại trang

#### Chức năng tìm kiếm

![](/assets/media/348f5fcbc3dfbac3077ade70b84877c5.png)

Thực hiện tìm kiếm dữ liệu tại vùng Tìm kiếm như hình sau:

-   (1): Tìm kiếm bằng cách nhập tên đăng nhập, tên, email của user

![](/assets/media/2de4a8ce738b8ace35e9dbad9ad18fa6.png)

(2): Nút Tìm kiếm – thực hiện chức năng tìm kiếm các thông tin được nhập vào và
trả về kết quả như hình sau:

1.  Chức năng tạo mới người dùng

    ![](/assets/media/deec5d0e7be06748cbf954aff5dc3e35.png)

    Nhấn Nút (6) Thêm tại phần 1.1, hiển thị màn hình Thêm mới người dùng như
    hình sau:

>   Thông tin người dùng mới

-   (1): Nhập tên đăng nhập của người dùng: tên đăng nhập chứa ký tự từ A-Z và
    từ 0-9, không có khoảng trắng và không chứa tiếng Việt có dấu.

-   (2): Nhập mật khẩu cho user. Tối thiểu là 6 ký tự

-   (3): Nhập họ của user

-   (4): Nhập tên của user

-   (5): Nhập email của user. Email phải đúng định dạng: …\@....

-   (6): Chọn ngôn ngữ sử dụng

-   (7): Phân quyền quản trị hay người dùng bình thường

-   (8): Tài khoản có khóa hay không

    Phòng ban

-   (9): Chọn phòng ban trực thuộc (Nếu phòng ban chưa có thực hiện thêm phòng
    ban mới ở mục hướng dẫn [Quản lý dữ liệu nền](#_Quản_lý_dữ) với loại dữ liệu
    là *Department Mode*)

    Chứng thực

-   (10): Chọn chế độ chứng thực đăng nhập nội bộ hoặc LDAP (Nếu chế độ chứng
    thực bằng LDAP chưa có thực hiện thêm chế độ chứng thực mới ở mục hướng dẫn
    [Quản lý dữ liệu nền](#_Quản_lý_dữ) với loại dữ liệu là *Authentication
    Mode*) khi chọn chế độ chứng thực dạng LDAP thì phải nhập *tài khoản
    principal* là user sử dụng trong LDAP

    Email thông báo

-   (11): Cấu hình cảnh báo qua email

    Nút chức năng

-   (12): Nút Lưu – thực hiện lưu dữ liệu vừa nhập

-   (13): Nút Tải lại – Tải lại trang

-   (14): Nút Quay lại – Quay lại trang danh sách người dùng

#### Chức năng sửa thông tin người dùng

![](/assets/media/7d04fee31797925e7d510a39e30f5045.png)

Nhấn Nút Sửa tại phần 1.1, hiển thị màn hình Sửa người dùng như hình sau:

Thông tin người dùng

-   (1): Nhập họ của user

-   (2): Nhập tên của user

-   (3): Nhập email của user. Email phải đúng định dạng: …\@....

-   (4): Chọn ngôn ngữ sử dụng

-   (5): Phân quyền quản trị hay người dùng bình thường

-   (6): Chọn thẻ có bị khóa hay không

    Phòng ban

-   (7): Chọn phòng ban trực thuộc (Nếu phòng ban chưa có thực hiện thêm phòng
    ban mới ở mục hướng dẫn [Quản lý dữ liệu nền](#_Quản_lý_dữ) với loại dữ liệu
    là *Department Mode*)

    Chứng thực

-   (8): Chọn chế độ chứng thực đăng nhập nội bộ hoặc LDAP (Nếu chế độ chứng
    thực bằng LDAP chưa có thực hiện thêm chế độ chứng thực mới ở mục hướng dẫn
    [Quản lý dữ liệu nền](#_Quản_lý_dữ) với loại dữ liệu là *Authentication
    Mode* sau đó thực hiện tạo thông tin server chứng thực trong mục hướng dẫn
    [Quản lý chứng thực](#_Quản_lý_chứng) với tên server trùng với mã khi tạo
    chế độ chứng thực) khi chọn chế độ chứng thực dạng LDAP thì phải nhập *tài
    khoản principal* là user sử dụng trong LDAP

    Email thông báo

-   (9): Cấu hình cảnh báo qua email

    Nút chức năng

-   (10): Nút Quay lại – Quay lại trang danh sách người dùng

-   (11): Nút Thêm – Thêm một người dung mới

-   (12): Nút Lưu – thực hiện lưu dữ liệu vừa nhập

-   (13): Nút Thiết lập mật khẩu – Thiết lập lại mật khẩu cho người dùng

-   (14): Nút Tải lại – Tải lại trang

#### Chức năng xóa người dùng

![](/assets/media/a842463b606c26657694950aca6b1eb8.png)

Tại màn hình Quản lý người dùng, tại vùng Danh sách người dùng thực hiện xóa 1
người dùng như hình sau:

-   (1): Chọn người dùng muốn xóa khỏi hệ thống

-   (2): Icon Delete – thực hiện xóa tên user

    ![](/assets/media/85e257975dd773f9d77d61493c5561c6.png)

    Sau khi nhấn vào Nút (2) Xóa thì hiển thị màn hình:

-   (3): Nút Có – thực hiện xóa thành công

-   (4): Nút Không – không thực hiện xóa

#### Chức năng thiết lập lại mật khẩu

![](/assets/media/1d32e0e74df341b9a5c22f0d301c37c4.png)

Tại màn hình (4) Thông tin người dùng, Quản trị viên thực hiện nhấn vào nút (10)
Thiết lập lại mật khẩu, màn hình xuất hiện thông tin yêu cầu mật khẩu mới:

-   (1): Mật khẩu mới: Nhập mật khẩu mới của người dùng

-   (2): Lặp lại Mật khẩu mới: Nhập lại mật khẩu mới của người dùng giống với
    (1)

-   (3): Nút Đồng ý: xác nhận thông tin vừa nhập

### Quản lý nhóm người dùng

#### Màn hình tổng quát Quản lý nhóm người dùng

![](/assets/media/7f2dc4ff027b46683b606422f36a2ff9.png)

Đăng nhập với quyền Quản trị và thực hiện các bước sau:

-   (1): Hiển thị chức năng

-   (2): Tab Quản Trị

-   (3): Nhóm Người Dùng

![](/assets/media/924257fe37be3af4fc88a881f03060d0.png)

Màn hình hiển thị như sau:

-   (4): Vùng Tìm kiếm dữ liệu

-   (5): Vùng Danh sách các Nhóm Người Dùng

-   (6): Nút Thêm – thực hiện thêm mới nhóm Người Dùng

-   (7): Nút Sửa – thực hiện sửa thông tin nhóm Người Dùng

-   (8): Nút Xóa – thực hiện xóa nhóm Người Dùng

-   (9): Nút Tải lại – thực hiện tải lại trang

#### Chức năng Thêm Người Dùng Vào Nhóm

![](/assets/media/f7abe35a012fd75b81591e3dd951d2f4.png)

Nhấn nút (6) trên màn hình chính để thực hiện Thêm Người Dùng Vào Nhóm. Màn hình
hiển thị như sau:

-   (1): Chọn Nhóm người dùng.

-   (2): Nhấn nút **Thêm Người Dùng.** Cửa sổ thêm Người dùng sẽ hiển thị như
    sau:

    ![](/assets/media/10762bca9f02178f46a22bf081ed869a.png)

-   (3): Chọn Người dùng cần thêm vào nhóm và nhấn **Đồng Ý.**

#### Chức năng Bỏ Người dùng ra khỏi Nhóm

![](/assets/media/f7abe35a012fd75b81591e3dd951d2f4.png)

Double click vào Nhóm Người Dùng. Màn hình chi tiết Nhóm Người Dùng sẽ hiển thị
như sau:

-   (1): Chọn Người Dùng cần bỏ khỏi nhóm.

-   (2): Nhấn nút Xóa.

#### Chức năng tạo nhóm mới

>   Nếu người dùng thuộc nhóm mới chưa có trong hệ thống thì thực hiện thêm nhóm
>   mới được hướng dẫn ở mục [Quản lý dữ liệu nền](#_Quản_lý_dữ) với loại dữ
>   liệu là **Department Mode.**

### Phân quyền người dùng

#### Màn hình phân quyền người dùng

![](/assets/media/c48e70d1737b8ff0556e77e46d657528.png)

Đăng nhập người dùng có quyền Quản trị và thực hiện các bước sau:

-   (1): Hiển thị chức năng

-   (2): Tab Quản trị

-   (3): Phân quyền người dùng

-   Màn hình hiển thị ra như sau:

    ![](/assets/media/7c0288c85c444ee024817668ecc83e30.png)

-   (4) Danh sách nhóm người dùng

-   (5) Danh sách màn hình mà nhóm người dùng đang được phân quyền

-   (6) Danh sách Vai trò (Roles) mà nhóm người dùng đang được phân quyền (Để
    tạo được danh sách các vai trò vui lòng xem cách tạo ở mục [Quản Lý Vai
    Trò](#_Quản_lý_vai))

#### Cấp và thu hồi quyền

-   Từ màn hình chính, chọn một nhóm người dùng muốn phân quyền.

-   Từ Danh sách màn hình, check (uncheck) vào màn hình hình muốn cấp (thu hồi)
    quyền sử dụng cho nhóm người dùng.

-   Từ Danh sách Vai trò, check (uncheck) vào vai trò muốn cấp (thu hồi) cho
    nhóm người dùng.

### Phân quyền công trường

#### Màn hình phân quyền công trường

![](/assets/media/10a59e4521acfd399a56d822fbe72960.png)

Đăng nhập người dùng có Quyền phân quyền công trường, và thực hiện các bước sau:

-   (1): Hiển thị chức năng

-   (2): Tab Quản trị

-   (3): Phân quyền công trường

![](/assets/media/da27bffb08d874915df6d99427099c5f.png)

Màn hình hiển thị như sau:

-   (4): Vùng phân quyền công trường

-   (5): Nút Tải lại trang hiện tại

#### Chức năng phân quyền công trường

![](/assets/media/8f2a54f5656eda627eceefe774efeea6.png)

Thực hiện phân quyền công trường cho người dùng như hình sau:

-   (1): Chọn nhóm người dùng cần phân quyền

-   (2): Chọn người dùng cần phân quyền với tên được hệ thống liệt kê

-   (3): Chọn Tổng Công ty

-   (4): Chọn Công ty con được liệt kê trực thuộc tổng công ty

-   (5): Chọn Công trường mà người dùng được phép truy cập

-   Hệ thống tự động lưu lại thông tin mà người dùng đã thực hiện phân quyền.

>   *Lưu ý: Xong những bước đã thực hiện trên thì tài khoản người dùng mới được
>   tạo đã có thể đăng nhập vào và sử dụng hệ thống CGS.*

### Quản lý vai trò

#### Màn hình tổng quát Thiết lập vai trò

-   Đăng nhập với quyền Quản trị, và thực hiện các bước sau:

    ![](/assets/media/294656c8fa37f43b1d3402d130cfcbed.png)

-   (1): Hiển thị chức năng

-   (2): Tab Quản trị

-   (3): Quản lý vai trò

![](/assets/media/3842e641b4bd70cd1dc1cdf48b83e5ca.png)

Màn hình hiển thị như sau:

-   (4): Vùng Tìm kiếm dữ liệu

-   (5): Vùng Danh sách các vai trò

-   (6): Nút Thêm – thực hiện thêm mới vai trò

-   (7): Nút Sửa – thực hiện sửa thông tin vai trò và các hành động ứng với vai
    trò

-   (8): Nút Xóa – thực hiện xóa vai trò

-   (9): Nút Tải lại – thực hiện tải lại trang

#### Chức năng tìm kiếm

![](/assets/media/bad9553d8a297f043102eb1cbadc57f4.png)

Thực hiện tìm kiếm dữ liệu tại vùng Tìm kiếm như hình sau:

-   (1): Tìm kiếm bằng cách nhập tên vai trò, mô tả

![](/assets/media/4e377ea96c099ff9dfa1590da6e8f56b.png)

(2): Nút Tìm kiếm – thực hiện chức năng tìm kiếm các thông tin được nhập vào và
trả về kết quả như hình sau:

-   (3): Danh sách kết quả trả về sau khi tìm kiếm

#### Chức năng tạo mới vai trò

![](/assets/media/c05a6bc3919e815c5977507b40142ce0.png)

Nhấn Nút (6) Thêm tại phần 1, hiển thị màn hình Thêm mới vai trò như hình sau:

>   Thông tin vai trò mới

-   (1): Nhập tên vai trò.

-   (2): Nhập mô tả vai trò

-   (3): Chọn cấp cho vai trò

    Thông tin hành động

-   (4): Hành động được thêm sau khi lưu vai trò

    Thông tin điều kiện

-   (5): Điều kiện được thêm sau khi lưu vai trò

    Nút chức năng

-   (6): Nút Tải lại – Tải lại trang

-   (7): Nút Quay lại – Quay lại trang danh sách người dùng

-   (8): Nút Thêm – thực hiện thêm vai trò mới

-   (9): Nút Lưu – thực hiện lưu dữ liệu vừa nhập

    -   Chọn hành động tại mục 4, hiển thị màn hình Thêm mới hành động như hình
        sau:

        ![](/assets/media/39480374d17a1b62511f7114dfc50841.png)

        ![](/assets/media/6144e64fc89f9b31c404ba5aa21808e2.png)

-   (10): Chọn chức năng

-   (11): Cho phép hiển thị control

-   (12): Cho phép thao tác với control

-   (13): Nút Tải lại – Tải lại trang

    Thêm thông tin điều kiện ứng với vai trò nếu có:

    ![](/assets/media/0e2467a29a98dab67574e74288235e17.png)

-   (14): Nút Thêm – thực hiện thêm điều kiện mới

-   (15): Nút Sửa – thực hiện sửa điều kiện đã có

-   (16): Nút Xóa - Xóa điều kiện hiện có

    ![](/assets/media/cd5e2509f2d24e34c8930bb5731d308c.png)

    Màn hình thêm điều kiện

-   (17): Chọn loại điều kiện

-   (18): Điền tên field trên chức năng cần so sánh

-   (19): Chọn loại so sánh

-   (20): Điền giá trị so sánh

-   (21): Nút Đồng Ý – Lưu điều kiện

-   (22): Nút Hủy – Hủy lưu điều kiện

1.  Chức năng sửa thông tin vai trò

    -   Nhấn Nút Sửa tại phần 1.1, hiển thị màn hình Sửa vai trò như hình sau:

![](/assets/media/01e46992caab7d4dd602b75152c1ec95.png)

>   Thông tin vai trò

-   (1): Sửa tên vai trò.

-   (2): Sửa mô tả vai trò

-   (3): Chọn cấp cho vai trò

    Thông tin hành động

![](/assets/media/39480374d17a1b62511f7114dfc50841.png)

(4): Sửa thông tin hành động

-   (12): Chọn chức năng

-   (13): Cho phép hiển thị control

-   (14): Cho phép thao tác với control

-   (15): Nút Tải lại – Tải lại trang

    Thông tin điều kiện

-   (5): Thêm điều kiện

-   (6): Sửa điều kiện

![](/assets/media/cd5e2509f2d24e34c8930bb5731d308c.png)

(16): Chọn loại điều kiện

-   (17): Điền tên field trên chức năng cần so sánh

-   (18): Chọn loại so sánh

-   (19): Điền giá trị so sánh

-   (20): Nút Đồng Ý – Lưu điều kiện

-   (21): Nút Hủy – Hủy lưu điều kiện

-   (7): Xóa điều kiện

    Nút chức năng

-   (6): Nút Tải lại – Tải lại trang

-   (7): Nút Quay lại – Quay lại trang danh sách người dùng

-   (8): Nút Thêm – thực hiện thêm vai trò mới

-   (9): Nút Lưu – thực hiện lưu dữ liệu vừa nhập

    *Lưu ý: Để một chức năng nào đó được áp dụng vai trò thì thực hiện theo
    hướng dẫn ở mục Quản lý chức năng*

### Định nghĩa tham số hệ thống

#### Mục đích chức năng

Hỗ trợ người dùng xem các tham số hệ thống đã được định nghĩa sẵn.

Tham số Hệ thống hỗ trợ trong việc tạo khóa dữ liệu trên toàn hệ thống. Ví dụ
như khóa dữ liệu khi tạo Công nhân, Đội thi công, Hợp đồng công nhân, …

#### Đối tượng sử dụng

Quản trị hệ thống

#### Màn hình chức năng

![](/assets/media/586b0c217ec0e347bb8a794285cdd2ec.png)

Đăng nhập với quyền Quản trị, và thực hiện các bước sau:

-   (1): Hiển thị chức năng

-   (2): Tab Quản trị

-   (3): Tham số hệ thống

![](/assets/media/b36b9c2dfbb0cc1f655c10419c1b3aa6.png)

Màn hình hiển thị như sau:

-   (4): Nút Thêm - Tạo mới Tham số Hệ thống

-   (5): Nút Sửa - Sửa Tham số Hệ thống (Không được phép sửa)

-   (6): Nút Xóa - Xóa Tham số Hệ thống (Không được phép xóa)

-   (7): Nút Tải lại - Tải lại trang

-   (8): Dữ liệu Tham số Hệ thống

#### Chức năng tạo mới Tham số Hệ thống

![](/assets/media/31bab1e7731b60779cd84ca7874c376f.png)

Nhấn nút (4) Thêm để tạo mới Tham số Hệ thống. Màn hình hiển thị như sau:

-   (1): Nút Lưu - Lưu mới Tham số vào hệ thống.

-   (2): Giá trị số.

-   (3): Giá trị ngày tháng.

-   (4): Giá trị liên hệ thống.

-   (5): XT của tham số. Giá trị này được phối hợp với Giá trị số để tạo khóa
    cho dữ liệu trong hệ thống.

-   (6): Mô tả của Tham số.

-   (7): Loại Tham số (là Chuỗi, Số hay Tệp tin).

*Lưu ý: Hiện tại các tham số đã được định nghĩa sẵn, việc tạo tham số sẽ không
ảnh hưởng gì đến hệ thống. Việc tạo thêm tham số hệ thống cũng không tác động gì
đến cách vận hành hiện tại.*

### Quản lý Báo cáo thống kê

#### Mục đích chức năng

Chức năng định nghĩa báo cáo thống kê hỗ trợ người tạo những báo cáo trên hệ
thống dựa trên các câu truy vấn dữ liệu từ cơ cở dữ liệu.

#### Đối tượng sử dụng

Quản trị hệ thống

#### Màn hình chức năng

-   Đăng nhập với quyền Quản trị, và thực hiện các bước sau:

    ![](/assets/media/967ec98e040c8bfe7ea07f0d536cd1a2.png)

-   (1): Hiển thị chức năng

-   (2): Tab Quản trị

-   (3): Quản Lý Báo Cáo Thống Kê

![](/assets/media/6923c6493a80f5e8f3bfff226151cb9c.png)

![](/assets/media/faaddecb9a6157ca2f85af6aebc367f4.png)

Màn hình hiển thị như sau:

-   (4): Nút Thêm - Tạo mới báo cáo

-   (5): Nút Sửa - Sửa báo cáo

-   (6): Nút Tải Lại - Tải lại trang

-   (7): Dữ liệu báo cáo

#### Chức năng tạo báo cáo

![](/assets/media/72563bc11cc9316f53bce82f990a72ba.png)

Nhấn nút (4) Thêm để tạo mới Báo cáo. Màn hình hiển thị như sau:

-   (1) Nút Lưu - Lưu báo cáo vào cơ sở dữ liệu.

-   (2) Nút Chạy thử - Chạy thử báo cáo.

-   (3) Tên báo cáo

-   (4) Mô tả của báo cáo

-   (5) Danh sách toàn bộ bảng cơ sở dữ liệu

-   (6) Lược đồ quan hệ các bảng

-   (7) Bảng truy vấn, dùng để hỗ trợ người dùng viết câu truy vấn trực quan

-   (8) Truy vấn sql

**Hướng dẫn dùng Truy vấn Sql để tạo báo cáo**

1.  Chọn tab Truy vấn Sql.

2.  Nhập trực tiếp câu truy vấn Sql vào ô nhập liệu.

3.  Nhấn chạy thử để xem kết quả.

4.  Nhấn **Lưu** để lưu dữ liệu báo cáo vào cơ sở dữ liệu.

**Hướng dẫn dùng Bảng truy vấn để tạo báo cáo**

1.  Người dùng xác định những trường cần hiển thị trong báo cáo sẽ tương ứng với
    cột nào, bảng nào bên dưới cơ sở dữ liệu.

2.  Người dùng nhấn chuột chọn bảng từ Danh sách bên trái.

![](/assets/media/1c5954c64750632ce7ee7a357208e333.png)

![](/assets/media/528cbd1b2c0e2c6ee102703df33c421d.png)

Chọn các cột cần thiết trong báo cáo. Trên bảng Truy vấn sẽ xuất hiện những cột
được chọn.

1.  Nếu cột được chọn có điều kiện thì nhập vào ô Điều kiện. Lưu ý: các Điều
    kiện cùng cột sẽ AND với nhau, nếu cần điều kiện ‘hoặc’ thì nhập vào các cột
    Or bên cạnh.

2.  Nhấn nút **Chạy thử** để xem kết quả.

3.  Nhấn **Lưu** để lưu dữ liệu báo cáo vào cơ sở dữ liệu.

**Ví dụ 1:** Xuất báo cáo các công nhân nữ trên toàn tập đoàn. Bảng truy vấn sẽ
như sau:

![](/assets/media/fa9f9cf5e0611e3546905d329d819243.png)

**Ví dụ 2:** Xuất báo cáo các công nhân ở công trường Landmark 81 và Đảo Kim
Cương. Bảng truy vấn sẽ như sau:

![](/assets/media/a53cba88f5026ac8a098cf4ee7a01f1f.png)

### Quản lý chứng thực

#### Màn hình tổng quát Quản lý chứng thực

![](/assets/media/c4cdb7ec6980fdab353f2e9ee401bcbb.png)

Đăng nhập người dùng có Quyền Quản lý chứng thực, và thực hiện các bước sau:

-   (1): Hiển thị chức năng

-   (2): Tab Quản trị

-   (3): Quản lý chứng thực

![](/assets/media/897a6805b3cab609d0b62b9aed024f2f.png)

Màn hình hiển thị như sau:

-   (4): Vùng Tìm kiếm dữ liệu

-   (5): Vùng Danh sách các cấu hình chứng thực

-   (6): Nút Thêm – thực hiện thêm mới cấu hình chứng thực

-   (7): Nút Sửa – thực hiện sửa thông tin cấu hình chứng thực

-   (8): Nút Xóa – thực hiện xóa cấu hình chứng thực

-   (9): Nút Tải lại – thực hiện tải lại trang

#### Chức năng tìm kiếm cấu hình

-   Thực hiện tìm kiếm dữ liệu tại vùng Tìm kiếm như hình sau:

![](/assets/media/13cb4ab9c4e1db923d5cb189fdaac9cf.png)

-   (1): Tìm kiếm bằng cách nhập tên chứng thực

-   (2): Nút Tìm kiếm – thực hiện chức năng tìm kiếm các thông tin được nhập vào
    và trả về kết quả

-   (3): Danh sách kết quả trả về sau khi tìm kiếm

#### Chức năng tạo mới cấu hình chứng thực

![](/assets/media/35b9b6f0f45de64d525db2bf51c66153.png)

Nhấn Nút (6) Thêm tại phần 1, hiển thị màn hình Thêm mới cấu hình chứng thực như
hình sau:

-   (1): Nhập Tên Cấu hình chứng thực

-   (2): Nhập tên máy chủ chứng thực

-   (3): Nhập Domain cần chứng thực

-   (4): Nhập Thuộc tính đăng nhập

-   (5): Nhấn Nút Lưu để lưu lại cấu hình vừa nhập

-   (6): Nhấn Nút Thêm để thêm mới hoàn toàn cấu hình chứng thực khác

-   (7): Nhấn Nút Tải lại để tải lại trang hiện tại

-   (8): Nhập Nút Quay lại để trở về trang quản lý cấu hình

#### Chức năng sửa thông tin cấu hình chứng thực

![](/assets/media/8d3fb9e55701868ded1f0181d9c351e8.png)

Nhấn Nút (7) Sửa tại phần 1, hiển thị màn hình Sửa cấu hình chứng thực như hình
sau:

-   (1): Tên Cấu hình chứng thực không thể thay đổi

-   (2): Nhập tên máy chủ chứng thực

-   (3): Nhập Domain cần chứng thực

-   (4): Nhập Thuộc tính đăng nhập

-   (5): Nhấn Nút Lưu để lưu lại cấu hình vừa nhập

-   (6): Nhấn Nút Thêm để thêm mới hoàn toàn cấu hình chứng thực khác

-   (7): Nhấn Nút Tải lại để tải lại trang hiện tại

-   (8): Nhập Nút Quay lại để trở về trang quản lý cấu hình chứng thực
