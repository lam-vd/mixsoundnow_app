# MixSoundNow

MixSoundNow là một ứng dụng được xây dựng bằng Ruby on Rails, cung cấp khả năng trộn các âm thanh và video YouTube. Ứng dụng này sử dụng Rails 7 kết hợp với Hotwire (Turbo) và Stimulus để tạo ra trải nghiệm người dùng mượt mà và tương tác thời gian thực.

## Phiên bản Ruby

Ứng dụng này được phát triển với Ruby 3.1.2 (có thể điều chỉnh theo phiên bản bạn sử dụng).

## Phụ thuộc hệ thống

- Rails 7.0 trở lên
- Node.js và Yarn (nếu không sử dụng Importmap)
- PostgreSQL (hoặc SQLite cho môi trường phát triển)
- Redis (nếu sử dụng Sidekiq cho background job)

## Cấu hình

1. Đảm bảo cài đặt Ruby và Bundler.
2. Clone repository:
   ```bash
   git clone https://github.com/lam-vd/mixsoundnow.git
   cd mixsoundnow
   ```
