# 🎮 Dịch Phụ Đề Game

Đọc phụ đề tiếng Anh trong game và dịch sang tiếng Việt bằng AI (miễn phí), hiện chữ to, đè lên phụ đề game (Windows) và đọc bằng giọng Việt.
Có bản cho **Windows** và **macOS**.

## ⬇️ Tải app
- **🪟 Windows 10/11 — v1.0.1d:** [bấm vào đây](https://github.com/HoangTran4869/DichPhuDeGame/releases/tag/v1.0.1) → chọn file `DichPhuDeGame_Windows_Setup_v1.0.1d.exe` (khoảng 94 MB)
- **🍎 macOS (chip Apple M1 trở lên) — v1.0.1:** [bấm vào đây](https://github.com/HoangTran4869/DichPhuDeGame/releases/tag/v1.0.1) → chọn file `DichPhuDeGame_v1.0.1.dmg`

---

## 🆕 Có gì mới

## 🪟 Windows
### 🛠 v1.0.1d (Windows) — nhẹ máy hơn, bớt "Not responding"
- Chế độ Màn hình máy tính: chỉ chụp **đúng vùng khung phụ đề** thay vì cả màn hình (nhẹ hơn nhiều lần).
- Bộ đọc chữ không còn chiếm hết CPU → máy yếu đỡ giật, app ít bị "Not responding".
- Sửa lỗi bản 1.0.1c: xem YouTube/phim trong cửa sổ trình duyệt **không phóng to** thì app đứng ở 1 câu, không dịch tiếp.
- Không dịch nhầm cửa sổ của công cụ chụp màn hình (Win+Shift+S).
- Kiểu **Việt + Anh**: chữ tiếng Anh và tiếng Việt trên màn hình **cùng cỡ**.
- **⚙️ Cài đặt → Chữ đè** có lại **nền đen mờ** (nhìn xuyên thấy game), bên cạnh nền sáng / xám đen / đen tuyền.
- **🔊 Chỉ đọc thoại** (trước là "Đọc sub tiếng Anh"): đọc đúng ngôn ngữ của phụ đề — phụ đề Anh đọc giọng Anh, game có sẵn phụ đề **tiếng Việt** thì đọc giọng Việt (không cần dịch), vẫn ngắt nghỉ, nhấn câu cảm thán như khi dịch.

### ✨ v1.0.1c (Windows) — chữ đè đẹp hơn + chế độ Đọc sub tiếng Anh
- Chữ đè có **1 khung nền gọn, bo góc** sau cả khối chữ (kiểu Google Dịch) cho dễ đọc.
- Nút ngôn ngữ có 3 kiểu: **🇻🇳 Tiếng Việt** (bản dịch đè lên phụ đề) → **Việt + Anh** (giữ câu tiếng Anh, bản dịch màu xanh nhạt nằm ngay bên dưới) → **🇬🇧 Đọc sub tiếng Anh** (không dịch, chỉ đọc to phụ đề gốc bằng giọng tiếng Anh, không tốn lượt).
- **⚙️ Cài đặt → Chữ đè:** chọn màu khung nền sau chữ (mặc định nền sáng chữ đen; hoặc xám đen / đen tuyền) cho hợp từng game.
- Khung chữ đè làm lại (nền đặc bo góc): app **không còn đọc nhầm chữ tiếng Việt của chính nó** → hết dịch lẫn chữ, hết đứng dịch, chữ đè đúng dòng.
- Không còn dịch nhầm chữ của cửa sổ khác (Task View "Desktop 1", menu Start, File Explorer...) khi chúng nằm đè lên khung phụ đề.
- Cửa sổ app **kéo nhỏ tùy ý**: nút tự gọn lại chỉ còn biểu tượng, chữ phụ đề tự thu nhỏ vừa cửa sổ; kéo thật thấp thì chỉ còn dòng phụ đề.

### 🛠 v1.0.1b (Windows) — sửa lỗi chữ đè làm dịch đứng lại
- Sửa lỗi khi bật **🎯 Đè lên phụ đề**: app đọc nhầm chữ tiếng Việt của chính nó → câu thoại mới không được dịch, dịch ra chữ lẫn lộn.

### 🛠 v1.0.1a (Windows) — sửa lỗi capture card
- Sửa lỗi bản cài đặt **không nhận capture card** (chọn Capture card nhưng không có hình, chế độ Màn hình PC vẫn chạy).
- App tự dò đúng capture card, tự thử nhiều cách mở hình cho hợp từng loại capture card.
- Thêm nút **⚙️ Cài đặt → 🎛 Chọn thiết bị** để tự chọn đúng capture card nếu app chọn nhầm webcam / camera ảo.
- Nhật ký ghi rõ lỗi thiết bị hình (gửi file `%APPDATA%\DichPhuDeGame\nhat_ky.txt` cho tác giả khi cần hỗ trợ).

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

## 🍎 macOS (v1.0.1)
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
1. Bấm đúp file **DichPhuDeGame_Windows_Setup_v1.0.1d.exe**.
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
