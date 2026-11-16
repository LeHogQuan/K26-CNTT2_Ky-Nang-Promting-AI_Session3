prompt CREATE

c context
bạn là nhân viên phòng đào tạo

r request
chuyển dữ liệu sinh viên thành JSON

e explanation
- gồm fullName, email, status
- status gồm đang học, bảo lưu, nghỉ học
- không thêm hoặc xóa dữ liệu
- không xác định được thì ghi UNKNOWN

a action
đọc dữ liệu, chuẩn hóa trạng thái, chuyển thành JSON và kiểm tra đủ 4 bản ghi

t tone
ngắn gọn, chính xác

e extras
chỉ xuất JSON

kết quả

students
- Nguyễn Văn An, an.nguyen@gmail.com, đang học
- Trần Thị Bình, binhtt@gmail.com, bảo lưu
- Lê Hoàng Nam, nam.le@gmail.com, đang học
- Phạm Minh Đức, duc.pham@gmail.com, nghỉ học

totalRecords: 4
