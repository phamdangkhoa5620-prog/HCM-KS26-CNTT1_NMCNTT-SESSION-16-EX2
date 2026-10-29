## 1\. Bản thiết kế phân quyền

Áp dụng **Quy tắc Cờ Đỏ Bảo mật**: dữ liệu có SĐT và mức lương phải giới hạn người truy cập, đặt phạm vi **Restricted**, chỉ cấp quyền tối thiểu cần thiết.

|Đối tượng|Quyền|Phạm vi|
|-|-|-|
|Trưởng phòng nhân sự|Editor|Restricted|
|Trưởng các bộ phận|Commenter|Restricted|
|Nhân viên không liên quan|Không cấp quyền|Restricted|
|Ứng viên bên ngoài|Thu hồi quyền ngay|Restricted|

* **Viewer:** Chỉ xem dữ liệu.
* **Commenter:** Xem và nhận xét, không sửa trực tiếp dữ liệu gốc.
* **Editor:** Xem, sửa và có thể chia sẻ tùy thiết lập.
* **Suggesting Mode:** Với Google Docs, bật chế độ đề xuất để chỉnh sửa chờ duyệt. Với bảng tính, dùng bình luận hoặc bản sao riêng vì chế độ này không áp dụng giống Docs.

## 2\. Kịch bản xử lý sự cố trong 3 bước

### Bước 1: Thu hồi quyền ngay lập tức

Mở **Share/Manage access**, xóa quyền của ứng viên, chuyển sang **Restricted**, gỡ liên kết chia sẻ công khai và kiểm tra những người còn quyền truy cập.

### Bước 2: Kiểm tra nhật ký truy cập

Xem **Activity/Audit Log** nếu dịch vụ hỗ trợ để xác định ai đã truy cập, thời điểm và các hành động tải xuống/sao chép nếu có ghi nhận. Lưu bằng chứng và báo bộ phận IT/bảo mật.

### Bước 3: Giảm thiểu thiệt hại

Đánh giá dữ liệu đã bị lộ, thông báo người phụ trách và thực hiện quy trình ứng phó sự cố. Cấp lại quyền đúng đối tượng, đổi thông tin xác thực nếu cần và rà soát quyền định kỳ.

**Lưu ý:** Thu hồi quyền không thể xóa bản dữ liệu người ngoài đã tải xuống hoặc sao chép. Nhật ký có thể không ghi nhận mọi thao tác; cần đánh giá rủi ro và xử lý theo quy định bảo vệ dữ liệu của công ty.

&#x20;- Dùng **Commenter** cho trưởng bộ phận, **Editor** chỉ cho người quản lý dữ liệu và **Restricted** cho toàn bộ tệp CV. Rà soát nhật ký truy cập định kỳ để phát hiện và ngăn chặn rò rỉ dữ liệu.



