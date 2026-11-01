# CHUYẾN ĐÒ TRI THỨC — BÁO TƯỜNG ĐIỆN TỬ 20/11/2026

Ấn phẩm số của **lớp 10A7 – Trường THCS&THPT Phạm Kiệt**.

- **Thông điệp:** Một đời gieo chữ – Vạn lời tri ân.
- **Giáo viên chủ nhiệm:** Cô Tạ Thị Thu Phường.
- **Công nghệ:** HTML, CSS và JavaScript thuần; tương thích GitHub Pages.

## Cấu trúc hiện tại

Website là một trang tạp chí số gồm sáu chuyên mục:

1. Lời ngỏ.
2. Trang thơ và tản văn.
3. Người gieo hạt.
4. Thanh xuân 10A7.
5. Những điều chúng em chưa kịp nói.
6. Vạn lời tri ân.

## Tài nguyên hình ảnh

Hai logo gốc được giữ nguyên tại thư mục gốc:

- `LOGO_MOI.png` — logo trường.
- `LOGO LOP.png` — logo lớp.

Khu vực album hiện là các khung chờ ảnh thật. Vui lòng thay các khung trong phần `#thanh-xuan` bằng ảnh đã được lớp cho phép sử dụng; không coi khung trang trí là ảnh tư liệu.

## Chỉnh sửa nội dung

Mở `index.html`. Các phần nội dung có ID tương ứng:

- `#loi-ngo`
- `#trang-tho`
- `#nguoi-gieo-hat`
- `#thanh-xuan`
- `#loi-nhan`
- `#van-loi-tri-an`

Thơ và lời nhắn đang hiển thị được biên soạn như nội dung gợi ý cho ấn phẩm, không gán cho học sinh cụ thể. Phần tri ân giáo viên chỉ sử dụng thông tin đã được cung cấp; chưa thêm kỷ niệm hoặc thành tích chưa xác minh.

## Tính năng và giới hạn

- Điều hướng đến từng chuyên mục, menu thu gọn trên điện thoại.
- Hiệu ứng xuất hiện khi cuộn, nút trở về đầu trang và hỗ trợ `prefers-reduced-motion`.
- Không tự phát âm thanh.
- Chưa tích hợp biểu mẫu gửi/lưu lời chúc hoặc backend. Không có dữ liệu nào được gửi hay lưu từ các thẻ lời nhắn hiện tại.

## GitHub Pages

Thiết lập xuất bản theo nhánh `main`, thư mục `/(root)` (nếu repository đang dùng cấu hình này). Sau khi hợp nhất thay đổi vào `main`, kiểm tra **Settings → Pages** và trạng thái triển khai trong tab **Actions**.

Website dự kiến: https://tranphuc2026abc-prog.github.io/BAO-TUONG-DIEN-TU-20-11/
