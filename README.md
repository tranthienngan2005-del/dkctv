# Đăng ký & theo dõi lịch trực CTV – Phòng CT-CTSV HUFLIT (2026-2027)

Web tĩnh (HTML + Firebase Auth/Firestore), host bằng GitHub Pages.

- `index.html` – toàn bộ ứng dụng (cấu hình Firebase nằm ở đầu phần `<script>`).
- `firestore.rules` – quy tắc bảo mật; dán vào Firebase Console → Firestore → Rules.

## Triển khai
1. Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
2. Firebase Console → Authentication → Settings → Authorized domains → thêm `<tên-github>.github.io`.
3. Mở `https://<tên-github>.github.io/<tên-repo>/`.

> Cấu hình web của Firebase (apiKey...) là thông tin công khai theo thiết kế; an toàn dữ liệu do `firestore.rules` đảm bảo.
