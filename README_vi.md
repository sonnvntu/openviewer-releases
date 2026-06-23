<div align="center">

<img src="assets/openviewer_256.png" alt="OpenViewer Logo" width="128" height="128">

# OpenViewer

**Truy Cập Từ Xa Và Camera Thông Minh AI**

[English](README.md) | [Tiếng Việt](README_vi.md)

[![License](https://img.shields.io/badge/license-Proprietary-blue.svg)](#)
[![Platform](https://img.shields.io/badge/platform-Windows%20|%20Linux%20|%20macOS%20|%20Android%20|%20iOS-brightgreen.svg)](#download)
[![GitHub Release](https://img.shields.io/github/v/release/sonnvntu/openviewer-releases?include_prereleases&label=latest)](https://github.com/sonnvntu/openviewer-releases/releases/latest)

</div>

---

## ✨ Giới thiệu

**OpenViewer** là nền tảng hỗ trợ bởi AI, kết hợp tính năng truy cập từ xa, giám sát camera và tự động hóa thông minh.

### Tính năng chính

- 🖥️ **Truy cập từ xa** — Xem và điều khiển bất kỳ máy tính nào từ mọi nơi
  - Truyền phát màn hình độ trễ thấp và FPS cao.
  - Điều hướng và quản lý nhiều màn hình cùng lúc.
  - Capture màn hình và âm thanh hiệu năng cao qua DXGI (Windows), ScreenCaptureKit (macOS) và X11/Wayland/PipeWire (Linux).
  - Truyền tệp tốc độ cao và bảo mật.
- 📹 **AI-Powered Vision** — Biến camera thành các cảm biến thông minh.
  - Hỗ trợ tăng tốc CPU và GPU sử dụng Vulkan.
  - Triển khai các mô hình AI tùy chỉnh được huấn luyện riêng cho nhu cầu của bạn.
  - Phát hiện người, đám cháy, phương tiện và các sự kiện quan trọng khác.
  - Tăng cường độ tin cậy với chuỗi xử lý (pipeline) Phát hiện & Phân loại đa tầng.
  - Thiết lập luồng công việc AI trực quan: Phát hiện → Phân loại → Luật → Cảnh báo.
  - Kích hoạt thông báo thời gian thực và các phản hồi tự động.
- 🔒 **Mã hóa đầu cuối** — Kết nối P2P được bảo mật bằng mã hóa DTLS
- 📱 **Đa nền tảng** — Windows, Linux, macOS, Android, iOS
- 🌐 **Không cần cấu hình cổng (Port Forwarding)** — Hoạt động tốt sau mạng NAT nhờ hệ thống STUN/TURN relay
- 🔔 **Thông báo đẩy** — Gửi trực tiếp các cảnh báo sự kiện AI đến điện thoại của bạn

---

## 🚀 Khởi động nhanh

Bắt đầu sử dụng **OpenViewer** chỉ với ba bước đơn giản:

### 1. Tải xuống OpenViewer
Tải xuống phiên bản cài đặt mới nhất phù hợp với thiết bị của bạn từ trang [GitHub Releases](https://github.com/sonnvntu/openviewer-releases/releases/latest).
* Hỗ trợ đầy đủ cho Windows, Linux, macOS, Android và iOS.

### 2. Cài đặt & Thiết lập
* **Trên máy tính cần điều khiển (Host)**: Khởi chạy ứng dụng OpenViewer Host để cho phép kết nối từ xa và cấu hình các tính năng Camera AI.
* **Trên thiết bị điều khiển (Client)**: Mở ứng dụng OpenViewer Client trên máy tính hoặc điện thoại.

### 3. Kết nối & Trải nghiệm
* Đăng nhập tài khoản hoặc sử dụng ID kết nối được cấp để bắt đầu phiên truy cập từ xa P2P bảo mật.
* Thêm camera và triển khai các mô hình AI trực tiếp từ giao diện điều khiển.

---

## 📦 Hướng dẫn cài đặt

### 🪟 Windows
1. Tải xuống tệp `openviewer-windows-x64.zip` hoặc `.exe` từ trang [Releases](https://github.com/sonnvntu/openviewer-releases/releases/latest).
2. Giải nén tệp ZIP (nếu tải bản zip) hoặc chạy tệp cài đặt `.exe`.
3. Chạy tệp `OpenViewer.exe` để bắt đầu.

### 🐧 Linux
1. Tải xuống tệp `openviewer-linux-x64.AppImage` (hoặc gói `OpenViewer-v1.0.1-linux-amd64.deb`).
2. Đối với **AppImage**:
   * Nhấp chuột phải vào tệp, chọn **Properties** (Thuộc tính) -> **Permissions** (Quyền) -> tích chọn **Allow executing file as program** (Cho phép thực thi tệp như một chương trình).
   * Hoặc mở Terminal và chạy lệnh sau:
     ```bash
     chmod +x openviewer-linux-x64.AppImage
     ./openviewer-linux-x64.AppImage
     ```
3. Đối với **DEB** (Debian/Ubuntu):
   ```bash
   # Cài đặt
   sudo apt install ./OpenViewer-v1.0.1-linux-amd64.deb

   # Cài đặt lại (reinstall)
   sudo apt install --reinstall ./OpenViewer-v1.0.1-linux-amd64.deb
   ```

### 🍎 macOS
1. Tải xuống tệp `openviewer-macos-x64.dmg` (hoặc bản arm64 cho Apple Silicon).
2. Nhấp đúp vào tệp `.dmg` và kéo thả biểu tượng **OpenViewer** vào thư mục **Applications** (Ứng dụng).
3. Nếu xuất hiện cảnh báo bảo mật ứng dụng chưa được xác minh:
   * Truy cập **System Settings** (Cài đặt hệ thống) > **Privacy & Security** (Quyền riêng tư & Bảo mật).
   * Cuộn xuống dưới và chọn **Open Anyway** (Vẫn mở).

### 🤖 Android (APK)
1. Tải xuống tệp `openviewer-android.apk` trực tiếp trên thiết bị của bạn.
2. Mở tệp APK vừa tải. Nếu được yêu cầu, hãy cấp quyền **"Cài đặt ứng dụng từ nguồn không xác định"** (Install from Unknown Sources) trong phần cài đặt của trình duyệt hoặc trình quản lý tệp.
3. Nhấn **Cài đặt** (Install) và mở ứng dụng.

---

## 📸 Giao diện ứng dụng

### 💻 Ứng dụng Desktop
<div align="center">
  <img src="assets/desktop_dashboard.png" alt="Bảng điều khiển & Thông báo Desktop" width="99%">
</div>
<div align="center" style="margin-top: 10px;">
  <img src="assets/desktop_ai_live.png" alt="Xem trực tiếp AI trên Desktop" width="49%">
  <img src="assets/desktop_ai_events.png" alt="Lịch sử sự kiện AI" width="49%">
</div>
<div align="center" style="margin-top: 10px;">
  <img src="assets/desktop_remote_win.png" alt="Điều khiển máy tính Windows" width="49%">
  <img src="assets/desktop_remote_linux.png" alt="Điều khiển máy tính Linux" width="49%">
</div>

### 📱 Ứng dụng Di động
<div align="center">
  <img src="assets/mobile_remote_connections.jpg" alt="Danh sách kết nối di động" width="32%">
  <img src="assets/mobile_remote.jpg" alt="Điều khiển từ xa trên di động" width="32%">
  <img src="assets/mobile_camera_live.jpg" alt="Xem trực tiếp camera trên di động" width="32%">
</div>
<div align="center" style="margin-top: 10px;">
  <img src="assets/mobile_ai_alerts.jpg" alt="Danh sách cảnh báo AI" width="32%">
  <img src="assets/mobile_ai_alert_local.jpg" alt="Chi tiết sự kiện AI" width="32%">
  <img src="assets/mobile_push_notifications.jpg" alt="Thông báo đẩy trên di động" width="32%">
</div>

---

</div>
