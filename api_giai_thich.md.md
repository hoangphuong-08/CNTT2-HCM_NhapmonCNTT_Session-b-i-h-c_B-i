


> 1.  ## Tôi là ai / Bối cảnh
2.  ## Chủ  / Nội dung cần xử lý
3.  ## Yêu cầu
- Định nghĩa API là gì bằng một hình ảnh so sánh thực tế
- Định nghĩa API là gì bằng một hình ảnh so sánh thực tế
- Trình bày ngắn gọn, súc tích bằng danh sách gạch đầu dòng
4. ## Không cần
- Không giải thích chuyên sâu về các phương thức HTTP

# Giải thích thuật ngữ API

## 1. Prompt theo Công thức 3 Phần gửi AI

## Tôi là ai / Bối cảnh
Tôi là sinh viên năm nhất ngành Công nghệ Thông tin và là thành viên mới của nhóm dự án SmartCampus. Tôi chưa hiểu rõ khái niệm API trong lập trình web/mobile.

## Chủ đề / Nội dung cần xử lý
Hãy giải thích thuật ngữ API một cách đơn giản, dễ hiểu cho người mới bắt đầu.

## Yêu cầu
- Định nghĩa API là gì bằng một hình ảnh so sánh thực tế (ví dụ: bồi bàn trong nhà hàng).
- Nêu rõ vai trò của API trong ứng dụng di động SmartCampus (khi ứng dụng cần lấy lịch học từ máy chủ của trường).
- Trình bày ngắn gọn, súc tích bằng danh sách gạch đầu dòng.

## Không cần
- Không giải thích chuyên sâu về các phương thức HTTP (GET, POST, PUT, DELETE) hay mã trạng thái (200, 404).
- Không đưa ra ví dụ bằng mã nguồn (code).

---

## 2. Tóm tắt câu trả lời của AI (Đọc 3 bước & Tóm tắt trong 3 câu)
1. API (Application Programming Interface) đóng vai trò như một người trung gian hoặc bồi bàn giúp ứng dụng di động gửi yêu cầu và nhận dữ liệu từ máy chủ.
2. Trong ứng dụng SmartCampus, API nhận mã sinh viên do người dùng nhập, gửi lên hệ thống của nhà trường để lấy thông tin lịch học rồi trả kết quả về màn hình điện thoại.
3. Nhờ có API, ứng dụng có thể lấy đúng dữ liệu cần thiết mà không cần truy cập trực tiếp vào cơ sở dữ liệu gốc của trường, đảm bảo an toàn và đồng bộ thông tin.

---

## 3. Nội dung tệp tài liệu tra cứu API
- API (Application Programming Interface) là giao diện lập trình ứng dụng, đóng vai trò làm cầu nối trung gian cho phép hai phần mềm hoặc hệ thống giao tiếp và trao đổi dữ liệu với nhau.
- Ví dụ thực tế: API giống như một **người bồi bàn** nhận yêu cầu từ khách (Mobile App) chuyển xuống nhà bếp (Server) và mang kết quả quay lại.
- Vai trò trong SmartCampus: Khi sinh viên xem lịch học, thư viện **Axios** gọi API để lấy dữ liệu từ Server của nhà trường và hiển thị lên giao diện.
