# WorkDesk - Quản lý nhiệm vụ thông minh

<div align="center">

<p align="center" style="display: flex; align-items: center; justify-content: center; gap: 30px;">
  <a href="https://github.com/mrtinhnguyen/deskhive/releases" style="text-decoration: none;">
    <span style="display: inline-block; background: linear-gradient(135deg, #6EE748 0%, #5fc940 100%); color: white; padding: 12px 28px; border-radius: 8px; font-size: 18px; font-weight: bold; box-shadow: 0 4px 15px rgba(110, 231, 72, 0.3); transition: all 0.3s ease;">
      📥 Tải về miễn phí
    </span>
  </a>
  <a href="#tính-năng-nổi-bật" style="text-decoration: none;">
    <span style="display: inline-block; background: linear-gradient(135deg, #2196F3 0%, #1976D2 100%); color: white; padding: 12px 28px; border-radius: 8px; font-size: 18px; font-weight: bold; box-shadow: 0 4px 15px rgba(33, 150, 243, 0.3); transition: all 0.3s ease;">
      ⭐ Tính năng
    </span>
  </a>
</p>

[![Version](https://img.shields.io/badge/phiên_bản-1.0.8-blue.svg)](https://github.com/mrtinhnguyen/deskhive/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Tauri](https://img.shields.io/badge/Tauri-2.0-orange.svg)](https://tauri.app/)
[![Vue](https://img.shields.io/badge/Vue-3.5-brightgreen.svg)](https://vuejs.org/)
[![Auto Update](https://img.shields.io/badge/auto_update-có_sẵn-purple.svg)](https://github.com/mrtinhnguyen/deskhive)

</div>

---

## 📖 Giới thiệu

**WorkDesk** là ứng dụng quản lý nhiệm vụ và công việc dành cho máy tính Windows, được xây dựng bằng **Vue 3**, **TypeScript** và **Tauri 2**. Ứng dụng giúp bạn theo dõi công việc hàng ngày, quản lý deadline, và phối hợp làm việc nhóm một cách hiệu quả.

### ✨ Tính năng nổi bật

#### 🔔 **Cập nhật tự động** (Mới trong v1.0.8)
- ✅ Tự động kiểm tra phiên bản mới khi khởi động
- ✅ Thông báo trực quan khi có cập nhật mới
- ✅ Một cú click để tải về và cài đặt
- ✅ Tự động khởi động lại sau khi cập nhật xong
- ✅ Không cần thao tác thủ công phức tạp

#### 🎯 **Quản lý nhiệm vụ**
- ✅ Tạo, chỉnh sửa, xóa nhiệm vụ nhanh chóng
- ✅ Double-click để xóa nhanh
- ✅ Menu ngữ cảnh với nhiều tùy chọn
- ✅ Đánh dấu hoàn thành với animation mượt mà
- ✅ Hỗ trợ kéo thả sắp xếp nhiệm vụ
- ✅ Nhiệm vụ đã hoàn thành được tách riêng

#### 📁 **Quản lý phòng ban & nhóm**
- ✅ Tạo nhóm nhanh: Gõ `/tên-nhóm` và nhấn Enter
- ✅ Tạo nhóm bằng hộp thoại: Click phải vào nút "+"
- ✅ Đổi tên, xóa, thu gọn/mở rộng nhóm
- ✅ Thay đổi thứ tự nhóm (lên/xuống)
- ✅ Kéo thả nhiệm vụ giữa các nhóm
- ✅ Phân công nhiệm vụ theo phòng ban

#### ⏰ **Quản lý thời gian**
- 🕐 Đặt deadline cho nhiệm vụ
- 🕐 Hiển thị đếm ngược thời gian thực
- 🕐 Bộ chỉ thị thời gian thông minh:
  - 🟢 Xanh: Còn đủ thời gian
  - 🔴 Đỏ: Quá hạn
  - 🟡 Vàng: Số ngày từ khi tạo
- 🕐 Di chuột để xem chi tiết thời gian
- 🌳 Xem dạng timeline (dòng thời gian)
- 🔔 Thông báo nhắc nhở deadline (tùy chỉnh)

#### 👥 **Quản lý người dùng & phân quyền**
- 👤 Đăng nhập/đăng xuất
- 👤 Hồ sơ người dùng
- 👤 Phân quyền Admin/Member
- 👤 Admin có thể tạo và quản lý nhiệm vụ server
- 👤 Cập nhật thông tin nhân sự, phòng ban

#### 🎨 **Giao diện & Trải nghiệm**
- 🌈 UI hiện đại, Material Design
- 🌈 Responsive layout, tự động thích ứng
- 🌈 Chế độ Sáng/Tối
- 🌈 Độ trong suốt cửa sổ tùy chỉnh
- 🌈 Animation mượt mà
- 🌈 Biểu tượng Material Icons

#### 🔧 **Tích hợp hệ thống**
- 💻 Khay hệ thống (system tray)
- 💻 Tự động khởi động cùng Windows
- 💻 Phím tắt toàn cục
- 💻 Ghi nhớ vị trí cửa sổ
- 💻 Tùy chọn vô hiệu hóa kéo cửa sổ

---

## 🚀 Cài đặt nhanh

### Yêu cầu hệ thống
- **Hệ điều hành**: Windows 10/11 (64-bit)
- **RAM**: Tối thiểu 10MB
- **Dung lượng**: ~50MB
- **.NET Framework**: 4.8+
- **Internet**: Để kiểm tra cập nhật

### Các bước cài đặt

1. **Tải về:**
   - Truy cập [Releases](https://github.com/mrtinhnguyen/deskhive/releases)
   - Tải file `.msi` mới nhất (ví dụ: `WorkHub_1.0.8_x64.msi`)

2. **Cài đặt:**
   - Double-click file `.msi` vừa tải
   - Làm theo hướng dẫn của trình cài đặt
   - Chờ quá trình cài đặt hoàn tất

3. **Khởi động:**
   - Mở WorkHub từ Desktop shortcut hoặc Start Menu
   - Bắt đầu sử dụng!

---

## 📚 Hướng dẫn sử dụng

### Tạo và quản lý nhiệm vụ

| Thao tác | Cách thực hiện |
|----------|----------------|
| **Tạo nhiệm vụ** | Nhập nội dung ở khung dưới, nhấn Enter hoặc click "+" |
| **Tạo nhóm nhanh** | Gõ `/tên-nhóm` và nhấn Enter |
| **Hoàn thành** | Di chuột vào nhiệm vụ, click nút "✓" |
| **Bỏ hoàn thành** | Trong nhóm "Hoàn thành", click nút "↶" |
| **Xóa nhiệm vụ** | Double-click vào nhiệm vụ |
| **Chỉnh sửa** | Click phải → "✏️ Chỉnh sửa nhiệm vụ" |
| **Kéo thả** | Giữ nút "☰" và kéo đến vị trí mong muốn |

### Quản lý nhóm

| Thao tác | Cách thực hiện |
|----------|----------------|
| **Tạo nhanh** | Gõ `/tên-nhóm` và nhấn Enter |
| **Tạo bằng dialog** | Click phải nút "+" → "📁 Tạo nhóm mới" |
| **Đổi tên** | Click phải tiêu đề nhóm → "✏️ Đổi tên nhóm" |
| **Xóa** | Click phải tiêu đề nhóm → "🗑️ Xóa nhóm" |
| **Thu gọn/Mở rộng** | Click icon "▼" bên trái tiêu đề |
| **Di chuyển** | Di chuột vào tiêu đề, click nút "▲▼" |

### Quản lý thời gian

| Thao tác | Cách thực hiện |
|----------|----------------|
| **Đặt deadline** | Click phải nhiệm vụ → "📅 Đặt deadline" |
| **Xóa deadline** | Click phải → "🗑️ Xóa deadline" |
| **Xem chi tiết** | Di chuột vào chỉ thị thời gian |
| **Xem timeline** | Click nút "Timeline" trên đầu trang |
| **Cấu hình thông báo** | Settings → Thông báo → Bật nhắc deadline |

### Kéo thả nhiệm vụ

- **Trong cùng nhóm:** Giữ "☰", kéo lên/xuống trong nhóm
- **Giữa các nhóm:**
  - Kéo vào danh sách nhiệm vụ → Chèn vào vị trí
  - Kéo vào tiêu đề nhóm → Thêm vào cuối nhóm
- **Hiển thị:** Vùng đích sẽ sáng màu xanh dương

### System Tray

- **Click trái:** Hiện/Ẩn cửa sổ chính
- **Click phải:** 
  - Hiện/Ẩn
  - Cài đặt
  - Thoát

---

## 🤝 Đóng góp

Chúng tôi rất hoan nghênh mọi đóng góp từ cộng đồng!

### Cách đóng góp

1. **Fork repository** này
2. **Tạo branch tính năng:** `git checkout -b feature/TenTinhNang`
3. **Commit thay đổi:** `git commit -m 'Them tinh nang XYZ'`
4. **Push lên branch:** `git push origin feature/TenTinhNang`
5. **Tạo Pull Request**

### Báo cáo lỗi

- Sử dụng [GitHub Issues](https://github.com/mrtinhnguyen/deskhive/issues)
- Mô tả chi tiết lỗi và các bước tái hiện
- Đính kèm ảnh chụp màn hình nếu có thể

---

## 📞 Liên hệ

- **Tác giả:** TinhNguyen
- **GitHub:** https://github.com/mrtinhnguyen
- **Issues:** https://github.com/mrtinhnguyen/deskhive/issues
- **Discussions:** https://github.com/mrtinhnguyen/deskhive/discussions

---

## 📄 Giấy phép

Dự án này được cấp phép theo **MIT License** - xem file [LICENSE](LICENSE) để biết thêm chi tiết.

---

## 🙏 Lời cảm ơn

- **[Tauri](https://tauri.app/)** - Framework desktop application tuyệt vời
- **[Vue.js](https://vuejs.org/)** - JavaScript framework linh hoạt
- **[Vite](https://vitejs.dev/)** - Build tool siêu nhanh
- **Cộng đồng người dùng** - Phản hồi và đóng góp quý báu

---

<div align="center">

### Made with ❤️ by TinhNguyen

**WorkDesk - Quản lý công việc thông minh, hiệu quả hơn mỗi ngày!**

⭐ **Nếu bạn thấy ứng dụng hữu ích, hãy cho chúng tôi một star nhé!** ⭐

</div>
