# LAB07 : Reflected XSS into attribute with angle brackets HTML-encoded

**Đề bài :**
<img width="871" height="94" alt="image" src="https://github.com/user-attachments/assets/629308fe-13f7-46da-af3f-f01cea0ffc0a" />

- Bài lab yêu cầu chúng ta tấn công vào HTML và gọi ra hàm **alert()**
- Ta tìm kiếm chuỗi ngẫu nhiên
<img width="1540" height="775" alt="image" src="https://github.com/user-attachments/assets/8708a26f-900e-4bfd-913d-fa6a92406b9c" />

- Ta thấy chuỗi tìm kiếm được gán vào biến value

- Ta thử tấn công vào biến value bằng "onmouseover="alert(1)
<img width="960" height="1029" alt="image" src="https://github.com/user-attachments/assets/15dfbff9-078d-4cb5-b74d-2226cebfc57d" />

- Chuỗi "onmouseover="alert(1) là một payload XSS dùng để chèn thuộc tính sự kiện HTML vào phần tử, cho phép thực thi
  JavaScript khi người dùng di chuột qua. Payload lợi dụng việc ứng dụng không escape dữ liệu đầu vào khi đưa vào HTML attribute, dẫn đến DOM-based hoặc Reflected XSS.
