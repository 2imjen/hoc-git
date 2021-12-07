# Học Git

## Câu lệnh cơ bản
1. git init: khởi tạo git
2. git status: kiểm tra trạng thái của các thay đổi
3. git add : thêm những thay đổi để chuẩn bị commit
4. git commit -m '...': hoàn tất những thay đổi

5. git log: xem lịch sử commit, xem id-commit 
6. git diff: hiển thị nội dung thay đổi của file modified
7. git show id-commit: xem commit thay đổi gì
8. git checkout:
    1. git checkout ten-file: bỏ thay đổi trên file chưa add
    2. git checkout -b ten-branch: tạo và chuyển sang nhánh ten-branch
    3. git checkout ten-branch: chuyển sang ten-branch để làm việc
9. git reset ten-fle:
    1. git reset HEAD ten-file: chuyển file từ ***sa -> wd***
10. git branch: hiển thị tất cả các nhánh, nhánh chính là main
11. git merge: kéo những thay đổi từ branch khác vào branch nào đó
12. git branch -D ten-branch: xóa branch

13. git reset:
    1. --soft + id-commit: đưa commit về sa 
    2. --mixed + id-commit: đưa commit về wd
    3. --hard + id-commit: bỏ đi commit ***(warning)***
## Thuật ngữ (term)
- working directory: những thay đổi chưa add (file màu đỏ)
- staging area: những thay đổi đã add (file màu xanh)
- git repository
