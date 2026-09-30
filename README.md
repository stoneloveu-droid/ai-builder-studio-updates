# AI Builder Studio — Cập nhật

Kho phát hành công khai cho plugin AI Builder Studio trong SketchUp 2021+.

## Bản hiện tại

**3.0.0-beta.4** — nguồn cập nhật GitHub được cấu hình sẵn.

[Tải AI_Builder_Studio_3.0_Beta4.rbz](https://raw.githubusercontent.com/stoneloveu-droid/ai-builder-studio-updates/0155789b4a53d355557f53adc647971c9c4e4a79/packages/AI_Builder_Studio_3.0_Beta4.rbz)

Cài bằng Extension Manager một lần và khởi động lại SketchUp. Những lần sau mở **Cập nhật → Kiểm tra bản mới → Cập nhật** khi có phiên bản mới được phát hành.

Nếu đã dùng Beta 3: vào **Cập nhật → Nguồn cập nhật**, dán địa chỉ dưới, bấm **Lưu cài đặt cập nhật → Kiểm tra bản mới → Cập nhật**. Không cần đăng nhập GitHub trong SketchUp.

```text
https://raw.githubusercontent.com/stoneloveu-droid/ai-builder-studio-updates/main/latest.json
```

Sau khi cài, lưu công việc và khởi động lại SketchUp. Quy chuẩn và mẫu lưu trong máy không nằm trong kho này và không bị thay thế bởi gói cập nhật.

## Phạm vi kiểm chứng

Đã kiểm tra bộ dựng, xác thực gói cập nhật và giao tiếp giao diện bằng giả lập. Chưa nghiệm thu cài đặt và DC/Scale trực tiếp trên SketchUp Windows.

## Phát hành lần sau

- Mỗi gói trong `packages/` dùng tên phiên bản riêng; không thay nội dung gói đã phát hành.
- Đưa gói lên kho trước, rồi cập nhật `latest.json` sau cùng.
- `url` trong manifest trỏ commit cụ thể; `bytes` và `sha256` phải khớp chính xác gói tải về.
- Plugin chỉ thông báo khi phiên bản mới lớn hơn phiên bản đang chạy. Mỗi bản mới cần được người quản lý chủ động phát hành.
