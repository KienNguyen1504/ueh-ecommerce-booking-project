# [PrintSlot – Website đặt dịch vụ in ấn tài liệu học tập/làm việc theo yêu cầu]

## 1. Giới thiệu

**Mô tả website:** PrintSlot là website đặt dịch vụ in ấn trực tuyến, cho phép khách hàng tải tài liệu, tùy chỉnh cấu hình in, nhận báo giá tự động, chọn khung giờ nhận, thanh toán và theo dõi đơn hàng.

**Vấn đề kinh doanh cần giải quyết:** Khắc phục tình trạng đặt in thủ công mất thời gian, khó dự trù chi phí, dễ sai sót và thiếu chủ động về thời gian nhận tài liệu, đặc biệt đối với học sinh, sinh viên có deadline gấp.

## 2. Khách hàng mục tiêu

*Bảng 1.2 Phân tích đặc điểm khách hàng mục tiêu của PrintSlot**

| Nhóm tiêu chí | Thuộc tính | Khách hàng mục tiêu chính |
| --- | --- | --- |
| Nhân khẩu học | Độ tuổi | Khoảng 16–25 tuổi |
|  | Thu nhập | Chủ yếu sử dụng ngân sách cá nhân hoặc hỗ trợ từ gia đình; chưa xác định mức thu nhập cụ thể. |
|  | Nghề nghiệp | Học sinh THPT, sinh viên cao đẳng/đại học tại TP.HCM, ưu tiên sinh viên UEH. |
|  | Nơi sinh sống | Học tập, cư trú tại TP.HCM; ưu tiên khu vực gần các cơ sở đào tạo và điểm giao nhận dự kiến. |
| Tâm lý học | Sở thích | Quan tâm đến công cụ học tập tiện lợi, dịch vụ trực tuyến và các giải pháp tiết kiệm chi phí. |
|  | Lối sống | Lịch học, bài tập và hoạt động nhóm có thể thay đổi; cần sắp xếp thời gian hiệu quả. |
|  | Giá trị sống | Đề cao tính tiết kiệm, sự thuận tiện, chủ động trong học tập và quản lý thời gian. |
|  | Quan điểm | Có xu hướng lựa chọn dịch vụ dễ thao tác, minh bạch giá và đáp ứng thời hạn nộp bài. |
| Hành vi | Tần suất sử dụng | Phát sinh theo bài tập, kỳ thi, bài thuyết trình, báo cáo nhóm và khóa luận; có thể tăng vào giai đoạn cao điểm học kỳ. |
|  | Kênh đặt dịch vụ | Tiệm in trực tiếp, tin nhắn/Zalo hoặc website đặt in trực tuyến. |
| Hành vi | Lý do lựa chọn | Giá phù hợp, quy trình nhanh, vị trí thuận tiện, chất lượng đáp ứng yêu cầu và nhận thành phẩm đúng thời hạn. |
|  | Mức độ trung thành | Có khả năng sử dụng lại nếu giá cả, chất lượng và thời gian nhận đáp ứng kỳ vọng; dễ cân nhắc lựa chọn khác khi có dịch vụ thuận tiện hơn. |

## 3. Chức năng chính
| **Mã** | **Chức năng** | **Mô tả** | **Người dùng** | **Ưu tiên** | **Tiêu chí nghiệm thu** |
|---|---|---|---|---|---|
| F01 | Hiển thị danh sách dịch vụ | Hiển thị các danh mục, dịch vụ và combo in ấn đang được cung cấp. | Khách chưa đăng nhập, Khách hàng | Cao | Người dùng xem được danh sách dịch vụ đang được cung cấp; mỗi dịch vụ có tên, mô tả và thông tin giá phù hợp. |
| F02 | Xem chi tiết dịch vụ | Hiển thị thông tin chi tiết, thông số in có thể lựa chọn, giá tham khảo và thời gian dự kiến. | Khách chưa đăng nhập, Khách hàng | Cao | Khi chọn một dịch vụ, hệ thống hiển thị đầy đủ thông tin và các tùy chọn được cấu hình cho dịch vụ đó. |
| F03 | Tìm kiếm và lọc dịch vụ | Hỗ trợ tìm kiếm và lọc theo loại dịch vụ, giá, khổ giấy, loại giấy, chế độ màu, kiểu in, kiểu đóng gáy và thời gian hoàn thành. | Khách chưa đăng nhập, Khách hàng | Cao | Kết quả tìm kiếm phù hợp với từ khóa; kết quả lọc đáp ứng các điều kiện người dùng đã chọn. |
| F04 | Đăng ký và đăng nhập | Cho phép khách hàng tạo tài khoản, đăng nhập và đăng xuất. | Khách chưa đăng nhập, Khách hàng | Cao | Người dùng đăng ký với dữ liệu hợp lệ và đăng nhập thành công; hệ thống thông báo khi thông tin không hợp lệ hoặc không chính xác. |
| F05 | Tải tệp PDF | Cho phép khách hàng tải lên tệp PDF dùng cho đơn in. | Khách hàng | Cao | Hệ thống chỉ chấp nhận tệp đáp ứng định dạng và giới hạn dung lượng được cấu hình; tệp không hợp lệ bị từ chối và có thông báo phù hợp. |
| F06 | Cấu hình thông số in | Cho phép chọn số lượng, khổ giấy, loại giấy, in màu hoặc trắng đen, in một mặt hoặc hai mặt và kiểu đóng gáy nếu dịch vụ hỗ trợ. | Khách hàng | Cao | Người dùng chỉ chọn được các tùy chọn hợp lệ của dịch vụ; cấu hình đã chọn được hiển thị trước khi xác nhận đơn. |
| F07 | Tính giá tự động | Tính giá dự kiến dựa trên dịch vụ, thông số in, số lượng và bảng giá hiện hành. | Khách hàng | Cao | Khi thông số hoặc số lượng thay đổi, giá dự kiến được cập nhật theo công thức và bảng giá đã cấu hình; tổng tiền được hiển thị rõ ràng. |
| F08 | Gợi ý cấu hình tiết kiệm | Đề xuất lựa chọn in có chi phí thấp hơn dựa trên những quy tắc được thiết lập trước. | Khách hàng | Trung bình | Khi có lựa chọn phù hợp, hệ thống hiển thị gợi ý và chi phí tương ứng; khách hàng có quyền chấp nhận hoặc giữ cấu hình ban đầu. |
| F09 | Giỏ hàng và xác nhận đặt in | Cho phép khách hàng thêm, xem, cập nhật hoặc xóa dịch vụ khỏi giỏ hàng và xác nhận thông tin trước khi đặt. | Khách hàng | Cao | Giỏ hàng thể hiện đúng dịch vụ, cấu hình, số lượng và tổng tiền; đơn chỉ được tạo khi dữ liệu bắt buộc hợp lệ. |
| F10 | Đặt combo in ấn | Cho phép khách hàng lựa chọn các combo được cấu hình sẵn, chẳng hạn combo in khóa luận hoặc combo poster và standee. | Khách chưa đăng nhập, Khách hàng | Trung bình | Combo hiển thị danh sách dịch vụ thành phần, điều kiện áp dụng và giá; khách hàng có thể xem hoặc đặt combo theo quy trình chung. |
| F11 | Đặt lịch và kiểm tra sức chứa | Cho phép khách hàng chọn khung giờ nhận đơn; hệ thống kiểm tra lịch hoạt động và sức chứa đã cấu hình. | Khách hàng, Quản trị viên hệ thống | Cao | Chỉ các khung giờ hợp lệ và còn khả năng tiếp nhận mới được chọn; khung giờ không còn chỗ không được xác nhận đặt đơn mới. |
| F12 | Chọn phương thức giao nhận | Cho phép khách hàng chọn nhận tại tiệm hoặc giao hàng trong khu vực được hỗ trợ; hiển thị phí giao hàng tương ứng. | Khách hàng | Cao | Phương thức giao nhận và phí được hiển thị trước khi xác nhận; địa chỉ giao hàng và thông tin bắt buộc được kiểm tra theo phương thức đã chọn. |
| F13 | Áp dụng voucher | Cho phép khách hàng nhập và sử dụng mã giảm giá đáp ứng điều kiện áp dụng. | Khách hàng, Quản trị viên hệ thống | Trung bình | Mã hợp lệ được áp dụng đúng quy tắc; mã hết hạn, không hợp lệ hoặc không đáp ứng điều kiện bị từ chối với thông báo phù hợp. |
| F14 | Thanh toán thử nghiệm | Cung cấp quy trình thanh toán thử nghiệm để kiểm tra kết quả thanh toán và cập nhật đơn hàng. | Khách hàng | Cao | Người dùng thực hiện được luồng thanh toán thử nghiệm; hệ thống ghi nhận kết quả mô phỏng và cập nhật trạng thái theo quy tắc đã định, không phát sinh giao dịch tiền thật. |
| F15 | Theo dõi đơn hàng | Cho phép khách hàng xem danh sách đơn và trạng thái xử lý của từng đơn. | Khách hàng | Cao | Khách hàng xem được lịch sử và trạng thái các đơn thuộc tài khoản của mình; trạng thái được cập nhật theo quy trình xử lý đơn. |
| F16 | Hủy đơn và ghi nhận hoàn tiền | Hỗ trợ yêu cầu hủy đơn theo điều kiện quy định; việc xử lý hủy hoặc hoàn tiền được ghi nhận trong hệ thống. | Khách hàng, Nhân viên vận hành tiệm in, Quản trị viên hệ thống | Trung bình | Đơn chỉ được hủy theo điều kiện cho phép; hệ thống ghi nhận kết quả xử lý. Việc hoàn tiền trong MVP được xử lý hoặc ghi nhận thủ công. |
| F17 | Gửi yêu cầu báo giá | Cho phép khách hàng gửi thông tin và yêu cầu báo giá cho dịch vụ đặc thù chưa được hỗ trợ tính giá tự động. | Khách hàng | Trung bình | Khách hàng gửi được yêu cầu với các thông tin bắt buộc; hệ thống lưu yêu cầu để bộ phận phụ trách tra cứu và xử lý. |
| F18 | Đánh giá dịch vụ | Cho phép khách hàng đánh giá và gửi nhận xét về đơn hàng sau khi hoàn tất. | Khách hàng | Trung bình | Chỉ khách hàng đáp ứng điều kiện đánh giá mới gửi được đánh giá; nội dung và điểm đánh giá được kiểm tra trước khi lưu. |
| F19 | Quản lý dịch vụ và bảng giá | Cho phép quản trị viên thêm, cập nhật, ẩn hoặc ngừng cung cấp dịch vụ; quản lý danh mục, combo và bảng giá. | Quản trị viên hệ thống | Cao | Quản trị viên thực hiện được các thao tác theo quyền được cấp; thay đổi được lưu và phản ánh trên giao diện phù hợp. |
| F20 | Xử lý đơn hàng in | Cho phép nhân viên vận hành xem các đơn được phân công, kiểm tra tệp và cập nhật trạng thái xử lý. | Nhân viên vận hành tiệm in | Cao | Nhân viên chỉ truy cập các đơn được phép xử lý; trạng thái được cập nhật theo các bước hợp lệ của quy trình. |
| F21 | Quản lý tài khoản, voucher và cấu hình | Cho phép quản trị viên quản lý tài khoản, phân quyền, voucher, lịch hoạt động, sức chứa và các cấu hình cần thiết. | Quản trị viên hệ thống | Cao | Quản trị viên thực hiện được các thao tác quản lý theo quyền; dữ liệu cập nhật được lưu và áp dụng đúng phạm vi. |
| F22 | Thống kê tổng quan | Hiển thị các chỉ số cơ bản phục vụ theo dõi hoạt động như số lượng đơn, trạng thái đơn và doanh thu ghi nhận. | Quản trị viên hệ thống | Trung bình | Các chỉ số được tổng hợp từ dữ liệu hiện có theo tiêu chí thống kê đã xác định; giao diện hiển thị số liệu rõ ràng. |
| F23 | Bảo vệ tệp và dữ liệu | Kiểm soát quyền truy cập dữ liệu, giới hạn truy cập tệp tải lên và kiểm tra dữ liệu đầu vào tại các chức năng liên quan. | Khách hàng, Nhân viên vận hành tiệm in, Quản trị viên hệ thống | Cao | Người dùng không có quyền không thể truy cập dữ liệu hoặc tệp riêng tư; dữ liệu đầu vào không hợp lệ bị từ chối; chức năng quản trị yêu cầu xác thực và kiểm tra quyền. |

## 4. Thành viên
- Kiên – Trưởng nhóm: quản lý repo, GitHub Issues (NV8), điều phối
- Hoa – Xác định vấn đề kinh doanh (NV1), phân công vai trò (NV7)
- Phương – Phân tích website tương tự (NV2)
- Nhi – Phân tích website tương tự (NV2)
- Thắng – AI phân tích và AI phản biện (NV3, NV4)
- Tuệ – Vai trò người dùng và chức năng (NV5)
- Hưng – Quy trình nghiệp vụ (NV6)

## 5. Công nghệ dự kiến
Ghi rõ công nghệ đã thống nhất. (chưa chốt)

## 6. Kế hoạch thực hiện
Tóm tắt các giai đoạn của dự án. (xem PROJECT_PLAN.md)

## 7. Liên kết
- Bảng yêu cầu: REQUIREMENTS.md
- Kế hoạch: PROJECT_PLAN.md
- Phân tích website: docs/competitor-analysis.md
- Quy trình nghiệp vụ: docs/business-workflow.md
- Vai trò người dùng: docs/user-roles.md
- Nhật ký sử dụng AI: AI_USAGE_LOG.md
