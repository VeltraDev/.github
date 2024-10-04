# Veltra Project

## 📚 Mục lục
- [Tên dự án và chủ đề](#tên-dự-án-và-chủ-đề)
- [Công nghệ sử dụng](#công-nghệ-sử-dụng)
- [Lấy ý tưởng dự án](#lấy-ý-tưởng-dự-án)
- [Nguyên tắc làm việc](#nguyên-tắc-làm-việc)

## 🚀 Tên dự án và chủ đề
**Veltra**: Kết hợp giữa “Velocity” (tốc độ) và “Ultra” (tối đa), thể hiện đây là nền tảng website nhanh chóng và mạnh mẽ.

**Chủ đề lựa chọn**: Mạng xã hội video call, chat thời gian thực... Do đây là môn lập trình mạng, nên dự án yêu cầu thực hiện một website liên quan đến thời gian thực.

## 🛠️ Công nghệ sử dụng
- **Front-end**: React.js, Redux, Tailwind CSS, Axios, TypeScript.
- **Back-end**: Nest.js, MySQL (sử dụng TypeORM), Socket.IO, WebRTC.
- **Others**: AWS (EC2, RDS, S3), Git & GitHub, GitHub Actions (CI/CD).

## 💡 Lấy ý tưởng dự án
### Các tính năng chính:
- **Đăng ký, đăng nhập tài khoản**.
- **Chat tin nhắn thời gian thực**:
  - Tin nhắn văn bản.
  - Biểu tượng "đang gõ" hiển thị khi người dùng khác đang nhập tin nhắn.
  - Hỗ trợ Emoji.
  - Upload file: hình ảnh, PDF, Word,...
- **Thông báo đẩy (Push Notifications)**: Hiển thị avatar của người dùng lên đầu cuộc trò chuyện khi có tin nhắn mới.
- **Tìm kiếm bạn bè và cuộc trò chuyện**.
- **Gọi video call**:
  - Gọi 1-1 hoặc nhóm nhiều người.
  - Giao diện hiển thị khi có cuộc gọi đến.
- **Nhóm chat**: Tạo nhóm với khả năng quản lý thành viên, đặt tên nhóm và thay đổi hình đại diện nhóm.

### Các tính năng có thể phát triển thêm (nếu có thời gian):
- Các tính năng nâng cao khác có thể sẽ được phát triển thêm khi có thời gian và tài nguyên.

## 📏 Nguyên tắc làm việc
> ### 🟢 Commit Convention (Quy ước khi commit code lên GitHub):
> ```
> feat:     thêm một feature mới
> fix:      sửa lỗi trong hệ thống
> refactor: sửa code mà không thêm tính năng hoặc fix bug
> docs:     cập nhật hoặc thay đổi tài liệu
> chore:    thay đổi nhỏ, không liên quan đến logic code
> style:    thay đổi về giao diện, CSS/UI
> perf:     cải thiện hiệu năng xử lý
> vendor:   cập nhật phiên bản dependencies, packages
> ```

> ### 🔵 Branch Naming Conventions (Quy ước đặt tên nhánh):
> ```
> feature/: dành cho phát triển tính năng mới
> bugfix/:  dành cho sửa lỗi
> 
> Quy ước: Tên nhánh ngắn gọn, rõ ràng, không dùng ký tự đặc biệt hay viết hoa.
> Ví dụ: feature/add-friend-functionality, bugfix/chat-not-loading
> ```

### 🖼️ Cấu hình Prettier
Cấu hình Prettier để tự động định dạng code:
```json
"editor.formatOnPaste": false,
"editor.formatOnSave": true,
"editor.defaultFormatter": "esbenp.prettier-vscode",
"prettier.singleQuote": true,
"prettier.semi": true
