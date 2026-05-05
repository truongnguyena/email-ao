# 📬 KurumiMail v2.1 - Giải pháp Email tạm thời chuyên nghiệp

![KurumiMail Banner](https://raw.githubusercontent.com/truongnguyena/email-ao/main/frontend/public/og-image.png)

**KurumiMail** là một hệ thống email tạm thời (disposable email) mã nguồn mở, hiện đại và mạnh mẽ, được thiết kế để bảo vệ quyền riêng tư của người dùng và hỗ trợ các nhà phát triển.

## ✨ Tính năng nổi bật

### 🎨 Giao diện & Trải nghiệm (UI/UX)
- **Thiết kế hiện đại:** Sử dụng phong cách Glassmorphism với hiệu ứng mượt mà.
- **Dark Mode:** Tối ưu hóa cho trải nghiệm ban đêm.
- **Responsive:** Hoạt động hoàn hảo trên cả máy tính và điện thoại.
- **Splash Screen:** Hiệu ứng khởi tạo chuyên nghiệp.

### 📧 Chức năng Email
- **Nhận thư tức thì:** Máy chủ SMTP riêng biệt, tốc độ nhận thư < 3 giây.
- **Tìm kiếm & Bộ lọc:** Tìm kiếm email theo tiêu đề/người gửi; lọc thư chưa đọc hoặc yêu thích (Starred).
- **Tải xuống EML:** Hỗ trợ tải email về máy dưới định dạng tiêu chuẩn `.eml`.
- **Thông báo:** Nhận thông báo trình duyệt (Browser Notification) ngay khi có thư mới.
- **QR Code:** Chia sẻ địa chỉ email nhanh chóng qua mã QR.

### 🛠 Dành cho Nhà phát triển (Developer API)
- **Hệ thống API Key:** Tạo và quản lý API Key dễ dàng.
- **Tài liệu đầy đủ:** Hướng dẫn sử dụng với code ví dụ (cURL, JavaScript, Python).
- **Rate Limiting:** Bảo vệ hệ thống bằng cơ chế giới hạn tần suất yêu cầu.

## 🚀 Công nghệ sử dụng
- **Frontend:** React, Vite, TailwindCSS, Axios.
- **Backend:** Node.js, Express, SMTP-Server, Mailparser.
- **Deployment:** Hỗ trợ PM2, Nginx Reverse Proxy, Docker Ready.

## 🛡 Bảo mật & Quyền riêng tư
- Tự động xóa dữ liệu sau khi hết hạn.
- Không yêu cầu thông tin cá nhân.
- Sử dụng Helmet & CSP để bảo vệ website khỏi các cuộc tấn công web.

---
*Phát triển bởi Kurumi Team - 2026*
