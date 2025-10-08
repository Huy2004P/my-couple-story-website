<div align="center">

# 💫 OurStories Web – Kỷ niệm của Huy & Trí  
# 💫 OurStories Web – Memories by Huy & Trí

> 🇻🇳 *“Mỗi kỷ niệm đều là một câu chuyện. Và mỗi câu chuyện đều xứng đáng được lưu giữ thật đẹp.”*  
> 🇬🇧 *“Every memory is a story — and every story deserves to be beautifully kept.”*

---

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Huy2004P/my-couple-story-website?style=social)](https://github.com/Huy2004P/my-couple-story-website/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Huy2004P/my-couple-story-website?style=social)](https://github.com/Huy2004P/my-couple-story-website/network/members)
[![GitHub issues](https://img.shields.io/github/issues/Huy2004P/my-couple-story-website)](https://github.com/Huy2004P/my-couple-story-website/issues)

</div>

---

## 📝 Giới thiệu | Introduction

🇻🇳 **OurStories Web** là website tĩnh (HTML/CSS/JS) để lưu giữ các kỷ niệm của *Huy & Trí*: ảnh, câu chuyện, thời gian và địa điểm — tất cả được trình bày nhẹ nhàng, ấm áp, phù hợp để chia sẻ với người thương.  

🇬🇧 **OurStories Web** is a static website (HTML/CSS/JS) to preserve memories of *Huy & Trí*: photos, stories, dates, and places — presented in a gentle, cozy style for sharing with the one you cherish.

---

## ✨ Tính năng | Features

🇻🇳
- 🖼️ **Album kỷ niệm**: Lưới ảnh kèm tiêu đề, ngày tháng, địa điểm.  
- 📖 **Xem chi tiết**: Khi click, hiển thị nội dung câu chuyện và ảnh lớn.  
- 🌗 **Theme dịu mắt**: Tối/ sáng (tùy chọn).  
- 📱 **Responsive**: Hiển thị tốt trên mobile/ tablet/ desktop.  
- 🧩 **JSON dữ liệu**: Dễ cập nhật nội dung mà không cần backend.

🇬🇧
- 🖼️ **Memories Grid**: Photo gallery with title, date, and location.  
- 📖 **Detail View**: Click to read the full story with larger photos.  
- 🌗 **Comfort Theme**: Optional dark/light modes.  
- 📱 **Responsive**: Works well on mobile, tablet, and desktop.  
- 🧩 **JSON Data**: Easy content updates without a backend.

---

## 🚀 Kế hoạch phát triển | Development Goals

- ✨ **Trang quản trị (Settings/Admin)** để thêm/ sửa/ xóa kỷ niệm trực tiếp trên web.  
- ☁️ **Đồng bộ dữ liệu online**: Lưu JSON và ảnh qua GitHub Pages/Netlify/Backend nhẹ.  
- 🧭 **Timeline tương tác**: Lọc theo mốc thời gian, địa điểm, tag.  
- 💌 **Hiệu ứng cảm xúc**: Nền 3D/ tuyết/ hoa anh đào/ trái tim rơi (tùy chọn bật/tắt).  
- 🔍 **Tìm kiếm & bộ lọc**: Theo keyword, ngày, địa điểm, mood.

---

## ⚠️ Hạn chế hiện tại | Current Limitations

🇻🇳  
- Chưa thể **thêm kỷ niệm trực tiếp từ giao diện web**.  
- Dữ liệu **chỉ hiển thị từ file JSON** đã chỉnh sửa và commit trên web (GitHub) rồi tải lại.  
- **Không có backend/ đăng nhập**, mọi nội dung hiển thị là công khai (nếu deploy công khai).

🇬🇧  
- **No in-browser create/edit** yet; stories are **read-only** from a JSON file.  
- Content must be **manually edited and committed** to JSON on the web (GitHub) and then reloaded.  
- **No backend/auth**: all displayed content is public when deployed publicly.

---

**Gợi ý chỉnh sửa nhanh | Quick Edits**
- Nội dung: `/data/stories.json`  
- CSS chủ đạo: `/assets/css/style.css`  
- Script tải & render JSON: `/assets/js/app.js`  
- Ảnh: `/assets/images/stories/…` (đặt tên không dấu, không khoảng trắng)

---

## 🧭 Tùy biến nội dung | How to Customize

- **Thêm kỷ niệm**: Bổ sung một object mới vào `stories.json` (title, date, location, photos[], content).  
- **Ảnh**: Tải ảnh vào `/assets/images/stories/` và tham chiếu đúng đường dẫn trong JSON.  
- **Giao diện**: Điều chỉnh màu/ font/ layout trong `style.css`.  
- **Hiệu ứng**: Bật/ tắt animation nền (tuyết/ hoa/ tim) trong `app.js` bằng cờ cấu hình.

---

## 📸 Ảnh minh hoạ | Screenshots

> *(Thêm ảnh thực tế của web vào thư mục `/screenshots` và hiển thị ở đây)*

| Trang chủ | Chi tiết |
|----------|----------|
| ![Home](screenshots/home.png) | ![Detail](screenshots/detail.png) |

---

## 🔗 Triển khai | Deployment

- **GitHub Pages**: Phù hợp site tĩnh, dễ chia sẻ link.  
- **Netlify/ Vercel**: Kéo-thả, build tự động từ Git, custom domain tiện lợi.  
- **Hosting tùy chọn**: Bất kỳ dịch vụ tĩnh nào (Nginx/ Apache/ S3…).

> *Mẹo:* Đặt `stories.json` cùng repo để cập nhật nội dung nhanh qua trình duyệt (chỉnh file → commit → web tự cập nhật nếu bật build tự động).

---

## 💌 Lời nhắn | Personal Message

🇻🇳  
Website này được mình làm bằng những điều dịu nhẹ nhất dành cho **Trí**.  
Hy vọng mỗi lần mở trang, tụi mình sẽ nhớ lại những khoảnh khắc đẹp nhất của nhau 🌿

🇬🇧  
This website is built with the gentlest feelings for **Trí**.  
I hope every visit brings back our brightest moments 🌿

---

## 📎 Tham khảo | References

- [MDN Web Docs (HTML/CSS/JS)](https://developer.mozilla.org)  
- [Web.dev Guides](https://web.dev/)

---

<div align="center">

💖 *Made with HTML/CSS/JS & love by Huy* 💖

</div>
