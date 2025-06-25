# Git Test
This is a test repository for learning Git commands and workflows.

# Description
Repository này được sử dụng để thực hành các lệnh Git cơ bản và nâng cao. Nó bao gồm các tệp tin mẫu và cấu trúc thư mục để giúp người dùng làm quen với việc quản lý mã nguồn.

> [!WARNING]
> Có thể trộn lẫn tiếng anh lẫn tiếng Việt do nhiều người cùng làm việc trên repo này.

# Các trường hợp cơ bản
## Cách khởi tạo một repository ở local
```bash
# Khởi tạo một repo mới
git init

# Thêm tệp tin vào staging area
git add <tên_tệp>

# Commit các thay đổi
git commit -m "Thông điệp commit"
```

## Kết nối với remote repository
```bash
# Thêm remote repository
git remote add origin <URL_của_remote_repo>

# Đẩy các thay đổi lên remote
git push -u origin main
```
