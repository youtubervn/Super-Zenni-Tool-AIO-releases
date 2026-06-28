<div align="center">

# 🎬 Super Zenni AIO Tool

### Bộ công cụ video All-in-One cho Streamer & Reup

**Livestream 24/7 · Render · Cắt / Ghép / Lặp · Intro-Outro-Logo · Phông xanh**

[![Download](https://img.shields.io/badge/⬇️_Tải_về-Bản_mới_nhất-22c55e?style=for-the-badge)](https://github.com/youtubervn/Super-Zenni-Tool-AIO-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Windows_·_macOS_·_Linux-0ea5e9?style=for-the-badge)](#-tải-về)
[![Website](https://img.shields.io/badge/🌐_viennv.dev-1e293b?style=for-the-badge)](https://viennv.dev)

</div>

---

**Super Zenni AIO Tool** gói gọn mọi thứ một streamer / reup cần vào **một ứng dụng desktop duy nhất**: phát trực tiếp nhiều luồng 24/7, xử lý video hàng loạt (render, cắt, ghép, lặp), chèn intro/outro/logo, ghép phông xanh — và **tự động cập nhật**.

> ⚡ Dùng FFmpeg & yt-dlp, **tự tải về khi mở lần đầu** — không cần cài đặt gì thêm.
> 🖥️ Chạy trên **Windows, macOS (Apple Silicon + Intel), và Linux**.

---

## 📥 Tải về

> 👉 Luôn lấy bản mới nhất tại trang **[Releases](https://github.com/youtubervn/Super-Zenni-Tool-AIO-releases/releases/latest)**.

| Hệ điều hành | File tải | Ghi chú |
| --- | --- | --- |
| 🪟 **Windows** (64-bit) | `Super-Zenni-AIO-Tool-windows-amd64.exe` | Tải về và chạy trực tiếp |
| 🍎 **macOS** (Apple Silicon + Intel) | `Super-Zenni-AIO-Tool-macos-universal.zip` | Giải nén → kéo vào Applications |
| 🐧 **Linux / Ubuntu** (64-bit) | `Super-Zenni-AIO-Tool-linux-amd64.tar.gz` | Giải nén → cấp quyền chạy |

### Hướng dẫn cài nhanh

<details>
<summary><b>🪟 Windows</b></summary>

1. Tải file `.exe` ở bảng trên.
2. Chạy file. Nếu Windows SmartScreen cảnh báo → **More info → Run anyway**.
3. Lần đầu mở, app tự tải FFmpeg/yt-dlp (chờ một chút).
</details>

<details>
<summary><b>🍎 macOS</b></summary>

1. Tải file `.zip`, bấm đúp để giải nén.
2. Kéo **Super Zenni AIO Tool.app** vào thư mục **Applications**.
3. Lần đầu mở: chuột phải vào app → **Open** → **Open** (để qua Gatekeeper).
4. App tự tải FFmpeg/yt-dlp khi chạy lần đầu.
</details>

<details>
<summary><b>🐧 Linux / Ubuntu</b></summary>

```bash
tar -xzf Super-Zenni-AIO-Tool-linux-amd64.tar.gz
chmod +x Super-Zenni-AIO-Tool-*
./Super-Zenni-AIO-Tool-*
```
Cần thư viện hệ thống `libgtk-3` và `libwebkit2gtk-4.0` (đa số bản Ubuntu đã có sẵn).
</details>

---

## ✨ Tính năng

### 📡 Phát trực tiếp (Livestream)
| Công cụ | Mô tả |
| --- | --- |
| **Super Live Stream** | Phát nhiều video tới RTMP (YouTube / Facebook / TikTok / server riêng). Quản lý **nhiều luồng cùng lúc**, theo dõi **FPS / bitrate / tốc độ** trực tiếp. Playlist, phát ngẫu nhiên, lặp vô hạn, **hẹn giờ** bật/tắt. Video lỗi **tự bỏ qua** để luồng không sập — lý tưởng cho **24/7**. |
| **Basic Live Stream** | Tạo **script độc lập** (`.bat`/`.sh`) chạy trong cửa sổ console riêng, log có thời gian, luôn hiển thị kể cả khi lỗi. Quản lý / chạy lại / xoá script. |

### 🎬 Xử lý video (hàng loạt)
| Công cụ | Mô tả |
| --- | --- |
| **Render H264 / H265** | Chuyển mã hàng loạt, preset độ phân giải / bitrate / fps, tăng tốc **GPU (NVENC)**. |
| **Split Video** | Cắt video dài thành nhiều phần theo thời gian (nhanh hoặc chính xác). |
| **Trim Video** | Cắt bỏ số giây ở đầu/cuối, theo lô. |
| **Loop Video** | Lặp video theo số lần hoặc tới thời lượng mục tiêu. |
| **Concat Videos** | Nối nhiều clip thành một, tự chuẩn hoá khi khác định dạng. |

### 🎨 Thương hiệu & ghép hình
| Công cụ | Mô tả |
| --- | --- |
| **Intro / Outro / Logo** | Ghép intro/outro và chèn logo watermark, có xem trước trực tiếp. |
| **Add Green Screen** | Ghép phông xanh lên video nền, tự dò màu key, clip phông tự lặp khớp độ dài. |

### 🧭 Tiện ích
- 📖 **Hướng dẫn trong app** — mỗi công cụ có nút `?` kèm giới thiệu, các bước dùng, bảng tham số và sơ đồ minh hoạ (**song ngữ Anh / Việt**).
- 🔄 **Tự động cập nhật** — app báo khi có bản mới, tải về kèm thanh tiến trình, rồi tự cài và mở lại (Windows/Linux) hoặc hướng dẫn cài (macOS).
- 🔒 **An toàn** — không lưu mật khẩu trần (dùng keychain hệ điều hành), kiểm tra checksum file tải về.

---

## 🔄 Cập nhật

Ứng dụng **tự kiểm tra bản mới khi mở** và hiển thị thông báo. Bạn cũng có thể bấm **"Kiểm tra cập nhật"** ở cuối thanh bên trái bất cứ lúc nào.

- **Windows / Linux:** tải và cài tự động, sau đó mở lại app.
- **macOS:** tải bản mới về máy rồi hiện hướng dẫn cài thủ công (kéo vào Applications).

---

## ❓ Câu hỏi thường gặp

<details>
<summary><b>App có cần cài FFmpeg trước không?</b></summary>
Không. App tự tải FFmpeg và yt-dlp vào thư mục <code>data/</code> cạnh ứng dụng khi chạy lần đầu.
</details>

<details>
<summary><b>Windows báo "Windows protected your PC"?</b></summary>
Đây là cảnh báo SmartScreen với ứng dụng mới. Bấm <b>More info → Run anyway</b>.
</details>

<details>
<summary><b>macOS báo "không mở được vì nhà phát triển chưa xác minh"?</b></summary>
Chuột phải vào app → <b>Open</b> → <b>Open</b>. Chỉ cần làm một lần.
</details>

<details>
<summary><b>Dữ liệu / cấu hình lưu ở đâu?</b></summary>
Trong thư mục <code>data/</code> cạnh ứng dụng: binary dùng chung ở <code>data/bin</code>, mỗi công cụ có thư mục riêng.
</details>

---

## 💬 Hỗ trợ

<div align="center">

[![Website](https://img.shields.io/badge/🌐_Website-viennv.dev-0ea5e9?style=flat-square)](https://viennv.dev)
[![Register](https://img.shields.io/badge/📝_Đăng_ký-panel.viennv.dev-22c55e?style=flat-square)](https://panel.viennv.dev/register)
[![Facebook](https://img.shields.io/badge/Facebook-viennv.tools-1877f2?style=flat-square&logo=facebook&logoColor=white)](https://www.facebook.com/viennv.tools)
[![Telegram](https://img.shields.io/badge/Telegram-viennv__web-26a5e4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/viennv_web)
[![YouTube](https://img.shields.io/badge/YouTube-Hướng_dẫn-ff0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/playlist?list=PLl-NYjxiUSc2CQV6jIHictnZ7jY9P2PZ6)

</div>

<div align="center">
<sub>© 2026 viennv.dev · Made with ❤️ for streamers & re-uploaders</sub>
</div>
