# Software Requirements Specification (SRS)

- **Sản phẩm:** CoffeeHub
- **Phiên bản tài liệu:** 0.1
- **Trạng thái:** Draft – chưa được xác nhận
- **Chuẩn tham khảo:** Cấu trúc SRS theo thông lệ kỹ nghệ phần mềm; nội dung phải được xác nhận với stakeholder.

## 1. Giới thiệu

### 1.1 Mục đích
Xác định yêu cầu chức năng và phi chức năng để làm cơ sở thiết kế, phát triển, kiểm thử và nghiệm thu CoffeeHub.

### 1.2 Phạm vi sản phẩm
Chưa thể xác định từ repository hiện tại. Bổ sung mô tả vấn đề, mục tiêu, ranh giới hệ thống và các phần không thuộc phạm vi sau khi có yêu cầu nghiệp vụ.

### 1.3 Thuật ngữ
- **Actor:** người dùng hoặc hệ thống bên ngoài tương tác với hệ thống.
- **Use case:** mục tiêu có thể quan sát được mà actor đạt được khi tương tác với hệ thống.
- **FR:** Functional Requirement – yêu cầu chức năng.
- **NFR:** Non-functional Requirement – yêu cầu phi chức năng.

### 1.4 Tài liệu tham chiếu
- Repository: https://github.com/Tson-dev/CoffeeHub
- [Tổng quan](../OVERVIEW.md)

## 2. Mô tả tổng thể

### 2.1 Bối cảnh sản phẩm
Chưa xác nhận. Cần mô tả hệ thống độc lập hay một phần của hệ thống lớn, cùng các hệ thống tích hợp.

### 2.2 Nhóm người dùng
Chưa xác nhận. Với mỗi nhóm, ghi vai trò, mục tiêu, quyền hạn và mức độ quen thuộc với công nghệ.

### 2.3 Môi trường vận hành
Chưa xác nhận. Ghi hệ điều hành, trình duyệt/thiết bị, runtime, database và môi trường triển khai sau khi kiểm tra source/config.

### 2.4 Ràng buộc
Chưa xác nhận. Ví dụ cần xem xét: công nghệ bắt buộc, ngân sách, quy định dữ liệu, thời hạn và hạ tầng.

### 2.5 Giả định và phụ thuộc
Chưa xác nhận. Không xem giả định là yêu cầu đã được duyệt.

## 3. Yêu cầu chức năng

Các mã dưới đây là mẫu để điền, không phải chức năng đã xác nhận.

| ID | Tên yêu cầu | Mô tả | Ưu tiên | Tiêu chí nghiệm thu | Trạng thái |
|---|---|---|---|---|---|
| FR-001 | [Tên chức năng] | [Actor, điều kiện, hành vi và kết quả] | TBD | [Kết quả kiểm thử đo được] | Chưa xác nhận |
| FR-002 | [Tên chức năng] | [Luồng chính và ngoại lệ] | TBD | [Kết quả kiểm thử đo được] | Chưa xác nhận |

Mỗi yêu cầu nên:
- Có mã duy nhất, một ý nghĩa rõ ràng và có thể kiểm thử.
- Nêu điều kiện trước, luồng chính, luồng thay thế/lỗi và điều kiện sau khi cần.
- Liên kết với use case và test case tương ứng.

## 4. Yêu cầu giao tiếp bên ngoài
Chưa xác nhận. Ghi giao diện người dùng, API, định dạng dữ liệu, giao thức, dịch vụ bên thứ ba và xử lý lỗi thực tế.

## 5. Yêu cầu phi chức năng

| ID | Nhóm | Yêu cầu/tiêu chí đo lường | Trạng thái |
|---|---|---|---|
| NFR-001 | Bảo mật | Xác định xác thực, phân quyền, bảo vệ dữ liệu và quản lý secret | Cần thống nhất |
| NFR-002 | Hiệu năng | Đặt ngưỡng thời gian phản hồi và tải mục tiêu có thể đo | Cần thống nhất |
| NFR-003 | Khả dụng | Xác định mục tiêu uptime, phục hồi và xử lý sự cố | Cần thống nhất |
| NFR-004 | Dễ bảo trì | Quy định lint, test, review và tiêu chuẩn code | Cần thống nhất |
| NFR-005 | Tương thích | Liệt kê trình duyệt/thiết bị/runtime được hỗ trợ | Cần thống nhất |

## 6. Dữ liệu
Xác định entity, thuộc tính, khóa, quan hệ, ràng buộc, lưu trữ, thời hạn lưu giữ, sao lưu và xóa dữ liệu. Xem [Database Design](../data/DATABASE.md).

## 7. Quy tắc nghiệp vụ
Chưa xác nhận. Mỗi quy tắc cần mã, mô tả, ví dụ hợp lệ/không hợp lệ và yêu cầu liên quan.

## 8. Tiêu chí nghiệm thu tổng thể
Chỉ nghiệm thu khi yêu cầu đã duyệt có test case, các luồng chính/ngoại lệ đạt kết quả mong đợi, lỗi nghiêm trọng được xử lý và tài liệu được cập nhật.

## 9. Truy vết yêu cầu
Duy trì bảng `Requirement ID → Use Case → API/Component → Test Case → Status` khi nội dung được xác nhận.

## 10. Lịch sử thay đổi

| Phiên bản | Ngày | Thay đổi |
|---|---|---|
| 0.1 | 2026-10-18 | Tạo khung SRS; chưa xác nhận nghiệp vụ |
