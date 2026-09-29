# 🔒 Modern Login Form with Floating Label & Toggle Password

Giao diện trang đăng nhập (Login Form) hiện đại, đáp ứng tốt trên màn hình thiết bị di động (Responsive), hỗ trợ các hiệu ứng tương tác mượt mà bằng HTML5, CSS3 và Vanilla JavaScript.

---

## ✨ Tính năng chính (Features)

- **Floating Label Input:** Nhãn di chuyển mượt mà khi người dùng focus hoặc nhập dữ liệu vào ô input.
- **Toggle Show/Hide Password:** Bật/Tắt hiển thị mật khẩu bằng biểu tượng con mắt dạng SVG (sử dụng Lucide Icons).
- **CSS Blob Keyframe Animation:** Hiệu ứng hình khối nền mờ trang trí động ở góc giao diện.
- **Social Login Options:** Hỗ trợ nút đăng nhập nhanh qua Google, Facebook và Apple.
- **Responsive Design:** Tương thích tốt trên cả giao diện Máy tính và Điện thoại thông thoại (Mobile).

---

## 🛠️ Công nghệ sử dụng (Tech Stack)

- **HTML5:** Cấu trúc form Semantic chuẩn SEO & Accessibility.
- **CSS3:** 
  - CSS Variables (`:root`) dễ dàng tùy chỉnh màu sắc.
  - Flexbox & CSS Grid cho bố cục linh hoạt.
  - Keyframe Animations (`@keyframes welcomeIn`) tạo hiệu ứng động.
- **JavaScript (Vanilla JS):** Thao tác DOM thuần để chuyển đổi loại input password và icon con mắt.
- **Fonts & Assets:** Font chữ `DM Sans` từ Google Fonts, icon SVG.

---

## 📂 Cấu trúc thư mục (Project Structure)

```text
├── assets/
│   ├── css/
│   │   └── style.css       # File chứa toàn bộ style & animation
│   └── images/
│       ├── blob.svg        # Hình nền động trang trí
│       ├── google.svg      # Icon đăng nhập Google
│       ├── facebook.svg    # Icon đăng nhập Facebook
│       └── apple.svg       # Icon đăng nhập Apple
├── index.html              # File giao diện chính & logic JS
└── README.md               # Tài liệu hướng dẫn dự án