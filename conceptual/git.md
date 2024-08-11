# Khái niệm Git
- Git là một Version Control (Kiểm soát phiên bản) là hệ thống ghi chú lại tất cả hoạt động dự án của chúng ta.
- Tương tự như một game Offline, và Git như một công cụ quản lý save game.
- git init: Bắt đầu trò chơi mới.
- git add & git commit: Quyết định lưu game khi cảm thấy an toàn, hay muốn backup.
- git checkout: Để tải lại game từ một file save trước đó.
- git branch: Tạo nhiều file save trong game để thử nghiệm nhiều kết quả khác nhau.
- git merge: Nếu thấy một item ngon hay phần chơi oke muốn kết hợp với một file save cũng tốt thì git merge để kết hợp 2 thứ đó.

- Lệnh setup config Git:
        + git config user.name: Xem username hiện tại.
        + git config user.email: Xem email user hiện tại.
        + git config user.name <username>: Nhập mới hay thay đổi username.
        + git config user.email <email>: Nhập mới hay thay đổi email.


# Terms
- Repository (Repo): Repo là một kho lưu trữ dự án của chúng ta, nó được xem như một thư mục.
- Branch: Giúp chúng ta tạo nhánh mới cho phép phát triển tính năng, sửa lỗi hoặc thử nghiệm mà không ảnh hưởng đến mã nguồn chính.
- Conflict: Xung đột trong Git xảy ra khi Git không thể tự động kết hợp các thay đổi từ hai hoặc nhiều nhánh khác nhau.

# Commands
- git init: Biến dự án chúng ta thành một Git repository.
- git status: Cho thấy trạng thái dự án, thấy các thay đổi trong dự án.
- git add <file>: Chuẩn bị lưu lại thời điểm hiện tại của dự án.
- git reset <file>: Khi đổi ý, muốn lấy lại file để sửa đổi.
- git commit -m "<message>": Lưu các file đã chuẩn bị lên repo.
- git log & git log --oneline: Xem lịch sử commit.
- git checkout <commit-id>: Quay lại trạng thái có id commit trên.
- git checkout <branch-name>: Quay lại thời điểm hiện tại.
- git branch: Coi danh sách các branch.
- git branch <new-branch-name> & git checkout -b <new-branch-name>: Tạo mới một branch trên local.
- git branch -m <new-branch-name>: Đổi tên branch hiện tại.
- git branch -d <branch-name>: Xóa một branch trên local.
- git push -u <remote-name> <new-branch-name>: Đẩy nhánh mới từ local lên remote.
- git branch <remote-branch-name> <remote-name>/<remote-branch-name>: lấy branch từ remote về local
- git push <remote-name> --delete <branch-name>: Xóa branch trên remote.
- git merge <branch-name>: Kết hợp hoặc thay đổi một branch khác với branch hiện tại.

