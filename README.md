# Phần Mềm Trắc Nghiệm Tiếng Anh 2 - READING COMPREHENSION
### Trường Cao đẳng Công nghệ Thủ Đức (TDC) - Khoa Tiếng Anh / Bộ môn Ngoại ngữ

Ứng dụng web trắc nghiệm đọc hiểu Tiếng Anh 2 (TA2) hiện đại, chuyên nghiệp, hỗ trợ đầy đủ 4 bài đọc (Passages 1 - 4) và 40 câu hỏi trắc nghiệm kèm hệ thống trích dẫn câu trong bài và dịch nghĩa giải thích chi tiết.

---

## 🌟 Tính Năng Nổi Bật

### 1. Nhận diện thương hiệu chuẩn TDC
- **Logo TDC** đặt ở góc trái phía trên cùng, bên cạnh là dòng chữ **English 2 - READING COMPREHENSION**.
- Tông màu xanh đại học và vàng kim đặc trưng của Trường Cao đẳng Công nghệ Thủ Đức.

### 2. Chế độ bảo mật đáp án chặt chẽ
- **Chỉ sau khi sinh viên hoàn tất bài thi mới kiểm tra được đáp án**:
  - Trong quá trình làm bài, hệ thống hoàn toàn ẩn đáp án đúng, không hiển thị màu xanh/đỏ hay bất kỳ gợi ý nào.
  - Sinh viên có thể tự do thay đổi đáp án, theo dõi tiến độ qua ma trận 40 câu hỏi (Question Palette).
  - Có cảnh báo nếu sinh viên còn câu chưa làm trước khi xác nhận nộp bài.

### 3. Giải thích chi tiết kèm trích dẫn và dịch nghĩa
- Sau khi nộp bài, mỗi câu hỏi sẽ mở khóa bảng giải thích:
  - 📌 **Trích dẫn từ bài đọc**: Trích chính xác câu văn chứa thông tin trả lời.
  - 💡 **Dịch nghĩa & Lời giải tiếng Việt**: Giải thích cặn kẽ vì sao đáp án đó là đúng.
  - 🔍 **Nút "Xem trong bài đọc"**: Tự động chuyển đến đoạn văn chứa câu trích dẫn và nhấp nháy phát sáng (pulse highlight) để sinh viên dễ dàng đối chiếu.

### 4. Hệ thống theo dõi số lượng sinh viên truy cập & Bảng điều khiển Giảng viên
- **Bộ đếm lượt truy cập**: Hiển thị trực tiếp ở thanh menu trên cùng theo thời gian thực.
- **Bảng điều khiển Giảng viên (Admin Dashboard)**:
  - Xem tổng lượt truy cập, số bài thi đã hoàn thành, điểm trung bình, tỷ lệ đạt (>= 5.0).
  - Bảng nhật ký sinh viên: Thời gian nộp, Mã số sinh viên (MSSV), Họ tên, Lớp, Điểm/40, Điểm hệ 10, Xếp loại.
  - **📥 Xuất file Excel (.csv)**: Một cú nhấp chuột để tải về bảng điểm chuẩn định dạng UTF-8 có dấu tiếng Việt, tiện lợi cho việc nhập điểm vào hệ thống của nhà trường.
  - Đặt lại dữ liệu với mã PIN bảo mật (Mã PIN mặc định: `1234`).

### 5. Tiện ích học tập nâng cao
- **Giao diện chia đôi màn hình (Split-Screen)**: Bài đọc bên trái, câu hỏi bên phải, cả 2 bên đều có thanh cuộn độc lập giúp sinh viên không bị trôi vị trí khi làm bài.
- **Phát âm bài đọc (Text-to-Speech)**: Nghe đọc bài văn bằng tiếng Anh chuẩn để luyện thêm kỹ năng nghe - phát âm.
- **Tùy chỉnh cỡ chữ (A- / A+)**: Phóng to, thu nhỏ cỡ chữ bài đọc giúp tránh mỏi mắt.
- **Bộ lọc câu hỏi khi xem lại**: Lọc xem riêng câu sai hoặc câu đúng để sinh viên ôn tập hiệu quả nhất.
- Tương thích 100% trên cả Máy tính bàn, Laptop, Máy tính bảng (iPad) và Điện thoại di động.

---

## 📂 Cấu Trúc Thư Mục

```
TA2-READING COMPREHENSION/
│
├── index.html            # Giao diện chính của ứng dụng
├── README.md             # Hướng dẫn sử dụng
│
├── assets/
│   └── tdc_logo.svg      # Logo vector Trường Cao đẳng Công nghệ Thủ Đức (TDC)
│
├── css/
│   └── style.css         # Kiểu dáng tùy biến, hiệu ứng highlight và thanh cuộn
│
└── js/
    ├── data.js           # Toàn bộ nội dung 4 bài đọc, 40 câu hỏi, trích dẫn và giải thích
    ├── tracker.js        # Module theo dõi lượt truy cập, lưu nhật ký điểm số & xuất Excel
    └── app.js            # Điều khiển logic làm bài thi, tính giờ, chấm điểm và xem lại
```

---

## 🚀 Hướng Dẫn Sử Dụng

### Dành cho Giảng viên:
1. **Mở trực tiếp trên máy tính**:
   - Chỉ cần nhấp đúp chuột vào file `index.html` là phần mềm sẽ mở ngay trên bất kỳ trình duyệt nào (Google Chrome, Microsoft Edge, Cốc Cốc, Firefox, Safari) mà không cần cài đặt thêm phần mềm nào.
2. **Chia sẻ cho sinh viên**:
   - Thầy/Cô có thể đưa thư mục này lên máy chủ nội bộ trường (LAN), Google Drive, hoặc tải lên các nền tảng hosting miễn phí như **GitHub Pages**, **Vercel**, **Netlify**.
3. **Theo dõi và lấy điểm**:
   - Bấm vào nút **"Thống kê"** ở góc trên bên phải màn hình để mở Bảng điều khiển.
   - Nhấn **"Xuất file Excel (.csv)"** để tải về danh sách điểm của cả lớp.

### Dành cho Sinh viên:
1. Mở bài thi và bấm nút **"Nhập Họ tên & MSSV"** ở góc trên màn hình.
2. Đọc bài văn ở khung bên trái (chọn Bài 1, 2, 3, 4 hoặc Tất cả).
3. Chọn câu trả lời trắc nghiệm (A, B, C) ở khung bên phải. Có thể bấm vào các số ở thanh ma trận 40 câu để chuyển nhanh đến câu muốn làm.
4. Sau khi hoàn thành xong, nhấn nút **"Nộp bài & Kiểm tra đáp án"**.
5. Xem điểm số và bấm **"Xem lại đáp án & Giải thích chi tiết"** để xem dẫn chứng bài đọc và dịch nghĩa từng câu.
