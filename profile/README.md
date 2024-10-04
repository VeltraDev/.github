# <span style="color:red;">🚀 Veltra Project</span>

## <span style="color:red;">📚 Mục lục</span>
- [<span style="color:red;">Tên dự án và chủ đề</span>](#tên-dự-án-và-chủ-đề)
- [<span style="color:red;">Công nghệ sử dụng</span>](#công-nghệ-sử-dụng)
- [<span style="color:red;">Lấy ý tưởng dự án</span>](#lấy-ý-tưởng-dự-án)
- [<span style="color:red;">Nguyên tắc làm việc</span>](#nguyên-tắc-làm-việc)

## <span id="tên-dự-án-và-chủ-đề" style="color:red;">🚀 Tên dự án và chủ đề</span>
**Veltra**: Kết hợp giữa “Velocity” (tốc độ) và “Ultra” (tối đa), thể hiện đây là nền tảng website nhanh chóng và mạnh mẽ.

**Chủ đề lựa chọn**: Mạng xã hội video call, chat thời gian thực... Do đây là môn lập trình mạng, nên dự án yêu cầu thực hiện một website liên quan đến thời gian thực.

## <span id="công-nghệ-sử-dụng" style="color:red;">🛠️ Công nghệ sử dụng</span>
- **Front-end**: React.js, Redux, Tailwind CSS, Axios, TypeScript.
- **Back-end**: Nest.js, MySQL (sử dụng TypeORM), Socket.IO, WebRTC.
- **Others**: AWS (EC2, RDS, S3), Git & GitHub, GitHub Actions (CI/CD).

## <span id="lấy-ý-tưởng-dự-án" style="color:red;">💡 Lấy ý tưởng dự án</span>
### <span style="color:blue;">Các tính năng chính:</span>
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

### <span style="color:blue;">Các tính năng có thể phát triển thêm (nếu có thời gian):</span>
- Các tính năng nâng cao khác có thể sẽ được phát triển thêm khi có thời gian và tài nguyên.

## <span id="nguyên-tắc-làm-việc" style="color:red;">📏 Nguyên tắc làm việc</span>

> ### <span style="color:blue;">🟢 Commit Convention (Quy ước khi commit code lên GitHub):</span>
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

> ### <span style="color:blue;">🔵 Branch Naming Conventions (Quy ước đặt tên nhánh):</span>
> ```
> feature/: dành cho phát triển tính năng mới
> bugfix/:  dành cho sửa lỗi
> 
> Quy ước: Tên nhánh ngắn gọn, rõ ràng, không dùng ký tự đặc biệt hay viết hoa.
> Ví dụ: feature/add-friend-functionality, bugfix/chat-not-loading
> ```

### <span style="color:blue;">🖼️ Cấu hình Prettier</span>
Cấu hình Prettier để tự động định dạng code:
```json
"editor.formatOnPaste": false,
"editor.formatOnSave": true,
"editor.defaultFormatter": "esbenp.prettier-vscode",
"prettier.singleQuote": true,
"prettier.semi": true
