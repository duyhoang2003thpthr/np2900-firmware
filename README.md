# MTC NP2900 — Firmware

Kho phát hành firmware chính thức cho máy in **MTC NP2900** (Mono Laser Printer).

## Cập nhật bằng ứng dụng (khuyến nghị)

Dùng **MTC NP2900 Update** cho Windows: ứng dụng tự nhận máy in, kiểm tra phiên bản,
tải và cập nhật firmware mới nhất. Xác thực chữ ký số tự động ở mọi bước.

## Cập nhật thủ công

1. Tải file `capt_update_vX.Y.Z_ENCRYPTED.bin` ở mục **Releases** (bản mới nhất).
2. Tắt máy in. Cắm cáp USB vào máy tính.
3. **Giữ phím GIẤY** trên máy in trong lúc bật nguồn — máy tính sẽ hiện ổ đĩa USB
   tên `LBP2900-FW`.
4. Chép file `.bin` vừa tải vào ổ đĩa đó. Máy tự kiểm tra, cập nhật và khởi động lại.
5. Mở file `LBP2900_LOG.TXT` trong ổ đĩa (vào lại chế độ cập nhật) để xem phiên bản
   và lịch sử cập nhật.

## An toàn

- File phát hành được **mã hóa và ký số**; máy in chỉ chấp nhận firmware chính chủ —
  file hỏng hoặc bị sửa đổi sẽ bị từ chối, máy không thể bị hỏng vì cập nhật sai file.
- `manifest.json` / `manifest.json.sig` trong mỗi Release dành cho ứng dụng cập nhật
  (kiểm tra phiên bản + toàn vẹn); người dùng thủ công không cần quan tâm.

---
© MTC. Mọi thắc mắc bảo hành vui lòng liên hệ nơi bán.
