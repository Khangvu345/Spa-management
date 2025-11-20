## Cấu trúc thư mục
```
docs/
├── architecture/
│   ├── system-overview.md
│   ├── technologies.md
│   └── diagrams/
├── requirements/
│   ├── functional-requirements.md
│   ├── business-rules.md
│   └── user-stories.md
├── design/
│   ├── ui-mockups/
│   └── style-guide.md
├── database/
│   ├── data-dictionary.md
│   └── erd-explanation.md
├── api/
│   ├── api-contract.md
│   └── postman/
└── guides/
    ├── setup-guide.md
    ├── deployment-guide.md
    └── troubleshooting.md
```

## Dự định

**Requirements** - Nơi chứa đề bài của dự án bao gồm:
* `functional-requirements.md`: Liệt kê các chức năng
* `business-rules.md`: Các quy tắc nghiệp vụ khó nhớ
* `user-stories.md`: Liệt kê các flow người dùng

**Architecture** - Giải thích lý do hệ thống được xây dựng:
* `system-overview.md`: Biểu đồ tổng quan hệ thống (Frontend <-> Backend <-> Database <-> 3rd Party)
* `technologies.md`: (Tech stack) Lý do chọn Java 21, React, MySQL
* `diagrams/`: Chứa các file ảnh sơ đồ (Sequence Diagram, Class Diagram)

**Database** - Tài liệu giải thích về CSDL:
* `data-dictionary.md`: Giải thích ý nghĩa các bảng và cột quan trọng
* `erd-explanation.md`: Giải thích mối quan hệ giữa các bảng

**Design** - Giao diện:
* `ui-mockups/`: Chứa ảnh chụp màn hình thiết kế hoặc file PDF export từ Figma
* `style-guide.md`: Quy định về màu sắc (Color Palette), Font chữ, khoảng cách (Spacing) mà Frontend đang tuân thủ

**Api** - Tài liệu API:
* `api-contract.md`: Quy định chung về format trả về, quy định về mã lỗi
* `postman/`: Chứa file export JSON của Postman Collection để FE import vào

**Guides** - Hướng dẫn:
* Nếu chưa có Docker: Hướng dẫn chạy chi tiết FE và BE cũng như kết nối DB
* Nếu có Docker: Câu lệnh để chạy ứng dụng
* Hướng dẫn deploy server
* Các quy tắc coding convention 
* Git Workflow để làm việc nhóm