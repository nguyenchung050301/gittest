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
## Các bước xử lý conflict:
- Git fetch: cập nhật các thay đổi.
- Git pull: lấy file về local.
- Xử lý conflict: nếu dùng vim ***-!wq***: ; hoặc sử dụng ***VS code***.
- Git add: thêm file đã chỉnh sửa vào stage.
- Git commit -m "[**message**]": thực hiện lệnh commit kèm message.
- Git push: push các thay đổi lên repository. 


# Cách tạo nhánh / checkout nhánh
- Git branch [**ten nhanh**]: tạo nhánh có tên **ten nhanh**.
- *Git branch -a để xem tất cả nhánh đang có ở local*.
- Git checkout [**ten nhanh**]: để chuyển sang nhánh **ten nhanh**.
- Git checkout -B [**ten nhanh**] *git branch **ten nhanh** + git checkout **ten nhanh***: tạo nhánh và chuyển sang nhánh.     