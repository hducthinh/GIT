# Lệnh git checkout

Lệnh `git checkout` (và các lệnh mới như `git switch`, `git restore`) được sử dụng chủ yếu để chuyển đổi giữa các nhánh (branch) hoặc khôi phục các file về trạng thái cũ.

## Tác dụng chính
- Chuyển không gian làm việc hiện tại sang một nhánh khác đã tồn tại.
- Tạo một nhánh mới và chuyển ngay sang nhánh đó (với tham số `-b`).
- Khôi phục file về trạng thái của lần commit gần nhất (loại bỏ các thay đổi chưa được commit).

## Cú pháp
Chuyển sang một nhánh khác:
```bash
git checkout <tên_nhánh>
```
Tạo và chuyển sang nhánh mới:
```bash
git checkout -b <tên_nhánh_mới>
```
Khôi phục một file (hủy thay đổi):
```bash
git checkout -- <tên_file>
```
