#LAB05 : SQL injection attack, listing the database contents on non-Oracle databases

- Đề bài yêu cầu trúng ta truy cập là lấy mật khẩu cho administrator : 
<img width="1058" height="212" alt="image" src="https://github.com/user-attachments/assets/2a698d16-a38a-4202-af05-c6ec33f80d6a" />

- Ta sử dụng ORDER BY để xác định số cột :
<img width="1422" height="131" alt="image" src="https://github.com/user-attachments/assets/164fea3e-997a-404a-9181-8559e84311a7" />
<img width="1419" height="124" alt="image" src="https://github.com/user-attachments/assets/d1f7391c-0cdf-4bc5-976a-3940e161e60d" />
<img width="1434" height="131" alt="image" src="https://github.com/user-attachments/assets/4b76c239-7ecc-47db-b2bd-e2e1695c791d" />

- Bảng này có 2 cột ta xác định kiểu dữ liệu của các cột:
<img width="1421" height="139" alt="image" src="https://github.com/user-attachments/assets/6be6c726-9873-4517-a210-2ec11cffee32" />

- Cả 2 cột đều có chứa văn bản nên trả về HTTP/2 200. Ta tiếp tục tìm các tên của tất cả bảng có trong danh sách :
<img width="1544" height="190" alt="image" src="https://github.com/user-attachments/assets/c8e9d546-588e-4ef1-8d02-0b99f10bac59" />

- Ta truy cập vào bảng users_gmbxii để tiếp tục tìm toàn bộ các cột trong bảng users_gmbxii :
<img width="1415" height="186" alt="image" src="https://github.com/user-attachments/assets/e642066d-cebe-4c7f-ae1d-edd1eba4f605" />

- Ta có thể thấy cột users_gmbxii và password_gkwfhm hiện ra. Ta tiếp tục truy cập 2 cột users_gmbxii và password_gkwfhm :
<img width="1542" height="778" alt="image" src="https://github.com/user-attachments/assets/228070a5-9700-4f82-989a-e75635c6bc8a" />

- Sau khi truy cập 2 cột đã hiện ra username và password của tài khoản administrator :
<img width="1542" height="778" alt="image" src="https://github.com/user-attachments/assets/fb81fb0f-9608-4020-bba7-add9252af5a9" />

