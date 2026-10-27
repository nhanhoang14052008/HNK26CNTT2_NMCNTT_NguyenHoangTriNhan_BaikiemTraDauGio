# H1

- [x]   Kiểm tra file log và cấu trúc thư mục dự án.
- [x]   Kiểm tra các dòng log có mức độ `ERROR` và `CRITICAL`.
-  [ ]  Đối soát mã linh kiện và tên thiết bị trong Excel.
-  [ ] Kiểm tra dung lượng RAM và ngày lắp đặt của trạm.
-  [ ] Kiểm tra báo cáo sự cố sau khi chạy script.

Tên thiết bị |	Đơn giá |	Loại storage
|-|-|-
Thiết bị sensor-01 |	500000 |	SSD
Thiết bị sensor-02 |	750000 |	HDD
Thiết bị sensor-03 |	1200000 |	SSD

Thành phần |	Mô tả
|-|-
Input |	File log-he-thong.log chứa nhật ký máy chủ với thời gian, mức độ log, thiết bị và nội dung sự kiện.
Process |	Sử dụng PowerShell đọc file bằng Get-Content, kết hợp pipeline `
Output |	File backup/bao-cao-su-co.txt chứa thông tin báo cáo và danh sách các sự cố được lọc.


Phát biểu |	Tầng DIKW |	Giải thích
|-|-|-
(a) “Quyết định thay modem trạm sensor-03 trước thứ Sáu.” |	Wisdom (Trí tuệ) |	Đưa ra quyết định và hành động cụ thể dựa trên thông tin, tri thức đã có.
(b) “2026-10-12 08:15:01 [ERROR] sensor-03 Connection TIMEOUT after 30s” |	Data (Dữ liệu) |	Bản ghi sự kiện thô, gồm thời gian, mức độ lỗi, thiết bị và nội dung.
(c) “Hôm nay hệ thống ghi nhận 8 sự cố, trong đó 4 sự cố đến từ trạm sensor-03.” |	Information (Thông tin) |	Dữ liệu đã được tổng hợp thành số liệu có ý nghĩa.
(d) “Trạm sensor-03 hay mất kết nối vào buổi chiều do sóng yếu, nên cần lắp thêm anten.” |	Knowledge (Tri thức) |	Nhận diện quy luật, xác định nguyên nhân và đưa ra hướng xử lý dựa trên kinh nghiệm hoặc phân tích.



