# Scientific Paper Reader & Analysis App 📄🔬

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Web-4CAF50?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Ứng dụng di động đọc, phân tích và trích xuất tài liệu nghiên cứu khoa học thông minh xây dựng trên Flutter**

</div>

---

## 📖 1. Giới thiệu Tổng quan (Overview)

**Scientific Paper Reader** là ứng dụng di động được thiết kế chuyên biệt dành cho sinh viên, giảng viên và các nhà nghiên cứu khoa học. Ứng dụng giải quyết khó khăn trong việc tiếp cận các tài liệu học thuật định dạng PDF dung lượng lớn trên thiết bị di động, mang lại trải nghiệm đọc mượt mà kết hợp các công cụ tóm tắt, trích xuất nội dung và phân tích học thuật trực quan.

---

## 🚀 2. Các Tính năng Nổi bật (Key Features)

- 📄 **Trình đọc PDF Học thuật Mượt mà (`Syncfusion PDF Viewer`):** Hỗ trợ hiển thị tài liệu nghiên cứu phức tạp, hỗ trợ phóng to/thu nhỏ, nhảy trang và tối ưu hóa bộ nhớ cho các tài liệu hàng trăm trang.
- 📑 **Trích xuất & Định dạng Markdown:** Tự động hiển thị tóm tắt bài báo, abstract, phương pháp nghiên cứu và kết quả dưới dạng Markdown thân thiện, dễ đọc (`flutter_markdown`).
- 📁 **Quản lý Tệp tin Linh hoạt (`File Picker`):** Cho phép người dùng tải lên các tệp tài liệu PDF từ bộ nhớ thiết bị hoặc tải trực tiếp qua đường dẫn HTTP/URL.
- 🎨 **Giao diện Khoa học & Hiện đại:** Thiết kế với bảng màu học thuật tinh tế (*Academic Ink & Sky Palette*), tạo cảm giác tập trung và thoải mái cho mắt khi đọc tài liệu dài hạn.
- ⚡ **Quản lý Trạng thái Hiệu quả (`Provider`):** Kiến trúc phân tách logic xử lý tệp và giao diện, đảm bảo ứng dụng luôn phản hồi nhanh và mượt mà.

---

## 🛠 3. Kiến trúc & Công nghệ (Tech Stack)

| Thành phần | Công nghệ / Thư viện | Mục đích sử dụng |
| :--- | :--- | :--- |
| **Framework** | **Flutter SDK (>=3.0.0)** | Phát triển ứng dụng đa nền tảng (Android, iOS, Web) |
| **Ngôn ngữ** | **Dart** | Ngôn ngữ lập trình cốt lõi |
| **State Management**| **Provider** | Quản lý trạng thái và luồng dữ liệu ứng dụng |
| **PDF Rendering** | **syncfusion_flutter_pdfviewer** | Trình hiển thị PDF hiệu năng cao |
| **Markdown View** | **flutter_markdown** | Trình bày nội dung trích xuất dạng rich text |
| **File Handling** | **file_picker** | Chọn và duyệt tệp từ bộ nhớ máy |
| **Networking** | **http** | Giao tiếp API và tải tài liệu trực tuyến |

---

## 📂 4. Cấu trúc Dự án (Project Structure)

```
scientific-paper-reader/
└── project_1_prm/
    ├── lib/
    │   └── main.dart            # Toàn bộ logic giao diện, bảng màu, PDF viewer & Markdown reader
    ├── pubspec.yaml             # Khai báo thư viện và cấu hình dự án Flutter
    ├── analysis_options.yaml    # Bộ quy tắc linter chuẩn Dart
    └── test/                    # Các kịch bản kiểm thử widget
```

---

## 💻 5. Hướng dẫn Cài đặt & Chạy ứng dụng (Getting Started)

### Yêu cầu môi trường:
- Flutter SDK (Phiên bản `>= 3.0.0`)
- Android Studio / VS Code có cài đặt Flutter & Dart extension
- Thiết bị giả lập (Android Emulator / iOS Simulator) hoặc thiết bị thật kết nối qua USB

### Các bước khởi chạy:

1. **Clone repository (nếu chưa có):**
   ```bash
   git clone https://github.com/tkiennt/scientific-paper-reader.git
   cd scientific-paper-reader/project_1_prm
   ```

2. **Cài đặt các gói phụ thuộc:**
   ```bash
   flutter pub get
   ```

3. **Chạy ứng dụng:**
   ```bash
   flutter run
   ```

---

## 👥 6. Tác giả & Đóng góp (Credits)

- **Dự án:** Ứng dụng đọc và phân tích tài liệu học thuật (PRM393).
- **Thành viên đóng góp:** Trung Kiên ([@tkiennt](https://github.com/tkiennt)) — Xây dựng giao diện, luồng duyệt tệp và tích hợp công cụ phân tích tài liệu.