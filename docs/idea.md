## Cấu trúc thư mục
├── docs/             
│   ├── architecture/ # Kiến trúc hệ thống, biểu đồ tổng quan
│   ├── requirements/ # Nghiệp vụ, User Stories, Use Cases
│   ├── design/       # UI/UX,..
│   ├── database/     # Từ điển dữ liệu, giải thích ERD (không chứa code SQL)
│   ├── api/          # Tài liệu đặc tả API Postman...
│   └── guides/       # Hướng dẫn deploy, setup môi trường, troubleshooting
└── ...
## Dự định
**Requirements** Là nơi chứa đề bài của dự án bao gồm: 
* functional-requirements.md: Liệt kê các chức năng 

* business-rules.md: Các quy tắc nghiệp vụ khó nhớ 

* user-stories.md: Liệt kê các flow người dùng 

**Architecture** Giải thích lí do hệ thống được xây dựng:
* system-overview.md: Biểu đồ tổng quan hệ thống (Frontend <-> Backend <-> Database <-> 3rd Party).

* technologies.md: (Tech stack) Lý do chọn Java 21, React, MySQL 

* diagrams/: Chứa các file ảnh sơ đồ (Sequence Diagram, Class Diagram).

**Database** tài liệu giải thích về CSDL
* data-dictionary.md: Giải thích ý nghĩa các bảng và cột quan trọng 

* erd-explanation.md: Giải thích mối quan hệ giữa các bảng 

**Design** Giao diện
* ui-mockups/: Chứa ảnh chụp màn hình thiết kế hoặc file PDF export từ Figma.

* style-guide.md: Quy định về màu sắc (Color Palette), Font chữ, khoảng cách (Spacing) mà Frontend đang tuân thủ 

**Api** Tài liệu API
* api-contract.md: Quy định chung về format trả về, quy định về mã lỗi.

* postman/: Chứa file export JSON của Postman Collection để FE import vào.

**Guides** Hướng dẫn READ.me
* Nếu chưa có docker hướng dẫn chạy chi tiết FE và BE cũng như kết nối DB
* Nếu có docker: Câu lệnh để chạy ứng dụng
* Hướng dẫn deploy sever