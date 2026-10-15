# XZalo · MemChoXD

**Một diện mạo riêng cho mỗi lần mở app.**

[Tải bản mới nhất · fix11](https://github.com/memchoxd/xzalo-releases/releases/latest) · [Chi tiết fix11](https://github.com/memchoxd/xzalo-releases/releases/tag/v2026.10.15-fix11) · [Lịch sử phiên bản](https://github.com/memchoxd/xzalo-releases/releases)

> **fix11 · Một APK XZalo, kèm bộ cài GmsCore — Latest**  
> Không cần tìm tải GmsCore riêng: bộ cài chính thức đã nằm trong APK XZalo (~187 MB). Cài từ màn chào hoặc mục Google Drive trong cài đặt, rồi xác nhận với Android. Máy đã có GmsCore hợp lệ sẽ dùng tiếp; Drive vẫn bật sẵn. Đã qua 38 kiểm tra Drive/bộ cài, 21 kiểm tra màn chào, 18 unit test và thử cài khi máy ảo Android 15 tắt mạng. Cập nhật tuỳ chọn cho fix08 trở lên. Chưa xác minh khôi phục toàn bộ ảnh từ bản sao lưu Zalo gốc.

Kho này chứa APK đã phát hành và thông tin cập nhật của XZalo. Mã nguồn được quản lý trong repo riêng tư.

## Cài đặt

1. Mở trang **Releases**, tải file **XZalo-MemChoXD-….apk**.
2. Cài đè bản XZalo cũ cùng chữ ký để giữ đăng nhập, cấu hình và bộ ảnh nền.
3. Vào **Cá nhân → XZalo** để chỉnh các tính năng hoặc chọn **Kiểm tra cập nhật**.

Package: `com.mcxdshinko.zalo`. Cài song song với Zalo gốc, không cần root hay mở khóa bootloader. Thiết bị đã thử: Samsung SM-A145F, Android 15.

## Google Drive qua GmsCore

Chọn **Thiết lập Google Drive** trên màn chào hoặc vào **Cài đặt XZalo → Google Drive qua GmsCore → Cài GmsCore có sẵn**. Cho phép cài ứng dụng từ XZalo và xác nhận cài. Bộ cài [ReVanced GmsCore chính thức](https://github.com/ReVanced/GmsCore/releases/tag/v0.3.13.2.250932) được giữ nguyên chữ ký; không cần mạng cho bước cài này. GmsCore vẫn là ứng dụng riêng trên máy. Khi có mạng, tự đăng nhập Google và cấp quyền tài khoản/Drive một lần; không cần giữ màn hình GmsCore mở. Bật sẵn không tự đăng nhập hoặc tự cấp quyền Google.

## Cập nhật trong app

Từ **fix05**, XZalo tự kiểm tra khi mở lại ứng dụng. Khi bản mới được đánh dấu bắt buộc, thông báo hướng dẫn tải APK mới để tiếp tục sử dụng. Android vẫn yêu cầu người dùng xác nhận cài đặt.

Các bản cũ hơn fix05 cần cài fix05 hoặc bản mới hơn một lần để có bộ kiểm tra cập nhật. File `update.json` và `SHA256SUMS.txt` trong mỗi Release mô tả đúng APK của bản đó.

## Diện mạo và tiện ích

- Bộ ảnh nền ngẫu nhiên, điều chỉnh độ đậm/độ mờ và thanh điều hướng trong suốt.
- Tùy chọn quyền riêng tư, sao lưu cấu hình và tìm kiếm cài đặt.
- Icon, màn hình mở app và giao diện mang tên **XZalo · MemChoXD**.

Tùy biến từ [ZaloXposed của ElectroHeavenVN](https://github.com/ElectroHeavenVN/ZaloXposed). XZalo là bản tùy biến độc lập.
