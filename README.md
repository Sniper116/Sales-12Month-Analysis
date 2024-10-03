# 🛍Sales-12Month-Analysis

## ✏️Các thao tác chính bao gồm
Dự án tập trung phân tích kết quả hoạt động kinh doanh của 1 cửa hàng bán hàng online bằng cách khai thác dữ liệu từ 12 file hóa đơn bán hàng của 12 tháng với các thao tác chính gồm:
- Sử dụng thư viện pandas để đọc và ghép 12 file thành 1 file tổng hợp và thực hiện tiền xử lý dữ liệu.
- Sử dụng thư viện os để xác định đường dẫn đến thư mục các file.
- Sử dụng thư viện seaborn để tạo heatmaps và boxplots, giúp phân tích và trực quan hóa mối quan hệ giữa các biến, cũng như xác định các ngoại lệ trong dữ liệu.
- Sử dụng thư viện matplotlib tạo các biểu đồ và trực quan hóa dữ liệu.
## ✏️Thông tin dữ liệu (Dataset)
- Order ID: Mã hóa đơn theo sản phẩm được mua của khách hàng. Order ID có thể trùng lặp vì khách hàng có thể mua nhiều sản phẩm trong 1 đơn.
- Product: Tên của sản phẩm trên hóa đơn.
- Quantity Ordered: Số lượng sản phẩm được mua trong hóa đơn.
- Price Each: Giá sản phẩm trên hóa đơn.
- Order Date: Thời gian đặt hàng trên hóa đơn.
- Purchase Address: Địa chỉ của khách hàng bao gồm số địa chỉ nhà, tên thành phố, tên bang, mã zipcode (được ngă cách nhau bởi dấu phẩy).
