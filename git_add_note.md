# Lệnh git add

Lệnh `git add` giúp bạn thêm các thay đổi từ working directory vào staging area. Đây là bước chuẩn bị để các thay đổi này được đưa vào lần commit tiếp theo.

## Tác dụng chính
- Báo cho Git biết bạn muốn theo dõi những file nào cho lần lưu lại (commit) sắp tới.
- Cho phép bạn thêm một file cụ thể, nhiều file hoặc tất cả các file đã thay đổi.
- Là bước trung gian quan trọng giữa việc chỉnh sửa file và lưu lại lịch sử bằng git commit.

## Cú pháp
Thêm một file cụ thể:
```bash
git add <tên_file>
```
Thêm tất cả các file thay đổi:
```bash
git add .
```
