**Nhiệm vụ 3 – Sử dụng AI để phân tích yêu cầu**
**Sử dụng Gemini để thực hiện phân tích**
# Thông tin dự án

| **Hạng mục**                                        | **Nội dung**                                                                                                                                                                                                                                                              |
|-----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Tên dự án**                                       | PrintSlot - Website đặt dịch vụ in ấn tài liệu học tập/làm việc theo yêu cầu.                                                                                                                                                                                             |
| **Sản phẩm / dịch vụ**                              | • In tài liệu học tập, slide thuyết trình, báo cáo nhóm, luận văn/khóa luận, đóng gáy, đóng bìa, in màu hoặc đen trắng.<br>• Bản vẽ kỹ thuật, poster, decal, standee.<br>• Combo báo cáo nhóm, combo khóa luận, combo in PowerPoint kèm standee (thuê/mua).               |
| **Hình thức bán hàng**                              | Đặt theo đơn. Đơn vị tính: trang/tờ, bản/bộ tài liệu. Khách chọn dịch vụ, cấu hình in, số bản, thời gian dự kiến hoàn thành, khung giờ nhận và phương thức giao nhận.                                                                                                     |
| **Khách hàng mục tiêu**                             | Học sinh/sinh viên tại TP.HCM có nhu cầu in tài liệu học tập, báo cáo, thuyết trình, khóa luận. Mở rộng: giảng viên, câu lạc bộ sinh viên, nhóm tổ chức sự kiện (poster, tài liệu số lượng lớn).                                                                          |
| **Vấn đề kinh doanh (giả thuyết, chưa kiểm chứng)** | • Phải đến tiệm hỏi giá, gửi file, chờ đợi - nhất là khi sát deadline.<br>• Giá thay đổi theo số trang, loại giấy, màu, hai mặt, đóng gáy, số bản nên khó dự trù chi phí.<br>• Trao đổi nhiều lần để thống nhất cấu hình dễ gây nhầm lẫn.                                 |
| **Giải pháp đề xuất**                               | Website cho chọn dịch vụ hoặc tải file PDF, thiết lập tùy chọn in, nhận báo giá tự động, chọn khung giờ nhận, thanh toán trực tuyến, theo dõi trạng thái: Đã tiếp nhận → Đang in → Đang hoàn thiện → Sẵn sàng nhận/Đang giao → Hoàn tất, nhận tại quầy hoặc giao tận nơi. |
| **Ba điểm khác biệt**                               | • Tính giá tự động.<br>• Đặt lịch thông minh (khung giờ theo năng lực xử lý, tùy chọn hỏa tốc).<br>• Gợi ý cấu hình in tiết kiệm.                                                                                                                                         |
| **Website tham khảo**                               | • **Website A:** [**<u>In Sài Gòn</u>**](https://insaigon.vn/)<br>• **Website B:** [**<u>In Nhanh Co</u>**](https://innhanh.co/)<br>• **Website C:** [**<u>In KTS Đại Dương</u>**](https://www.inandaiduong.com/)                                                         |
| **Thời gian thực hiện**                             | Từ 2-3 tháng                                                                                                                                                                                                                                                              |
| **Quy mô nhóm**                                     | Nhóm gồm có 7 thành viên                                                                                                                                                                                                                                                  |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

# 1. MỤC TIÊU VÀ PHẠM VI DỰ ÁN (PROJECT OBJECTIVES & SCOPE)

## 1.1. Bối cảnh & Phát biểu Vấn đề Kinh doanh (Business Problem Statement)

Trong môi trường đại học tại TP.HCM (đặc biệt là các cụm trường trọng điểm như UEH, Bách Khoa, Quốc Gia...), nhu cầu in ấn tài liệu học tập, slide thuyết trình, báo cáo nhóm, luận văn tốt nghiệp và ấn phẩm sự kiện là rất lớn. Tuy nhiên, quy trình in ấn truyền thống hiện nay đang bộc lộ nhiều hạn chế nghiêm trọng từ cả hai phía:

- **Nỗi đau của sinh viên (Khách hàng):** Sinh viên tốn rất nhiều thời gian di chuyển, xếp hàng chờ đợi tại cửa hàng in ấn, đặc biệt vào các đợt cao điểm nộp bài (deadline).

- **Bất bất transparent về giá:** Giá thành in ấn bị phụ thuộc vào nhiều biến số phức tạp (khổ giấy, định lượng giấy, in màu hay đen trắng, 1 mặt hay 2 mặt, kiểu đóng gáy ghim/lò xo/bìa cứng mạ vàng, số lượng bản). Việc không có công cụ tính giá tự động khiến sinh viên khó dự trù chi phí trước khi quyết định.

- **Nguy cơ sai sót file & cấu hình:** Việc gửi file qua USB, Zalo, Email hoặc trao đổi trực tiếp dễ dẫn đến sai lệch cấu hình in (in sai khổ, mất margin, tràn lề, sai loại giấy), gây lãng phí chi phí và tranh chấp.

- **Nỗi đau của tiệm in (Vận hành):** Chủ tiệm in bị quá tải khâu tư vấn báo giá trực tiếp/qua nhắn tin vào đợt cao điểm, khó sắp xếp thứ tự ưu tiên đơn hàng và quản lý khung giờ trả hàng (capacity), dẫn đến tình trạng trễ hẹn.

## 1.2. Mục tiêu Dự án (Project SMART Objectives)

- **1. Mục tiêu Kinh doanh & Sản phẩm:** Xây dựng nền tảng Web E-commerce chuyên biệt cho dịch vụ in ấn, tự động hóa 100% quy trình tính giá và tiếp nhận đơn hàng trực tuyến.

- **2. Mục tiêu Trải nghiệm Người dùng:** Rút ngắn thời gian chờ đợi tại quầy của sinh viên từ trung bình 20-30 phút xuống còn 0 phút (chỉ đến nhận hàng theo khung giờ đã đặt trước - Pick-up Slot).

- **3. Mục tiêu Vận hành Tiệm in:** Tối ưu hóa năng lực phục vụ của tiệm in đối tác, tăng 30-40% sản lượng đơn hàng xử lý trong đợt cao điểm nhờ việc chuẩn hóa cấu hình in và lịch hẹn.

- **4. Mục tiêu Học thuật:** Hoàn thiện hệ thống Web TMĐT có khả năng trích xuất thông tin file PDF, tính giá tự động đa thông số, đặt lịch hẹn slot thông minh và thanh toán trực tuyến đáp ứng yêu cầu môn học.

## 1.3. Phạm vi Dự án (Project Scope Boundary)

**Bảng đề xuất phạm vi dự án** 

| **HẠNG MỤC NẰM TRONG PHẠM VI (IN-SCOPE)**                                                    | **HẠNG MỤC NẰM NGOÀI PHẠM VI (OUT-OF-SCOPE)**                                                    |
|----------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| • Upload file PDF & trích xuất số trang tự động.                                             | • Công cụ chỉnh sửa / thiết kế đồ họa trực tuyến phức tạp (Canvas Editor full-featured).         |
| • Cấu hình in linh hoạt (khổ A4/A3/A5, giấy F70/F80/C200, 1/2 mặt, màu/đen trắng, đóng gáy). | • In công nghiệp quy mô lớn (bao bì thương mại, hộp giấy, tem nhãn số lượng hàng trăm ngàn bản). |
| • Các gói sản phẩm Combo (Combo Báo cáo nhóm, Combo Khóa luận, Combo PP + Standee).          | • Tích hợp hệ thống quản trị kho nguyên vật liệu chuyên sâu (ERP full-suite cho nhà in).         |
| • Thuật toán tính giá tự động theo thời gian thực dựa trên cấu hình.                         | • Tự động chỉnh sửa lỗi layout/font chữ bên trong file PDF của khách hàng.                       |
| • Đặt lịch hẹn nhận hàng thông minh theo Slot Capacity của tiệm in.                          | • Cho thuê thiết bị máy in vật lý cho cá nhân/hộ gia đình.                                       |
| • Thanh toán trực tuyến (MoMo, VNPay, ZaloPay, QR Code) & Tracking đơn 5 bước.               | • Đội ngũ giao hàng nội bộ riêng biệt (Sử dụng đối tác vận chuyển giao hàng API ngoài).          |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

# 2. CÁC NHÓM NGƯỜI DÙNG VÀ MA TRẬN PHÂN QUYỀN

## 2.1. Xác định Các Nhóm Người dùng (User Roles)

- **1. Khách vãng lai (Guest):** Khách truy cập chưa đăng nhập. Chỉ có quyền xem thông tin giới thiệu, bảng giá tham khảo, hướng dẫn sử dụng, dịch vụ in ấn và danh mục Combo.

- **2. Khách hàng Cá nhân (Student/Individual Customer):** Sinh viên/Học sinh có tài khoản cá nhân. Quyền upload file PDF, cấu hình thông số in, xem báo giá tự động, đặt lịch nhận hàng, chọn phương thức thanh toán, nhận gợi ý tiết kiệm chi phí, theo dõi trạng thái đơn hàng và đánh giá dịch vụ.

- **3. Khách hàng Tổ chức / CLB / Giảng viên (B2B Group Customer):** Đại diện CLB sinh viên, Ban cán sự lớp, Giảng viên hoặc Nhóm sự kiện. Được hỗ trợ đặt đơn hàng số lượng lớn (Poster, Standee, Combo sự kiện), xuất hóa đơn GTGT/chứng từ thanh toán đồ án, hưởng chính sách chiết khấu B2B.

- **4. Nhân viên Vận hành Tiệm in (Print Shop Operator):** Nhân viên vận hành tại tiệm in đối tác. Quyền tiếp nhận đơn hàng, tải file PDF nguyên bản, kiểm tra lỗi định dạng, cập nhật trạng thái đơn (Đã tiếp nhận → Đang in → Đang hoàn thiện → Sẵn sàng nhận/Đang giao → Hoàn tất), báo sự cố file.

- **5. Quản trị viên Hệ thống (System Admin):** Quản trị viên hệ thống PrintSlot. Quyền quản lý danh mục dịch vụ, cấu hình bảng đơn giá vật liệu/in ấn, thiết lập giới hạn Capacity Slot theo khung giờ, quản lý tài khoản người dùng, xem báo cáo doanh thu và lịch sử vận hành.

## 2.2. Ma trận Phân quyền Chi tiết (Role-Based Access Control Matrix)

**Bảng phân quyền chức năng cho từng người dùng** 

| **Chức năng / Mô-đun**            | **Guest** | **Student**     | **B2B / Club** | **Operator** | **Admin**     |
|-----------------------------------|-----------|-----------------|----------------|--------------|---------------|
| Xem bảng giá & dịch vụ            | X         | X               | X              | X            | X             |
| Upload PDF & Trích xuất trang     | \-        | X               | X              | \-           | \-            |
| Cấu hình in & Nhận báo giá        | Tham khảo | X               | X              | \-           | \-            |
| Gợi ý cấu hình tiết kiệm          | \-        | X               | X              | \-           | \-            |
| Đặt lịch hẹn & Chọn Slot          | \-        | X               | X              | \-           | \-            |
| Thanh toán trực tuyến             | \-        | X               | X              | \-           | \-            |
| Tracking trạng thái đơn 5 bước    | \-        | X (Đơn cá nhân) | X (Đơn nhóm)   | X (Toàn bộ)  | X (Toàn bộ)   |
| Yêu cầu xuất hóa đơn GTGT         | \-        | \-              | X              | \-           | Xem/Duyệt     |
| Duyệt file & Cập nhật trạng thái  | \-        | \-              | \-             | X            | X             |
| Quản lý bảng giá & Dynamic Slot   | \-        | \-              | \-             | \-           | X             |
| Xem Báo cáo Analytics / Doanh thu | \-        | \-              | \-             | Chỉ cửa hàng | Toàn hệ thống |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

# 3. CƠ SỞ ĐỀ XUẤT VÀ PHÂN LOẠI YÊU CẦU CHI TIẾT

Nhằm đảm bảo dự án được triển khai đúng tiến độ môn học, phù hợp với năng lực kỹ thuật và nguồn lực thực tế của nhóm sinh viên, toàn bộ các chức năng đề xuất được phân loại minh bạch dựa trên 3 tiêu chí cốt lõi:

- **1. \[MUST-HAVE / BẮT BUỘC\]:** Những tính năng không thể thiếu để hình thành luồng giao dịch E-commerce hoàn chỉnh từ đặt hàng -\> thanh toán -\> xử lý -\> giao nhận. Bắt buộc hoàn thành ở phiên bản MVP.

- **2. \[PHASE 2 / CÓ THỂ PHÁT TRIỂN SAU\]:** Những tính năng mang lại giá trị gia tăng, tối ưu trải nghiệm hoặc phục vụ mở rộng quy mô, sẽ được phát triển ở Giai đoạn 2 sau khi bản MVP hoạt động ổn định.

- **3. \[HYPOTHESIS / CẦN KHẢO SÁT XÁC MINH\]:** Những giả định về thói quen sinh viên hoặc quy trình vận hành tiệm in chưa có số liệu thực tế, cần tiến hành khảo sát thị trường để kiểm chứng trước khi lập trình.

## 3.1. Bảng Phân loại Chức năng & Giải trình Cơ sở Khoa học

**Phân loại chức năng**

| **Mã CN** | **Tên Chức năng / Tính năng**                   | **Phân loại**  | **Cơ sở Đề xuất & Giải trình Nghiệp vụ**                                                           |
|-----------|-------------------------------------------------|----------------|----------------------------------------------------------------------------------------------------|
| FN-01     | Upload PDF & Đếm trang tự động                  | **MUST-HAVE**  | Cốt lõi để tính giá tự động. Loại bỏ hoàn toàn việc đếm thủ công, giảm 90% thời gian báo giá.      |
| FN-02     | Bộ cấu hình in đa thông số                      | **MUST-HAVE**  | Đảm bảo tính chính xác của đơn hàng (Khổ, giấy, 1/2 mặt, màu/đen trắng, đóng gáy).                 |
| FN-03     | Công thức tính giá tự động Real-time            | **MUST-HAVE**  | Giải quyết vấn đề minh bạch chi phí, giúp sinh viên dự trù ngân sách tức thì.                      |
| FN-04     | Gợi ý cấu hình in tiết kiệm chi phí             | **MUST-HAVE**  | Đặc thù UVP cho sinh viên (gợi ý in 2 mặt, đen trắng cho trang chữ) giúp tiết kiệm 20-40% chi phí. |
| FN-05     | Đặt lịch khung giờ nhận hàng (Slot)             | **MUST-HAVE**  | Giải quyết nỗi đau chờ đợi sát deadline, phân bổ đều tải xử lý cho tiệm in.                        |
| FN-06     | Thanh toán trực tuyến (MoMo/QR)                 | **MUST-HAVE**  | Đảm bảo sinh viên cam kết đơn hàng, giảm rủi ro bùng đơn đối với sản phẩm in theo yêu cầu.         |
| FN-07     | Tracking trạng thái đơn hàng 5 bước             | **MUST-HAVE**  | Minh bạch tiến độ sản xuất, giảm số cuộc gọi/tin nhắn hỏi 'In xong chưa?'.                         |
| FN-08     | Gói sản phẩm Combo (Báo cáo/Khóa luận)          | **MUST-HAVE**  | Đóng gói sẵn dịch vụ phổ biến giúp đặt hàng nhanh trong 1 click.                                   |
| FN-09     | Chế độ in Hỏa tốc (Express Printing)            | **PHASE 2**    | Phục vụ nhóm sinh viên cần gấp trong 1-2 tiếng. Cần thuật toán ưu tiên hàng chờ nâng cao.          |
| FN-10     | Giao hàng tận nơi qua API Vận chuyển            | **PHASE 2**    | Tích hợp GrabExpress/Ahamove. Cần vốn và API tích hợp phức tạp cho giai đoạn MVP.                  |
| FN-11     | Tự động phân tích tỷ lệ bao phủ màu (Ink Ratio) | **PHASE 2**    | Tính giá in màu chính xác dựa trên độ phủ mực thực tế của file PDF.                                |
| FN-12     | Chương trình Tích điểm & Ưu đãi B2B CLB         | **PHASE 2**    | Chính sách giữ chân khách hàng lâu dài, mở rộng khách hàng tổ chức.                                |
| HYP-01    | Sinh viên sẵn sàng trả tiền trước 100%          | **HYPOTHESIS** | Cần khảo sát sinh viên: Có chấp nhận chuyển khoản trước khi tiệm chưa in không?                    |
| HYP-02    | Tiệm in tuân thủ đúng Slot Capacity             | **HYPOTHESIS** | Cần phỏng vấn tiệm in: Quy trình thực tế có thể cập nhật trạng thái đơn liên tục không?            |
| HYP-03    | Nhu cầu thuê Standee sự kiện của CLB            | **HYPOTHESIS** | Cần khảo sát các CLB UEH/TPHCM: Có nhu cầu thuê khung Standee hay chỉ mua?                         |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

# 4. Quy trình nghiệp vụ chính

## 4.1. Quy trình đặt in từ đầu đến cuối

Quy trình dưới đây mô tả luồng chuẩn của một đơn hàng, từ lúc khách chọn dịch vụ đến khi hoàn tất. Cột cuối nêu quy tắc nghiệp vụ mà hệ thống phải thực thi.

**Quy trình đặt in** 

| **Bước** | **Người thực hiện**         | **Hoạt động**                                                         | **Hệ thống xử lý / quy tắc nghiệp vụ**                                                                                                                |
|----------|-----------------------------|-----------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1        | **Khách**                   | Truy cập, chọn dịch vụ hoặc combo.                                    | Hiển thị mô tả và giá “từ”. Dịch vụ đặc thù chuyển sang biểu mẫu yêu cầu báo giá.                                                                     |
| 2        | **Khách**                   | Tải file PDF lên (C1).                                                | Kiểm tra định dạng và dung lượng, đếm số trang, báo lỗi rõ ràng nếu file hỏng, có mật khẩu hoặc quá nặng.                                             |
| 3        | **Khách**                   | Chọn cấu hình in, ghi chú.                                            | Mỗi lần đổi cấu hình, tính lại giá và hiển thị chi tiết.                                                                                              |
| 4        | **Hệ thống**                | Đưa ra gợi ý tiết kiệm.                                               | Chỉ hiển thị khi quy tắc thỏa, nêu số tiền tiết kiệm và điều đánh đổi, khách chấp nhận hoặc bỏ qua, hệ thống không tự đổi.                            |
| 5        | **Khách**                   | Thêm mục vào đơn, có thể lặp bước 1-4 cho mục khác.                   | Đơn gồm nhiều mục, tổng tạm tính cập nhật liên tục.                                                                                                   |
| 6        | **Khách**                   | Chọn ngày, khung giờ nhận hoặc hỏa tốc.                               | Chỉ hiển thị khung giờ còn chỗ và thỏa thời gian xử lý tối thiểu của đơn. Hỏa tốc cộng phụ phí và bị giới hạn hạn mức.                                |
| 7        | **Khách**                   | Chọn nhận tại quầy hoặc giao tận nơi và địa chỉ .                     | Tính phí giao theo quy tắc, kiểm tra địa chỉ nằm trong vùng phục vụ.                                                                                  |
| 8        | **Khách**                   | Xem lại đơn và xác nhận, đăng nhập nếu chưa.                          | Hệ thống **tính lại giá ở máy chủ** và chốt “ảnh chụp giá” của đơn, giữ chỗ khung giờ trong N phút. Trạng thái: Chờ thanh toán.                       |
| 9        | **Khách / Cổng thanh toán** | Thanh toán trực tuyến.                                                | Nhận kết quả từ cổng, cập nhật trạng thái thanh toán không trùng lặp. Thất bại hoặc quá hạn giữ chỗ → hủy giữ chỗ, đơn quay về Chờ thanh toán/Đã hủy. |
| 10       | **Hệ thống**                | Tạo đơn chính thức, trạng thái **Đã tiếp nhận**.                      | Trừ sức chứa khung giờ, gửi xác nhận (H3 nếu có).                                                                                                     |
| 11       | **Nhân viên**               | Kiểm tra file, chuyển **Đang in**.                                    | Nếu file lỗi: gắn cờ, liên hệ khách xin file mới, ghi lại trong nhật ký.                                                                              |
| 12       | **Nhân viên**               | In xong, thực hiện đóng gáy/bìa/kiểm tra, chuyển **Đang hoàn thiện**. | Hệ thống ghi thời điểm từng trạng thái (phục vụ đo thời gian xử lý thực tế).                                                                          |
| 13       | **Nhân viên**               | Chuyển **Sẵn sàng nhận** (quầy) hoặc **Đang giao**.                   | Khách nhìn thấy trạng thái mới, có thể nhận thông báo.                                                                                                |
| 14       | **Khách / Nhân viên**       | Khách nhận hàng hoặc nhận giao, nhân viên xác nhận **Hoàn tất** (F3). | Đóng đơn, đơn trở thành lịch sử.                                                                                                                      |
_**Nguồn: Nhóm tác giả đề xuất (2026)**_

**Cơ sở:** các bước 1-14 bám sát luồng được mô tả trong đề tài, hai điểm bổ sung là (a) bước 8-9 xử lý thanh toán dở dang và giữ chỗ, vì thực tế khách có thể bỏ giữa chừng, (b) bước 11 xử lý file lỗi, vì file PDF hỏng/sai khổ là tình huống thường gặp.

## 4.2. Vòng đời trạng thái của đơn hàng

Đề tài xác định năm trạng thái nhìn thấy với khách. Đề xuất bổ sung hai trạng thái kỹ thuật (Chờ thanh toán, Đã hủy) để hệ thống xử lý đầy đủ các tình huống ngoài luồng chuẩn (loại XM, vì cần cửa hàng thống nhất tên gọi và chính sách).

| **Đã tiếp nhận** | **→** | **Đang in** | **→** | **Đang hoàn thiện** | **→** | **Sẵn sàng nhận / Đang giao** | **→** | **Hoàn tất** |
|------------------|-------|-------------|-------|---------------------|-------|-------------------------------|-------|--------------|

Trước luồng trên: **Chờ thanh toán**. Ngoài luồng: **Đã hủy** (chỉ trước khi chuyển Đang in).

**Luồng trạng thái xử lý đơn hàng** 

| **Trạng thái**                | **Điều kiện chuyển vào**                                                           | **Người / hệ thống kích hoạt** | **Ghi chú**                                                                |
|-------------------------------|------------------------------------------------------------------------------------|--------------------------------|----------------------------------------------------------------------------|
| **Chờ thanh toán**            | Khách đã xác nhận đơn, chưa thanh toán xong.                                       | Hệ thống                       | Có thời hạn giữ chỗ, hết hạn thì giải phóng khung giờ. Trạng thái bổ sung. |
| **Đã tiếp nhận**              | Thanh toán thành công (hoặc quản trị xác nhận thủ công).                           | Hệ thống / Quản trị            | Đơn xuất hiện trong danh sách xử lý của nhân viên.                         |
| **Đang in**                   | Nhân viên đã kiểm tra file hợp lệ và bắt đầu in.                                   | Nhân viên                      | Từ thời điểm này khách không tự hủy được.                                  |
| **Đang hoàn thiện**           | In xong, đang đóng gáy, cắt, kiểm tra chất lượng.                                  | Nhân viên                      | Có thể bỏ qua nếu đơn không có gia công.                                   |
| **Sẵn sàng nhận / Đang giao** | Thành phẩm sẵn sàng, chọn “Sẵn sàng nhận” (quầy) hoặc “Đang giao”.                 | Nhân viên                      | Thể hiện khung giờ nhận hoặc thông tin giao.                               |
| **Hoàn tất**                  | Khách đã nhận hoặc giao thành công.                                                | Nhân viên                      | Đóng đơn, không chỉnh sửa tiếp.                                            |
| **Đã hủy**                    | Khách hủy hoặc quản trị hủy khi đơn chưa vào in, hoặc thanh toán thất bại/quá hạn. | Khách / Quản trị / Hệ thống    | Xử lý hoàn tiền theo chính sách. Trạng thái bổ sung.                       |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

**Cơ sở:** trạng thái được kiểm soát chặt (chỉ chuyển theo thứ tự hợp lệ) để khách luôn thấy thông tin đáng tin cậy và để cửa hàng có số liệu thời gian xử lý thật cho việc cải tiến công suất sau này (liên quan E6).

## 4.3. Quy trình báo giá tự động

**Công thức đề xuất** (dạng khái quát, nhóm điều chỉnh theo cách cửa hàng tính giá thực tế):

**Công thức tính giá**

Chi phí in của một mục = (số mặt in × đơn giá in theo màu/khổ) + (số tờ giấy × đơn giá giấy theo loại/khổ).

Số tờ = số trang (in một mặt) hoặc làm tròn lên của số trang chia 2 (in hai mặt).

Tổng đơn = Σ các mục \[ (chi phí in + phí đóng gáy/bìa mỗi bản) × số bản \] + phụ phí hỏa tốc + phí giao − giảm giá (nếu có).

**Ví dụ minh họa** (đơn giá giả định để minh họa cách tính, **không phải giá thực tế**): tài liệu 60 trang A4, đen trắng, 3 bản, đóng gáy xoắn. Giả định: in đen trắng 300 đồng/mặt, giấy A4 200 đồng/tờ, gáy xoắn 10.000 đồng/bản.

| **Phương án**         | **Số tờ** | **Chi phí in + giấy / bản**    | **Gáy / bản** | **Tổng (3 bản)**                  |
|-----------------------|-----------|--------------------------------|---------------|-----------------------------------|
| In một mặt            | 60        | 60 × 300 + 60 × 200 = 30.000 đ | 10.000 đ      | (30.000 + 10.000) × 3 = 120.000 đ |
| In hai mặt (gợi ý D3) | 30        | 60 × 300 + 30 × 200 = 24.000 đ | 10.000 đ      | (24.000 + 10.000) × 3 = 102.000 đ |
| **Tiết kiệm**         |           |                                |               | **18.000 đ (15%)**                |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

Ví dụ cho thấy gợi ý tiết kiệm có thể được hiển thị bằng đúng công thức đang dùng để tính giá, nên D3 chỉ cần so sánh hai lần tính D1 - đây là lý do D3 khả thi ở mức quy tắc.

**Các quy tắc nghiệp vụ cần chốt:**

- Cách cửa hàng tính “trang” hay “mặt” hay “tờ”, và cách làm tròn tiền (ví dụ làm tròn đến 100 hoặc 1.000 đồng).

- Có áp giá tối thiểu cho mỗi đơn hay không, có bậc giá theo số lượng hay không.

- Tài liệu có cả trang màu lẫn đen trắng được tính thế nào (phiên bản đầu: khách chọn một chế độ cho cả mục, theo dải trang).

- Giá được **chốt tại thời điểm xác nhận đơn**, thay đổi bảng giá sau đó chỉ áp dụng cho đơn mới.

## 4.4. Quy trình đặt lịch và quản lý sức chứa

1. **Cấu hình (quản trị):** đặt giờ mở cửa, độ dài mỗi khung giờ, số đơn tối đa mỗi khung, hạn mức hỏa tốc, thời gian xử lý tối thiểu theo dịch vụ (E2, E3).
2. **Lọc khung giờ hợp lệ (hệ thống):** một khung được hiển thị là “còn chỗ” khi thời điểm bắt đầu không sớm hơn (bây giờ + thời gian xử lý tối thiểu của đơn) và số đơn đã giữ/đã đặt chưa vượt sức chứa.
3. **Hỏa tốc:** khi khách chọn, hệ thống áp thời gian xử lý rút ngắn và phụ phí, chỉ cho phép nếu còn hạn mức hỏa tốc, nếu hết, thông báo rõ và đề xuất khung giờ thường gần nhất.
4. **Giữ chỗ:** khi khách xác nhận đơn, khung giờ được giữ N phút, thanh toán thành công thì chuyển thành đã đặt, thất bại/quá hạn thì giải phóng.
5. **Xử lý đồng thời:** hai khách chọn cùng một chỗ cuối thì chỉ một người thành công, người còn lại nhận thông báo và chọn lại (thực hiện bằng giao dịch cơ sở dữ liệu hoặc ràng buộc duy nhất).
6. **Khi cửa hàng trễ:** nhân viên cập nhật, hệ thống thông báo cho khách. Khung giờ hiển thị là **dự kiến**, chưa phải cam kết (cam kết dịch vụ SLA là XM).

**Cơ sở:** sức chứa theo số đơn do quản trị đặt là cách đơn giản nhất để “theo năng lực xử lý dự kiến” mà không cần dữ liệu lịch sử, sức chứa tính theo tổng số trang hoặc theo thời gian máy (chính xác hơn) được đưa vào E6/V2.

## 4.5. Quy trình xử lý ngoại lệ: file lỗi, hủy đơn, khiếu nại

**Các tình huống ngoại lệ có thể xảy ra**

| **Tình huống**                                           | **Đề xuất xử lý**                                                                                                                                                           |
|----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| File PDF hỏng, có mật khẩu, sai khổ hoặc mờ.             | Hệ thống chặn ngay khi tải lên nếu phát hiện được, nếu sót, nhân viên gắn cờ “cần file mới”, đơn tạm dừng, khách được liên hệ và tải lại file, thời hạn nhận được tính lại. |
| Khách muốn hủy trước khi in.                             | Cho phép hủy tự động khi đơn ở “Chờ thanh toán” hoặc “Đã tiếp nhận”, hoàn tiền theo chính sách.                                                                             |
| Khách muốn hủy sau khi đã vào in.                        | Mặc định không hủy tự động, quản trị xem xét từng trường hợp. Chính sách này cần đối chiếu quy định bảo vệ người tiêu dùng và thực tế cửa hàng.                             |
| Thành phẩm sai do lỗi cửa hàng (in sai cấu hình đã đặt). | In lại hoặc hoàn tiền, ghi nhận trong nhật ký để cải tiến.                                                                                                                  |
| Khách tải lên nội dung vi phạm bản quyền/pháp luật.      | Điều khoản yêu cầu khách chịu trách nhiệm về quyền sử dụng tài liệu, cửa hàng có quyền từ chối đơn.                                                                         |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

# 5. YÊU CẦU PHI CHỨC NĂNG (NON-FUNCTIONAL REQUIREMENTS - NFRs)

**Bảng yêu cầu phi chức năng**

| **Nhóm Yêu cầu** | **Tiêu chuẩn / Chỉ số Đạt được (Metric)** | **Giải pháp Kỹ thuật & Vận hành** |
|---|---|---|
| **Hiệu năng (Performance)** | • Thời gian trích xuất trang PDF < 2 giây cho file 100 trang.<br>• Thời gian tính giá Real-time < 0.5 giây.<br>• Tải trang Web < 2.5 giây. | Sử dụng Async Background Worker xử lý PDF, Cache Redis cho bảng giá vật tư. |
| **Bảo mật (Security & Privacy)** | • 100% kết nối qua HTTPS/TLS 1.3.<br>• File PDF của khách hàng được mã hóa lưu trữ.<br>• Tự động xóa vĩnh viễn file trên Server sau 30 ngày hoàn tất đơn. | Bảo mật tài liệu luận văn/khóa luận chưa công bố cho sinh viên. Tuân thủ bảo vệ dữ liệu cá nhân. |
| **Khả dụng (Usability & UX)** | • Thiết kế Chuẩn Responsive (Mobile/Tablet/Desktop).<br>• Luồng đặt hàng không quá 3 bước chính. | Giao diện tối giản, tối ưu hóa cho thao tác trên điện thoại thông minh của sinh viên. |
| **Độ tin cậy (Reliability)** | • Uptime hệ thống đạt 99.5% trong suốt kỳ học.<br>• Tự động sao lưu Database hàng ngày (Daily Backup). | Triển khai trên hạ tầng Cloud (AWS/Google Cloud) có cơ chế Auto-scaling khi cao điểm. |
| **Khả năng nâng cấp (Maintainability)** | • Kiến trúc Mô-đun hóa (Modular Architecture / RESTful API).<br>• Dễ dàng bổ sung tiệm in đối tác mới. | Tách biệt hoàn toàn Frontend (ReactJS/NextJS) và Backend (NodeJS/Python Django/Laravel). |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

# 6. Các chức năng nên hoàn thành ở phiên bản đầu tiên

## 6.1. Nguyên tắc chọn phạm vi

Vì nhóm chưa cung cấp thời gian và quy mô, tài liệu không ấn định một danh sách cố định rằng nhóm “sẽ làm xong”, mà đưa ra phạm vi phân tầng và quy tắc cắt giảm. Ba nguyên tắc chọn:

- **Chạy được trọn một đơn** (“xương sống”, walking skeleton): có đường đi từ chọn dịch vụ đến hoàn tất, dù mỗi bước còn đơn giản. Cơ sở: một hệ thống chạy thông suốt nhưng thô có giá trị hơn nhiều module đẹp nhưng chưa nối được với nhau.

- **Có đủ ba điểm khác biệt ở mức tối thiểu**: tính giá tự động, đặt lịch có sức chứa, gợi ý tiết kiệm bằng quy tắc. Cơ sở: đây là lý do tồn tại của PrintSlot so với việc nhắn tin hỏi tiệm.

- **Ưu tiên rủi ro cao làm sớm**: các phần phụ thuộc bên ngoài hoặc khó (đọc PDF, thanh toán, tính giá) nên làm thử sớm để biết khả thi. Cơ sở: rủi ro bị phát hiện muộn sẽ phá kế hoạch.

## 6.2. Danh sách ưu tiên (làm trước)

Cột “độ phức tạp” là **đánh giá tương đối của người phân tích** (T: thấp, TB: trung bình, C: cao), chỉ để nhóm tham khảo khi ước lượng, nhóm cần tự đánh giá lại theo năng lực.

**Bảng danh sách các chức năng được ưu tiên thực hiện**

| **Chức năng**                                                 | **Độ phức tạp** | **Phụ thuộc / ghi chú**                                                                                   |
|---------------------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------|
| Đăng ký, đăng nhập                                            | TB              | Nền tảng cho phân quyền và đơn hàng.                                                                      |
| Hồ sơ và địa chỉ (mức tối thiểu)                              | T               | Cần cho giao nhận (F2) và liên hệ.                                                                        |
| Phân quyền (tối thiểu hai vai trò: khách, quản trị/nhân viên) | TB              | Làm cùng A1, có thể tách nhân viên/quản trị sau.                                                          |
| Danh mục dịch vụ                                              | T               | Dữ liệu dịch vụ nhập sẵn.                                                                                 |
| Bảng giá và quản lý bảng giá                                  | TB              | Là dữ liệu đầu vào của D1, cần số liệu từ cửa hàng hoặc giả định ghi rõ.                                  |
| Tải PDF, đếm trang                                            | TB              | Cần thư viện đọc PDF và nơi lưu file, thử sớm.                                                            |
| Cấu hình in                                                   | TB              | Phụ thuộc B2.                                                                                             |
| Đơn nhiều mục                                                 | TB              | Quyết định cấu trúc dữ liệu đơn - làm đúng ngay từ đầu.                                                   |
| Bộ tính giá và hiển thị chi tiết                              | C               | Cốt lõi, cần bộ tes.                                                                                      |
| Chọn khung giờ và cấu hình sức chứa                           | TB              | Cần xử lý đồng thời, mức đầu chỉ dùng sức chứa theo số đơn.                                               |
| Nhận tại quầy và xác nhận hoàn tất                            | T               | Đóng vòng đời đơn.                                                                                        |
| Thanh toán trực tuyến và ghi nhận                             | C               | Phụ thuộc bên ngoài, làm thử (spike) sớm, có thể bắt đầu bằng thanh toán giả lập rồi thay bằng cổng thật. |
| Theo dõi trạng thái và lịch sử đơn                            | TB              | Phụ thuộc cấu trúc đơn và trạng thái.                                                                     |
| Quản lý đơn và cập nhật trạng thái                            | TB              | Giao diện nhân viên.                                                                                      |
| Trang chủ và chính sách                                       | T               | Nội dung tĩnh, cần rà soát                                                                                |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

**Thứ tự phụ thuộc kỹ thuật gợi ý** (không phải lịch thời gian): (1) nền tảng tài khoản, vai trò, cơ sở dữ liệu → (2) danh mục dịch vụ và bảng giá → (3) tải file, cấu hình, bộ tính giá, đơn nhiều mục → (4) khung giờ và nhận hàng → (5) tạo đơn và thanh toán → (6) theo dõi trạng thái và giao diện nhân viên.

## 6.3. Tiêu chí hoàn thành các chức năng ưu tiên

Được coi là hoàn thành khi trình diễn được kịch bản sau không cần can thiệp thủ công vào cơ sở dữ liệu:

1. Khách đăng ký/đăng nhập, xem dịch vụ và bảng giá.
2. Khách tải một file PDF (nhiều trang), hệ thống tự đếm trang.
3. Khách đổi các cấu hình (màu, mặt, số bản, đóng gáy) và thấy báo giá thay đổi đúng, có chi tiết.
4. Khách thêm hai mục vào một đơn với cấu hình khác nhau.
5. Khách chọn khung giờ nhận còn chỗ, khung giờ hết chỗ không chọn được.
6. Khách thanh toán (môi trường thử nghiệm) và thấy đơn ở trạng thái Đã tiếp nhận.
7. Nhân viên đăng nhập, thấy đơn, tải file, chuyển lần lượt các trạng thái tới Hoàn tất, khách thấy trạng thái cập nhật.
8. Quản trị đổi đơn giá, đơn mới theo giá mới, đơn cũ giữ giá cũ.

# 7. Các chức năng nâng cao có thể bổ sung

Các chức năng dưới đây **không thuộc phạm vi bàn giao đầu tiên**. Mỗi mục nêu giá trị, điều kiện để làm và cơ sở đề xuất để nhóm cân nhắc khi còn nguồn lực hoặc trình bày hướng phát triển.

**Bảng chức năng nâng cao bổ sung**

| **Chức năng nâng cao**                                     | **Giá trị và cơ sở đề xuất**                                                                                                                  | **Điều kiện / phụ thuộc**                                                                                                      |
|------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| **Cấu hình theo dải trang và xem trước PDF**               | Cho phép in màu đúng những trang cần và giúp khách kiểm tra file, liên quan trực tiếp đến mục tiêu tiết kiệm chi phí.                         | M1 ổn định, cần xử lý PDF phía máy chủ/trình duyệt, cần khảo sát để biết nhu cầu thực.                                         |
| **Phát hiện trang màu và gợi ý đen trắng**                 | Nâng gợi ý tiết kiệm từ quy tắc cố định lên gợi ý dựa trên nội dung file.                                                                     | Xử lý ảnh/PDF tốn tài nguyên, cần kiểm chứng độ chính xác để tránh gợi ý sai.                                                  |
| **Hỗ trợ Word/PowerPoint**                                 | Giảm bước cho khách vì không phải tự xuất PDF.                                                                                                | Cần dịch vụ chuyển đổi, phải xử lý lệch font/bố cục, nên chuyển PDF để khách xem trước.                                        |
| **Ước tính thời gian và công suất động, xếp lịch tối ưu**  | Thay con số sức chứa thủ công bằng ước tính theo khối lượng thực (tổng số trang, số máy, nhân lực), gộp các đơn cùng cấu hình để in một lượt. | Cần dữ liệu thời gian xử lý thật tích lũy từ vận hành, cần thông tin thiết bị.                                                 |
| **Giảm giá bậc thang, voucher, ưu đãi thành viên**         | Khuyến khích đơn lớn và khách quay lại, phù hợp nhóm CLB/sự kiện.                                                                             | Chính sách giá do cửa hàng quyết, cần quy tắc chống lạm dụng.                                                                  |
| **Combo PowerPoint kèm standee thuê/mua**                  | Hoàn thiện đề tài gốc, mở rộng doanh thu từ nhóm sự kiện.                                                                                     | Cần quản lý tồn kho, lịch thuê, đặt cọc, hoàn trả, xác nhận cửa hàng có dịch vụ này.                                           |
| **Tài khoản tổ chức/CLB (A6) và đơn nhóm**                 | Nhiều người cùng góp file, một người đại diện thanh toán, phù hợp “báo cáo nhóm”.                                                             | Cần khảo sát nhu cầu, thêm vai trò và luồng phê duyệt.                                                                         |
| **Tích hợp đơn vị vận chuyển**                             | Theo dõi hành trình, tính phí động, giảm công giao hàng nội bộ.                                                                               | Phụ thuộc API và chi phí, cần hợp đồng/điều kiện của bên thứ ba.                                                               |
| **Thông báo Zalo/SMS, nhắc lịch nhận, mã QR nhận hàng**    | Kênh phù hợp thói quen sinh viên, giảm nhỡ hẹn.                                                                                               | Chi phí và điều kiện kết nối của nhà cung cấp, cần sự đồng ý nhận thông báo của khách.                                         |
| **Hoàn tiền tự động và hóa đơn điện tử**                   | Giảm công đối soát, phục vụ nhu cầu chứng từ.                                                                                                 | Phụ thuộc API cổng thanh toán và quy định hóa đơn hiện hành.                                                                   |
| **Chat, đánh giá đơn, báo cáo nâng cao**                   | Tăng chăm sóc khách hàng và dữ liệu cải tiến dịch vụ.                                                                                         | Cần nhân lực trả lời, cần dữ liệu tích lũy.                                                                                    |
| **Đăng nhập Google, đặt lại đơn**                          | Giảm ma sát đăng ký và thao tác lặp lại.                                                                                                      | Giả thuyết cần kiểm chứng bằng khảo sát.                                                                                       |
| **Mở rộng nhiều cửa hàng / nhiều điểm nhận (marketplace)** | Mở rộng quy mô, phân bổ đơn theo công suất từng tiệm.                                                                                         | Thay đổi mô hình kinh doanh, cần đối soát, phân quyền theo cửa hàng. Chỉ nên xét sau khi mô hình một cửa hàng được kiểm chứng. |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

# 8. RỦI RO TRIỂN KHAI VÀ BIỆN PHÁP GIẢM THIỂU

**Bảng quản trị rủi ro đề xuất**

| **Mã Rủi ro** | **Mô tả Rủi ro Triển khai**                                                     | **Mức độ**     | **Xác suất** | **Biện pháp Giảm thiểu & Dự phòng**                                                                                                                                                     |
|---------------|---------------------------------------------------------------------------------|----------------|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| RSK-01        | File PDF bị khóa mật khẩu, mã hóa hoặc đếm sai trang do đè layer vector.        | **Cao**        | Trung bình   | Tích hợp thư viện PDF Parser chuẩn hóa. Nếu gặp file mã hóa, hệ thống yêu cầu nhập Password hoặc cho phép khách tự điền số trang thủ công kèm xác nhận.                                 |
| RSK-02        | Tiệm in bị quá tải vỡ ca (quá Capacity Slot) vào tuần lễ thi/nộp khóa luận.     | **Cao**        | Cao          | Thuật toán Dynamic Slot giới hạn cứng số đơn tiếp nhận theo giờ. Cho phép tiệm in bật chế độ 'Tạm ngưng nhận đơn' chỉ bằng 1-click trên Dashboard.                                      |
| RSK-03        | Khách hàng bùng đơn / Không đến nhận thành phẩm (đặc biệt đơn C.O.D).           | **Cao**        | Trung bình   | Bắt buộc thanh toán trực tuyến 100% trước khi tiệm in tiến hành sản xuất đối với toàn bộ các sản phẩm in theo yêu cầu (C.O.D chỉ áp dụng đơn Combo có sẵn).                             |
| RSK-04        | Rò rỉ tài liệu học tập, báo cáo nghiên cứu, đề thi hoặc khóa luận chưa công bố. | **Rất Cao**    | Thấp         | Cam kết điều khoản bảo mật (NDA) trên Web. Thiết lập Script tự động xóa sạch file trên Server sau 30 ngày kể từ khi giao hàng.                                                          |
| RSK-05        | Tiến độ dự án bị trễ do nhóm sinh viên thiếu thời gian hoặc kỹ năng lập trình.  | **Trung bình** | Trung bình   | Thực hiện phân kỳ rõ ràng: Chỉ tập trung làm xong 100% tính năng Bắt buộc (MVP). Không tham làm tính năng nâng cao (Nội thành giao hỏa tốc/Phân tích độ phủ mực) khi MVP chưa chạy tốt. |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

**Nhiệm vụ 4 – Dùng một công cụ AI khác để phản biện**
**Sử dụng Claude AI để phẩn biện lại**
# 1. Dữ liệu đầu vào dùng để phản biện

Thông tin dự án: 7 thành viên, thời gian thực hiện 2-3 tháng, khách hàng mục tiêu là học sinh, sinh viên tại TP.HCM. Vấn đề kinh doanh trong đề tài được ghi rõ là giả thuyết, chưa kiểm chứng. Ba điểm khác biệt đề xuất: tính giá tự động, đặt lịch thông minh theo năng lực xử lý, gợi ý cấu hình in tiết kiệm.

**Kết quả quan sát ba website tham khảo**

| **Website**                 | **Tính năng thấy trên trang**                                                                                                                                                           | **Tính năng không thấy**                                                                                                      |
|-----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| Website A: In Sài Gòn       | Biểu mẫu yêu cầu báo giá (gửi thủ công), giỏ hàng, thanh toán, nhiều cổng thanh toán, COD, chuyển khoản QR, tra cứu đơn hàng, chọn hãng vận chuyển hoặc nhận tại cửa hàng, mã giảm giá. | Báo giá tự động, tải file lên, chọn thông số in, đặt lịch nhận hàng.                                                          |
| Website B: In Nhanh Co      | Nút “Đặt in ngay”, giỏ hàng có mã giảm giá và ghi chú, đồng hồ đếm ngược thời hạn thanh toán, đăng ký, đăng nhập, đặt lại mật khẩu, tra cứu đơn hàng, hướng dẫn đặt in.                 | Báo giá tự động (bảng giá tĩnh), tải file lên, chọn thông số in chi tiết, đặt lịch nhận hàng.                                 |
| Website C: In KTS Đại Dương | Danh mục sản phẩm, liên hệ qua Zalo, Messenger, điện thoại, làm mẫu thử, các trang hướng dẫn đặt hàng, thanh toán, giao hàng.                                                           | Báo giá tự động, tải file, chọn thông số in, thanh toán online, theo dõi đơn, đặt lịch nhận hàng (không thấy trên trang chủ). |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

# 2. Kết quả phản biện theo sáu khía cạnh

Mỗi vấn đề có mã riêng (ví dụ 3.2 là vấn đề thứ hai của khía cạnh 3) để dễ tham chiếu ở bảng tổng hợp. Khi bảng nhắc “mục X”, “FN”, “HYP”, “RSK” là nội dung trong bản yêu cầu của AI thứ nhất (file bài tập), mã dạng 3.2 là mã vấn đề trong tài liệu này.

## Khía cạnh 1. Có thực sự giải quyết vấn đề kinh doanh không?

Nhận xét chung: hướng đi đúng. Phần lớn chức năng MUST-HAVE bám sát các nỗi đau đã nêu (chờ đợi, giá không rõ, sai cấu hình, tiệm quá tải). Điểm yếu nằm ở chỗ nhiều con số mục tiêu chưa có cơ sở và các giả thuyết quan trọng nhất chưa được đưa vào kế hoạch kiểm chứng.

| **Mã** | **Vấn đề phát hiện**                                                                                                                             | **Lý do**                                                                                                                                                                                                                                                       | **Đề xuất điều chỉnh**                                                                                                                                                                                                                                                                         |
|--------|--------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.1    | Các con số mục tiêu chưa có cơ sở: “20-30 phút xuống 0 phút”, “tăng 30-40% sản lượng”, “giảm 90% thời gian báo giá”, “tiết kiệm 20-40% chi phí”. | Đề tài ghi rõ vấn đề kinh doanh là giả thuyết, chưa kiểm chứng. Con số “0 phút” không đạt được vì khách vẫn phải đến quầy nhận hàng.<br>Ví dụ ở mục 4.3 của chính bản yêu cầu chỉ tiết kiệm 15%, không phải 20-40%.                                             | Gắn nhãn “giả định, cần khảo sát” cho mọi con số chưa có nguồn.<br>Thay bằng chỉ tiêu đo được trong khả năng của nhóm, ví dụ: khách nhận báo giá chi tiết trong vòng 1 phút sau khi tải file, khách đến đúng khung giờ nhận hàng trong ≤ 5 phút (đo bằng thử nghiệm nhỏ).                      |
| 1.2    | Giả thuyết cốt lõi chưa nằm trong danh sách cần kiểm chứng. Hiện chỉ có 3 giả thuyết (HYP-01 đến HYP-03).                                        | Chưa có giả thuyết nào hỏi: sinh viên có sẵn sàng đặt in qua web thay vì đến tiệm không, báo giá tự động có thật sự hữu ích không, có tiệm thật nào cung cấp bảng giá và nhận làm đối tác không.<br>Nếu các giả thuyết này sai thì dự án mất cơ sở.             | Thêm HYP-04: sinh viên chấp nhận tải file PDF và đặt in qua web, coi báo giá tự động là hữu ích.<br>Thêm HYP-05: có ít nhất một tiệm cung cấp bảng giá thật và mô tả quy trình xử lý đơn.<br>Cách kiểm chứng: khảo sát sinh viên (đề xuất tối thiểu khoảng 30 phiếu) và phỏng vấn 1-3 tiệm in. |
| 1.3    | Bản yêu cầu khẳng định “tính giá tự động” và “đặt lịch” là điểm khác biệt nhưng không trích dẫn kết quả khảo sát ba website.                     | Một điểm khác biệt chỉ thuyết phục khi có đối chứng. Quan sát trang chủ ba website tham khảo (xem phần 3 của tài liệu này) cho thấy chưa có website nào có báo giá tự động hay đặt lịch nhận hàng, nên nhận định của AI thứ nhất là hợp lý nhưng cần dẫn chứng. | Đưa bảng so sánh ba website vào phần giải trình lựa chọn chức năng MUST-HAVE. Nếu bảng khảo sát của nhóm khác với quan sát ở phần 3 của tài liệu này thì dùng bảng của nhóm.                                                                                                                   |

## Khía cạnh 2. Có yêu cầu nào trùng lặp hoặc không cần thiết không?

Nhận xét chung: có, chủ yếu do cùng một nội dung được viết ở nhiều mục và do một số chức năng chỉ phục vụ Phase 2 nhưng vẫn nằm trong danh sách phiên bản đầu.

| **Mã** | **Vấn đề phát hiện**                                                                                                                  | **Lý do**                                                                                                                                                                                                    | **Đề xuất điều chỉnh**                                                                                                                                 |
|--------|---------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2.1    | Mục “Hồ sơ và địa chỉ” nằm trong danh sách làm trước.                                                                                 | Địa chỉ chỉ cần cho giao tận nơi (FN-10, thuộc Phase 2). Phiên bản đầu chỉ nhận tại quầy.                                                                                                                    | Phiên bản đầu chỉ lưu họ tên, số điện thoại, email. Địa chỉ chuyển sang Phase 2 cùng giao hàng.                                                        |
| 2.2    | Vai trò Khách hàng tổ chức/CLB/Giảng viên (B2B) được tách riêng, kèm hóa đơn GTGT và chiết khấu.                                      | Quyền gần như trùng khách cá nhân (tải file, cấu hình, thanh toán, theo dõi). Phần khác biệt (hóa đơn, chiết khấu, đơn nhóm) lại được mục 7 xếp vào chức năng nâng cao. Mục 6.2 cũng chỉ làm 2 nhóm vai trò. | Phiên bản đầu dùng 4 vai trò: Guest, Khách hàng, Nhân viên, Quản trị. Vai trò B2B, hóa đơn GTGT, chiết khấu chuyển sang Phase 2.                       |
| 2.3    | Vòng đời trạng thái đơn được mô tả ở nhiều nơi: FN-07, mục 4.1, mục 4.2, ma trận phân quyền.                                          | Dễ viết hai lần và lệch nhau. Đã có chỗ lệch: trạng thái “Đang giao” vẫn xuất hiện trong khi phiên bản đầu chỉ nhận tại quầy.                                                                                | Gộp thành một yêu cầu “Vòng đời trạng thái đơn” gồm bảng chuyển trạng thái hợp lệ và người được phép chuyển. FN-07 chỉ còn là phần hiển thị cho khách. |
| 2.4    | Mốc xóa file ghi ở hai nơi với hai mốc khác nhau: mục 5 ghi “30 ngày sau khi hoàn tất đơn”, RSK-04 ghi “30 ngày kể từ khi giao hàng”. | Hai mốc khác nhau sẽ cho hai cách lập trình và hai cách kiểm thử.                                                                                                                                            | Chọn một mốc duy nhất (kể từ khi đơn ở trạng thái Hoàn tất), ghi tại một chỗ, các mục khác chỉ tham chiếu.                                             |
| 2.5    | Từ “Real-time” trong FN-03.                                                                                                           | Chỉ cần tính lại giá mỗi khi khách đổi cấu hình. Từ này gợi ý một cơ chế phức tạp mà bài toán không cần.                                                                                                     | Viết lại: hệ thống tính lại và hiển thị giá trong vòng 0,5 giây sau mỗi lần khách đổi cấu hình.                                                        |

## Khía cạnh 3. Có chức năng nào vượt quá phạm vi của nhóm không?

Nhận xét chung: có. Với 7 người trong 2-3 tháng, các hạng mục dưới đây nên cắt khỏi phiên bản đầu hoặc thu nhỏ.

| **STT** | **Vấn đề phát hiện**                                                                                                                                                                                     | **Lý do**                                                                                                                                                                                                 | **Đề xuất điều chỉnh**                                                                                                                                                                                                                      |
|---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1       | Combo PowerPoint kèm standee (thuê/mua) nằm trong phạm vi (mục 1.3), trong khi FN-08 chỉ nêu Combo báo cáo và khóa luận, còn HYP-03 chưa biết có nhu cầu thuê hay không.                                 | Cho thuê cần quản lý tồn kho, lịch thuê, đặt cọc, hoàn trả. Chính mục 7 của bản yêu cầu cũng nêu các điều kiện này. Vượt năng lực 2-3 tháng của nhóm.                                                     | Phiên bản đầu: Combo chỉ gồm báo cáo nhóm và khóa luận. Poster, standee, decal, bản vẽ xử lý bằng biểu mẫu yêu cầu báo giá (xem vấn đề 4.1). Cho thuê standee chuyển sang Phase 2, chỉ làm nếu HYP-03 được xác nhận.                        |
| 2       | Thanh toán trực tuyến liệt kê 4 phương thức (MoMo, VNPay, ZaloPay, QR) ở mục 1.3, trong khi FN-06 chỉ ghi MoMo/QR.                                                                                       | Mỗi cổng là một lần tích hợp, kiểm thử và xử lý lỗi riêng. Hai phần của bản yêu cầu cũng không thống nhất. Các website thương mại lâu năm có nhiều cổng nhưng đó không phải chuẩn cho một nhóm sinh viên. | Phiên bản đầu: một cổng ở môi trường thử nghiệm (sandbox), cộng một cách thanh toán dự phòng bằng QR chuyển khoản do nhân viên xác nhận thủ công. Các cổng còn lại chuyển sang Phase 2. Nhóm chọn cổng sau khi đọc tài liệu và thử gọi sớm. |
| 3       | Hỏa tốc và giao tận nơi được xếp Phase 2 ở mục 3 nhưng vẫn nằm trong luồng chuẩn: bước 6, 7 của mục 4.1, mục 4.4 (điểm 3), trạng thái “Đang giao”. Mục 1.3 lại loại “đội giao hàng nội bộ” khỏi phạm vi. | Phân loại và quy trình mâu thuẫn nhau nên lập trình viên không biết phải làm hay không làm.                                                                                                               | Chuyển nhất quán sang Phase 2. Phiên bản đầu chỉ nhận tại quầy, trạng thái cuối là “Sẵn sàng nhận”. Giữ tên “Đang giao” trong bảng trạng thái nhưng ghi chú là dùng từ Phase 2.                                                             |
| 4       | Yêu cầu phi chức năng chỉ định hạ tầng và công nghệ: AWS/Google Cloud có auto-scaling, Redis, uptime 99,5% suốt kỳ học, TLS 1.3 cho 100% kết nối.                                                        | Chi phí và công vận hành vượt khả năng của nhóm. Phần “giải pháp kỹ thuật” là thiết kế, không phải yêu cầu, nên làm yêu cầu bị gắn chặt vào một công nghệ.                                                | Viết lại thành yêu cầu đo được: hệ thống chạy ổn định trong các buổi thử nghiệm và buổi bảo vệ, dùng HTTPS, sao lưu cơ sở dữ liệu định kỳ. Việc chọn cloud, Redis, framework chuyển sang tài liệu thiết kế, chọn theo kỹ năng của nhóm.     |
| 5       | Phiên bản đầu có “đối tác tiệm in” (số nhiều) và NFR “dễ dàng bổ sung tiệm in đối tác”, trong khi mục 7 ghi mô hình nhiều cửa hàng (marketplace) chỉ nên xét sau.                                        | Nhiều tiệm kéo theo phân quyền theo cửa hàng, đối soát, bảng giá riêng từng tiệm.                                                                                                                         | Ghi rõ: phiên bản đầu chỉ phục vụ một cửa hàng. Mô-đun hóa chỉ cần đủ để Phase 2 mở rộng, không phải làm sẵn.                                                                                                                               |

## Khía cạnh 4. Có thiếu chức năng cơ bản hoặc quy trình nghiệp vụ nào không?

Nhận xét chung: có. Nhiều tình huống đã được mô tả trong quy trình nhưng không có chức năng tương ứng, và có mâu thuẫn giữa các mục.

| **STT** | **Vấn đề phát hiện**                                                                                                                                                                                                                                                                                       | **Lý do**                                                                                                                                                                                                                                    | **Đề xuất điều chỉnh**                                                                                                                                                                                 |
|---------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1       | Có “biểu mẫu yêu cầu báo giá” cho dịch vụ đặc thù trong luồng (mục 4.1, bước 1) nhưng danh sách chức năng không có chức năng tương ứng.                                                                                                                                                                    | Đề tài có bản vẽ kỹ thuật, poster, decal, standee, là loại khó tính giá tự động. Không có chức năng này thì phần dịch vụ đó của đề tài không có cách đặt. Website A cũng dùng biểu mẫu yêu cầu báo giá (quan sát ở phần 3 của tài liệu này). | Thêm chức năng: khách gửi yêu cầu (loại sản phẩm, kích thước, số lượng, file, số điện thoại), nhân viên trả lời giá thủ công, đơn tạo sau khi khách đồng ý.                                            |
| 2       | Hủy đơn và hoàn tiền chỉ được mô tả ở mục 4.5, không có trong danh sách chức năng và ma trận phân quyền.                                                                                                                                                                                                   | Đây là tình huống chắc chắn xảy ra khi có thanh toán trước. Thiếu chức năng thì không có gì để lập trình và kiểm thử.                                                                                                                        | Thêm: khách tự hủy khi đơn ở “Chờ thanh toán” hoặc “Đã tiếp nhận”, Quản trị ghi nhận hoàn tiền (làm thủ công ở phiên bản đầu), thêm quyền “Hủy đơn” cho Khách và “Hoàn tiền” cho Quản trị vào ma trận. |
| 3       | Mục 4.5 nói đơn “tạm dừng” khi file lỗi nhưng bảng trạng thái ở mục 4.2 không có trạng thái này, và chưa có chức năng khách tải lại file.                                                                                                                                                                  | Khách không biết vì sao đơn đứng yên, nhân viên không có cách ghi nhận.                                                                                                                                                                      | Thêm trạng thái hoặc cờ “Cần bổ sung file”, kèm chức năng khách tải file thay thế và quy tắc tính lại thời hạn nhận.                                                                                   |
| 4       | Chưa có quy tắc cho trường hợp khách thanh toán thành công sau khi hết hạn giữ chỗ.                                                                                                                                                                                                                        | Kết quả từ cổng thanh toán có thể đến trễ. Lúc đó khung giờ có thể đã được giải phóng và người khác đã đặt. Tiền đã thu nhưng không còn chỗ.                                                                                                 | Quy tắc: nếu khung giờ còn trống thì chuyển đơn sang Đã tiếp nhận, nếu không thì báo khách chọn khung giờ khác trong một thời hạn hoặc hoàn tiền, ghi nhật ký mọi trường hợp.                          |
| 5       | Thiếu chức năng tài khoản cơ bản: quên mật khẩu, đổi mật khẩu, xác thực email.                                                                                                                                                                                                                             | Không có thì khách mất mật khẩu sẽ mất luôn lịch sử đơn. Website B có đặt lại mật khẩu (quan sát ở phần 3 của tài liệu này), nên đây là chức năng thông thường.                                                                              | Thêm: đổi mật khẩu, quên mật khẩu qua email. Xác thực email ở mức đơn giản.                                                                                                                            |
| 6       | Thông báo chỉ ghi “nếu có” (H3).                                                                                                                                                                                                                                                                           | Slot nhận hàng chỉ có ý nghĩa khi khách biết đơn đã xong. Thiếu thông báo thì khách vẫn phải hỏi tiệm, trái với mục tiêu ban đầu.                                                                                                            | Phiên bản đầu: gửi email khi đơn được tiếp nhận và khi “Sẵn sàng nhận”. Zalo/SMS để Phase 2.                                                                                                           |
| 7       | Chưa có cách xác nhận đúng người nhận khi nhận tại quầy.                                                                                                                                                                                                                                                   | Bước 14 chỉ ghi nhân viên xác nhận. Tài liệu có thể chưa công bố nên giao nhầm là sự cố nghiêm trọng.                                                                                                                                        | Mỗi đơn có mã nhận hàng, nhân viên đối chiếu mã đơn và số điện thoại khi giao.                                                                                                                         |
| 8       | “Tạm ngưng nhận đơn bằng 1 click” (RSK-02) chỉ có trong bảng rủi ro, không có trong chức năng, ma trận phân quyền hay mục 4.4. Cũng chưa có ngày nghỉ/đóng cửa cho khung giờ.                                                                                                                              | Một biện pháp giảm thiểu rủi ro mà không có chức năng tương ứng thì chỉ là lời hứa.                                                                                                                                                          | Thêm vào chức năng Quản trị: bật/tắt nhận đơn, đặt ngày nghỉ và khung giờ không nhận.                                                                                                                  |
| 9       | Mục 3 và mục 6 mâu thuẫn nhau: FN-04 (gợi ý tiết kiệm) và FN-08 (Combo) là MUST-HAVE nhưng không có trong danh sách ưu tiên 6.2, báo cáo doanh thu có trong ma trận nhưng cũng không có trong 6.2. Mục 6.1 còn viết “nhóm chưa cung cấp thời gian và quy mô” trong khi đề tài ghi 2-3 tháng, 7 thành viên. | Tài liệu yêu cầu phải nhất quán thì mới làm căn cứ lập kế hoạch và nghiệm thu. Nếu theo 6.2 thì phiên bản đầu thiếu một trong ba điểm khác biệt (gợi ý tiết kiệm).                                                                           | Bổ sung FN-04 (dạng quy tắc, xem vấn đề 6.1) và Combo vào 6.2. Báo cáo doanh thu: mức tối thiểu (tổng đơn, doanh thu theo ngày) hoặc Phase 2. Sửa 6.1 theo dữ kiện thật: 7 người, 2-3 tháng.           |

## Khía cạnh 5. Có rủi ro về dữ liệu, bảo mật hoặc quyền riêng tư không?

Nhận xét chung: có. Bản yêu cầu nhận ra rủi ro rò rỉ tài liệu (RSK-04) nhưng biện pháp đưa ra còn chung chung, thiếu việc cụ thể để lập trình.

| **STT** | **Vấn đề phát hiện**                                                                                          | **Lý do**                                                                                                                                                                                                                                 | **Đề xuất điều chỉnh**                                                                                                                                                                                                                                                                                       |
|---------|---------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 5.1     | Dùng “cam kết NDA trên web” để bảo vệ tài liệu khách.                                                         | NDA là thỏa thuận giữa các bên cụ thể, không phải biện pháp bảo mật của một website. Điều khách cần là biết dữ liệu của mình được dùng và lưu thế nào. Bản yêu cầu cũng mới nói “tuân thủ bảo vệ dữ liệu cá nhân” mà chưa có việc cụ thể. | Thay bằng: chính sách quyền riêng tư, điều khoản sử dụng (gồm điều khoản khách chịu trách nhiệm bản quyền tài liệu, đã có ở mục 4.5), ô đồng ý khi đăng ký và khi xác nhận đơn, chỉ thu dữ liệu cần thiết. Nhóm đối chiếu với Nghị định 13/2023/NĐ-CP và văn bản về bảo vệ dữ liệu cá nhân đang có hiệu lực. |
| 5.2     | Chưa nêu kiểm soát truy cập file của khách (RSK-04 được đánh giá mức Rất cao).                                | Khóa luận chưa công bố là dữ liệu nhạy cảm nhất của hệ thống. Lỗi thường gặp là người dùng đổi mã đơn trên đường dẫn để xem đơn người khác.                                                                                               | Chỉ chủ đơn và nhân viên/quản trị được tải file, đường dẫn tải có thời hạn, kiểm tra quyền ở máy chủ cho mỗi lần tải, ghi nhật ký ai đã tải file nào, lúc nào.                                                                                                                                               |
| 5.3     | Xóa file sau 30 ngày kể từ khi hoàn tất đơn.                                                                  | Lưu lâu hơn mức cần thiết làm tăng rủi ro rò rỉ. Mặt khác cần giữ một thời gian để xử lý khiếu nại hoặc in lại. File của đơn đã hủy hoặc chưa thanh toán không có lý do lưu lâu. Cũng chưa nói “xóa vĩnh viễn” có gồm bản sao lưu không.  | Đặt thời hạn là tham số cấu hình, nhóm chốt sau khi hỏi tiệm (ví dụ 7-14 ngày sau Hoàn tất, nhóm tự xác nhận), đơn hủy/chưa thanh toán xóa sau vài ngày, cho khách chủ động xóa file, ghi rõ cách xử lý bản sao lưu.                                                                                         |
| 5.4     | Kiểm tra file tải lên mới dừng ở định dạng và dung lượng.                                                     | Chỉ kiểm tra đuôi .pdf thì file giả mạo vẫn qua được. Tên file do khách đặt không nên dùng làm tên lưu.                                                                                                                                   | Kiểm tra loại thật của file, giới hạn dung lượng và số trang cụ thể, lưu bằng tên ngẫu nhiên, không thực thi nội dung file. Quét mã độc để Phase 2.                                                                                                                                                          |
| 5.5     | Thanh toán: bản yêu cầu đã nêu tính giá ở máy chủ và chống ghi nhận trùng, nhưng thiếu các biện pháp còn lại. | Nếu tin kết quả do trình duyệt báo về, khách có thể tự giả mạo “đã thanh toán”.                                                                                                                                                           | Không lưu dữ liệu thẻ, chỉ lưu mã giao dịch. Xác thực chữ ký thông báo kết quả từ cổng. Chỉ đổi trạng thái đơn theo kết quả máy chủ nhận được từ cổng.                                                                                                                                                       |
| 5.6     | Chưa có yêu cầu về bảo vệ tài khoản.                                                                          | Mật khẩu và số điện thoại khách là dữ liệu cá nhân. Nhân viên có quyền xem file nên cần giới hạn phạm vi.                                                                                                                                 | Mật khẩu lưu dạng băm, giới hạn số lần đăng nhập sai, kiểm tra phân quyền ở máy chủ, nhân viên chỉ xem thông tin liên hệ khi cần xử lý đơn.                                                                                                                                                                  |

## Khía cạnh 6. Có yêu cầu nào chưa đủ rõ để lập trình và kiểm thử không?

Nhận xét chung: có. Phần quy trình khá chi tiết nhưng nhiều quy tắc và con số còn để ngỏ, nên chưa thể viết kiểm thử.

| **Mã** | **Vấn đề phát hiện**                                                                                                                                | **Lý do**                                                                                                                                                                                                 | **Đề xuất điều chỉnh**                                                                                                                                                                                                                                                                                                          |
|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1      | FN-04 (gợi ý tiết kiệm) nói gợi ý “đen trắng cho trang chữ” và “tiết kiệm 20-40%”.                                                                  | Nhận diện trang nào chỉ có chữ cần phân tích nội dung file, chính là FN-11 (Phase 2). Con số 20-40% cũng không khớp ví dụ 15% ở mục 4.3. Chưa có quy tắc cụ thể nên không viết được kiểm thử.             | Phiên bản đầu chỉ dùng quy tắc dựa trên cấu hình. Quy tắc 1: nếu đang chọn in một mặt và có từ 2 trang trở lên thì gợi ý in hai mặt. Quy tắc 2: nhóm chọn thêm 1 quy tắc từ bảng giá thật. Chỉ hiển thị khi số tiền tiết kiệm đạt ngưỡng nhóm đặt. Hệ thống không tự đổi cấu hình (đã đúng ở bước 4 mục 4.1). Bỏ con số 20-40%. |
| 2      | Các quy tắc tính giá ở mục 4.3 (cách tính trang/mặt/tờ, làm tròn, giá tối thiểu, bậc giá, tài liệu lẫn trang màu) vẫn để mở.                        | Chưa chốt thì không viết được công thức và không biết kết quả đúng là bao nhiêu. Ví dụ minh họa ở mục 4.3 tính đúng (120.000 đ so với 102.000 đ, tiết kiệm 18.000 đ = 15%) nhưng đơn giá chỉ là giả định. | Chốt các quy tắc này trước khi lập trình. Lập bảng ít nhất 5 ca kiểm thử có đáp số mong đợi (số trang chẵn, lẻ, một mặt, hai mặt, nhiều bản, có đóng gáy). Thêm quy tắc: nếu khổ trang trong PDF khác khổ khách chọn thì hiện cảnh báo.                                                                                         |
| 3      | Sức chứa khung giờ đo bằng số đơn (mục 4.4).                                                                                                        | Đơn 5 trang và đơn 500 trang cùng chiếm 1 đơn, nên giới hạn không phản ánh năng lực thật và RSK-02 (quá tải) vẫn xảy ra. “Thời gian xử lý tối thiểu” cũng chưa có công thức.                              | Dùng hai giới hạn cho mỗi khung giờ: số đơn tối đa và tổng số mặt in tối đa. Thời gian xử lý tối thiểu = thời gian cố định + số trang × hệ số, do Quản trị cấu hình. Giá trị mặc định lấy từ trao đổi với tiệm.                                                                                                                 |
| 4      | Nhiều tham số quan trọng chưa có giá trị: số phút giữ chỗ (N), độ dài khung giờ, dung lượng và số trang tối đa của file, thời hạn xóa file.         | Lập trình viên và người kiểm thử cần giá trị cụ thể.                                                                                                                                                      | Lập bảng tham số cấu hình với giá trị khởi điểm do nhóm chốt, ví dụ: giữ chỗ 15 phút, khung giờ 60 phút, file tối đa vài chục MB. Đây là giá trị đề xuất để nhóm xác nhận, không phải số liệu thực tế.                                                                                                                          |
| 5      | Yêu cầu phi chức năng thiếu điều kiện đo: “trích xuất \< 2 giây cho 100 trang”, “tải trang \< 2,5 giây”, “luồng đặt hàng không quá 3 bước chính”.   | Không nói file nặng bao nhiêu, máy chủ nào, mạng nào. “3 bước” mâu thuẫn với luồng 14 bước của mục 4.1 vì chưa định nghĩa “bước”.                                                                         | Viết lại có điều kiện: ví dụ file ≤ X MB, 100 trang, đo trên môi trường triển khai của nhóm. Định nghĩa bước là một màn hình, ví dụ: (1) chọn và cấu hình, (2) chọn lịch và hình thức nhận, (3) xác nhận và thanh toán.                                                                                                         |
| 6      | Ma trận phân quyền ghi Guest không được tải PDF nhưng luồng 4.1 cho khách tải file, cấu hình, chọn khung giờ rồi mới “đăng nhập nếu chưa” ở bước 8. | Hai phần mô tả hai hành vi khác nhau. Cho khách chưa đăng nhập tải file còn kéo theo vấn đề file không có chủ sở hữu.                                                                                     | Đăng nhập trước khi tải file (đúng với ma trận). Guest vẫn dùng được công cụ ước tính giá bằng cách tự nhập số trang.                                                                                                                                                                                                           |
| 7      | Thiếu bảng chuyển trạng thái đầy đủ và xử lý trường hợp hai hành động đến cùng lúc, ví dụ khách bấm hủy đúng lúc nhân viên bấm “Đang in”.           | Mục 4.4 đã xử lý đồng thời cho khung giờ nhưng chưa cho việc hủy. Có thể một đơn vừa bị hủy vừa được in.                                                                                                  | Lập bảng: trạng thái hiện tại, hành động, ai làm, trạng thái mới. Quy tắc: chỉ một trong hai hành động thành công, hành động còn lại nhận thông báo rõ ràng.                                                                                                                                                                    |
| 8      | Chỉ có một kịch bản nghiệm thu chung (mục 6.3, 8 bước), từng chức năng chưa có tiêu chí chấp nhận riêng. Kịch bản cũng chưa gồm tình huống lỗi.     | Kịch bản “đường đi đẹp” không phát hiện lỗi file hỏng, hết hạn giữ chỗ, thanh toán thất bại, hủy đơn.                                                                                                     | Mỗi chức năng MUST-HAVE có ít nhất 2 tiêu chí dạng Cho trước, Khi, Thì. Ví dụ FN-01: cho trước PDF 60 trang thì hiển thị “60 trang”, cho trước PDF có mật khẩu thì báo lỗi và không tạo mục đơn.<br>Thêm kịch bản 9 đến 11: file lỗi, hết hạn giữ chỗ, hủy đơn trước khi in.                                                    |

# 3. Những điểm đồng ý với AI thứ nhất

Phản biện không có nghĩa là phủ nhận tất cả. Các điểm dưới đây được giữ nguyên:

- Giữ làm MUST-HAVE: tải PDF và đếm trang, cấu hình in, tính giá tự động, đặt lịch nhận hàng, thanh toán trực tuyến, theo dõi trạng thái. Các chức năng này bám đúng vấn đề kinh doanh và ba điểm khác biệt.

- Hỏa tốc, giao hàng tận nơi, phân tích độ phủ mực, tích điểm đúng là Phase 2 (phần mâu thuẫn trong luồng cần sửa theo 3.3).

- Tính lại giá ở máy chủ và chốt giá tại thời điểm xác nhận đơn (bước 8, mục 4.1). Đây là biện pháp chống sửa giá từ phía khách.

- Gợi ý tiết kiệm để khách chấp nhận hoặc bỏ qua, hệ thống không tự đổi cấu hình.

- Giữ chỗ khung giờ và xử lý đồng thời khi hai khách chọn cùng chỗ cuối.

- Cách phân loại MUST-HAVE, PHASE 2, HYPOTHESIS và nguyên tắc “chạy được trọn một đơn” trước (walking skeleton).

- Ví dụ tính giá ở mục 4.3 tính đúng số học (120.000 đ, 102.000 đ, tiết kiệm 18.000 đ, tức 15%).

# 4. Bảng tổng hợp: nhóm xử lý ý kiến khác nhau

Bảng dùng nội dung thực của đề tài PrintSlot. Cột cuối là quyết định đề xuất, nhóm họp, xác nhận hoặc sửa trước khi nộp.

| **Nội dung**                                 | **AI thứ nhất đề xuất**                                                         | **AI thứ hai phản biện**                                                                                            | **Quyết định của nhóm**                                                          |
|----------------------------------------------|---------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| Mục tiêu định lượng                          | Có: 20-30 phút xuống 0 phút, tăng 30-40% sản lượng, giảm 90% thời gian báo giá. | Số liệu chưa kiểm chứng, “0 phút” không đạt được, mâu thuẫn ví dụ 15%.                                              | Điều chỉnh: ghi là giả định, thay bằng chỉ tiêu đo được (1.1).                   |
| Giả thuyết cần kiểm chứng                    | Có: HYP-01 đến HYP-03.                                                          | Thiếu giả thuyết cốt lõi về nhu cầu đặt in online và về tiệm đối tác.                                               | Bổ sung HYP-04, HYP-05 (1.2).                                                    |
| Tải PDF và đếm trang (FN-01)                 | Có: MUST-HAVE.                                                                  | Đồng ý, cần kiểm tra loại file thật, giới hạn dung lượng, xử lý file lỗi.                                           | Giữ lại, bổ sung kiểm tra (5.4, 4.3).                                            |
| Cấu hình in và tính giá (FN-02, FN-03)       | Có: MUST-HAVE, có chữ “Real-time”.                                              | Đồng ý, quy tắc làm tròn, giá tối thiểu, trang màu lẫn chưa chốt.                                                   | Giữ lại, chốt quy tắc và lập 5 ca kiểm thử trước khi lập trình (6.2).            |
| Gợi ý cấu hình tiết kiệm (FN-04)             | Có: MUST-HAVE, “đen trắng cho trang chữ”, tiết kiệm 20-40%.                     | Nhận diện trang chữ thuộc Phase 2, con số không khớp ví dụ, không có trong danh sách 6.2.                           | Giữ lại ở dạng quy tắc theo cấu hình, bỏ con số 20-40%, thêm vào 6.2 (6.1, 4.9). |
| Đặt lịch khung giờ (FN-05)                   | Có: MUST-HAVE, sức chứa theo số đơn.                                            | Đồng ý, số đơn không phản ánh năng lực, thiếu tham số.                                                              | Giữ lại, thêm giới hạn tổng số mặt in và bảng tham số (6.3, 6.4).                |
| Thanh toán trực tuyến (FN-06)                | Có: MoMo, VNPay, ZaloPay, QR.                                                   | Vượt phạm vi, hai phần liệt kê khác nhau, thiếu xác thực kết quả từ cổng.                                           | Giữ một cổng sandbox và QR thủ công, các cổng khác Phase 2 (3.2, 5.5).           |
| Hỏa tốc và giao tận nơi (FN-09, FN-10)       | Phase 2 nhưng vẫn có trong luồng và trạng thái.                                 | Mâu thuẫn nội bộ.                                                                                                   | Phase 2 nhất quán, phiên bản đầu chỉ nhận tại quầy (3.3).                        |
| Combo và standee (FN-08)                     | Có: Combo, gồm PowerPoint kèm standee thuê/mua.                                 | Cho thuê vượt năng lực, HYP-03 chưa kiểm chứng.                                                                     | Combo báo cáo và khóa luận, standee xử lý bằng báo giá, cho thuê Phase 2 (3.1).  |
| Yêu cầu báo giá dịch vụ đặc thù              | Có trong luồng nhưng không có chức năng.                                        | Thiếu chức năng.                                                                                                    | Bổ sung biểu mẫu yêu cầu báo giá (4.1).                                          |
| Hủy đơn, hoàn tiền, file lỗi, thanh toán trễ | Chỉ mô tả ở mục 4.5.                                                            | Thiếu chức năng, trạng thái và quy tắc.                                                                             | Bổ sung, hoàn tiền thủ công ở phiên bản đầu (4.2, 4.3, 4.4).                     |
| Vai trò B2B, hóa đơn GTGT, chiết khấu        | Có: vai trò riêng.                                                              | Trùng quyền với khách cá nhân, hóa đơn vượt năng lực.                                                               | Phase 2, phiên bản đầu 4 vai trò (2.2).                                          |
| Tài khoản và thông báo                       | Có đăng ký, đăng nhập, thông báo “nếu có”.                                      | Thiếu quên mật khẩu, email xác nhận, mã nhận hàng, tạm ngưng nhận đơn.                                              | Bổ sung mức tối thiểu (4.5 đến 4.8).                                             |
| Bảo mật và quyền riêng tư                    | NDA trên web, xóa file sau 30 ngày, mã hóa lưu trữ.                             | NDA không phải biện pháp bảo mật, thiếu kiểm soát truy cập, kiểm tra file, bảo vệ tài khoản, hai mốc xóa khác nhau. | Điều chỉnh theo 5.1 đến 5.6 và 2.4.                                              |
| Yêu cầu phi chức năng                        | AWS/GCP auto-scaling, Redis, 99,5%, TLS 1.3, “không quá 3 bước”.                | Vượt năng lực, thiếu điều kiện đo, lẫn giải pháp với yêu cầu.                                                       | Viết lại có điều kiện đo, công nghệ chuyển sang thiết kế (3.4, 6.5).             |
| Tính nhất quán của tài liệu                  | Mục 3 và mục 6 lệch nhau, mục 6 ghi nhóm chưa cung cấp thời gian và quy mô.     | Mâu thuẫn làm sai căn cứ lập kế hoạch và nghiệm thu.                                                                | Sửa theo dữ kiện thật: 7 người, 2-3 tháng (4.9, 6.6).                            |
