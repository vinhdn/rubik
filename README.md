# Rubik 3x3 3D

Website chơi Rubik 3x3 3D trên trình duyệt (hỗ trợ mobile): vuốt để xoay lớp, gợi ý nước đi, undo/redo, và các chế độ luyện tập công thức tầng 2 + tầng 3 (dấu cộng vàng, 4 cạnh, 4 góc, lật góc).

Mở `index.html` là chơi — trang tự chứa hoàn toàn, không cần cài thêm gì.

## Cài như app (PWA)

Trang là PWA cài được qua Chrome: mở trang trên Chrome (Android hoặc máy tính) → menu ⋮ → **Cài đặt ứng dụng / Thêm vào màn hình chính**, hoặc bấm nút **📲 Cài app** ngay trong trang. App mở toàn màn hình như app thật và chơi được cả khi không có mạng.

Các file PWA đi kèm: `manifest.webmanifest`, `sw.js` (cache app shell, điều hướng ưu tiên mạng), `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png` — tất cả dùng đường dẫn tương đối nên chạy đúng cả khi host ở thư mục con (ví dụ GitHub Pages `/rubik/`).
