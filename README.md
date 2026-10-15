# XZalo · MemChoXD

**Một diện mạo riêng cho mỗi lần mở app.**

[Tải bản mới nhất · fix10](https://github.com/memchoxd/xzalo-releases/releases/latest) · [Chi tiết fix10](https://github.com/memchoxd/xzalo-releases/releases/tag/v2026.10.15-fix10) · [Lịch sử phiên bản](https://github.com/memchoxd/xzalo-releases/releases)

> **fix10 · Bật sẵn Google Drive qua GmsCore — Latest**  
> GmsCore và tuỳ chọn sao lưu ảnh Drive được bật sẵn khi cài mới hoặc nâng cấp từ bản cũ. Nếu chủ động tắt sau đó, app giữ lựa chọn. Nhận bản này qua **Cài đặt XZalo → Kiểm tra cập nhật** hoặc mở lại app; cập nhật tuỳ chọn cho fix08/fix09. Đã qua 29 kiểm tra Android, 18 unit test và kết nối Drive chỉ đọc trên Samsung Android 15. Chưa xác minh khôi phục toàn bộ ảnh từ bản sao lưu Zalo gốc.

Kho này chứa APK đã phát hành và thông tin cập nhật của XZalo. Mã nguồn được quản lý trong repo riêng tư.

## Cài đặt

1. Mở trang **Releases**, tải file **XZalo-MemChoXD-….apk**.
2. Cài đè bản XZalo cũ cùng chữ ký để giữ đăng nhập, cấu hình và bộ ảnh nền.
3. Vào **Cá nhân → XZalo** để chỉnh các tính năng hoặc chọn **Kiểm tra cập nhật**.

Package: `com.mcxdshinko.zalo`. Cài song song với Zalo gốc, không cần root hay mở khóa bootloader. Thiết bị đã thử: Samsung SM-A145F, Android 15.

## Google Drive qua GmsCore

Cài [ReVanced GmsCore chính thức](https://github.com/ReVanced/GmsCore/releases/latest), tự đăng nhập Google rồi chọn chia sẻ tài khoản và cấp quyền Drive cho XZalo một lần. Từ fix10, công tắc đã bật sẵn; không cần giữ màn hình GmsCore mở. Trong **Cài đặt XZalo → Google Drive qua GmsCore**, có hướng dẫn tài khoản và kiểm tra dữ liệu chỉ đọc. Bật sẵn không tự đăng nhập hoặc tự cấp quyền Google.

## Cập nhật trong app

Từ **fix05**, XZalo tự kiểm tra khi mở lại ứng dụng. Khi bản mới được đánh dấu bắt buộc, thông báo hướng dẫn tải APK mới để tiếp tục sử dụng. Android vẫn yêu cầu người dùng xác nhận cài đặt.

Các bản cũ hơn fix05 cần cài fix05 hoặc bản mới hơn một lần để có bộ kiểm tra cập nhật. File `update.json` và `SHA256SUMS.txt` trong mỗi Release mô tả đúng APK của bản đó.

## Diện mạo và tiện ích

- Bộ ảnh nền ngẫu nhiên, điều chỉnh độ đậm/độ mờ và thanh điều hướng trong suốt.
- Tùy chọn quyền riêng tư, sao lưu cấu hình và tìm kiếm cài đặt.
- Icon, màn hình mở app và giao diện mang tên **XZalo · MemChoXD**.

Tùy biến từ [ZaloXposed của ElectroHeavenVN](https://github.com/ElectroHeavenVN/ZaloXposed). XZalo là bản tùy biến độc lập.
