# LAB03 : Web shell upload via path traversal

**Đề bài :**
<img width="940" height="203" alt="image" src="https://github.com/user-attachments/assets/7b7e784f-f64d-48c6-940c-7ec9fa639025" />

- Gửi ảnh lên để lấy gói POST và tìm kiếm gói GET
- Chỉnh sửa gói POST để thực thi lệnh PHP bằng cách sử dụng **../example.php** :
<img width="1543" height="701" alt="image" src="https://github.com/user-attachments/assets/eb457a02-65cb-4a52-a7a2-e0bf669f8d23" />


- Lấy gói GET và chỉnh sửa để lấy ra file **example.php** bằng cách truy cập thư mục cha của **avatar** :
<img width="1540" height="360" alt="image" src="https://github.com/user-attachments/assets/b25a40c0-6e03-4078-87ac-4aedef0b3f27" />

- Ta có được mật khẩu bằng cách bypass path traversal để thực thi lệnh webshell ngay trên trang web : Q3akR2xCAYZS2C8cQvulmgpcfDl4eb7D
