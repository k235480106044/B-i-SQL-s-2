Sinh viên thực hiện: Bùi Hoàng Long

Mã sinh viên: K235480106044

Lớp: K59KMTK01

NỘI DUNG YÊU CẦU (GỒM 5 PHẦN):

Phần 1: Thiết kế và Khởi tạo Cấu trúc Dữ liệu (Kiến thức 6, 7)

Sinh viên tự chọn một chủ đề quản lý (Ví dụ: Quản lý thư viện, Quản lý khách sạn, hoặc Quản lý dự án, HOẶC BẤT KỲ BÀI TOÁN QUẢN LÝ NÀO KHÁC).

Tạo một Database mới với tên [Tên dự án]_[MaSV]. //LƯU Ý PHẢI CÓ MÃ SV CÁ NHÂN Ở TÊN CỦA DB ĐÚNG NHƯ YÊU CẦU, vd: QuanLyKhachSan_K123456789

Tạo ít nhất 3 bảng có quan hệ với nhau. Yêu cầu:

Sử dụng đa dạng các kiểu dữ liệu (Số nguyên, số thực, chuỗi ký tự Unicode, ngày tháng, tiền tệ, ...).

Áp dụng đúng quy tắc đặt tên (BướuLạcĐà).

Sử dụng cặp ngoặc [ ] để bọc tên bảng và tên trường trong script khởi tạo.

Có giải thích chỗ nào là PK, chỗ nào là FK, trường nào có ràng buộc cứng CK (ví dụ điểm từ 0..10),...

Phần 2: Xây dựng Function (Kiến thức 8, 9)
Hãy cho biết trong SQL Server có những loại function build_in (hàm có sẵn) nào, nêu 1 vài system function build_in mà em tìm hiểu được (ko cần nhiều, cần đặc sắc theo góc nhìn của em), cho SQL khai thác các hàm đó.

Hàm do người dùng tự viết trong SQL thường mang mục đích gì? Nó có những loại nào? Mỗi loại thường được dùng khi nào? Tại sao có nhiều system function rồi mà vẫn cần tự viết fn riêng?

Viết 01 Scalar Function (Hàm trả về một giá trị): Đưa ra 1 logic cho cơ sở dữ liệu của em, mà cần dùng đến function này. (SV TỰ NGHĨ RA YÊU CẦU CỦA HÀM VÀ VIẾT HÀM GIẢI QUYẾT NÓ)

Sau khi đã có hàm, viết câu lệnh sql khai thác hàm đó.

Viết 01 Inline Table-Valued Function: Trả về danh sách các bản ghi theo một điều kiện lọc cụ thể (SV TỰ NGHĨ RA YÊU CẦU CỦA HÀM VÀ VIẾT HÀM GIẢI QUYẾT NÓ)

Sau khi đã có hàm, viết câu lệnh sql khai thác hàm đó.

Viết 01 Multi-statement Table-Valued Function: Thực hiện xử lý logic phức tạp bên trong (có sử dụng biến bảng) trước khi trả về kết quả. (SV TỰ NGHĨ RA YÊU CẦU CỦA HÀM VÀ VIẾT HÀM GIẢI QUYẾT NÓ)

Sau khi đã có hàm, viết câu lệnh sql khai thác hàm đó.

Phần 3: Xây dựng Store Procedure (Kiến thức 10)
Trong SQL Server có những SP có sẵn nào? nêu 1 vài system sp mà em tìm hiểu được, giải thích cách dùng chúng.

Viết 01 Store Procedure đơn giản để thực hiện lệnh INSERT hoặc UPDATE dữ liệu, có kiểm tra điều kiện logic (SV TỰ NGHĨ RA YÊU CẦU CỦA SP VÀ VIẾT SP GIẢI QUYẾT NÓ)

Viết 01 Store Procedure có sử dụng tham số OUTPUT để trả về một giá trị tính toán (SV TỰ NGHĨ RA YÊU CẦU CỦA SP VÀ VIẾT SP GIẢI QUYẾT NÓ, SP NÀY CÓ DÙNG THAM SỐ LOẠI OUTPUT)

Viết 01 Store Procedure trả về một tập kết quả (Result set) từ lệnh SELECT sau khi đã join nhiều bảng. (SV TỰ NGHĨ RA YÊU CẦU CỦA SP VÀ VIẾT SP GIẢI QUYẾT NÓ)

Phần 4: Trigger và Xử lý logic nghiệp vụ (Kiến thức 11)
Viết 01 Trigger để tự động làm gì đó tại 1 bảng B khi mà dữ liệu thay đổi dữ liệu ở bảng A. Logic giải quyết do sv tự nghĩ ra, sao cho thực tế và thuyết phục.

Thử viết Trigger cho Bảng A : Khi insert thì cập nhật dữ liệu vào bảng B; sau đó viết trigger cho bảng B để khi B được cập nhật thì cập nhật sang bảng A : Quan sát các thông báo (nếu có) của hệ thống, giải thích các thông báo đó (nếu có). Đưa ra nhật xét cuối cùng về tình trạng này.

Phần 5: Cursor và Duyệt dữ liệu (Kiến thức 11)
Viết một đoạn script sử dụng CURSOR để duyệt qua danh sách của 1 câu lệnh SQL dạng SELECT, duyệt qua từng bản ghi, xử lý riêng từng bản ghi (THEO LOGIC SV TỰ ĐẶT RA: SAO CHO HỢP LÝ VÀ THUYẾT PHỤC)

Tìm cách không sử dụng CURSOR để giải quyết bài toán mà em đã dùng CURSOR mới giải quyết được ở trên. thử so sánh tốc độ giữa có dùng cursor và không dùng cursor (nếu cùng kết quả) thì thời gian xử lý cái nào nhanh hơn, cần ảnh chụp màn hình minh chứng.

Nếu vẫn tìm được cách dùng SQL để giải quyết vấn đề mà ko cần CURSOR: thử nghĩ bài toán khác, mà chỉ CURSOR mới giải quyết được, còn SQL rất khó giải quyết đc (theo logic suy nghĩ của em)

Phần 1: Thiết kế và Khởi tạo Cấu trúc Dữ liệu

<img width="2519" height="1599" alt="Ảnh chụp màn hình 2026-04-30 090130" src="https://github.com/user-attachments/assets/9ffe9818-17cc-427c-b50a-50625763bb9f" />
Chú thích: tạo Database về đề tài QuanLyBanLaptop

<img width="2558" height="1599" alt="Ảnh chụp màn hình 2026-04-30 090240" src="https://github.com/user-attachments/assets/eebaf90d-680a-4c7e-8cd9-acd13cbd8074" />
Chú thích: Tạo 3 bảng [NhanVien], [SanPham], [HoaDon] với các yêu cầu của đề 

<img width="2559" height="1599" alt="Ảnh chụp màn hình 2026-04-30 090454" src="https://github.com/user-attachments/assets/2e334381-ec5b-4549-a73e-0c487bb84879" />
Chú thích: Tạo dữ liệu cho từng bảng


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

2. Hàm do người dùng tự viết trong SQL thường mang mục đích gì? Nó có những loại nào? Mỗi loại thường được dùng khi nào? Tại sao có nhiều system function rồi mà vẫn cần tự viết fn riêng?

Mục đích: UDF được viết để đóng gói các logic nghiệp vụ (business logic) lặp đi lặp lại. Thay vì viết lại một đoạn tính toán phức tạp ở 10 câu lệnh khác nhau, bạn chỉ cần gọi hàm.

- Phân loại:

Scalar Function (Hàm đơn trị): Trả về một giá trị duy nhất. Dùng khi cần tính toán (thuế, giảm giá, format tên)

Inline Table-Valued Function (Hàm bảng nội tuyến): Trả về một tập kết quả (table). Không có thân hàm phức tạp, chỉ có một câu lệnh RETURN SELECT. Dùng để thay thế các View có tham số.

Multi-statement Table-Valued Function (Hàm bảng đa câu lệnh): Trả về một bảng nhưng có cấu trúc phức tạp, sử dụng nhiều bước xử lý, biến tạm, vòng lặp bên trong.

- Tại sao cần tự viết khi đã có System Functions?

Dù hệ thống có nhiều hàm, nhưng nó không thể biết logic riêng của từng doanh nghiệp. Ví dụ: SQL có hàm cộng trừ, nhưng không có hàm "Tính mức chiết khấu cho khách hàng VIP vào ngày sinh nhật". Đó là lúc cần UDF.

<img width="2559" height="1599" alt="Ảnh chụp màn hình 2026-04-30 090736" src="https://github.com/user-attachments/assets/7d350d9a-6737-4633-9d50-a28ca738e8c9" />
Chú thích: Tạo hàm fn_TinhThanhTienSauVAT để tính tiền cho một dòng sản phẩm (Số lượng * Giá * 1.1). Đây là hàm trả về một giá trị đơn.

<img width="1280" height="800" alt="Ảnh chụp màn hình 2026-04-30 090839" src="https://github.com/user-attachments/assets/298f5ad7-23c2-44e1-881d-78bb15d7d060" />
Chú thích: Tạo hàm fn_HoaDonTheoNhanVien để trả về một bảng danh sách các hóa đơn do một nhân viên cụ thể phụ trách.

<img width="2559" height="1599" alt="Ảnh chụp màn hình 2026-04-30 090940" src="https://github.com/user-attachments/assets/7dde3ead-3e57-4a28-8082-dd041e3320e4" />
Chú thích: Tạo hàm fn_DanhSachHoaDonDayDu xử lý logic phức tạp hơn (sử dụng biến bảng @KetQua) để gộp dữ liệu từ nhiều bảng và tính toán thuế VAT trước khi trả về kết quả cuối cùng.

Phần 3: Xây dựng Store Procedure

1. SQL Server có những SP có sẵn nào? nêu 1 vài system sp mà em tìm hiểu được, giải thích cách dùng chúng.
   
SQL Server cung cấp các SP có sẵn (thường bắt đầu bằng tiền tố sp_) để giúp quản trị viên quản lý hệ thống mà không cần viết các truy vấn phức tạp vào các bảng hệ thống.

- 1 vài system sp mà em tìm hiểu được:
  
sp_help: Cung cấp thông tin chi tiết về bất kỳ đối tượng nào (bảng, view, index). Rất hữu ích khi bạn quên cấu trúc bảng.

Cách dùng: EXEC sp_help '[DanhMucSanPham]';

sp_rename: Dùng để đổi tên một đối tượng (bảng hoặc cột) mà không cần xóa đi tạo lại.

Cách dùng: EXEC sp_rename 'TenCu', 'TenMoi';

<img width="1280" height="800" alt="Ảnh chụp màn hình 2026-04-30 091214" src="https://github.com/user-attachments/assets/1b10c632-cef9-4075-b3ba-c7959e95ed01" />
Chú thích: Tạo thủ tục sp_ThenHoaDon để bán hàng. Thủ tục này có logic kiểm tra: Nếu số lượng mua lớn hơn số lượng tồn trong kho thì báo lỗi, ngược lại thì tiến hành trừ kho và thêm hóa đơn.

<img width="2559" height="1599" alt="Ảnh chụp màn hình 2026-04-30 091448" src="https://github.com/user-attachments/assets/9a82f4cf-07ca-46d5-86e5-5f3addaa604b" />
Chú thích: Tạo thủ tục sp_TinhTongTienHoaDon sử dụng biến @TongTien MONEY OUTPUT để tính và trả về giá trị tổng tiền của một hóa đơn cụ thể cho chương trình gọi nó.

<img width="2559" height="1599" alt="Ảnh chụp màn hình 2026-04-30 091630" src="https://github.com/user-attachments/assets/50bc9191-8841-472d-8b1d-e5f3dd0499b3" />
Chú thích: Tạo thủ tục sp_DanhSachHoaDon thực hiện JOIN 3 bảng (HoaDon, NhanVien, SanPham) để xuất ra báo cáo chi tiết: Tên nhân viên nào đã bán sản phẩm gì, số lượng bao nhiêu.

Phần 4: Trigger và Xử lý logic nghiệp vụ (Kiến thức 11)

<img width="2559" height="1599" alt="Ảnh chụp màn hình 2026-04-30 100412" src="https://github.com/user-attachments/assets/8bcae63b-e6e7-4ec3-8033-514c24a501b8" />
Chú thích: Kiểm tra lại bảng [SanPham], [HoaDon]

<img width="2559" height="1599" alt="Ảnh chụp màn hình 2026-04-30 095716" src="https://github.com/user-attachments/assets/67562601-200d-4559-9ab6-528e0e65702e" />




