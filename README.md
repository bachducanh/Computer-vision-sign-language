Hướng dẫn sử dụng Git
- push code to github from local
1. git init: khởi tạo kho lưu trữ git mới
2. git remote add origin https://github.com/.....
3. git remote -v : kiểm tra đường dẫn đã remote
4. git add . : thêm tất cả thay đổi trong thư mục hiện tại
5. git commit -m "your commit": để tạo một commit với thông điệp được chỉ định ngay trong dòng lệnh.
6. git push origin master: đẩy code lên nhánh master => có thể chia ra nhiều nhánh khác nhau
- clone dự án bằng git
1. git clone https://......
- Update code sau mỗi lần sửa
1. git add .
2. git commit -m "second commit"
3. git push origin master
