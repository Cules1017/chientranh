# Lá Chắn Rồng 3D

Game chiến thuật thời gian thực 3D chạy trên trình duyệt, viết bằng một tệp HTML duy nhất (`index.html`) với three.js.

- 7 chiến trường: Việt Nam toàn quốc, Quảng Trị, TP. Hồ Chí Minh, Phú Quốc, An Giang, Campuchia – An Giang, Nga (Moskva – Volga)
- 8 quốc gia: Việt Nam, Thái Lan, Malaysia, Campuchia, Nga, Hoa Kỳ, Trung Quốc, Pháp
- 19 binh chủng & vũ khí hiện đại: Bộ binh, Tổ chống tăng, Phòng không vác vai, Công binh, Đặc công, Bắn tỉa, Súng cối, Xe thiết giáp chở quân, Xe chiến đấu bộ binh, Xe tăng chủ lực, Pháo tự hành, Pháo phản lực, Phòng không cơ động, Drone trinh sát (scout), Drone tấn công/Kamikaze (ucav), Trực thăng vũ trang, Tiêm kích, Tàu chiến, Tàu ngầm (sub)
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
