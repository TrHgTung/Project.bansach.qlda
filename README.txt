admin admintest mk: admin
guest: tungdeeptry - mk: abc123

Gốc: https://drive.google.com/file/d/1wlSw1iJSLCBukMYgvmG2Cu6wIl2eW9dT/view

Nếu không chạy được do lỗi địa chỉ localhost:
  - Mở cả folder chứa src code bằng VS Code
  - Nhấn Ctrl + Shift + H:
    + Find: (nhập) http://localhost:8080/
    + Replace: (nhập) http://localhost/
    + Nhấn nút Replace All
    --> Mục đích: thay đổi địa chỉ localhost mà XAMPP đang chiếm, đổi từ cổng 8080 thành mặc định của XAMPP ('80' hoặc '3000' tùy phiên bản của XAMPP)


Updated:
    ./mvc/controllers/Logined.php: Line 45 changed: 'if($kq = 0' as origin (because signup role had problem with admins/customers)
      + For some cases
