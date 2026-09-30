# 🎮 Dịch Phụ Đề Game

Đọc phụ đề tiếng Anh trong game và dịch sang tiếng Việt bằng AI (miễn phí), hiện chữ to, đè lên phụ đề game (Windows) và đọc bằng giọng Việt.
Có bản cho **Windows** và **macOS**.

## ⬇️ Tải app — v1.0.1
**[Bấm vào đây](https://github.com/HoangTran4869/DichPhuDeGame/releases/tag/v1.0.1)**, rồi chọn file:
- **🪟 Windows 10/11:** `DichPhuDeGame_Windows_Setup_v1.0.1.exe` (khoảng 94 MB)
- **🍎 macOS (chip Apple M1 trở lên):** `DichPhuDeGame_v1.0.1.dmg`

---

## 🆕 Có gì mới ở v1.0.1

## 🪟 Windows
### 🎯 Chữ tiếng Việt ĐÈ lên phụ đề trong game (Windows, game PC / Steam)
- Chọn nguồn **🖥 Màn hình máy tính** → bấm nút **🎯 Đè lên phụ đề**: bản dịch hiện **ngay trên phụ đề tiếng Anh**, đúng từng dòng (phụ đề 2 dòng → dịch 2 dòng), cỡ chữ bằng phụ đề gốc.
- Nền **trong suốt**, chỉ có dải **nền mờ** sau chữ Việt cho dễ đọc; chuột bấm xuyên qua, không vướng game.
- **Ctrl+Shift+H**: ẩn / hiện chữ đè bất cứ lúc nào. Hết thoại **3 giây** chữ tự tắt.
- Game cần để chế độ **Borderless / Windowed Fullscreen** (Exclusive Fullscreen không đè được).
- Ở chế độ màn hình, **đọc thoại tắt sẵn** (khỏi lẫn tiếng game). Mẹo: vào Audio của game, kéo **Dialogue/Voice Volume** về 0 để chỉ nghe giọng Việt.

### 🎙 Giọng đọc (Windows)
- **Đọc kịp thoại, không bỏ câu**: có câu chờ thì tự đọc nhanh lên; câu dài đọc nhanh ngay từ đầu.
- **Ngắt nghỉ theo dấu câu**, **cảm thán đọc to hơn** và gấp hơn, câu dài có nhanh chậm, lên xuống giọng.
- Nút đổi tên: **🔊 Đọc thoại / 🔇 Tắt đọc**.

### ⚡ Dịch nhanh và bền hơn · 🎨 Giao diện
- Dự phòng **Groq** khi Gemini chậm/quá tải; hỗ trợ **mã Gemini kiểu mới** (`AQ.`); **báo lỗi tiếng Việt dễ hiểu**.
- **Hướng dẫn 4 bước**, **đèn trạng thái**, **⚙️ Cài đặt** gọn; **Game + Sổ ghi chú** chung 1 cửa sổ; **phong cách dịch theo thể loại game**.
- Thanh nút **dàn đều, tự xuống hàng** khi thu nhỏ cửa sổ.

## 🍎 macOS
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

## 🪟 Windows — cài đặt

### Cần có
- Windows 10 hoặc 11 (64-bit)
- Tài khoản Google để lấy **mã Gemini** miễn phí; nên có thêm **mã Groq** miễn phí (app có hướng dẫn)
- Chơi PS5/console: cần **capture card** cắm vào máy tính. Game PC, YouTube, phim trên máy tính thì không cần.

### Cài đặt
1. Bấm đúp file **DichPhuDeGame_Windows_Setup_v1.0.1.exe**.
2. Nếu Windows hiện màn hình xanh **"Windows protected your PC"**: bấm **More info** → **Run anyway**.
   (Windows cảnh báo vì app chưa mua chứng chỉ, chỉ cần làm 1 lần.)
3. Bấm **Next** → **Install**, xong bấm **Finish** là app mở lên. Trên Desktop có biểu tượng app.

### Lần đầu dùng
App có **hướng dẫn 4 bước**: mã Gemini → mã Groq → nguồn hình → chọn khung.
- **🎮 Capture card (PS5, console)** hoặc **🖥 Màn hình máy tính** (game PC, YouTube, phim).
- **Chọn khung:** đợi phụ đề hiện → **⏸ Dừng hình** → kéo khung quanh phụ đề → **Enter**.
- Game PC: bấm **🎯 Đè lên phụ đề** để chữ Việt hiện ngay trong game.
- Nghe đọc tiếng Việt: bấm **🔊 Đọc thoại**. Máy chưa có giọng Việt: **Settings → Time & language → Language & region → Add a language → Vietnamese** (tick **Text-to-speech**).

---

## 🍎 macOS — cài đặt
1. Mở file **.dmg**, **kéo biểu tượng app** vào thư mục **Applications**.
2. Lần đầu mở: vào **Applications**, **chuột phải** vào app → **Mở (Open)** → bấm **Mở** lần nữa.
   Nếu vẫn không mở được: **Cài đặt hệ thống → Quyền riêng tư & Bảo mật** → bấm **Vẫn mở (Open Anyway)**.
3. Làm theo hướng dẫn 4 bước; macOS hỏi quyền **Camera** (capture card được coi như camera) → bấm **Cho phép**.

---

## 🔄 Cập nhật
Bấm **⚙️ Cài đặt → ⬆️ Cập nhật** trong app. Dữ liệu của bạn (mã, sổ ghi chú, cài đặt) được giữ nguyên.

---
App tạo bởi Hoàng Trần. Nếu thấy hữu ích, bạn có thể ủng hộ qua nút ⭐ Ủng hộ trong app. Cảm ơn bạn! 💛
