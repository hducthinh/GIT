# Lệnh git pull

Lệnh `git pull` được sử dụng để lấy (fetch) và gộp (merge) các thay đổi từ remote repository về nhánh hiện tại trên local repository.

## Cú pháp cơ bản
```bash
git pull <remote> <tên-nhánh>
```

## Cách sử dụng phổ biến
- `git pull origin master`: Cập nhật nhánh master ở local với các thay đổi mới nhất từ nhánh master trên remote.
- `git pull --rebase`: Lấy thay đổi về và áp dụng các commit của bạn lên trên cùng (rebase) thay vì tạo ra một merge commit.
