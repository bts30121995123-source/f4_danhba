# LAB F4 – ĐIỀU HƯỚNG ĐA MÀN HÌNH FLUTTER

**Sinh viên:** Trịnh Phạm Xuân Nghi  
**MSSV:** 231A010740  
**Môn học:** Lập trình trên các thiết bị di động  
**Công nghệ:** Flutter – Dart  
**Dự án:** Ứng dụng Danh bạ Mini

---

## 1. Giới thiệu

Lab F4 xây dựng ứng dụng Danh bạ Mini bằng Flutter. Ứng dụng giúp người dùng quản lý thông tin liên hệ và thực hành kỹ thuật điều hướng giữa nhiều màn hình, truyền dữ liệu và nhận kết quả trả về bằng Navigator.

## 2. Chức năng chính

- Hiển thị danh sách liên hệ.
- Xem thông tin chi tiết của từng liên hệ.
- Thêm liên hệ mới.
- Chỉnh sửa thông tin liên hệ.
- Xóa liên hệ.
- Truyền dữ liệu giữa các màn hình.
- Nhận kết quả trả về sau khi thêm hoặc chỉnh sửa.
- Xác nhận khi thoát màn hình nếu có thay đổi chưa lưu.

## 3. Bài nâng cao

### NC1 – Thêm màn hình tìm kiếm

- Bổ sung màn hình tìm kiếm liên hệ.
- Tìm kiếm theo họ tên, số điện thoại và email.
- Hiển thị danh sách kết quả phù hợp với từ khóa.
- Thông báo khi không tìm thấy liên hệ.
- Sử dụng `Navigator.push<Contact>()` để mở màn hình tìm kiếm và `Navigator.pop(context, contact)` để trả liên hệ được chọn về màn hình trước.
- Khi chọn liên hệ, ứng dụng mở màn hình chi tiết tương ứng.

### NC2 – Sử dụng Hero tạo hiệu ứng ảnh đại diện

- Bổ sung avatar cho từng liên hệ.
- Sử dụng widget `Hero` ở màn hình danh sách và màn hình chi tiết.
- Sử dụng số điện thoại làm giá trị `tag` để xác định avatar tương ứng.
- Tạo hiệu ứng chuyển động phóng to ảnh đại diện khi chuyển giữa hai màn hình.

## 4. Công nghệ sử dụng

- Flutter Framework.
- Ngôn ngữ lập trình Dart.
- Material Design.
- Navigator và MaterialPageRoute.
- Hero Animation.
- Android Studio.
- Android Emulator.

## 5. Cấu trúc dự án

```text
f4_danhba/
├── android/
├── ios/
├── lib/
│   └── main.dart
├── test/
├── web/
├── windows/
├── pubspec.yaml
└── README.md
```

## 6. Hướng dẫn chạy chương trình

**Bước 1:** Mở project bằng Android Studio hoặc VS Code.

**Bước 2:** Mở Terminal và chạy lệnh:

```bash
flutter pub get
```

**Bước 3:** Khởi động máy ảo Android.

**Bước 4:** Chạy ứng dụng:

```bash
flutter run
```

## 7. Kết quả thực hiện

Ứng dụng hoàn thành các chức năng quản lý danh bạ cơ bản và hai bài nâng cao NC1, NC2. Người dùng có thể tìm kiếm, lựa chọn liên hệ, xem chi tiết và quan sát hiệu ứng chuyển động avatar khi chuyển màn hình.

## 8. Kết luận

Thông qua Lab F4, sinh viên đã thực hành điều hướng đa màn hình trong Flutter, truyền dữ liệu giữa các màn hình và nhận kết quả trả về bằng Navigator. Bên cạnh đó, việc thực hiện hai bài nâng cao giúp hiểu thêm về chức năng tìm kiếm và hiệu ứng chuyển động Hero, góp phần hoàn thiện ứng dụng Danh bạ Mini.
