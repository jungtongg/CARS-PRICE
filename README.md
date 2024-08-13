Mục tiêu chính của hệ thống này là tạo ra một mô hình học máy có thể phân tích các thuộc 
tính của xe và dự đoán giá trị thị trường hiện tại của xe một cách chính xác và đáng tin cậy. 
Hệ thống này sẽ giúp người dùng dễ dàng đánh giá giá trị của xe trong các giao dịch mua bán,
từ đó tối ưu hóa quyết định mua bán xe.

Thu thập dữ liệu: Thu thập một bộ dữ liệu xe trên trang web Kaggle.

Thống kê dữ liệu mẫu: Sử dụng ngôn ngữ lập trình python để thống kê và trực quan hóa
dữ liệu, từ đó giúp hiểu rõ về mối quan hệ giữa các biến độc lập và biến mục tiêu.
Xử lý và làm sạch dữ liệu:
• Loại bỏ khoảng trắng dư thừa trong cột Model.
• Chuyển cột Price từ kiểu int sang kiểu float.
• Biến đổi phân bố của cột Mileage.
• Kiểm tra và xử lý dữ liệu ngoại lệ của các cột sau: Mileage, Mpg, EngineSize.
• Chuyển đổi các dữ liệu định danh thành dạng số đối với các cột sau: Model, Transmission, FuelType và Manufacturer.
• Chuẩn hoá dữ liệu của tập dữ liệu huấn luyện và tập dữ liệu kiểm tra.

Chọn và xây dựng mô hình: Áp dụng thuật toán KNN để huấn luyện mô hình trên tập dữ
liệu huấn luyện và điều chỉnh các tham số của mô hình.

Đánh giá mô hình: Sử dụng các chỉ số đánh giá có thể bao gồm: MSE (Mean Squared
Error) và R2(R-squared).

Triển khai mô hình: Sau khi mô hình đạt được độ chính xác mong muốn, triển khai mô
hình để dự đoán giá xe trên tập dữ liệu kiểm tra.

Ứng dụng mô hình: Mô tả ứng dụng mô hình (dự báo với dữ liệu mới hay mô tả các trường
hợp ứng dụng khác của các mô hình không giám sát).
