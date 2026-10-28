# Hướng dẫn quản trị Thiện Thệ Phật Điển Tùng Thư

## Địa chỉ
- Website: https://241814010103-cyber.github.io/thienthephatdien/
- Trang quản trị: https://241814010103-cyber.github.io/thienthephatdien/admin.html
- Mã nguồn: https://github.com/241814010103-cyber/thienthephatdien

## Thiết lập quyền quản trị
Trang quản trị là giao diện tĩnh; nó không giữ mật khẩu hay token. Để chỉnh sửa, mở GitHub > Settings > Developer settings > Personal access tokens > Fine-grained tokens. Chọn chủ sở hữu tài khoản, repository **thienthephatdien** và quyền repository **Contents: Read and write**. Hãy chọn ngày hết hạn ngắn, giữ bí mật token, không dán token vào bài viết hoặc commit. Token chỉ được giữ trong bộ nhớ của tab quản trị, mất khi đóng/tải lại trang.

## Đăng bài
1. Mở admin.html, dán token vào ô kết nối.
2. Chọn Bài mới; nhập nhan đề, tác giả, chuyên mục, tóm tắt và toàn văn.
3. Có thể chọn một tệp PDF dưới 10 MB. Tệp PDF sẽ được tải vào thư mục tailieu; bài viết sẽ được gắn đường dẫn tự động.
4. Chọn Xem trước, sau đó Lưu và công bố bài. Mỗi lần lưu tạo một commit vào nhánh main. GitHub Actions sẽ xuất bản lại trang tự động.

## Sửa bài và bố cục
- Ở Danh mục bài viết, nhấn Sửa.
- Ở khối Chỉnh bố cục, cập nhật tên, phụ đề, bìa, giới thiệu, liên hệ và màu giao diện.
- Nhấn Lưu giao diện để công bố thay đổi.
- Có thể xem lại và phục hồi các phiên bản cũ trong lịch sử GitHub commits.

## Lưu ý
- Không cần đóng phí hosting. Giới hạn sử dụng của GitHub Pages và GitHub API vẫn áp dụng.
- Trang quản trị là đường dẫn công khai nhưng chỉ người có GitHub token đủ quyền mới ghi dữ liệu; tuyệt đối không chia sẻ token.
- Không đưa bản thảo chưa công bố, dữ liệu riêng tư hay tệp mật lên repository Public.
- Nội dung mới lưu lên GitHub sẽ chỉ xuất hiện trên website sau khi GitHub Pages triển khai thành công.
- Để xuất bản với tên miền ngắn hơn, cần cấu hình hostname trong GitHub Pages và xác minh quyền sở hữu tên miền. Thay đổi tên repository đơn thuần không rút ngắn được URL.
