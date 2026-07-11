# Lệnh git push

Lệnh `git push` được dùng để tải các commit từ kho chứa cục bộ (local repository) của bạn lên kho chứa từ xa (remote repository), chẳng hạn như trên GitHub, GitLab hay Bitbucket.

## Tác dụng chính
- Chia sẻ mã nguồn và những thay đổi của bạn với những người khác trong nhóm.
- Cập nhật kho chứa từ xa để nó đồng bộ với những thay đổi bạn đã thực hiện ở máy cá nhân.
- Là bước cuối cùng trong quy trình cơ bản: sửa file -> add -> commit -> push.

## Cú pháp
```bash
git push origin <tên_nhánh>
```
Đẩy lên nhánh hiện tại:
```bash
git push
```
