# Lá Chắn Rồng 3D

Game chiến thuật thời gian thực 3D chạy trên trình duyệt, viết bằng một tệp HTML duy nhất (`index.html`) với three.js.

- 7 chiến trường: Việt Nam toàn quốc, Quảng Trị, TP. Hồ Chí Minh, Phú Quốc, An Giang, Campuchia – An Giang, Nga (Moskva – Volga)
- 8 quốc gia: Việt Nam, Thái Lan, Malaysia, Campuchia, Nga, Hoa Kỳ, Trung Quốc, Pháp
- 19 binh chủng & vũ khí hiện đại: Bộ binh, Tổ chống tăng, Phòng không vác vai, Công binh, Đặc công, Bắn tỉa, Súng cối, Xe thiết giáp chở quân, Xe chiến đấu bộ binh, Xe tăng chủ lực, Pháo tự hành, Pháo phản lực, Phòng không cơ động, Drone trinh sát (scout), Drone tấn công/Kamikaze (ucav), Trực thăng vũ trang, Tiêm kích, Tàu chiến, Tàu ngầm (sub)
- Sàn Triển Lãm Khí Tài 3D Ngoài Trang Chủ: Xem trước mô hình 3D xoay 360 độ, tương tác chuột/chạm vuốt, phóng to/thu nhỏ và bảng thông số tác chiến chi tiết của toàn bộ khí tài 8 quốc gia
- Phong cách Red Alert Cốt Lõi:
  + Hệ thống Thăng cấp 3 Sao (Veterancy): Tân binh $\rightarrow$ Kỳ cựu ★ $\rightarrow$ Tinh nhuệ ★★★ (tự hồi phục máu ngoài chiến trường sau 3s, xe tăng bắn đạn plasma hạt nhân mini nổ chùm, pháo MLRS bắn chùm đạn rải thảm, hào quang vàng dưới chân)
  + Lưới điện & Cơ chế sập nguồn Blackout: thiếu điện thì trụ SAM, Tên lửa bờ và Tháp phòng thủ tắt ngắt điện hoàn toàn, radar minimap chuyển nhiễu CRT analog "RADAR OFFLINE"
  + Giọng thông báo chỉ huy EVA tiếng Việt ("Căn cứ đang bị tấn công!", "Cảnh báo mất điện!", "Đơn vị sẵn sàng!", "Thăng cấp tinh nhuệ!") và lời thoại quân sĩ hào sảng khi xuất kích
- Thao tác di chuyển & Đi tuần: Giữ Shift (PC) hoặc nút "⛓ Nối lệnh" (Mobile) để nối chuỗi chặng đi có số thứ tự; chế độ Đi tuần ("🔄 Đi tuần" / phím T) tuần tra khép kín tự đánh địch rồi đi tiếp
- Tối ưu chơi trên điện thoại: Nút "🏭 Ẩn xưởng" mở rộng chiến trường 100% toàn màn hình, thanh công cụ cảm ứng chống tràn cuộn ngang mượt mà, hỗ trợ safe area
- Bản đồ An Giang & Địa hình Chiến tranh Chân thực: Dãy Thất Sơn trùng điệp, Đại Tượng Phật Di Lặc và Tháp Chùa Vạn Linh trên Núi Cấm, Tượng đài Cá Ba Sa Châu Đốc, Cầu Cồn Tiên, Quảng trường An Phú, hố bom B-52, chiến hào zíc-zắc và boong-ke phòng ngự
- Trí tuệ nhân tạo AI 2.0: Dồn hỏa lực (Focus Fire) kết liễu mục tiêu trọng yếu, giữ cự ly giãn cách pháo binh/phòng không ngoài tầm tháp canh, điều tiết tốc độ hành quân bảo toàn đội hình
- Tàu ngầm & Cơ chế Sonar Cloaking: Tàu ngầm Kilo 636MV Lữ đoàn 189 Cam Ranh (VN), Kilo 636.3 (Nga), Virginia hạt nhân (Mỹ), Type 039A Yuan (TQ), Suffren hạt nhân (Pháp), S26T (Thái Lan), Scorpène (Malaysia), Xuồng ngầm chiến thuật (Campuchia). Tàu ngầm lặn tàng hình dưới nước, phóng ngư lôi và tên lửa diệt hạm tầm xa cực mạnh; chỉ bị lộ diện khi khai hỏa hoặc bị tàu chiến, trực thăng, drone hay tàu ngầm ta dò bằng sonar.
- Đòn chiến lược quốc gia tối tân: Tên lửa bờ Bastion-P (Oniks) của Việt Nam, Tên lửa siêu vượt âm Oreshnik của Nga, AGM-158 JASSM của Mỹ...
- Drone & vũ khí đặc trưng theo thời đại: VT-Patrol & BXL Kamikaze (VN), ZALA Lancet (Nga), MQ-9 Reaper & Gray Eagle (Mỹ), Wing Loong (Trung Quốc), nEUROn tàng hình (Pháp), KB-5E (Thái Lan), ANKA-S (Malaysia), CH-4 (Campuchia)
- Kinh tế và hậu cần: Trạm tiếp tế, Mỏ vàng và Giếng dầu đặt trên điểm tài nguyên của bản đồ, Nhà máy điện và Trụ điện cao thế (thiếu điện thì mọi thứ chậm lại)
- Công trình quân sự: Lô cốt, Trạm radar, Tên lửa phòng không tầm xa (S-300PMU1, S-400, Patriot, HQ-9B, SAMP/T…), Tên lửa bờ biển (Redut, Bastion, NMESIS, YJ-62, Exocet…)
- Quân phục theo từng nước: rằn ri (OCP, EMR, Type 07, CEN, kỹ thuật số Thái/Malaysia…), mũ đúng kiểu (mũ cối, ACH, 6B47…), cờ trên vai
- Địa hình ảnh hưởng trận đánh: đường, rừng, sườn dốc, cao điểm, sông và cầu
- Nhiều ô lưu trong `localStorage` của trình duyệt (tối đa 12 ván), chọn ván nào chơi tiếp cũng được

Đây là trò chơi giả tưởng. Tên vũ khí là tên thật, chỉ số được cân chỉnh cho dễ chơi.

## Đồ họa theo cấu hình máy

Mục **6 · Đồ họa** ở màn hình bắt đầu (hoặc nút ☰ khi đang chơi):

- **Tự động** (mặc định): đọc tên GPU, số luồng CPU, RAM, màn hình để chọn mức ban đầu, sau đó đo khung hình và hạ/nâng dần mức đồ họa và độ phân giải để giữ khoảng 60 FPS. Mức đã ổn định được nhớ cho lần sau.
- **Thấp / Vừa / Cao / Rất cao**: cố định. Mức thấp tắt bóng đổ và viền, giảm độ phân giải, mật độ và tầm nhìn cây, số hạt hiệu ứng.
- Giới hạn **60 FPS** hoặc **30 FPS** để tiết kiệm pin, máy đỡ nóng. **F2** bật/tắt bảng FPS.
- Khử răng cưa chỉ đổi được khi tải lại trang.

## Chạy thử

Mở `index.html` bằng trình duyệt có WebGL (Chrome, Edge, Firefox, Safari). Cần mạng để tải three.js và phông chữ từ CDN.

## Đưa lên GitHub Pages

Vào Settings → Pages của kho, chọn nhánh `main`, thư mục `/ (root)`. Game sẽ chạy tại `https://<tên-tài-khoản>.github.io/chientranh/`.
