# Mở Quán — App lập kế hoạch theo vốn đầu tư

Website tĩnh bằng HTML, CSS và JavaScript. Người dùng nhập số vốn và được chuyển vào một trong bốn mẫu: xe trà, Cafe & Tea mang đi, Cafe & Tea ngồi lại, hoặc đồ uống online. Mỗi mẫu có bảng vốn đầu tư, hòa vốn, menu, địa điểm và lộ trình. Các tỷ lệ phân bổ và số liệu mặc định chỉ là giả định minh họa có thể chỉnh sửa.

## Đưa lên GitHub Pages

1. Tạo một repository mới trên GitHub. Giải nén gói này và đưa **toàn bộ file trong thư mục** lên thư mục gốc của nhánh `main`. `index.html`, `style.css` và `app.js` cần nằm cùng cấp.
2. Trong repository, vào **Settings → Pages**. Ở **Build and deployment**, chọn **Deploy from a branch**; chọn nhánh `main` và thư mục `/(root)`; bấm **Save**.
3. Khi GitHub Pages hoàn tất, mở địa chỉ được hiển thị trong mục Pages để kiểm tra. Có thể dùng đường dẫn này để chia sẻ.

Hướng dẫn chính thức: [GitHub Pages — cấu hình nguồn xuất bản](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Trạng thái form

Form đăng ký đang ở chế độ **xem trước**. App hiển thị thông tin người đăng ký và toàn bộ kế hoạch được gửi kèm, nhưng chưa gửi hay lưu dữ liệu lên máy chủ. Khi hệ thống nhận đăng ký của bạn sẵn sàng, kết nối phần gửi form trong `app.js` với hệ thống đó trước khi dùng để thu khách hàng tiềm năng. Nội dung khóa học hiện là ví dụ theo bốn mô hình, cần thay bằng thông tin khóa học chính thức trước khi dùng để bán hàng.

Không cần cài đặt thư viện hoặc chạy lệnh build. Có thể mở `index.html` trực tiếp để xem thử.
