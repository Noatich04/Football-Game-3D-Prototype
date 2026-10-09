# Football Game 3D Prototype

Game bóng đá 3D chạy trên trình duyệt, lấy cảm hứng từ thể loại football simulation. Đây là dự án độc lập, không sử dụng tài sản độc quyền của FC Online.

## Chạy game
- Mở `index.html` trên trình duyệt hiện đại khi có Internet.
- Nếu trình duyệt chặn JavaScript module khi mở file trực tiếp, chạy một máy chủ tĩnh trong thư mục dự án, ví dụ:
  - Python: `python -m http.server 8000`
  - Mở `http://localhost:8000`

Thư viện Three.js được tải từ CDN nên cần Internet.

## Điều khiển
- **W A S D** hoặc phím mũi tên: di chuyển
- **Shift**: chạy nhanh
- **Giữ Space rồi thả**: lấy lực và sút
- **W A S D + E**: chuyền theo hướng đang chọn; nếu không giữ hướng, chuyền theo hướng cầu thủ đang quay mặt
- **Q**: đổi sang cầu thủ xanh gần bóng
- **Esc**: tạm dừng / tiếp tục

## Có trong prototype
- Sân bóng 3D, đường biên, vòng tròn giữa sân và hai khung thành
- Cơ chế khống chế và dẫn bóng theo cầu thủ đang giữ bóng
- AI biết chạy chỗ hỗ trợ, chuyền bóng khi bị áp sát, dâng lên tấn công và lùi về phòng thủ
- Cầu thủ phòng ngự gây áp lực lên người giữ bóng; đồng đội còn lại giữ vị trí
- Hai đội cầu thủ, AI di chuyển và tranh bóng
- Thủ môn cơ bản, va chạm cầu thủ-bóng
- Sút, chuyền, bảng tỷ số và đồng hồ trận đấu

## Giới hạn hiện tại
Đây là prototype để phát triển tiếp, chưa phải mô phỏng hoàn chỉnh như FC Online. AI chiến thuật, animation, vật lý nâng cao, menu đội hình, âm thanh và multiplayer trực tuyến có thể bổ sung ở các phiên bản sau.
