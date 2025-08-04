
---

# Chatbot HTML Đơn Giản

## Mô tả
Dự án này là một giao diện chatbot cơ bản được xây dựng bằng HTML, CSS và JavaScript. Nó bao gồm:
- Khung chat với viền, header và khả năng cuộn tin nhắn.
- Ô nhập tin nhắn và nút "Gửi" (hỗ trợ gửi bằng phím Enter).
- Phản hồi tự động từ bot (logic đơn giản, ví dụ: trả lời "Chào bạn!" nếu gửi "hi" hoặc "xin chào").

Đây chỉ là phiên bản demo tĩnh, không kết nối với server hoặc AI thực tế. Bạn có thể mở rộng bằng cách tích hợp API như OpenAI để làm cho bot thông minh hơn.

## Công nghệ sử dụng
- **HTML5**: Cấu trúc giao diện.
- **CSS3**: Thiết kế khung chat, màu sắc và responsive.
- **JavaScript**: Xử lý sự kiện gửi tin nhắn và phản hồi bot.

## Hướng dẫn cài đặt
1. Tải về file `chatbot.html` từ repository (hoặc copy mã từ hướng dẫn).
2. Không cần cài đặt gì thêm – chỉ cần mở file bằng trình duyệt web (Chrome, Firefox, Edge, v.v.).

## Cách sử dụng
1. Mở file `chatbot.html` trong trình duyệt.
2. Nhập tin nhắn vào ô input ở dưới cùng.
3. Nhấn nút "Gửi" hoặc phím Enter để gửi.
4. Bot sẽ trả lời tự động dựa trên logic đơn giản (xem hàm `getBotResponse` trong mã JavaScript để chỉnh sửa).

Ví dụ:
- Gửi "hi" hoặc "xin chào" → Bot trả lời "Chào bạn! Bạn khỏe không?".
- Gửi "bye" → Bot trả lời "Tạm biệt! Hẹn gặp lại.".
- Các tin nhắn khác → Bot trả lời "Tôi không hiểu. Bạn có thể hỏi lại không?".

Chat sẽ cuộn tự động xuống dưới cùng khi có tin nhắn mới.

## Tùy chỉnh
- **Thay đổi phản hồi bot**: Chỉnh sửa hàm `getBotResponse()` trong phần `<script>` của file HTML.
- **Thêm tính năng**: Kết nối với API bên ngoài (ví dụ: fetch API để gọi server AI).
- **CSS**: Chỉnh sửa phần `<style>` để thay đổi màu sắc, kích thước khung chat.

## Lưu ý
- Dự án này chạy hoàn toàn trên client-side (trình duyệt), không cần server.
- Không lưu trữ tin nhắn (mọi thứ reset khi tải lại trang).
- Nếu bạn muốn đẩy lên GitHub, hãy tạo repository và thêm file này.

## Tác giả
- Được tạo bởi AI Assistant (dựa trên yêu cầu của bạn).
- Nếu có góp ý hoặc cần hỗ trợ, hãy liên hệ!

---

Nếu bạn cần thêm phần nào (như hình ảnh demo, license, hoặc phiên bản chi tiết hơn), hãy cho tôi biết nhé! 😊
