# Lệnh git branch

Lệnh `git branch` được sử dụng để làm việc với các nhánh (branch) trong Git. Nhánh giúp bạn cô lập công việc phát triển để không ảnh hưởng đến phiên bản mã nguồn chính.

## Tác dụng chính
- Liệt kê các nhánh hiện có trong repository của bạn.
- Tạo một nhánh mới để phát triển một tính năng hoặc sửa lỗi một cách độc lập.
- Xóa các nhánh đã hoàn thành hoặc không còn cần thiết.

## Cú pháp
Xem danh sách nhánh:
```bash
git branch
```
Tạo nhánh mới:
```bash
git branch <tên_nhánh>
```
Xóa nhánh:
```bash
git branch -d <tên_nhánh>
```
