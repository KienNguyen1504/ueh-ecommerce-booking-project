# Project Plan

## 1. Thành viên và vai trò

**Bảng phân chia công việc và vai trò**

| Thành viên | Vai trò | Trách nhiệm chính |
|---|---|---|
| Kiên | Trưởng nhóm / BA | Quản lý tiến độ, yêu cầu, GitHub Issues, điều phối nhóm, triển khai |
| Nhi | UI/UX | Thiết kế giao diện, bộ thành phần giao diện dùng chung, tài nguyên hình ảnh |
| Tuệ | Front-end | Giao diện phía khách hàng: dịch vụ, tìm kiếm, cấu hình in, tính giá; giao diện quản lý dịch vụ |
| Phương | Front-end | Giao diện đặt hàng: giỏ hàng, đặt lịch, thanh toán, theo dõi đơn; giao diện nhân viên và thống kê |
| Hoa | Back-end | Cơ sở dữ liệu, xác thực và phân quyền, API dịch vụ, tải tệp, tính giá |
| Thắng | Back-end | API đơn hàng, đặt lịch và sức chứa, thanh toán thử nghiệm, trạng thái đơn, voucher |
| Hưng | QA / Integration | Kế hoạch và kịch bản kiểm thử, kiểm tra tích hợp, quản lý lỗi, tài liệu hướng dẫn chạy |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

Đây là vai trò chính, không phải giới hạn công việc. Các thành viên hỗ trợ nhau khi tích hợp và kiểm thử. Mỗi công việc có một người chịu trách nhiệm chính; cuối học phần, từng thành viên phải giải thích được phần việc mình phụ trách.

## 2. Các giai đoạn

Thời gian thực hiện: 8 tuần. Các giai đoạn 3 và 4 chạy song song; tích hợp được thực hiện liên tục từ Tuần 5.

**Bảng đề xuất giai đoạn thực hiện dự án**

| Giai đoạn | Thời gian | Nội dung chính |
|---|---|---|
| 1. Khảo sát và xác định yêu cầu | Tuần 1 | Hoàn thiện tài liệu khởi tạo, chốt phạm vi MVP và công nghệ |
| 2. Thiết kế giao diện và dữ liệu | Tuần 2 | Wireframe, mockup, thiết kế CSDL (ERD) |
| 3. Xây dựng frontend | Tuần 3 – 4 | Giao diện các trang, xử lý tương tác bằng dữ liệu mẫu |
| 4. Phát triển backend và cơ sở dữ liệu | Tuần 4 – 6 | CSDL, API, nghiệp vụ tính giá, đặt lịch, thanh toán sandbox |
| 5. Tích hợp và kiểm thử | Tuần 6 – 7 | Nối frontend với backend, kiểm thử, sửa lỗi |
| 6. Triển khai và hoàn thiện | Tuần 8 | Triển khai, báo cáo, demo |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

### Giai đoạn 1: Khảo sát và xác định yêu cầu (Tuần 1)
- **Công việc:**
  - Bổ sung phần thiếu của Buổi 1: `docs/business-workflow.md`, URL trong `docs/competitor-analysis.md`, prompt và người kiểm tra trong `AI_USAGE_LOG.md`.
  - Họp nhóm chốt phạm vi MVP, chia F01–F23 thành 3 lớp: lõi / nên có / mở rộng.
  - Chốt công nghệ (frontend, backend, CSDL, nơi triển khai) và ghi vào README.
  - Tạo bộ GitHub Issues cho Giai đoạn 2–3, gán người phụ trách.
- **Sản phẩm:** REQUIREMENTS.md đã được nhóm xác nhận; README đủ mục công nghệ và chức năng; PROJECT_PLAN cập nhật.
- **Tiêu chí hoàn thành:** mỗi yêu cầu lõi có mã, người dùng, tiêu chí nghiệm thu; công nghệ được cả nhóm đồng ý.

### Giai đoạn 2: Thiết kế giao diện và dữ liệu (Tuần 2)
- **Công việc:**
  - Thiết kế wireframe cho các trang chính: trang chủ, danh mục/tìm kiếm, chi tiết dịch vụ và cấu hình in, giỏ hàng, đặt lịch, thanh toán, theo dõi đơn, trang nhân viên, trang quản trị.
  - Chọn bảng màu, font, bộ thành phần giao diện dùng chung (nút, form, thẻ dịch vụ, bảng).
  - Thiết kế mockup có bản desktop và mobile (Figma hoặc công cụ tương đương).
  - Thiết kế ERD: người dùng, dịch vụ, bảng giá, đơn hàng, chi tiết đơn, tệp tải lên, khung giờ/sức chứa, voucher, thanh toán.
  - Viết quy tắc tính giá và quy tắc kiểm tra sức chứa khung giờ, kèm ít nhất 5 ca kiểm thử mẫu.
- **Sản phẩm:** file thiết kế, ảnh ERD, tài liệu quy tắc nghiệp vụ trong `docs/`.
- **Tiêu chí hoàn thành:** mỗi chức năng lõi có màn hình tương ứng; ERD được cả nhóm review; Frontend và Backend cùng đọc hiểu một bộ thiết kế.

### Giai đoạn 3: Xây dựng frontend (Tuần 3 – 4)
- **Công việc:**
  - Dựng khung trang, thanh điều hướng, giao diện responsive (NFR01).
  - Làm các trang theo thứ tự: danh sách và chi tiết dịch vụ (F01–F03) → đăng ký/đăng nhập (F04) → tải PDF và cấu hình in (F05–F06) → tính giá hiển thị (F07) → giỏ hàng (F09) → chọn khung giờ (F11) → thanh toán và theo dõi đơn (F14–F15) → giao diện nhân viên và quản trị (F19–F20).
  - Xử lý tương tác phía trình duyệt: kiểm tra dữ liệu nhập, báo lỗi, cập nhật giá khi đổi tùy chọn.
  - Dùng dữ liệu mẫu (JSON) để chạy độc lập, chưa cần backend.
- **Sản phẩm:** mã nguồn frontend trên nhánh riêng, chạy được với dữ liệu mẫu.
- **Tiêu chí hoàn thành:** duyệt được toàn bộ luồng đặt in trên giao diện với dữ liệu mẫu; hiển thị tốt trên máy tính và điện thoại.

### Giai đoạn 4: Phát triển backend và cơ sở dữ liệu (Tuần 4 – 6)
- **Công việc:**
  - Tuần 4: dựng CSDL theo ERD, nhập dữ liệu mẫu (dịch vụ, bảng giá, khung giờ); làm xác thực và phân quyền 4 vai trò (F04, F23).
  - Tuần 5: API dịch vụ, tìm kiếm/lọc, tải tệp PDF có kiểm tra định dạng và dung lượng, API tính giá, giỏ hàng, tạo đơn (F01–F09).
  - Tuần 6: đặt lịch và kiểm tra sức chứa (F11), thanh toán sandbox (F14), trạng thái đơn và xử lý của nhân viên (F15, F20), quản trị dịch vụ/bảng giá/cấu hình lịch (F19, F21).
  - Chức năng "nên có" (F08, F10, F13, F16, F18, F22) làm sau khi lõi chạy ổn.
- **Sản phẩm:** CSDL, bộ API có tài liệu ngắn (danh sách endpoint), dữ liệu mẫu.
- **Tiêu chí hoàn thành:** mỗi API lõi chạy đúng với dữ liệu hợp lệ và từ chối dữ liệu không hợp lệ; phân quyền chặn đúng người dùng không có quyền; không có mật khẩu/API key trong mã nguồn (NFR11).

### Giai đoạn 5: Tích hợp và kiểm thử (Tuần 6 – 7)
- **Công việc:**
  - Tuần 6: bắt đầu nối frontend với API theo từng chức năng ngay khi API xong, không đợi hết Giai đoạn 4.
  - Lập kịch bản kiểm thử từ tiêu chí nghiệm thu của F01–F23 và NFR; ưu tiên các luồng chính: đăng nhập, tải tệp, tính giá, đặt hàng, kiểm tra khung giờ, thanh toán sandbox, phân quyền (NFR12).
  - Tuần 7: kiểm thử toàn luồng, ghi lỗi thành Issue, sửa và kiểm thử lại; thử trên ít nhất 2 trình duyệt và 2 kích thước màn hình (NFR01, NFR13).
  - Soát bảo mật cơ bản: quyền truy cập tệp, kiểm tra dữ liệu đầu vào, repo không lộ thông tin bí mật.
- **Sản phẩm:** bảng kết quả kiểm thử, danh sách lỗi đã xử lý và còn tồn tại.
- **Tiêu chí hoàn thành:** luồng "đặt một đơn in từ đầu đến cuối" chạy không lỗi chặn; các lỗi mức cao đã sửa.

### Giai đoạn 6: Triển khai và hoàn thiện (Tuần 8)
- **Công việc:**
  - Triển khai bản demo lên môi trường trực tuyến, hoặc chuẩn bị hướng dẫn chạy cục bộ nếu không triển khai được.
  - Chuẩn bị dữ liệu mẫu sạch cho buổi demo, không dùng dữ liệu cá nhân thật.
  - Hoàn thiện README (cách cài đặt, chạy, tài khoản thử nghiệm), cập nhật REQUIREMENTS với phần chức năng đã làm / chưa làm, và AI_USAGE_LOG đầy đủ.
  - Viết báo cáo và tập thuyết trình; mỗi thành viên luyện giải thích phần việc mình phụ trách.
- **Sản phẩm:** ứng dụng demo, tài liệu hướng dẫn, báo cáo, slide.
- **Tiêu chí hoàn thành:** người ngoài nhóm chạy được hoặc truy cập được bản demo theo hướng dẫn; repo Public, không lộ thông tin bí mật.

## 3. Công việc (Buổi 1)

**Bảng phân chia công việc Buổi 1**

| Mã | Người phụ trách | Kết quả cần đạt | Thời hạn | Trạng thái |
|---|---|---|---|---|
| NV1 | Hoa (cả nhóm góp ý) | Xác định vấn đề kinh doanh | 17/10/2026 | Hoàn thành |
| NV8 | Kiên | Repo Public + Issues | 17/10/2026 | Hoàn thành |
| NV2 | Phương, Nhi | docs/competitor-analysis.md | 18/10/2026 | Hoàn thành |
| NV3+NV4 | Thắng | AI_USAGE_LOG.md + bảng quyết định | 18/10/2026 | Hoàn thành |
| NV5 | Tuệ | REQUIREMENTS.md, docs/user-roles.md | 19/10/2026 20:00 | Hoàn thành |
| NV6 | Hưng | docs/business-workflow.md | 19/10/2026 20:00 | Hoàn thành |
| NV7 | Hoa | README.md, PROJECT_PLAN.md (phân công) | 19/10/2026 20:00 | Hoàn thành |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_

## 4. Rủi ro

**Bảng rủi ro đề xuất** 

| Rủi ro | Phương án xử lý |
|---|---|
| Trễ chốt đề tài làm chậm các việc phụ thuộc | Bỏ phiếu ngay trong cuộc họp, không kéo dài |
| Xung đột khi nhiều người sửa cùng file | Mỗi file có một người chịu trách nhiệm chính, git pull trước khi sửa |
| Lộ API key, dữ liệu cá nhân trong repo Public | Dùng .gitignore, kiểm tra trước khi push |

_**Nguồn: Nhóm tác giả đề xuất (2026)**_
