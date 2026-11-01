# VideoDich AI PWA — bản 0.2

## Đây là gì?
Bộ khung Progressive Web App (PWA) tối ưu cho Android. Có thể thêm biểu tượng ngoài màn hình chính sau khi được đưa lên hosting HTTPS.

## Đã làm được
- Giao diện mobile phong cách tối chuyên nghiệp.
- Chọn video trên thiết bị và đọc thời lượng.
- Từ chối video dài hơn 15 phút.
- Chọn ngôn ngữ nguồn, kiểu giọng và bật/tắt phụ đề/lồng tiếng.
- Có manifest, service worker và biểu tượng cài đặt.

## Chưa làm được
Nút “Bắt đầu dịch video” chưa gọi dịch vụ AI. Muốn dịch và xuất video thật cần triển khai backend xử lý âm thanh/video, ASR, dịch máy, TTS và muxing. Không có backend thì PWA không thể tự làm trọn quy trình một cách ổn định trên điện thoại.

## Cách đưa lên điện thoại
1. Giải nén thư mục này.
2. Đưa toàn bộ nội dung lên hosting tĩnh có HTTPS (ví dụ Cloudflare Pages hoặc GitHub Pages).
3. Mở URL bằng Chrome Android.
4. Chọn menu ⋮ > “Cài đặt ứng dụng” hoặc “Thêm vào màn hình chính”.

Lưu ý: PWA cần được phục vụ qua HTTPS (localhost chỉ dành cho phát triển). APK native chưa được tạo trong gói này.
