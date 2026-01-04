# LAB01 : Remote code execution via web shell upload

**Đề bài :**
<img width="891" height="190" alt="image" src="https://github.com/user-attachments/assets/a414f3ea-9c3a-4a01-add1-3ea496983399" />

- Up 1 ảnh bất kì lên để lấy gói **POST** và cho vào **Repeater**
<img width="769" height="793" alt="image" src="https://github.com/user-attachments/assets/cf466a0d-80ea-4010-b145-3f12026d6e86" />

- Ta thay đổi filename của ảnh và thay vào đó là một file có đuôi **.php**. Tiếp đó thay đổi nội dung của file thành một câu lệnh để đọc nội dung file
  và in nó ra ngoài (đề bài yêu cầu đọc file /home/carlos/secret)
<img width="1548" height="693" alt="image" src="https://github.com/user-attachments/assets/ed16681c-5c80-4afd-9964-f1692b3f1a95" />

- Sau khi gửi request thành công ta sửi dụng lệnh **GET** để lấy file **example.php** ra
<img width="1543" height="409" alt="image" src="https://github.com/user-attachments/assets/88308dcb-eb65-4ec5-b292-52bb66962bb6" />

- Ta có được chuỗi : **6bkKgMbJxEhnRPVgo4LpBllx5Hi88P3x** chính là flag của bài này.
- Bài này ta sử dụng một câu lệnh PHP để chạy lệnh thẳng trên hệ thống và tận dụng lỗi đó để lấy flag về vì hệ thống này không chặn các file có đuôi .php
  và điều này rất nguy hiểm khi mà cho phép người dùng có quyền chạy câu lệnh thẳng trên hệ thống.  
