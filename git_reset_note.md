# Lệnh git reset

Lệnh `git reset` là một công cụ mạnh mẽ dùng để quay ngược lại các commit trước đó hoặc hủy bỏ các file đã đưa vào staging area. Cần cẩn thận khi sử dụng lệnh này, đặc biệt là với tham số `--hard`.

## Tác dụng chính
- Gỡ bỏ các file khỏi staging area (chưa bị xóa nội dung thay đổi) để không commit chúng.
- Quay ngược con trỏ (HEAD) về một commit trước đó trong lịch sử.
- Có thể xóa vĩnh viễn các thay đổi chưa được lưu nếu dùng chế độ `--hard`.

## Cú pháp
Gỡ bỏ tất cả các file khỏi staging (nhưng giữ nguyên thay đổi trong file):
```bash
git reset
```
Quay về commit trước đó và giữ nguyên thay đổi ở working directory:
```bash
git reset --soft HEAD~1
```
Quay về commit trước đó và **xóa bỏ hoàn toàn** mọi thay đổi chưa commit:
```bash
git reset --hard HEAD~1
```
