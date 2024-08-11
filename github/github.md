# Khái niệm Github
- Github là một nền tảng lưu trữ mã nguồn. Cho phép dễ dàng lưu trữ mã nguồn, quản lý và theo dõi cá nhân hay đội nhóm với nhau.

- Local Repository: repo được lưu trong máy tính hiện tại.
- Remote Repository: repo được lưu trên server.


# Commands
- git remote add <remote-name> <remote-url>: tạo remote repository trên local
- git push -u <remote-name> <branch-name>: thiết lập nhánh cục bộ theo dõi nhánh trên remote.
- git push <remote-name>: đẩy các thay đổi từ local lên remote.

- git push -u <remote-name> <new-branch-name>: Đẩy nhánh mới từ local lên remote.
- git fetch: cập nhật thông tin về các nhánh trên remote.
-> git branch <remote-branch-name> <remote-name>/<remote-branch-name>: lấy branch từ remote về local

