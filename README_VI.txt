HiFi Video Studio AI — PWA MVP 0.2

CÁCH ĐƯA LÊN MÀN HÌNH CHÍNH (MIỄN PHÍ)
1) Giải nén ZIP.
2) Tạo repository GitHub mới, ví dụ hifi-video-studio.
3) Upload toàn bộ nội dung bên trong thư mục HiFi_Video_Studio_AI_PWA (giữ nguyên thư mục icons).
4) Vào Settings > Pages > Build and deployment > Deploy from a branch.
5) Chọn branch main, folder /(root), nhấn Save.
6) Chờ GitHub Pages xuất URL HTTPS. Mở URL đó bằng Chrome hoặc Samsung Internet trên Samsung A17.
7) Android: menu ⋮ > Install app / Cài đặt ứng dụng hoặc Add to Home screen / Thêm vào màn hình chờ. Nếu nút Install hiện trong app, có thể nhấn nút đó.
8) Windows: mở URL bằng Chrome/Edge > biểu tượng Install trên thanh địa chỉ hoặc menu > Install HiFi Video Studio AI.

LƯU Ý
- PWA cài đặt cần được phục vụ qua HTTPS (GitHub Pages đáp ứng). Mở index.html trực tiếp từ ZIP không đủ để cài PWA đúng chuẩn.
- Offline: giao diện và các tệp ứng dụng đã cache sẽ mở được; Google/YouTube cần internet. Media được chọn vẫn được xử lý cục bộ.
- WAV PCM 16-bit: giải mã bằng Web Audio API; codec đầu vào tùy trình duyệt.
- Video: ghi canvas thành WebM ở kích thước 2K/4K theo thời gian thực nếu MediaRecorder/captureStream được hỗ trợ. Có thể không ghi âm thanh trên một số thiết bị. Video dài/4K có thể gây quá tải.
- Không tải trực tiếp video từ YouTube, không vượt DRM hoặc hạn chế tải xuống.
- ALAC/FLAC và AI super-resolution/khử nhiễu thực sự CHƯA có. Bản này không tuyên bố có các tính năng đó.
