# NH-M_8_TH8
Bài 1: Tìm Hiểu Thông Số IP & Lệnh Mạng (Buoi01_NHOM.docx)
Kiểm tra thông số IP:
Mở Command Prompt (CMD) trên máy tính.
Gõ lệnh ipconfig /all và điền các thông số (IP Address, Subnet Mask, Default Gateway, DNS Server) vào Bảng 1.
Trình bày lý thuyết & tính năng:
Tìm hiểu và điền chức năng của Gateway, DNS Server, DHCP vào Bảng 2.
Trình bày các loại địa chỉ IPv6 và cách biểu diễn rút gọn vào Bảng 3.
Tìm kiếm thông tin về Router và Switch (Chức năng, Ứng dụng) điền vào Bảng 4.
Sử dụng lệnh tracert:
Chạy lệnh tracert <tên_miền> trong CMD lần lượt với:
www.gmail.com
www.facebook.com
www.ctu.edu.vn
www.twitter.com
Ghi lại các nút trung gian (hops) thu được vào Bảng 5.
Bài 2: Thiết Kế & Mô Phỏng Sơ Đồ Mạng (Bai02_NHOM.pkt)
1. Thiết kế sơ đồ mạng đơn giản
Tạo thiết bị: Kéo 1 PC (Client), 1 Server (Web Server), và 1 Switch 2960 vào Workspace.
Đặt tên & Cấu hình IP:
Client: IP 192.168.1.10 | Subnet Mask 255.255.255.0
Web Server: IP 192.168.1.2 | Subnet Mask 255.255.255.0
Kết nối dây: Dùng cáp thẳng (hoặc Auto Cable) nối PC -> Switch và Switch -> Server.
2. Kiểm tra kết nối & Dịch vụ
Kiểm tra Ping: Trên Client, mở Desktop > Command Prompt, gõ ping 192.168.1.2.
Kiểm tra Web: Trên Client, mở Desktop > Web Browser, nhập URL http://192.168.1.2.
3. Mô phỏng mạng (Simulation Mode)
Đổi sang chế độ Simulation.
Chọn Edit Filters > Chỉ đánh dấu giao thức ICMP (hoặc DNS).
Dùng công cụ Add Simple PDU (P) click từ Client (nguồn) đến Web Server (đích).
Nhấn Play để xem luồng di chuyển của gói tin.
4. Thiết kế mạng đa phân đoạn (Router ISR4331)
Lắp sơ đồ mạng gồm 1 Router central (ISR4331), 3 Switches và các PC phân vào 3 dải mạng:
Room 1: 172.16.1.0/24
Room 2: 192.168.1.0/24
Web Server: 192.168.5.0/24
Cấu hình Default Gateway cho các PC và kiểm tra thông tuyến bằng ping/tracert.
 Bài 3: Giao Tiếp Trực Tuyến (Bai3_NHOM-Giao_tiep_truc_tuyen_co_ban.docx)
1. Thao tác trên Gmail
Tạo nhóm liên hệ: Tạo Contact Group và gửi thử 1 email chung cho nhóm.
Tạo Bộ lọc (Filter): Cấu hình lọc tự động các email gửi từ địa chỉ lthtran@ctu.edu.vn.
Quản lý Nhãn (Label):
Tạo nhãn mới theo cú pháp tên lớp (Ví dụ: CNTTA1_K51).
Import danh sách sinh viên từ file Danhsach_K51.csv vào nhãn vừa tạo.
2. Mạng xã hội & Tin nhắn
Facebook Page: Tạo 1 Page lớp tên Lop X... K51, sau đó cấp quyền Quản trị viên (Admin) cho 1 thành viên trong lớp.
Zalo Group: Tạo nhóm Zalo lớp, truy cập Cài đặt nhóm > Thiết lập phân quyền Chỉ Ban cán sự mới được gửi tin nhắn.
3. Hội nghị trực tuyến (Zoom / Google Meet)
Tạo một cuộc họp trực tuyến.
Thực hành thao tác duyệt/từ chối thành viên tham gia.
Chia sẻ màn hình để trình chiếu 1 file slide PowerPoint (.pptx).
