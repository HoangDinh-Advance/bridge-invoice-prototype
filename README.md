# Bridge Invoice Prototype

Bản demo tương tác của cổng hóa đơn Bridge Finance, dùng hoàn toàn dữ liệu tổng hợp.

**Demo:** https://hoangdinh-advance.github.io/bridge-invoice-prototype/

Tài khoản mẫu đã điền sẵn; bấm **Đăng nhập** để trải nghiệm. Có 52 hóa đơn đầu ra và 13 hóa đơn đầu vào, tìm kiếm/lọc, chi tiết hóa đơn mẫu, bán mô phỏng, lịch sử bán và cấu hình đồng bộ. **Đặt lại demo** để thử từ đầu.

Thao tác lưu trong sessionStorage của tab, còn sau refresh và đăng xuất/đăng nhập lại. Không gọi GDT/API nghiệp vụ, không yêu cầu tài khoản thật và không tạo giao dịch thật.

## Nội dung repo

Repo chỉ chứa HTML/CSS/JavaScript đã build cho base path `/bridge-invoice-prototype`. Không có backend, env, API key, CAPTCHA solver hoặc tài liệu khách hàng. `.nojekyll` giữ nguyên thư mục `_next` khi GitHub Pages xuất bản.

GitHub Pages phục vụ nhánh `main`, thư mục gốc. Push bản tĩnh mới lên `main` để cập nhật demo. Bản build được tạo từ frontend của dự án Bridge Invoice Portal bằng `scripts/build-prototype.mjs` với `PROTOTYPE_BASE_PATH=/bridge-invoice-prototype`.

Đây là prototype trình diễn UI, không phải hệ thống tài trợ/hóa đơn chạy nghiệp vụ thực tế.
