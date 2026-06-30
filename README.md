# POSM Display Dashboard

Trang web HTML tĩnh hiển thị dashboard trưng bày POSM — đọc dữ liệu từ file JSON.

## Tính năng

- 12 KPI: khách hàng mới, trưng bày, POSM, hợp đồng, FOC, doanh số, % phí trưng bày
- Bộ lọc: tháng, miền (HQ), khu vực, product line, loại trưng bày
- 6 biểu đồ Chart.js
- Bảng chi tiết: tìm kiếm, phân trang, xuất CSV

## Chạy local

```bash
python -m http.server 8080
```

Mở http://localhost:8080/posm-dashboard.html

Đặt file dữ liệu thật cùng thư mục với tên `Display raw - Copy.json` (ưu tiên) hoặc `data/display-data.json`.

## GitHub Pages

Repo này dùng `data/display-data.json` (dữ liệu mẫu đã ẩn danh) cho bản public.

Bật Pages: **Settings → Pages → Source: main branch → / (root)**.

URL: `https://phungbui2203.github.io/posm-display-dashboard/posm-dashboard.html`

## Lưu ý bảo mật

Không commit file JSON chứa tên cửa hàng, SĐT, địa chỉ thật lên repo public.
