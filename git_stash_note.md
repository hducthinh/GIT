# Lệnh git stash

Lệnh `git stash` được sử dụng để "cất tạm" những thay đổi đang làm dở nhưng chưa muốn commit. Nó rất hữu ích khi bạn đang làm việc trên một nhánh nhưng cần chuyển sang nhánh khác gấp để sửa lỗi mà không muốn commit code chưa hoàn thiện.

## Tác dụng chính
- Lưu trữ tạm thời các thay đổi chưa được commit (bao gồm cả staged và unstaged).
- Giúp dọn dẹp working directory để bạn có thể chuyển nhánh an toàn.
- Có thể lấy lại các thay đổi đã cất tạm bất cứ lúc nào.

## Cú pháp
Cất tạm các thay đổi:
```bash
git stash
```
Xem danh sách các lần cất tạm:
```bash
git stash list
```
Lấy lại các thay đổi đã cất tạm và xóa khỏi danh sách stash:
```bash
git stash pop
```
