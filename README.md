# CoffeeHub

> Tài liệu dự án CoffeeHub. Nội dung mô tả chức năng và công nghệ cần được xác nhận dựa trên source code thực tế.

## Tổng quan
CoffeeHub là tên repository hiện tại. Mục đích, nhóm người dùng, chức năng chính và công nghệ sử dụng chưa được mô tả đầy đủ trong repository tại thời điểm soạn tài liệu.

## Bắt đầu
Hiện chưa thể cung cấp lệnh cài đặt/chạy chính xác vì repository chưa có mã nguồn ứng dụng hoặc hướng dẫn triển khai. Khi bổ sung source code, cập nhật phần này với:
1. Yêu cầu môi trường và phiên bản công cụ.
2. Cách cấu hình biến môi trường (không commit secret).
3. Cách cài dependency và chạy ứng dụng.
4. Cách chạy kiểm thử.

## Tài liệu
- [Tổng quan dự án](docs/OVERVIEW.md)
- [SRS – Đặc tả yêu cầu phần mềm](docs/requirements/SRS.md)
- [Use Case](docs/uml/USECASE.md)
- [UML – Class Diagram](docs/uml/CLASS_DIAGRAM.md)
- [UML – Sequence Diagram](docs/uml/SEQUENCE_DIAGRAM.md)
- [Data Flow](docs/architecture/DATAFLOW.md)
- [Kiến trúc hệ thống](docs/architecture/ARCHITECTURE.md)
- [Thiết kế dữ liệu](docs/data/DATABASE.md)
- [API Specification](docs/api/API_SPEC.md)
- [Quyết định kiến trúc (ADR)](docs/decisions/README.md)
- [Hướng dẫn đóng góp](CONTRIBUTING.md)

## Trạng thái tài liệu
**Bản khung ban đầu – cần xác minh.** Các actor, use case, entity, luồng dữ liệu và API trong tài liệu chưa được xác nhận từ mã nguồn. Không dùng các sơ đồ minh họa như mô tả hệ thống đã triển khai cho đến khi rà soát source code và thống nhất yêu cầu.

## Cập nhật tài liệu
Khi thay đổi chức năng, cập nhật SRS, use case, sơ đồ liên quan và API/database docs trong cùng pull request.
