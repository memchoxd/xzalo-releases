# XZalo · MemChoXD

**Một diện mạo riêng cho mỗi lần mở app.**

[Tải bản mới nhất · fix09](https://github.com/memchoxd/xzalo-releases/releases/latest) · [Chi tiết fix09](https://github.com/memchoxd/xzalo-releases/releases/tag/v2026.10.15-fix09) · [Lịch sử phiên bản](https://github.com/memchoxd/xzalo-releases/releases)

> **fix09 · Google Drive qua GmsCore — Latest**  
> XZalo đã có thể nhận fix09 qua **Cài đặt XZalo → Kiểm tra cập nhật** hoặc khi mở lại app. Với fix08, đây là cập nhật tùy chọn. Tính năng Drive còn thử nghiệm: sao lưu trên tài khoản test có danh mục 390 ảnh trong 26 gói; chưa xác minh khôi phục đầy đủ bản sao lưu Zalo gốc. Xem hướng dẫn GmsCore và kết quả kiểm tra trong [Release fix09](https://github.com/memchoxd/xzalo-releases/releases/tag/v2026.10.15-fix09).

Kho này chứa APK đã phát hành và thông tin cập nhật của XZalo. Mã nguồn được quản lý trong repo riêng tư.

## Cài đặt

1. Mở trang **Releases**, tải file **XZalo-MemChoXD-….apk**.
2. Cài đè bản XZalo cũ cùng chữ ký để giữ đăng nhập, cấu hình và bộ ảnh nền.
3. Vào **Cá nhân → XZalo** để chỉnh các tính năng hoặc chọn **Kiểm tra cập nhật**.

Package: `com.mcxdshinko.zalo`. Cài song song với Zalo gốc, không cần root hay mở khóa bootloader. Thiết bị đã thử: Samsung SM-A145F, Android 15.

## Cập nhật trong app

Từ **fix05**, XZalo tự kiểm tra khi mở lại ứng dụng. Khi bản mới được đánh dấu bắt buộc, thông báo hướng dẫn tải APK mới để tiếp tục sử dụng. Android vẫn yêu cầu người dùng xác nhận cài đặt.

Các bản cũ hơn fix05 cần cài fix05 hoặc bản mới hơn một lần để có bộ kiểm tra cập nhật. File `update.json` và `SHA256SUMS.txt` trong mỗi Release mô tả đúng APK của bản đó.

## Diện mạo và tiện ích

- Bộ ảnh nền ngẫu nhiên, điều chỉnh độ đậm/độ mờ và thanh điều hướng trong suốt.
- Tùy chọn quyền riêng tư, sao lưu cấu hình và tìm kiếm cài đặt.
- Icon, màn hình mở app và giao diện mang tên **XZalo · MemChoXD**.

Tùy biến từ [ZaloXposed của ElectroHeavenVN](https://github.com/ElectroHeavenVN/ZaloXposed). XZalo là bản tùy biến độc lập.
