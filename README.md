Phần 1: Thiết kế và Khởi tạo Cấu trúc Dữ liệu
Phần 2: Xây dựng Function
1. Build-in Functions trong SQL Server
SQL Server chia thành các nhóm chính:
Hàm toán học: ABS, ROUND, CEILING,...
Hàm chuỗi: LEN, UPPER, LOWER, SUBSTRING, REPLACE,...
Hàm ngày tháng: GETDATE, DATEDIFF, DATEPART,...
Hàm tổng hợp (Aggregate): SUM, AVG, COUNT, MIN, MAX.
Hàm hệ thống (System Functions): Dùng để lấy thông tin nội tại của SQL Server.
- 1 vài system function build_in mà em tìm hiểu được: 
HOST_NAME(): Trả về tên máy tính của người dùng đang kết nối.
ISNULL(check_expression, replacement_value): Kiểm tra nếu giá trị là NULL thì thay thế bằng một giá trị khác
2. Mục đích: UDF được viết để đóng gói các logic nghiệp vụ (business logic) lặp đi lặp lại. Thay vì viết lại một đoạn tính toán phức tạp ở 10 câu lệnh khác nhau, bạn chỉ cần gọi hàm.
- Phân loại
Scalar Function (Hàm đơn trị): Trả về một giá trị duy nhất. Dùng khi cần tính toán (thuế, giảm giá, format tên).
Inline Table-Valued Function (Hàm bảng nội tuyến): Trả về một tập kết quả (table). Không có thân hàm phức tạp, chỉ có một câu lệnh RETURN SELECT. Dùng để thay thế các View có tham số.
Multi-statement Table-Valued Function (Hàm bảng đa câu lệnh): Trả về một bảng nhưng có cấu trúc phức tạp, sử dụng nhiều bước xử lý, biến tạm, vòng lặp bên trong.
- Tại sao cần tự viết khi đã có System Functions?
Dù hệ thống có nhiều hàm, nhưng nó không thể biết logic riêng của từng doanh nghiệp. Ví dụ: SQL có hàm cộng trừ, nhưng không có hàm "Tính mức chiết khấu cho khách hàng VIP vào ngày sinh nhật". Đó là lúc cần UDF.
