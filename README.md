# Portfolio — Phan Quốc Chiến

Website tĩnh song ngữ Việt/Anh. Cấu trúc thư mục:

- `index.html`: nội dung và giao diện website.
- `assets/portrait.jpg`: ảnh chân dung.
- `assets/og.jpg`: ảnh xem trước khi chia sẻ liên kết.
- `assets/photos/`: ảnh giải thưởng, ảnh đội, ảnh thiết bị ReTrack, ảnh hội nghị ICHST.
- `assets/awards/bk-ecogreen-2024.svg`: hình minh họa cho giải BK EcoGreen 2024 (chưa có ảnh chụp).
- `index.backup.html`: bản cũ trước khi làm lại giao diện (có thể xoá).

Hiệu ứng dùng GSAP + ScrollTrigger và Lenis (tải từ CDN), nên cần có mạng khi xem. Nếu CDN lỗi hoặc máy bật chế độ giảm chuyển động, trang vẫn hiển thị đầy đủ nội dung, chỉ không có hiệu ứng.

## Xem trên máy

Mở `index.html` bằng trình duyệt. Giữ nguyên thư mục `assets` cạnh file HTML để ảnh hiển thị. Không cần upload thư mục `ảnh` (đã được sao chép sang `assets/photos`).

## Public miễn phí bằng Netlify Drop

1. Giải nén file ZIP của portfolio nếu bạn đang dùng gói ZIP.
2. Mở [Netlify Drop](https://app.netlify.com/drop) và đăng nhập.
3. Kéo **cả thư mục đã giải nén** (có `index.html` và `assets`) vào trang.
4. Netlify cấp cho bạn một đường dẫn public. Trong phần quản lý site, bạn có thể đổi tên đường dẫn.
5. Khi cập nhật, kéo lại thư mục đã cập nhật để xuất bản bản mới.

## Trước khi public

- Xác nhận email liên hệ và tên chính thức của các giải thưởng.
- Bổ sung tên robot, cuộc thi, vai trò và kết quả cụ thể nếu muốn đưa vào portfolio.
- Bổ sung liên kết LinkedIn, GitHub hoặc demo dự án nếu có.
- Cập nhật URL đầy đủ của `assets/og.jpg` trong thẻ `og:image` sau khi đã có địa chỉ public, để ảnh xem trước hiện đúng khi chia sẻ.
