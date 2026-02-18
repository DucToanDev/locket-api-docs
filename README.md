# Locket Gold Unlocker - DNS Method 🔓

![Locket Gold](https://img.shields.io/badge/Locket-Gold-gold?style=for-the-badge&logo=app-store)
![Status](https://img.shields.io/badge/Status-Working-brightgreen?style=for-the-badge)
![Method](https://img.shields.io/badge/Method-DNS_Blocking-blue?style=for-the-badge)

> **Lưu ý:** Dự án này được chia sẻ với mục đích nghiên cứu kỹ thuật và giáo dục (Educational Purposes Only).

## 🌐 Trang chủ & Tải Profile
Để cập nhật Profile DNS mới nhất và ổn định nhất (đã fix lỗi mất Gold), vui lòng truy cập website chính thức:

👉 **[https://locketgold.top](https://locketgold.top)** 👈

---

## 🛠 Cơ chế hoạt động (How it works)

Locket Widget sử dụng dịch vụ bên thứ 3 là **RevenueCat** để kiểm tra trạng thái đăng ký (Subscription) của người dùng. Phương pháp này hoạt động dựa trên nguyên lý can thiệp vào quá trình phân giải tên miền (DNS) để chặn hoặc điều hướng các yêu cầu xác thực.

### Quy trình kỹ thuật:
1.  **Block Verification:** Sử dụng NextDNS hoặc AdGuard Home để chặn kết nối đến các endpoint của RevenueCat (ví dụ: `api.revenuecat.com`).
2.  **Fallback State:** Khi ứng dụng không thể kết nối đến máy chủ kiểm tra bản quyền, trong một số phiên bản, ứng dụng sẽ giữ nguyên trạng thái cache cũ (nếu đã từng kích hoạt) hoặc không thể xác nhận trạng thái "Free", từ đó cho phép sử dụng các tính năng Gold.
3.  **Privacy Protection:** Việc sử dụng DNS mã hóa (DoH/DoT) giúp bảo vệ quyền riêng tư và ngăn chặn việc theo dõi hành vi người dùng.

## ✨ Tính năng (Features)

Sau khi áp dụng cấu hình DNS từ **[LocketGold.top](https://locketgold.top)**, bạn có thể trải nghiệm:
- 📸 **Upload video dài:** Không bị giới hạn thời gian.
- 🕵️ **Who viewed:** Xem ai đã vào xem trang cá nhân của bạn.
- 🖼 **Change Icons:** Thay đổi icon ứng dụng tùy thích.
- 🚫 **No Ads:** Chặn quảng cáo trong ứng dụng (tùy profile).

## 🚀 Hướng dẫn cài đặt nhanh (Quick Start)

Do cấu hình DNS thay đổi liên tục để đối phó với các bản cập nhật của Locket, chúng tôi không công khai trực tiếp file config tại đây.

1.  Truy cập **[https://locketgold.top](https://locketgold.top)**.
2.  Chọn server phù hợp (Server 1 hoặc Server 2).
3.  Tải Profile về iPhone/iPad.
4.  Vào **Cài đặt (Settings)** -> **Đã tải về hồ sơ** -> **Cài đặt**.
5.  Khởi động lại máy hoặc bật tắt chế độ máy bay để DNS có hiệu lực.

## ⚠️ Khắc phục sự cố (Troubleshooting)

**Hỏi: Tại sao tôi bị mất Gold sau vài ngày?**
> **Đáp:** Locket liên tục thay đổi domain check bản quyền. Hãy quay lại **[LocketGold.top](https://locketgold.top)** để tải profile mới nhất. Ngoài ra, hãy thử xóa cache ứng dụng hoặc cài đặt lại Locket sau khi bật DNS.

**Hỏi: Phương pháp này có an toàn không?**
> **Đáp:** Chúng tôi sử dụng NextDNS, một dịch vụ DNS uy tín toàn cầu. Dữ liệu của bạn được mã hóa và bảo mật.

---

### 🔗 Liên kết
- **Website:** [https://locketgold.top](https://locketgold.top)
- **Support:** Liên hệ qua website.

*(C) 2026 Locket Gold Project. Developed for research.*
