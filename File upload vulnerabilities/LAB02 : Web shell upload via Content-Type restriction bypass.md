# LAB02 : Web shell upload via Content-Type restriction bypass

**Đề bài :**
<img width="869" height="198" alt="image" src="https://github.com/user-attachments/assets/02894be7-8e9e-461b-b1b2-83ed1c671bad" />

- Gửi ảnh bất kì lên và lấy gói **POST**
- Sửa **filename** và nội dung của gói POST thành một câu lệnh PHP. Ta tiếp tục sửa cả **Content-Type** thành **image/jpeg**  :
<img width="1549" height="695" alt="image" src="https://github.com/user-attachments/assets/acf1d4fb-6c28-422c-ab25-eb94025ba095" />

- Lấy ra file **example.php** nhờ gói **GET** :
<img width="1541" height="366" alt="image" src="https://github.com/user-attachments/assets/71e80124-bd90-4a6f-825b-bd8ede965bf0" />

- Bài lab này chỉ chúng ta bypass Content-Type khi trang chủ hẹn chế loại file tải lên.
