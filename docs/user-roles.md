# Vai trò người dùng

Người phụ trách: Tuệ (NV5)

PrintSlot là website đặt dịch vụ in ấn tài liệu học tập và làm việc theo yêu cầu. Dựa trên quy trình nghiệp vụ dự kiến, hệ thống có bốn vai trò chính trong phiên bản MVP: khách chưa đăng nhập, khách hàng, nhân viên vận hành tiệm in và quản trị viên hệ thống.

| Vai trò | Nhiệm vụ chính | Quyền hạn dự kiến |
|---|---|---|
| **Khách chưa đăng nhập** | Tìm hiểu dịch vụ in ấn, tham khảo giá và lựa chọn dịch vụ phù hợp. | Xem trang chủ, danh mục và chi tiết dịch vụ; xem combo; tìm kiếm và lọc dịch vụ; xem hướng dẫn đặt in và thông tin giá công khai; sử dụng công cụ ước tính giá nếu chức năng được cung cấp. Không được tạo đơn in hoặc tải tệp để đặt in khi chưa đăng nhập. |
| **Khách hàng** | Đặt dịch vụ in, thanh toán và theo dõi đơn hàng của bản thân. | Đăng ký, đăng nhập và quản lý hồ sơ; tải tệp PDF; cấu hình thông số in; xem báo giá; nhận gợi ý cấu hình tiết kiệm; quản lý giỏ hàng; chọn khung giờ nhận và phương thức giao nhận; áp dụng voucher; thanh toán; theo dõi và hủy đơn theo điều kiện quy định; xem lịch sử đơn hàng và đánh giá dịch vụ sau khi đơn hoàn tất. |
| **Nhân viên vận hành tiệm in** | Tiếp nhận, kiểm tra tệp và xử lý các đơn in được phân công. | Xem các đơn được phép xử lý; truy cập tệp phục vụ việc in; kiểm tra tệp và ghi nhận lỗi; yêu cầu khách hàng bổ sung tệp; cập nhật trạng thái đơn theo quy trình; xác nhận tài liệu đã sẵn sàng nhận hoặc giao và ghi nhận việc hoàn tất. Không được tự ý thay đổi bảng giá, phân quyền hoặc cấu hình quản trị hệ thống. |
| **Quản trị viên hệ thống** | Quản lý cấu hình và giám sát hoạt động của PrintSlot. | Quản lý dịch vụ, danh mục, combo và bảng giá; quản lý tài khoản và phân quyền; cấu hình khung giờ, sức chứa và lịch ngừng nhận đơn; quản lý voucher; theo dõi và xử lý đơn hàng theo quyền được cấp; ghi nhận việc hủy đơn và xử lý hoàn tiền; xem dashboard thống kê. |

## Nguyên tắc phân quyền

- **Khách chưa đăng nhập:** Chỉ được truy cập thông tin công khai và các chức năng không yêu cầu xác thực.
- **Khách hàng:** Chỉ được xem và quản lý hồ sơ, tệp tải lên, giỏ hàng và đơn hàng thuộc tài khoản của mình.
- **Nhân viên vận hành tiệm in:** Chỉ được truy cập thông tin cần thiết để xử lý đơn được phân công. Quyền xem hoặc tải tệp của khách hàng phải được kiểm soát.
- **Quản trị viên hệ thống:** Được thực hiện các nghiệp vụ quản trị theo quyền được cấp. Những thao tác quan trọng như thay đổi bảng giá, cập nhật trạng thái đơn hàng và xử lý hoàn tiền phải tuân theo quy tắc nghiệp vụ của hệ thống.
