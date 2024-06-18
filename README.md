# QUẢN LÝ CỬA HÀNG ĐIỆN THOẠI

+ Tác giả: Đặng Trung Dũng
+ Mssv: K215480106138
+ Lớp: K57KMT.01

## Mô tả bài toán: 
__1. Quản lý sản phẩm__
- Thêm, sửa, xoá sản phẩm
- Tìm kiến, lọc sản phẩm theo các tiêu chí của người dùng
- Xem thông tin chi tiết từng sản phẩm
- Xem số lượng tồn kho của mỗi sản phẩm

__2. Quản lý nhà cung cấp__
- Thêm, xóa, sửa thông tin nhà cung cấp
- Theo dõi và quản lý các đơn hàng nhập từ nhà cung cấp.

__3. Quản lý bán hàng__
- Tạo đơn hàng: Ghi nhận thông tin khách hàng, sản phẩm mua, số lượng, giá cả.
- Thanh toán: Hỗ trợ các phương thức thanh toán khác nhau (tiền mặt, thẻ, chuyển khoản).
- Xuất hóa đơn: Tạo và in hóa đơn cho khách hàng.

__4. Quản lý khách hàng__
- Thêm, xóa, sửa thông tin khách hàng
- Lưu trữ và truy vấn các đơn hàng đã mua của khách hàng.

**Thông tin cụ thể các bảng như sau:**
- Sản phẩm : 🔑Mã sản phẩm, tên sản phẩm, thương hiệu, thông số, giá, số lượng còn lại. 
- Khách hàng: 🔑 Mã khách hàng, tên khách hàng, số điện thoại, địa chỉ. 
- Đơn hàng: 🔑 Mã đơn hàng, mã khách hàng, ngày đặt hàng, tổng tiền. 
- Chi tiết đơn hàng: 🔑Mã chi tiết đơn hàng, mã đơn hàng, mã sản phẩm, số lượng, giá. 
- Nhà cung cấp: 🔑Mã nhà cung cấp, tên nhà cung cấp, tên người liên hệ, số điện thoại người liên hệ, địa chỉ. 

__1. Bảng sản phẩm__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/6960ce27-b843-49b7-9b24-6fa20e4124d8)

__2. Bảng Nhà Cung Cấp__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/c0d1d38d-b11c-4f29-8df4-5e45c515b31d)

__3. Bảng khách hàng__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/d40233b9-3a44-4a1d-a76a-7d817791355c)

__4. Bảng đơn hàng__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/467d0517-7250-43d6-bb57-9ef094c50049)

__5. Bảng chi tiết đơn hàng__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/7180d214-a5e1-44bf-904d-334976075a30)

__Sơ đồ thực thể liên kết giữa các bảng__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/013dc261-d799-4d48-be04-009773308295)

__Thêm dữ liệu vào các bảng__
__1. Bảng sản phẩm__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/390c4bfe-9b84-41ab-b69b-3eb107a44a25)

__2. Bảng Nhà Cung Cấp__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/66ae8f56-3be6-4563-ae19-517b578c4772)

__3. Bảng khách hàng__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/7004f897-bb2c-48c4-837c-71b0040a3958)

__4. Bảng đơn hàng__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/477888ce-d109-4ebd-83c8-31f474fa2ca1)

__5. Bảng chi tiết đơn hàng__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/ee31e5a5-551d-43c4-b8e9-317e5caaab42)

## XÂY DỰNG CÁC THỦ TỤC
__1. Quản lý việc bán hàng__
- Thêm, sửa, xoá sản phẩm
- Tìm kiếm sản phẩm, lọc sản phẩm theo các tiêu chí của người quản lý hoặc của khách hàng
- Xem thông tin chỉ tiết mỗi sản phẩm
- Doanh thu của một ngày, một tháng,...
- Số lượng sản phẩm bán chạy nhất.

__2. Quản lý kho __
- Thống kê số lượng hàng trong kho
- Báo cáo tình trạng hàng trong kho, số hàng tồn, số hàng đã hết chưa nhập về.

----

__1.	Liệt kê sản phẩm bán được trong một ngày__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/cb5e67e0-0f74-4ab0-b27b-98eaf2fcec27)

__2.	Tìm kiếm thông tin khách hàng__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/2e2a700c-9584-4798-bafd-076ed69d9358)

__3.	Tìm kiếm sản phẩm__
 
![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/6db34329-b77b-43a9-93f1-750b5583e8ca)
 
__4.	Tính tổng tiền hóa đơn__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/39480b42-fc4e-48cb-8ef7-4e0d72c5dce6)

__5.	Chỉnh sửa hóa đơn__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/c497e213-8721-4803-9832-3506f5596d09)

__6.	Xóa sản phẩm__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/cb9b1a97-1b64-4643-9288-7694d438b440)

__7.	Xem chi tiết một sản phẩm__

![image](https://github.com/Trungdung090/BTL_SQL/assets/168762836/ca4421f9-8a2f-43ec-b73e-0a6ea0cd1146)

