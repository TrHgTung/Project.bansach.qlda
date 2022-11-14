admin admintest mk: admin
guest: tungdeeptry - mk: abc123

Src gốc: https://drive.google.com/file/d/1wlSw1iJSLCBukMYgvmG2Cu6wIl2eW9dT/view

- Bắt buộc: đổi tên thư mục chứa toàn bộ source code thành `Project` (rename từ `Project.bansach.qlda-master`)

Nếu vẫn không chạy được do lỗi địa chỉ localhost:

  - Mở cả folder chứa src code bằng VS Code
  - Nhấn Ctrl + Shift + H:
    + Find: (nhập) http://localhost:8080/
    + Replace: (nhập) http://localhost/
    + Nhấn nút Replace All
    --> Mục đích: thay đổi địa chỉ localhost mà XAMPP đang chiếm, đổi từ cổng 8080 thành mặc định của XAMPP (http://localhost:80/)


Setup XAMPP có MySQL: bật MySQL bằng XAMPP lên >> mở XAMPP tích chọn Start 2 dịch vụ: Apache và MySQL  >>  mở 1 trình duyệt lên: gõ vào thanh địa chỉ: http://localhost/phpmyadmin/  sau đó Enter để truy cập MySQL  >>  Tạo 1 database mới, lấy tên `bansach2`, import file *.sql vào db bansach2 này   >>  mở http://localhost/Project  Enter
