# UML Sequence Diagram

- **Trạng thái:** Template – luồng nghiệp vụ thực tế chưa xác nhận.

```mermaid
sequenceDiagram
    actor User as Actor (placeholder)
    participant UI as Client/UI (nếu có)
    participant App as Application (nếu có)
    participant DB as Data Store (nếu có)

    User->>UI: Bắt đầu [use case]
    UI->>App: Gửi yêu cầu
    App->>DB: Đọc/ghi dữ liệu
    DB-->>App: Kết quả
    App-->>UI: Kết quả xử lý
    UI-->>User: Hiển thị kết quả
```

## Quy tắc
Thay participant và thông điệp bằng thành phần thực tế. Thể hiện rõ nhánh thành công, xác thực/phân quyền, lỗi validation, lỗi phụ thuộc và phản hồi trả về.
