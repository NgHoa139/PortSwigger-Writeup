# LAB01 : File path traversal, simple case 

**Đề bài :** 
<img width="990" height="148" alt="image" src="https://github.com/user-attachments/assets/9faa5411-57d9-4ce0-9ca4-ebf2c82c82c1" />

- Chỉnh sửa thư mục **GET/filename** để máy chủ trả lên file **/etc/passwd**
<img width="1490" height="391" alt="image" src="https://github.com/user-attachments/assets/a8c35130-ca70-4a6b-b4cf-8d30659d2523" />

- Yêu cầu bị sai nên nghĩa là file etc/passwd đang ở trong 1 thư mục cha nào đó ta lùi lên 1 cấp thư mục
bằng cách sử dụng ../
- Sau khi lùi lại 3 thư mục thì đã trả về request đúng : 
<img width="1493" height="394" alt="image" src="https://github.com/user-attachments/assets/3f136a97-bba9-4638-8685-5769fa5d9609" />
