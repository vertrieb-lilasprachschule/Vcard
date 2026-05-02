# Vcard
# Danh thiếp online – Đoàn Trần Hùng (Lukas Hoff)

Trang danh thiếp cá nhân, deploy miễn phí vĩnh viễn trên GitHub Pages.

---

## Hướng dẫn deploy lên GitHub Pages (5 bước)

### Bước 1 — Tạo tài khoản GitHub
Vào https://github.com → Sign up (nếu chưa có)

### Bước 2 — Tạo repository mới
1. Nhấn nút **+** góc trên phải → **New repository**
2. Đặt tên repository: `lukas-hoff` (hoặc tên bất kỳ)
3. Chọn **Public**
4. Nhấn **Create repository**

### Bước 3 — Upload file
1. Trong trang repository vừa tạo, nhấn **uploading an existing file**
2. Kéo thả file `index.html` vào
3. Nhấn **Commit changes**

### Bước 4 — Bật GitHub Pages
1. Vào tab **Settings** của repository
2. Kéo xuống mục **Pages** (cột bên trái)
3. Trong **Branch**, chọn `main` → thư mục `/ (root)`
4. Nhấn **Save**
5. Chờ 1-2 phút, GitHub sẽ hiện link dạng:
   `https://tên-tài-khoản.github.io/lukas-hoff/`

### Bước 5 — Tạo mã QR
Vào https://qr.io hoặc https://goqr.me, dán link GitHub Pages vào, tải QR về.

---

## Cách hoạt động khi khách quét QR

1. Camera điện thoại quét QR → mở trang web
2. Khách nhấn nút **"Lưu vào danh bạ"**
3. Điện thoại tự động tải file `.vcf` → mở ứng dụng Danh bạ → hiện đầy đủ thông tin
4. Khách nhấn **Lưu** là xong — không cần gõ tay gì cả

Hoạt động trên: iPhone (iOS 12+), Android (mọi phiên bản), Samsung, Xiaomi, Oppo...

---

## Cập nhật thông tin sau này

Chỉ cần vào GitHub, mở file `index.html`, nhấn biểu tượng bút chì để chỉnh sửa, rồi **Commit** — trang web và QR cũ vẫn dùng được, nội dung tự cập nhật.
