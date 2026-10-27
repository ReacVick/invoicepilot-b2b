# InvoicePilot — Nhánh Nghiệp vụ Quản trị Hệ thống, Tài khoản & Cấu hình (System Administration & RBAC) (`feature/quan-tri`)

> **Kho lưu trữ:** `https://github.com/ReacVick/invoicepilot-b2b` | **Nhánh:** `feature/quan-tri`
> Nhánh này được tổ chức chuyên biệt, độc lập cho **Nghiệp vụ Quản trị Hệ thống, Tài khoản & Cấu hình (System Administration & RBAC)** phục vụ phân chia công việc theo BTL CSE122. Toàn bộ mã nguồn cốt lõi của nghiệp vụ khác đã được tinh gọn, chỉ giữ lại các màn hình, module JavaScript, CSS và dữ liệu MockAPI của đúng phân hệ này.

---

## 1. Danh sách các Tệp tin Mã nguồn của Phân hệ này
### 1.1. Các Màn hình HTML Giao diện
- [`admin-customer-management.html`](./admin-customer-management.html) : Màn hình nghiệp vụ chính
- [`admin-user-management.html`](./admin-user-management.html) : Màn hình nghiệp vụ chính
- [`admin-invoice-settings.html`](./admin-invoice-settings.html) : Màn hình nghiệp vụ chính
- [`index.html`](./index.html) : Màn hình giới thiệu tổng quan
- [`login.html`](./login.html) : Đăng nhập xác thực vai trò
- [`profile.html`](./profile.html) & [`notifications.html`](./notifications.html) : Hồ sơ cá nhân & Thông báo
- [`ui-state-loading.html`](./ui-state-loading.html), [`ui-state-empty.html`](./ui-state-empty.html), [`ui-state-error.html`](./ui-state-error.html) : 3 trạng thái mạng & tra cứu

### 1.2. Các Module JavaScript & CSS Nghiệp vụ Riêng biệt
- CSS nghiệp vụ: `assets/css/modules/admin.css`
- Các Page Controller JS:
  - `assets/js/pages/admin-customers.js`
  - `assets/js/pages/admin-users.js`
  - `assets/js/pages/admin-settings.js`
- Tích hợp các công tắc cấu hình AI hệ thống
- Tệp dữ liệu MockAPI Cloud: `mockapi-data/4-mockapi-quantri-system.json`

---

## 2. Tài liệu Nghiệp vụ Chi tiết
Xem đặc tả quy tắc nghiệp vụ, tính toán công thức, trợ lý AI và luồng xác nhận Lưu/Hủy tại:
👉 [`docs/features/quan-tri.md`](./docs/features/quan-tri.md)

---

## 3. Hướng dẫn Chạy & Kiểm thử trên Nhánh này
1. Clone hoặc chuyển sang nhánh này:
   ```bash
   git checkout feature/quan-tri
   ```
2. Mở trực tiếp màn hình khởi đầu của nghiệp vụ: [`admin-user-management.html`](./admin-user-management.html) bằng trình duyệt web hoặc Live Server trong VS Code.
3. Hệ thống sẽ tự động nhận diện và đăng nhập đúng vai trò của nghiệp vụ để demo trực tiếp.

---
© 2026 Nhóm InvoicePilot — CSE122 (Lớp 67KTPM)
