# NEMESIS-AUTO-DAILY-BOT
Swap , liqui.....
===========================================================================
🚀 HƯỚNG DẪN CÀI ĐẶT & SỬ DỤNG NEMESIS MULTI-TASK BOT
===========================================================================

1. YÊU CẦU HỆ THỐNG
- Đã cài đặt Node.js (Khuyên dùng bản LTS mới nhất).
- Máy tính có kết nối Internet ổn định.

2. CÀI ĐẶT THƯ VIỆN (DEPENDENCIES)
Mở Terminal/Command Prompt tại thư mục chứa Bot và chạy các lệnh sau:

# Khởi tạo dự án
npm init -y

# Cài đặt các thư viện cần thiết
npm install ethers@6 chalk axios https-proxy-agent socks-proxy-agent node-machine-id readline-sync

3. CẤU HÌNH QUAN TRỌNG (BẮT BUỘC)
Để Bot chạy được chuẩn Module (import/export), bạn cần:
- Mở file 'package.json' bằng Notepad hoặc VS Code.
- Thêm dòng: "type": "module", vào ngay sau dòng "main": "index.js",

4. CHUẨN BỊ CÁC FILE DỮ LIỆU
Trong thư mục Bot, hãy tạo các file văn bản (.txt) sau:

- main.js: Dán mã nguồn của Bot vào đây.
- pk.txt: Dán danh sách Private Key của các ví (Mỗi ví một dòng).
- proxy.txt: (Tùy chọn) Dán danh sách Proxy (Định dạng http://user:pass@ip:port).
- user_agents.txt: (Tùy chọn) Danh sách User-Agent để giả lập trình duyệt.

5. CÁC TÍNH NĂNG CHÍNH
- Tự động Verify License qua mã máy (HWID) bảo mật.
- Swap Token: ETH sang USDC, DAI, UNI tự động theo dải số lượng ngẫu nhiên.
- Add Liquidity: Thực hiện thêm thanh khoản để tối ưu hóa Point.
- Margin Trading: Tự động mở vị thế Long/Short x30 để lấy Volume.
- Anti-Detection: Cơ chế nghỉ (Delay) ngẫu nhiên giữa các ví và hành động.
- Proxy Support: Hỗ trợ cả Https và Socks5 giúp bảo vệ IP ví.

6. HƯỚNG DẪN CHẠY BOT
- Bước 1: Gõ lệnh 'node main.js' vào Terminal.
- Bước 2: Trong lần đầu tiên, Bot sẽ yêu cầu nhập License Key. Hãy nhập Key của bạn.
- Bước 3: Bot sẽ tự động chạy xuyên suốt cho đến khi hoàn thành tất cả ví trong danh sách.

⚠️ LƯU Ý:
- Điểm (Points) của từng ví sẽ được lưu tại file 'profiles.json'.
- Hãy đảm bảo các ví có một ít ETH mạng Sepolia để làm phí Gas.
===========================================================================

Tham Gia NHóm tele : https://t.me/HVchannelss

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 1 Tháng 4u - 15u 6thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây
