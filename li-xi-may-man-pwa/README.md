# Lì xì may mắn – PWA

## Có gì trong bộ này?
- Vòng quay 23 ô đúng cơ cấu giải: 1K×3, 2K×3, 5K×3, 10K×3, 20K×3, 50K×2, 100K×1, 200K×1, 500K×1, LỜI CHÚC×3.
- Chạm trực tiếp vào vòng quay để quay.
- Hiệu ứng hoa mai/đào trang trí và giao diện Tết.
- PWA có manifest, biểu tượng và service worker để mở lại khi offline sau lần tải đầu tiên.

## Đưa lên GitHub Pages bằng Windows
1. Giải nén `li-xi-may-man-pwa.zip`.
2. Đăng nhập https://github.com và chọn **New repository**.
3. Đặt tên `li-xi-may-man`, chọn **Public**, nhấn **Create repository**.
4. Trong repository, chọn **Add file → Upload files**.
5. Mở thư mục đã giải nén, kéo toàn bộ NỘI DUNG bên trong thư mục `li-xi-may-man-pwa` (index.html, manifest.webmanifest, sw.js và thư mục icons) vào vùng upload. Đừng chỉ tải file ZIP lên.
6. Nhấn **Commit changes**.
7. Vào **Settings → Pages**.
8. Ở **Build and deployment**, chọn **Deploy from a branch**.
9. Chọn branch **main**, folder **/(root)**, rồi nhấn **Save**.
10. Đợi GitHub Pages triển khai. Đường link thường có dạng:
   `https://TEN-GITHUB-CUA-BAN.github.io/li-xi-may-man/`

## Cài lên iPhone
1. Mở đường link ở trên bằng Safari (không dùng trình duyệt trong ứng dụng khác).
2. Chạm nút **Chia sẻ**.
3. Chọn **Thêm vào Màn hình chính**.
4. Nếu thấy tùy chọn **Open as Web App / Mở dưới dạng ứng dụng web**, bật tùy chọn đó.
5. Đổi tên thành **Lì xì may mắn**, nhấn **Thêm**.

## Kiểm tra offline
- Mở app khi đang có mạng và chờ trang tải xong.
- Đóng app, bật Chế độ máy bay, mở lại biểu tượng trên Màn hình chính.
- Nếu đây là lần đầu cài hoặc vừa cập nhật, hãy mở app online ít nhất một lần để service worker lưu các tệp.

## Cập nhật sau này
Khi sửa code, tải lại các tệp lên GitHub và commit. Nếu có thay đổi lớn, đổi `CACHE_NAME` trong `sw.js` (ví dụ v1 thành v2) để trình duyệt tạo cache mới.

Lưu ý: đây là trò chơi giải trí; kết quả và số tiền chỉ mang tính mô phỏng, không phải giao dịch tiền thật.
