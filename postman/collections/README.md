# Postman Collections

Thư mục này chứa collection dùng cho Lab 05.

- `FIT4110_lab05_iot.postman_collection.json` kiểm tra `/health`, `POST /readings` và `GET /readings/latest`.
- Environment đi kèm là `FIT4110_lab05_local.postman_environment.json`.

Khi chạy Newman, đảm bảo `baseUrl` trỏ tới `http://localhost:8000` và token khớp với `.env` cục bộ.