# Lệnh git merge

Lệnh `git merge` dùng để kết hợp (gộp) các thay đổi từ một nhánh này sang một nhánh khác. Thường được sử dụng để đưa một tính năng đã hoàn thiện vào nhánh chính.

## Tác dụng chính
- Tích hợp lịch sử commit từ nhánh đang phát triển vào nhánh chính (thường là `master` hoặc `main`).
- Git sẽ cố gắng tự động gộp các file, nếu có xung đột (conflict), bạn sẽ phải giải quyết bằng tay.
- Duy trì sự liên tục và toàn vẹn của mã nguồn sau quá trình phát triển song song.

## Cú pháp
Gộp nhánh chỉ định vào nhánh hiện tại:
```bash
git merge <tên_nhánh>
```
