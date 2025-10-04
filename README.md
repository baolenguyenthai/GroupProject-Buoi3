
1. Một thành viên commit sai nội dung vào README.md.
2. Thực hiện rollback bằng git reset --soft HEAD~1.
3. Commit lại nội dung đúng.
4. Thành viên khác rollback bằng git revert.
5. Lặp lại: tạo commit lỗi mới, dùng git restore để phục hồi file.

