# 🎮 Dịch Phụ Đề Game

Đọc phụ đề tiếng Anh trong game và dịch sang tiếng Việt bằng AI (miễn phí), hiện chữ to và đọc bằng giọng Việt.
Có bản cho **macOS** và **Windows**.

## ⬇️ Tải app
- **🍎 macOS — v1.0.1 (mới):** [bấm vào đây](https://github.com/HoangTran4869/DichPhuDeGame/releases/tag/v1.0.1) → chọn file **DichPhuDeGame_v1.0.1.dmg** (khoảng 73 MB)
- **🪟 Windows 10/11 — v1.0.0:** [bấm vào đây](https://github.com/HoangTran4869/DichPhuDeGame/releases/tag/V1.0.0) → chọn file Setup `.exe`
  (bản Windows v1.0.1 đang hoàn thiện)

## 🆕 Có gì mới ở v1.0.1 (macOS)
### 🎙 Giọng đọc (macOS) — làm lại hoàn toàn
- Dùng bộ đọc giọng của Apple ngay trong app: **phụ đề hiện là đọc ngay**, không còn khựng chờ.
- Tự chọn giọng hay nhất trên máy (Linh Nâng cao/Enhanced); chưa có thì app hướng dẫn tải miễn phí.
- **Đọc kịp thoại, không bỏ câu nào:** có câu mới đang chờ thì tự đọc nhanh lên, bớt nghỉ để bắt kịp.
- **Ngắt nghỉ theo dấu câu** (chấm, phẩy, "...") và tự bù thời gian nghỉ nên câu không bị kéo dài.
- **Câu cảm thán đọc TO hơn**, cụm như "Trời ơi", "Chết tiệt" đọc nhanh, gấp gáp hơn.
- **Câu dài có nhanh chậm, lên xuống giọng** giống người thật: ngắt ở dấu phẩy và từ nối, nhấn "Nhưng", "Tuy nhiên"...
- Nút đổi tên: **🔊 Đọc thoại / 🔇 Tắt đọc**.

### ⚡ Dịch nhanh và bền hơn
- Thứ tự dịch: **Gemini 3.5 Flash Lite → Groq (Qwen) → Gemini 3.1 Flash Lite**. Gemini chậm hoặc quá tải thì Groq (rất nhanh, miễn phí) dịch thay.
- Thêm mục **Mã Groq** (⚙️ Cài đặt → Dự phòng), nên có 2 mã từ 2 tài khoản Groq. Hết lượt Groq thì app báo để thêm mã.
- Hỗ trợ **mã Gemini kiểu mới** (bắt đầu bằng `AQ.`), hướng dẫn lấy mã cập nhật: mỗi mã 1 dự án (project) riêng để có thêm lượt.
- Mã hỏng thì hiện bảng báo, có nút mở lại hướng dẫn lấy mã.
- **Báo lỗi bằng tiếng Việt dễ hiểu** (quá tải, hết lượt, mất mạng, mã sai...). Lỗi thì hiện câu tiếng Anh gốc thay vì im lặng.

### 🎨 Giao diện
- **Hướng dẫn 4 bước** khi mở app lần đầu (mã Gemini → mã Groq → nguồn hình → chọn khung).
- **Đèn trạng thái** to, rõ: xanh = ổn, vàng = dịch chậm, đỏ = có lỗi (rê chuột để xem lý do).
- Gom các nút ít dùng vào **⚙️ Cài đặt**; cửa sổ Cài đặt và Ủng hộ có nền màu dịu.
- **Game + Sổ ghi chú** gộp 1 cửa sổ, nút "Thêm vào <tên game>".
- **Phong cách dịch theo thể loại game:** tự động, đường phố/băng đảng, viễn tây, thần thoại/cổ trang, quân sự, hiện đại.
- Chọn khung: nhắc rõ **dừng hình trước rồi mới kéo khung**; kéo khung mượt, không giật.

---

## 🍎 macOS

### Cần có
- Máy Mac chip Apple (M1/M2/M3/M4…), macOS 12 trở lên
- Capture card cắm vào Mac (PS5 → capture card → Mac)
- Tài khoản Google để lấy **mã Gemini** miễn phí
- Nên có thêm **mã Groq** miễn phí (dịch dự phòng, rất nhanh) — app có hướng dẫn

### Cài đặt
1. Mở file **.dmg** vừa tải.
2. **Kéo biểu tượng app** vào thư mục **Applications**.
3. Lần đầu mở: vào **Applications**, **chuột phải** vào app → chọn **Mở (Open)** → bấm **Mở** lần nữa.
   (macOS cảnh báo vì app chưa đăng ký với Apple, chỉ cần làm 1 lần.)
   Nếu vẫn không mở được: vào **Cài đặt hệ thống → Quyền riêng tư & Bảo mật**, kéo xuống bấm **Vẫn mở (Open Anyway)**.

### Lần đầu dùng
App có **hướng dẫn 4 bước**:
1. Nhập **mã Gemini** (nên có 2–3 mã, mỗi mã 1 dự án riêng).
2. Nhập **mã Groq** (nên có 2 mã từ 2 tài khoản Groq). Có thể bỏ qua nhưng dịch sẽ chậm hơn khi Gemini quá tải.
3. Nguồn hình: capture card. macOS hỏi quyền **Camera** → bấm **Cho phép** (capture card được coi như camera).
4. **Chọn khung:** đợi phụ đề hiện → bấm **⏸ Dừng hình** → kéo khung quanh phụ đề → nhấn **Enter**.

💡 Giọng đọc hay nhất: tải giọng **Linh (Nâng cao / Enhanced)** miễn phí trong Cài đặt hệ thống → Trợ năng → Nội dung được đọc. App có mẹo hướng dẫn.

---

## 🪟 Windows (v1.0.0)
1. Bấm đúp file Setup `.exe`. Nếu Windows hiện **"Windows protected your PC"**: bấm **More info** → **Run anyway**.
2. Bấm **Next** → **Install** → **Finish**.
3. Nhập mã Gemini, chọn nguồn hình (capture card hoặc màn hình máy tính), kéo khung quanh phụ đề → **Enter**.

---

## 🔄 Cập nhật
Bấm **⚙️ Cài đặt → ⬆️ Cập nhật** trong app. Dữ liệu của bạn (mã, sổ ghi chú, cài đặt) được giữ nguyên.

---
App tạo bởi Hoàng Trần. Nếu thấy hữu ích, bạn có thể ủng hộ qua nút ⭐ Ủng hộ trong app. Cảm ơn bạn! 💛
