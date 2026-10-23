# Đồ Án Quản Trị Hệ Thống - Đề 19: Website Tin Tức / Cổng Thông Tin

## 1. Kiến trúc hệ sinh thái
- **Web App**: WordPress (Website tin tức, quản lý bài viết, danh mục).
- **Cơ sở dữ liệu & Quản trị**: MySQL 8.0 + phpMyAdmin.
- **Reverse Proxy**: Nginx SSL (HTTPS tự ký) kèm Security Headers.
- **Giám sát (Monitoring)**: Prometheus + Grafana + cAdvisor + MySQL Exporter + Nginx Exporter.
- **Hệ thống ghi log tập trung (Logging)**: Grafana Loki + Promtail (truy vấn LogQL).

## 2. Hướng dẫn khởi chạy
```bash
docker compose up -d
