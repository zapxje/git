# Khái niệm Git
- Git là một Version Control (Kiểm soát phiên bản) là hệ thông ghi chú lại tất cả hoạt động dự án của chúng ta.
- Tương tự như một game Offlice, và git như một công cụ quản lí save game.
- Git init: Bắt đầu trò chơi mới.
- Git add & git commit: Quyết định lưu game khi cảm thấy an toàn, hay muốn backup.
- Git checkout: Để tải lại game từ một file save trước đó.
- Git branch: Tạo nhiều file save trong game để thử nghiệm nhiều kết quả khác nhau.
- Git merge: Nếu thấy một item ngon hay phần chơi oke muốn kết hợp với một file save cũng tốt thì git merge để kết hợp 2 thứ đó.

- Lệnh setup config Git: + "git config user.name": xem username hiện tại
                         + "git config user.email": xem email user hiện tại
                         + "git config user.name username": nhập mới hay thay đổi username
                         + "git config user.email": nhập mới hay thay đổi email


# Terms
- Repository (Repo): repo là một kho lưu trữ dự án của chúng ta, nó được xem như một thư mục.

- Branch: giúp chúng ra tạo nhánh mới cho phép phát triển tính năng, sửa lỗi hoặc thử nghiệm mà không ảnh hưởng đến mã nguồn chính.

- Conflict: xung đột trong Git xảy ra khi Git không thể tự động kết hợp các thay đổi từ hai hoặc nhiều nhánh khác nhau.
- Local & Remote

# Commands
- "git init": biến dự án chúng ta thành một git repository.
- "git status": cho thấy trạng thái dự án, thấy các thay đổi trong dự án.
- "git add": chuẩn bị lưu lại thời điểm hiện tại của dự án.
- "git reset": khi đổi ý, muốn lấy lại file để sửa đổi.
- "git commit": lưu cái các file đã chuẩn bị lên repo.

- "git log" & "git log --oneline": xem lịch sử commit.
- "git checkout" + {id commit}: quay lại trạng thái có id commit trên.
- "git checkout" + {branch name}: quay lại thời điểm hiện tại.

- "git branch": coi danh sách các branch.
- "git checkout -b" + {new branch name}: tạo mới một branch.
- "git branch -d" + {branch name}: xóa một branch.
- "git push origin --delete" + {branch name}: xóa branch trên remote.

- "git merge" + {branch name}: kết hợp hoặc thay đổi một branch khác với branch hiện tại.

- "git branch -m" + {new branch name}: đổi tên branch hiện tại.