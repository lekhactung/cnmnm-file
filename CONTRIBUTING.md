# Hướng dẫn đóng góp

Repo tập hợp tài liệu thực hành do giảng viên cung cấp. Các đóng góp tập trung vào việc sắp xếp tài liệu, cải thiện hướng dẫn và sửa liên kết. Giữ nguyên tài liệu gốc của giảng viên; nếu phát hiện lỗi trong bài thực hành, hãy tạo issue để trao đổi và ghi chú riêng.

## Báo lỗi hoặc đề xuất

Tạo một issue và chọn mẫu phù hợp. Nêu rõ bài thực hành, đường dẫn tập tin liên quan và nội dung cần sửa hoặc bổ sung. Với lỗi khi chạy lệnh, cung cấp hệ điều hành, câu lệnh, kết quả thực tế và kết quả mong đợi.

## Gửi thay đổi

1. Tạo nhánh riêng từ nhánh mặc định của repo, ví dụ `docs/lab02-guide` hoặc `fix/lab02-links`. Nếu không có quyền ghi, hãy fork repo và tạo nhánh trên bản fork.
2. Thực hiện thay đổi theo quy ước bên dưới.
3. Kiểm tra nội dung, đường dẫn và các lệnh thực hành có liên quan.
4. Commit với thông điệp mô tả rõ thay đổi, ví dụ `docs: bổ sung hướng dẫn Lab02`.
5. Mở pull request về nhánh mặc định, mô tả thay đổi và cách đã kiểm tra. Liên kết issue nếu có.

## Quy ước nội dung

- Mỗi buổi thực hành nằm trong thư mục `LabXX/` và có `README.md` giới thiệu nội dung, liên kết tài liệu cùng hướng dẫn cần thiết.
- Khi thêm lab mới, cập nhật mục lục trong [README chính](./README.md).
- Dùng tiếng Việt rõ ràng và liên kết tương đối giữa các tập tin trong repo.
- Với tập tin mới, ưu tiên tên ngắn gọn, không dấu, dùng dấu gạch ngang thay khoảng trắng.
- Mã nguồn, báo cáo và ảnh kết quả được lưu trong thư mục lab tương ứng; hình ảnh dùng chung đặt trong `assets/`.
- Lệnh thực hành cần ghi rõ môi trường và quyền cần thiết; nêu tác động trước các lệnh xóa dữ liệu hoặc thay đổi cấu hình hệ thống.
- Không đưa mật khẩu, token, khóa riêng, dữ liệu cá nhân hoặc tập tin sinh tự động không cần thiết vào repo.
- Chỉ đóng góp nội dung có quyền chia sẻ. Ghi nguồn và giữ thông báo bản quyền của tài liệu bên thứ ba theo [thông tin giấy phép](./LICENSING.md).

## Kiểm tra trước khi gửi

- Nội dung hiển thị đúng trên GitHub và các liên kết mở được.
- Tài liệu hoặc hình ảnh bổ sung đọc được, không chứa thông tin nhạy cảm.
- Nếu có mã nguồn hoặc câu lệnh: đã kiểm tra trong môi trường phù hợp, hoặc ghi rõ phần chưa kiểm tra và lý do trong pull request.
- Thay đổi chỉ bao gồm các tập tin liên quan đến mục đích đóng góp.

## Trao đổi trong nhóm

Góp ý lịch sự, tập trung vào nội dung và giải thích lý do khi đề nghị thay đổi. Khi chưa thống nhất, trao đổi trong issue hoặc pull request để các thành viên cùng theo dõi.

[← Trang chủ](./README.md)
